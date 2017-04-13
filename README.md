# diskimage_build_patch
patch for diskimage_build to support root password injection image create



the patch currently only support ubuntu and centos 7 to fit the root password.hope to provide scripts making the process more automatic.



## step to patch 

* git clone this repository
* cp {diskimage_build_patch}/centos7 diskimage-builder/elements/centos7
* cp {diskimage_build_patch}/ubuntu diskimage-builder/elements/ubuntu