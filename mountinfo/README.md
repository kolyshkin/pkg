### mountinfo: Linux /proc/mountinfo parser

The Linux kernel provides information about mount points in the process'
mount namespace in the `/proc/<pid>/mountinfo` file (a process can use
`/proc/self/mountinfo` for its own mount namespace).

This package is a parser for `/proc/self/mountinfo`.
