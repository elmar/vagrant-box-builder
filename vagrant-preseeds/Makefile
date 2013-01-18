preseeds = debian.cfg ubuntu.cfg

all: $(preseeds)

%.cfg : %.skel
	cat common.cfg $< > $@
