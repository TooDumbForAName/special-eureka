To run on Linux/Unix, invoke with **./<filename>**. The proper permissions should be set if the repository is cloned with git.

**dos-works-unix-works.bat** -- This should work on both MS-DOS/Windows and Unix/Linux

**dos-works-unix-fails.bat**  -- This should fail to work properly on Unix/Linux, because of improper line endings.

**dos-fails-unix-fails.bat** -- This should fail to work properly on both DOS and Linux, because of improper (Classic Mac) line endings.

**dos-fails-unix-works.bat** -- This should fail to work on DOS, but work on Linux. To be honest, I had to go out of my way to make this, so it's unlikely to be encountered normally, and might not work on some Unix systems, either, for all I know.
