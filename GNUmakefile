SUFFIX:=svg

all: open

civ.svg: civ.dot
	dot -o civ.svg -Tsvg civ.dot

open: civ.svg
	open -a Safari.app civ.svg
