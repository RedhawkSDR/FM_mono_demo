# REDHAWK Basic Waveforms - FM Mono Demo
 
## Description

Contains the source and build script for the REDHAWK FM Mono Demo Waveform. This
waveform processes the mono audio channel of broadcast FM Radio.

## Branches and Tags

All REDHAWK core assets use the same branching and tagging policy. Upon release,
the `master` branch is rebased with the specific commit released, and that
commit is tagged with the asset version number. For example, the commit released
as version 1.0.0 is tagged with `1.0.0`.

Development branches (i.e. `develop` or `develop-X.X`, where *X.X* is an asset
version number) contain the latest unreleased development code for the specified
version. If no version is specified (i.e. `develop`), the branch contains the
latest unreleased development code for the latest released version.

## REDHAWK Version Compatibility

| Asset Version | Minimum REDHAWK Version Required |
| ------------- | -------------------------------- |
| 1.x           | 2.0                              |

## Build/Installation Instructions
This is a wavform project and thus does not need to be built just installed into
the $SDRROOT/dom/waveforms directory. One way to do that is to open the project
in the REDHAWK IDE and drag it into the Target SDR Folder.

## Copyrights

This work is protected by Copyright. Please refer to the
[Copyright File](COPYRIGHT) for updated copyright information.

## License

REDHAWK Basic Waveforms are licensed under the GNU Lesser General Public License
(LGPL).
