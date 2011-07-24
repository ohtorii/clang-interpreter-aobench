aobench in clang-interpreter.
========

![aobench](http://cdn-ak.f.st-hatena.com/images/fotolife/o/ohtorii/20110717/20110717001052.png)


### What is aobench.
> AO bench is a small ambient occlusion renderer for benchmarking realworld floating point performance in various languages.

### how to run.
- clang-interpreter.exe aobench.cpp

### environment.
- Windows7 64bit
- Intel Core i7 CPU 3.07GHz
- Visual Studio 2010
- LLVM/clang build on VisualStudio 2010.

### performance.
		WIDTH=256/HEIGHT=256(default)
			clang-interpreter        5,887ms
			VC2010 Release mode      1,040ms
			
		WIDTH=512/HEIGHT=512
			clang-interpreter       23,364ms
			VC2010 Release mode      4,155ms
			
		WIDTH=1024/HEIGHT=1024
			clang-interpreter       94,805ms
			VC2010 Release mode     17,851ms

### aobench web.
<http://code.google.com/p/aobench/>
