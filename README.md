# THIS PROJECT IS ARCHIVED   
Intel will not provide or guarantee development of or support for this project, including but not limited to, maintenance, bug fixes, new releases or updates.  
Patches to this project are no longer accepted by Intel.  
 If you have an ongoing need to use this project, are interested in independently developing it, or would like to maintain patches for the community, please create your own fork of the project.  
  
# Linux branches for fuzzing with kAFL

WARNING - this project contains experimental and unsupported software for purpose of research. Do not use for production.

Overview:

* `kvm-nyx-N` tracks the Nyx KVM tree at https://github.com/nyx-fuzz/KVM-Nyx/
* `kafl/sdv-N` are variants of the Nyx KVM tree with TDX 'SDV' emulation + kAFL support
* `guest` tracks upstream TDX guest kernel at https://github.com/intel/tdx/
* `kafl/fuzz-N` are variants of Linux guest kernels for fuzzing with kAFL

See also:
* [IntelLabs/kAFL](https://github.com/IntelLabs/kAFL)
* [KVM-Nyx](https://github.com/nyx-fuzz/KVM-Nyx)
* [Linux Kernel Hardening for Intel TDX](https://intel.github.io/ccc-linux-guest-hardening-docs/)
