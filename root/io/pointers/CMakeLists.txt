#-------------------------------------------------------------------------------
#
# Placeholder file to translate the tests to the new CTest system. Meanwhile we
# define a CTest test that calls 'make' in ${CMAKE_CURRENT_SOURCE_DIR}
#
#-------------------------------------------------------------------------------

ROOTTEST_ADD_TEST(multiTree
   MACRO runCanvases.C
   OUTREF Canvases.ref)

ROOTTEST_ADD_TEST(restoreCanvas
   MACRO restoreCanvas.C
   OUTREF restoreCanvas.ref)
