# Operating System Actions, Proc/Thread Management

- A cheap Linux syscall, 100-500ns. 
    - trapping and prelude: 50-100ns
    - dispatching: 10-50ns
    - real logic, non-blocking IO, 200ns
    - epilog, switching, 20-100ns.

- MD5 a 64-bit number: 200ns

- Context switching, POSIX thread, 1-5s.

