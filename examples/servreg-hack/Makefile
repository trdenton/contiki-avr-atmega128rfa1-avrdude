CONTIKI_PROJECT = example-servreg-client
all: $(CONTIKI_PROJECT)

WITH_UIP6=1
CFLAGS += -DUIP_CONF_IPV6=1

APPS=servreg-hack
CONTIKI = ../..
include $(CONTIKI)/Makefile.include
-include /home/user/nes/testbed-scripts/Makefile.include

