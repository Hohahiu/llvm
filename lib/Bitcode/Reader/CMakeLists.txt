add_llvm_library(LLVMBitReader
  BitReader.cpp
  BitcodeReader.cpp
  BitstreamReader.cpp
  )

add_dependencies(LLVMBitReader intrinsics_gen)
