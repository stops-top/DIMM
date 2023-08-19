#!/usr/bin/make
KIBOT?=kibot
DEBUG?=
OUT_DIR=Generated

all: erc drc template

erc:
	$(KIBOT) $(DEBUG) -d $(OUT_DIR) -s run_drc,update_xml -i

drc:
	$(KIBOT) $(DEBUG) -d $(OUT_DIR) -s run_erc,update_xml -i

netlist:
	$(KIBOT) $(DEBUG) -d $(OUT_DIR) -s run_erc,run_drc -i

var_default:
	$(KIBOT) $(DEBUG) -d $(OUT_DIR)/default -g variant=default -s all

template: netlist var_default 

.PHONY: template erc drc netlist var_default
