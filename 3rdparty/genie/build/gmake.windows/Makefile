# GNU Make solution makefile autogenerated by GENie
# Type "make help" for usage help

ifndef config
  config=release
endif
export config

PROJECTS := genie

.PHONY: all clean help $(PROJECTS)

all: $(PROJECTS)

genie: 
	@echo "==== Building genie ($(config)) ===="
	@${MAKE} --no-print-directory -C . -f genie.make

clean:
	@${MAKE} --no-print-directory -C . -f genie.make clean

help:
	@echo "Usage: make [config=name] [target]"
	@echo ""
	@echo "CONFIGURATIONS:"
	@echo "   release"
	@echo "   debug"
	@echo ""
	@echo "TARGETS:"
	@echo "   all (default)"
	@echo "   clean"
	@echo "   genie"
	@echo ""
	@echo "For more information, see https://github.com/bkaradzic/genie"
