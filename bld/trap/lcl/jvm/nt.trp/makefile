#pmake: trap lcl os_dos dsx cpu_386 x86
host_CPU = 386
host_os = nt

os = nt
cpu = x86
srv = jvm
which = TRAP

extra_objs = $(jvmx_trap_objs) jvminfo.obj acclcl.obj
extra_c_flags = -dJVM -dJVMXTRAP -fh

!include $(trap_dir)/lcl/jvm/jvm.mif
!include $(trap_dir)/master.mif
