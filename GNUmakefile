SUFFIX:=svg

all: civ.${SUFFIX}

civ.svg: civ.dot
	dot -o civ.svg -Tsvg civ.dot
	open -a Safari.app civ.svg
