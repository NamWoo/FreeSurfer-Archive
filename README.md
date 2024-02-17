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


# Clinica

참고
* https://github.com/aramis-lab/clinica

PET+T1을 이용한 Projected PET in FsAverage's Space 만들기


`Input Data`
* Coregistered PET

`Output Data`
* Projected PET in FsAverage's Space




---
ref

https://github.com/dr-xenia/mne_course?tab=readme-ov-file
https://github.com/tsbinns/mne_course?tab=readme-ov-file
https://github.com/dr-xenia/mne_course?tab=readme-ov-file
https://github.com/BIDS-Apps/MRtrix3_connectome
https://github.com/dr-xenia?tab=repositories
https://aramislab.paris.inria.fr/clinica/docs/public/latest/Pipelines/PET_Volume/
https://aramislab.paris.inria.fr/clinica/docs/public/latest/CAPS/Introduction/
https://bids.neuroimaging.io/
https://bids-standard.github.io/bids-starter-kit/tutorials/pet.html
https://bids-specification.readthedocs.io/en/latest/
https://aramislab.paris.inria.fr/clinica/docs/public/latest/BIDS/
http://www.turkupetcentre.net/petanalysis/image_pve.html
https://github.com/aramis-lab/clinica?tab=readme-ov-file
https://www.clinica.run/
