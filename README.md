# DCLP
Double-Checked Locking

The C++ and the risks of Double-Checked Locking Pattern (DCLP) are discussed. DCLP is designed to add efficient thread safety to initialization of a shared resource but it is not reliable and can fail for different reasons on uniprocessor and multiprocessor architectures. The relationships among statement ordering in source code, sequence points, compiler and hardware optimizations and the actual order of statement execution are analyzed. Some suggestions are given regarding the addition of thread safety to singleton so that the resulting code will be both reliable and efficient.
