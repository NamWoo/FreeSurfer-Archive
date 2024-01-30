# FreeSurfer-Archive
FreeSurfer ...


https://github.com/freesurfer/freesurfer/blob/dev/Dockerfile
https://neurostars.org/t/recon-all-clinical-command-in-freesurfer-docker/27956/5
https://surfer.nmr.mgh.harvard.edu/fswiki/infantFS-containers
https://www.repronim.org/neurodocker/index.html

```bash
docker build --tag freesurfer:1.0 .
docker run -it --rm --gpus all --name free freesurfer:1.0
```
