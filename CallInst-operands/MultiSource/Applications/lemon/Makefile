LEVEL = ../../../

Source = lemon.c

PROG = lemon
RUN_OPTIONS = $(PROJ_SRC_DIR)/parse.y $(PROJ_SRC_DIR)/example1.y $(PROJ_SRC_DIR)/example2.y $(PROJ_SRC_DIR)/example3.y $(PROJ_SRC_DIR)/example4.y $(PROJ_SRC_DIR)/example5.y $(PROJ_SRC_DIR)/lighttpd_configparser.y $(PROJ_SRC_DIR)/lighttpd_mod_ssi_exprparser.y $(PROJ_SRC_DIR)/wireshark_dtd_grammar.lemon $(PROJ_SRC_DIR)/wireshark_grammar.lemon $(PROJ_SRC_DIR)/wireshark_mate_grammar.lemon $(PROJ_SRC_DIR)/xapian_queryparser.lemony $(PROJ_SRC_DIR)/ecmascript.y

include $(LEVEL)/Makefile.config

include ../../Makefile.multisrc
DIFFPROG := $(PROGDIR)/DiffOutput.sh "diff "

