# Installation

Prebuilt binaries are available from [Github Actions](https://github.com/comp500/packwiz/actions) - the UI is a bit terrible, but essentially select the top build, then download the artifact zip for your system at the bottom of the page. To run the executable, add the folder where you downloaded it to your PATH environment variable ([see tutorial for Windows here](https://www.howtogeek.com/118594/how-to-edit-your-system-path-for-easy-command-line-access/)) or move it to where you want to use it.

In future I will have a lot more installation options, but you can also compile from source:

1. Install Go (1.17 or newer) from https://golang.org/dl/
2. Run `go install github.com/comp500/packwiz@latest`. Be patient, it has to download and compile dependencies as well!
