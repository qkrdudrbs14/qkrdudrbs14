
rem Classpath addition for release
 for %%i in ("%BASE_DIR%\libs\*") do (
 	call :concat "%%i"
 )

 -->
rem Classpath addition for release
call :concat "%BASE_DIR%\libs\*;
 
