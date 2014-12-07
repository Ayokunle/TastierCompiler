make 
mono bin/tcc.exe test/Programs/test.TAS test.asm
tasm test.asm test.bc
tvm test.bc test/Inputs/test.IN