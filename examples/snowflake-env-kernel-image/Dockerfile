FROM continuumio/miniconda3:23.3.1-0

COPY environment.yml .
RUN conda env update -f environment.yml --prune
