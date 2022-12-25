# Exploración de las principales funciones del terminal de OpenBB v.1.9.0
OpenBB es un framework gratuito que busca brindar información financiera de manera gratuita. Este proyecto consiste en explorar las principales funciones de su API en Python: `stocks`, `econometrics`, `forecast` y `economy`.

<p align="center">
  <img src="figures/openbb.png" width="300">
</p>

La instalación se realiza mediante este proceso:
1. Contar con Python, Anaconda y Visual Studio para C++ (Community 2022 version). Todos agregando al PATH.
2. En el CMD, se debe instalar Git mediante anaconda: `conda install -c anaconda git`.
3. Se debe clonar el repositorio del proyecto OpenBB: `git clone https://github.com/OpenBB-finance/OpenBBTerminal.git`.
4. Nos dirigimos a la carpeta del proyecto: `cd openbbterminal`.
5. Se debe construir el entorno más actual de OpenBB: `conda env create -n obb --file build/conda/conda-3-9-env-full.yaml`.
6. Activamos el entorno: `conda activate obb`.
7. Instalamos algunas dependiencias: `pip install -r requirements-full.txt`.
8. Instalamos los requerimientos: `poetry install`.

Luego, se podrá usar la librería `openbb_terminal.api`.
