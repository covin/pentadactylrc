
WGET     = wget
WGET_OPT = 

PLUGIN_BASE = http://5digits.org/plugins/

plugins := $(wildcard *.js)
updates := $(plugins:.js=.update)

%.update: %.js
	# [update] $<
	$(WGET) $(WGET_OPT) $(PLUGIN_BASE)$< -O $<

update: $(updates)

		
