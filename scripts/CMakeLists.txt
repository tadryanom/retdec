install(PROGRAMS "retdec-color-c.py" DESTINATION bin)
install(PROGRAMS "retdec-config.py" DESTINATION bin)
install(PROGRAMS "retdec-archive-decompiler.py" DESTINATION bin)
install(PROGRAMS "retdec-decompiler.py" DESTINATION bin)
install(PROGRAMS "retdec-fileinfo.py" DESTINATION bin)
if(RETDEC_TESTS)
	install(PROGRAMS "retdec-tests-runner.py" DESTINATION bin)
endif()
install(PROGRAMS "retdec-signature-from-library-creator.py" DESTINATION bin)
install(PROGRAMS "retdec-unpacker.py" DESTINATION bin)
install(PROGRAMS "retdec-utils.py" DESTINATION bin)
