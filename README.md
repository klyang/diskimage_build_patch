# diskimage_build_patch
patch for diskimage_build to support root password injection image create



the patch currently only support ubuntu and centos 7 to fit the root password.hope to provide scripts making the process more automatic.



## step to patch 

* git clone this repository
* cp -r {diskimage_build_patch}/centos7/install.d diskimage-builder/elements/centos7
* cp -r {diskimage_build_patch}/ubuntu/install.d diskimage-builder/elements/ubuntu
* chmod +755 diskimage-builder/elements/ubuntu/install.d/99-modifycloudinit
* chmod +755 diskimage-builder/elements/centos7/install.d/99-modifycloudinit