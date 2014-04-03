all: udp-server udp-client

CFLAGS += -DUIP_CONF_IPV6=1

DEFINES=UIP_CONF_ND6_REACHABLE_TIME=0xffffffff

CONTIKI = ../../..
include $(CONTIKI)/Makefile.include
