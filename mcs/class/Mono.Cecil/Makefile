thisdir = class/Mono.Cecil
include ../../build/rules.make

LIBRARY = Mono.Cecil.dll
LIBRARY_SNK = ../mono.snk
LIBRARY_PACKAGE = none

LIB_MCS_FLAGS = /r:$(corlib) -keyfile:$(LIBRARY_SNK) -r:System.Core.dll -d:NET_3_5

NO_TEST = yes

ifneq (net_2_0, $(PROFILE))
NO_INSTALL = yes
endif

include ../../build/library.make
