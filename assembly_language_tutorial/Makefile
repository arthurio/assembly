astmut.o:
	nasm -o asmtut.tmp -f macho asmtut.s && ld -arch i386 -macosx_version_min 10.6 -no_pie -e _main -o asmtut.o asmtut.tmp
clean:
	      rm *.o asm
