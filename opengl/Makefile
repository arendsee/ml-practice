TARGET=x

# Requires LablGL, an OCaml adapter to OpenGL
# 

CC=ocamlopt
FLAGS=-I ${HOME}/.opam/system/lib/lablgl -I +lablGL lablglut.cmxa lablgl.cmxa

all:
	${CC} ${FLAGS} ${TARGET}.ml

.PHONY: clean
clean:
	rm -f a.out ${TARGET}.cmi ${TARGET}.cmo ${TARGET}.cmx ${TARGET}.o
