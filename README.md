# BuildContainer
build singularity containers with different versions of TF and softwares

`sudo singularity build 3dSlicer-containerV3.sif 3DSlicerContainer.def`<br>
X11 dependency (qt5 platform dependency) search `sudo apt-cache search qt5 | grep 'X11 extras'`<br>

`sudo singularity build --sandbox container/ container.def`<br>
`sudo singularity shell --writable container/`<br>
`sudo singularity build container.sif container/`<br>
[ref](https://gist.github.com/rohitfarmer/af486e346900534274cdc1153a764c90)
