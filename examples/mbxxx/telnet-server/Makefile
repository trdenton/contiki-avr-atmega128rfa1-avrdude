CONTIKI_PROJECT = telnet-server

CFLAGS += -DUIP_CONF_IPV6=1
			
APPS = telnetd

PROJECTDIRS = $(CONTIKI)/platform/mbxxx/apps
PROJECT_SOURCEFILES = shell-sensors.c


all: $(CONTIKI_PROJECT)

CONTIKI = ../../..
include $(CONTIKI)/Makefile.include
