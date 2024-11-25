build:
	cd tools; dune build

run: build
	cd tools; dune exec tools

with_input: ./input 
	cd tools; cat ../input | dune exec tools

test: build
	cd tools; dune runtest --auto-promote

format:
	cd tools; dune fmt

fmt: format
