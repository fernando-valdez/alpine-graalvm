# Alpine + GraalVM
A collection of DockerFiles that show the integration Alpine Linux distribution with GraalVM

## What is this?
Alpine is security-oriented, lightweight Linux distribution. 


## How can I use it with GraalVM?

When using GraalVM (or Java) in a Alpine distribution, it is required to install glibc first.

Inside the `alpine-graalvm` folder, you will find a DockerFile that use the official alpine (version 3.7) image, and then install GraalVM CE 20.2.0 (Java 8), as well as, the required dependencies. 

Another approach is to use the DockerFile in the folder `alpine-glibc-graalvm`. That is a simpler version that uses a image that includes the glibc library already (frolvlad/alpine-glibc), and then installs GraalVM 20.2.0 (Java 8).
