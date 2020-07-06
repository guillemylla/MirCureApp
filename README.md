# MirCure: A tool for quality control, filter, and curation of microRNAs of animals and plants 

MirCure is a computational application to assist on filtering and curating microRNA annotations obtained from databases or de novo miRNA annotation tools.


## New repository
![DMaintained](https://img.shields.io/badge/Maintained at new repo:- ConesaLab github - orange)

MirCure is officially mentained at: https://github.com/ConesaLab/MirCure


## Run MirCure from Docker
![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/guillemy/mircure)

```
docker run --rm -p 3838:3838 \
 -v LOCAL_Genome_DIR:/srv/shiny-server/data/genomes \
 -v LOCAL_BAMFILE_DIR:/srv/shiny-server/data/bamfiles \
 -v LOCAL_DIR_TO_SAVE_MIRCUREREPORTS:/srv/shiny-server/reports\
     conesalab/mircure

```



## Citation

Ylla, G., Tianyuan, L., & Ana, C. (2020). MirCure: A tool for quality control, filter, and curation of microRNAs of animals and plants.


