set(LLVM_LINK_COMPONENTS
  DebugInfoCodeView
  DebugInfoPDB
  )

set(DebugInfoPDBSources
  MappedBlockStreamTest.cpp
  MsfBuilderTest.cpp
  PDBApiTest.cpp
  )

add_llvm_unittest(DebugInfoPDBTests
  ${DebugInfoPDBSources}
  )
