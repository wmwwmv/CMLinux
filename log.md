# time_log

- 20160708
    - Debugging
    - Completing the process of performing local on `Cent OS`, meeting no fatal errors.
    - Preparing For re-define the build_steps for more detailed and professional.
    - Changing the flowchart to meet the need of build the system.
    - Re-basing the building process towards `Cent OS`, deploying the Virtual Machine for build
    - Fatal error on `libtinfo.so.5`, fallback to debug
- 20160707
    - Comleting the build of the temporary system.
    - Encountr a error when pending `perl`, cannot link ***libtinfo.so.5***, preparing backup and experiental settings  
    - Find a bug of the `lfs-7.9`, the `gperf` must be set before the configuring of `grep`, add gperf
    - Encounter a problem of ***Ubuntu 14+ x86_64 cannot load ia32-libs***, the package `file` cannot being configured well, jump to next package
    - Complete the build process of the whole `GCC` toolchain, wait for adding functions
    - Complete the build process of `binutils/gcc/Linux Header API/glibc`
    - Starting the build process of a minimal Linux System.
- 20160706
    - Preparing localhost for deploying the temporary mirror of the LFS.
    - Testing all the URLs of source packages and retrieving them to the LFS folder.