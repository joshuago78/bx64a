icalc.g: memory.o
	gcc -o icalc.g memory.o -no-pie
icalc.g.o: memory.asm
	nasm -f elf64 -g -F dwarf icalc.g.asm -l memory.lst
