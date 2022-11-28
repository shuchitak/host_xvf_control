# HOST_XVF_CONTROL Repository

HOST_XVF_CONTROL is host control reference application to be used for XVF3800 and onwards.

## Cloning

Some dependent components are included as git sub modules. These can be obtained by cloning this repository with the following command:

    git clone --recurse-submodules git@github.com:xmos/sw_xvf_host.git

## Building

Build with cmake:

    mkdir build && cd build && cmake -S.. && make
