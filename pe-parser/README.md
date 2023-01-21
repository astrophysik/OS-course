Examples of using

```sh
$ ./pe-parser is-pe ./examples/1/1.exe
PE
$ ./pe-parser is-pe ./pe-parser
Not PE
$
```

```sh
$ ./pe-parser import-functions examples/2/2.exe
VCRUNTIME140.dll
    __current_exception
    __current_exception_context
    memset
    __C_specific_handler
api-ms-win-crt-stdio-l1-1-0.dll
    __stdio_common_vfprintf
    __acrt_iob_func
    __p__commode
    _set_fmode
api-ms-win-crt-runtime-l1-1-0.dll
    _register_onexit_function
    _crt_atexit
    terminate
    _seh_filter_exe
    _set_app_type
    _cexit
    _register_thread_local_exe_atexit_callback
    __p___argv
    __p___argc
    _c_exit
    _exit
    exit
    _initterm_e
    _initterm
    _get_initial_narrow_environment
    _initialize_narrow_environment
    _configure_narrow_argv
    _initialize_onexit_table
api-ms-win-crt-math-l1-1-0.dll
    __setusermatherr
api-ms-win-crt-locale-l1-1-0.dll
    _configthreadlocale
api-ms-win-crt-heap-l1-1-0.dll
    _set_new_mode
KERNEL32.dll
    GetCurrentThreadId
    RtlLookupFunctionEntry
    RtlVirtualUnwind
    UnhandledExceptionFilter
    SetUnhandledExceptionFilter
    GetModuleHandleW
    IsDebuggerPresent
    InitializeSListHead
    GetSystemTimeAsFileTime
    RtlCaptureContext
    GetCurrentProcessId
    QueryPerformanceCounter
    IsProcessorFeaturePresent
    TerminateProcess
    GetCurrentProcess
$
```