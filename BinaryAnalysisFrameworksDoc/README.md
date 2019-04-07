# Binary Analysis Frameworks
This page is just a list fo available binary analysis frameworks. The idea come from this tweet: https://twitter.com/elvanderb/status/773442426203668481

LLVM IR:
	FCD - http://zneak.github.io/fcd/2016/02/16/lifting-x86-code.html
	MCSEMA - https://github.com/trailofbits/mcsema
	Dagger - http://dagger.repzret.org/


Nrop IR: mix of QEMU IR (TCG) and LLVM IR 
	https://aurelien.wail.ly/nrop/index.html
	http://wiki.qemu.org/Documentation/TCG

VEX:
	https://github.com/lu-zero/vex/blob/master/pub/libvex_ir.h

ANGR - VEX based
	http://angr.io/

BAP:
	https://github.com/BinaryAnalysisPlatform/bap

*REIL:
	https://www.zynamics.com/binnavi/manual/html/reil_language.htm
	https://github.com/Cr4sh/openreil 
	https://bitbucket.org/mihaila/bindead/wiki/Home

BIL: 
	OCaml
	https://github.com/BinaryAnalysisPlatform/bil

MIASM:
	Python - X86 / ARM / MIPS / SH4 / MSP430
	http://miasmdoc.ajax.re/

Metasm:
	Ruby - x86 (16 and 32bits), X86_64, MIPS, PowerPC, Sh4
	https://github.com/jjyg/metasm

Binary Ninja IR:
	C++, Python bindings
	https://api.binary.ninja/binaryninja.LowLevelILExpr.html

Triton IR:
	C/C++, Python bindings - x86, x86_64
	http://triton.quarkslab.com/

Amoco:
	Python - arm, msp430, pic, sparc, x64, x86, z80
	https://github.com/bdcht/amoco

REVEN: 
	http://www.tetrane.com/en/products.html
	http://doc.tetrane.com/latest/
	"Commercial product, the internal IR is only documented/accessible for some filtered customers though..."

BinSec IR - DBA:
	 http://binsec.gforge.inria.fr/

SNOWMAN IR:
	x86-64, arm
	https://derevenets.com/
	https://github.com/yegord/snowman/blob/master/src/nc/arch/x86/X86InstructionAnalyzer.cpp
	https://github.com/yegord/snowman/blob/master/src/nc/arch/arm/ArmInstructionAnalyzer.cpp

Medusa IR:
	C++/Python
	https://github.com/wisk/medusa

r2 IR - ESIL
	https://github.com/radare/radare2book/blob/master/esil.md

ghidra p-code
	Java
	http://ghidra.re/courses/languages/html/pcoderef.html

Hex-Rays microcode
	C++ / python planned
	http://www.hexblog.com/?p=1248

grammatechs gtirb 
	protobuf / C++
	https://github.com/GrammaTech/gtirb