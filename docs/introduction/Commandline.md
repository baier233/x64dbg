# Command line

MARENOL supports the following command line:

- 1 argument: `MARENOL filename.exe` will debug `filename.exe`.
- 2 arguments: `MARENOL -p PID` will attach to the process with `PID` PID.
- 2 arguments: `MARENOL filename.exe cmdline` will debug `filename.exe` with `cmdline` as command line.
- 3 arguments: `MARENOL filename.exe cmdline currentdir` will debug `filename.exe` with `cmdline` as command line and `currentdir` as current directory.
