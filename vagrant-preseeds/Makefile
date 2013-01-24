preseeds = debian.cfg ubuntu.cfg

all: $(preseeds)

%.cfg : %.skel common.cfg packages.cfg
	cat common.cfg packages.cfg $< > $@
