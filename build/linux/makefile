export DIR_REFERENCES :=  $(realpath $(dir $(lastword $(MAKEFILE_LIST))))/../../

include $(DIR_BUILD_CONFIG)/project.properties

DIR_INSTALL=$(DIR_GRASSROOTS_INSTALL)/references

.PHONY: all install clean 

all: 
clean: 

install:
	mkdir -p $(DIR_INSTALL)
	cp $(DIR_REFERENCES)/*.json $(DIR_INSTALL)/