add_llvm_library(LLVMAsmPrinter
  AddressPool.cpp
  ARMException.cpp
  AsmPrinter.cpp
  AsmPrinterDwarf.cpp
  AsmPrinterInlineAsm.cpp
  DbgValueHistoryCalculator.cpp
  DebugHandlerBase.cpp
  DebugLocStream.cpp
  DIE.cpp
  DIEHash.cpp
  DwarfAccelTable.cpp
  DwarfCFIException.cpp
  DwarfCompileUnit.cpp
  DwarfDebug.cpp
  DwarfExpression.cpp
  DwarfFile.cpp
  DwarfStringPool.cpp
  DwarfUnit.cpp
  EHStreamer.cpp
  ErlangGCPrinter.cpp
  OcamlGCPrinter.cpp
  WinException.cpp
  CodeViewDebug.cpp

  DEPENDS
  intrinsics_gen
  )
