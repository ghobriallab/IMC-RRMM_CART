FROM jupyter/datascience-notebook

USER root
RUN apt update
RUN pip install 'scanpy[leiden]' 
RUN pip install numpy==1.26.4  pyyaml
RUN pip install seaborn
RUN pip install inmoose
RUN pip install networkx
RUN pip install shapely geopandas
RUN pip install scikit-image
RUN pip install opencv-python
RUN pip install tifffile
RUN pip install pandas==2.2.0

USER foster
WORKDIR /workspace
