################## BASE IMAGE ######################
FROM biocontainers/biocontainers:latest

################## METADATA ######################
LABEL base_image="biocontainers:latest"
LABEL version="1"
LABEL software="emboss"
LABEL software.version="6.5.7"
LABEL about.summary="software analysis package"
LABEL about.home="http://emboss.sourceforge.net/what/"
LABEL about.documentation="http://emboss.sourceforge.net/docs/"
LABEL about.license_file="http://emboss.sourceforge.net/licence/"
LABEL about.license="SPDX:GPL-3.0"
LABEL about.tags="Proteomics"
LABEL extra.identifiers.biotools="EMBOSS"

################## MAINTAINER ######################
MAINTAINER Felipe da Veiga Leprevost <felipe@leprevost.com.br>

################## INSTALLATION ######################

RUN conda install emboss=6.5.7

WORKDIR /data/
