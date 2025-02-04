FROM quay.io/jupyter/pytorch-notebook:cuda12-python-3.11.8

COPY requirements.txt /tmp/requirements.txt
RUN conda install --file /tmp/requirements.txt
RUN fix-permissions "${CONDA_DIR}"