# build
Unified way to build software out of Source code with confidence.

## Types of Data
We got 2 main types Assets and Chunks Chunks do always reference in this case to Build Instructions not the Chunks of your software
sure your software can consiste out of chunks but that is not relevant for this documentation.

the secund type is the asset it is anything but it is referenced 

chunks are parts of executeable code including maybe sourceMaps where they orginateFrom as they are highly dynamical as a structure.
Often they get build dynamical with a mixed set of Assets to build software. 

so you learned chunks are dynamic build instructions and assets are static referenced content assets of any type even other source code that can produce chunks is a assets until it produced a chunk :)

so you can simply think of them as processed and unprocessed assets a processed parsed asset that generates code gets a chunk a filesystem entry for example is a asset and gets a chunk 

Combined Chunks and assets do form whats called Artifact

that gets us the the next chapter the two main build types source builds and artifact builds. 

## Build Types
a Artifact build is based on pre build artifacts from a prev build step in general this is the most fastest and stable way.
and should be the prefered unless your working on some internal binary code. Most Application developers should not need
to ever use a other development mode then the Artifact mode. 

The Artificat mode also enables so called rolling releases
