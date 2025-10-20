# scriptdll/dllscript

Execute a script DLL.

## arguments

`arg1` The filename and path of the script DLL. If a full path is not provided MARENOL will look in the `scripts` directory for the DLL.

## results

This command does not set any result variables. However, the script DLL may set any variable.

## remarks

A script DLL is a DLL that exports either `AsyncStart()` or `Start()` function.

If the DLL exports `AsyncStart()` function, then MARENOL will call this function on a separate thread. If the DLL exports `Start()` function, then MARENOL will call this function on the current thread, blocking any further command execution until the script DLL finishes execution. If both `AsyncStart()` and `Start()` are exported, only `AsyncStart()` will be executed. Any return value of `AsyncStart()` and `Start()` will not be used by MARENOL.

After `AsyncStart()` or `Start()` finishes, the script DLL will be unloaded from the process.