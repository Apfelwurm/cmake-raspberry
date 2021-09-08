# cmake build for raspberry pi os (armhf)

This repository houses newer cmake builds for the raspberry pi (armhf). It is intended for the github actions build steps for the raspberry of [VolumeHIDtoOSC](https://github.com/Apfelwurm/VolumeHIDtoOSC) and [debughidevent](https://github.com/Apfelwurm/debughidevent) inside of [arm-runner-action](https://github.com/pguyot/arm-runner-action).

Because the build times on the free runners of github exceeds the 6 hour limit of a job, we dont build new versions automatically, because therefore one of my self hosted runners is nessecary. If you need a newer version in your CI, just open an issue here and we will build it for you.
