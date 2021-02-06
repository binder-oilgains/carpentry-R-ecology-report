# BUILD


* Builds an RStudio environment. Anaconda included
* Installs the following packages
    ```
    install.packages("gridExtra") # Download and install gridExtra
    install.packages("hexbin") # Download and install hexbin
    install.packages("tidyverse") # Download and install tidyverse
    install.packages("lubridate")
    install.packages("readr")
    install.packages("ggplot2")
    install.packages("dplyr")
    install.packages("magrittr")
    install.packages("tidyr")
    install.packages("knitr")
    install.packages("tidyverse")
    install.packages("shiny")
    install.packages("DT")
    install.packages("rmarkdown")
    install.packages("caTools")
    install.packages("bitops")
    install.packages("rprojroot")
    ```



* R version from `2019-03-17`. See `runtime.txt`.

*   Run `final-report.Rmd` in RStudio

    ![image-20210206100604653](assets/BUILD/image-20210206100604653.png)

*   R-3.6.3

*   RStudio 1.2.5001

*   HTML report generated from RStudio

![image-20210206100736773](assets/BUILD/image-20210206100736773.png)



*   Anaconda version: 4.9.2

```
conda info
```



![image-20210206101034228](assets/BUILD/image-20210206101034228.png)

```
conda info --envs
```



![image-20210206101230745](assets/BUILD/image-20210206101230745.png)





## After adding environment.yml

```
channels:
  - conda-forge
dependencies:
  - numpy
  - matplotlib
  - pandas
```



## List Python packages through RStudio terminal

```
conda init bash
source ~/.bashrc
conda activate notebook
conda list
```



```
(notebook) jovyan@jupyter-binder-2doilgains-2d-2decology-2dreport-2d27f3s86n:~$ conda list
```

```

# packages in environment at /srv/conda/envs/notebook:
#
# Name                    Version                   Build  Channel
_libgcc_mutex             0.1                 conda_forge    conda-forge
_openmp_mutex             4.5                       0_gnu    conda-forge
aiohttp                   3.7.3                    pypi_0    pypi
alembic                   1.4.2              pyh9f0ad1d_0    conda-forge
async-timeout             3.0.1                    pypi_0    pypi
async_generator           1.10                       py_0    conda-forge
attrs                     19.3.0                     py_0    conda-forge
backcall                  0.2.0              pyh9f0ad1d_0    conda-forge
bleach                    3.1.5              pyh9f0ad1d_0    conda-forge
blinker                   1.4                        py_1    conda-forge
brotlipy                  0.7.0           py37h8f50634_1000    conda-forge
ca-certificates           2020.6.20            hecda079_0    conda-forge
certifi                   2020.6.20        py37hc8dfbb8_0    conda-forge
certipy                   0.1.3                      py_0    conda-forge
cffi                      1.14.0           py37hd463f26_0    conda-forge
chardet                   3.0.4           py37hc8dfbb8_1006    conda-forge
cryptography              3.0              py37hb09aad4_0    conda-forge
cycler                    0.10.0                     py_2    conda-forge
dbus                      1.13.18              hb2f20db_0    defaults
decorator                 4.4.2                      py_0    conda-forge
defusedxml                0.6.0                      py_0    conda-forge
entrypoints               0.3             py37hc8dfbb8_1001    conda-forge
expat                     2.2.10               h9c3ff4c_0    conda-forge
fontconfig                2.13.1            hba837de_1004    conda-forge
freetype                  2.10.4               h0708190_1    conda-forge
gettext                   0.19.8.1          hf34092f_1004    conda-forge
glib                      2.66.3               h58526e2_0    conda-forge
gst-plugins-base          1.14.5               h0935bb2_2    conda-forge
gstreamer                 1.14.5               h36ae1b5_2    conda-forge
icu                       64.2                 he1b5a44_1    conda-forge
idna                      2.10               pyh9f0ad1d_0    conda-forge
importlib-metadata        1.7.0            py37hc8dfbb8_0    conda-forge
importlib_metadata        1.7.0                         0    conda-forge
ipykernel                 5.3.4            py37h43977f1_0    conda-forge
ipython                   7.16.1           py37h43977f1_0    conda-forge
ipython_genutils          0.2.0                      py_1    conda-forge
ipywidgets                7.5.1                      py_0    conda-forge
jedi                      0.17.2           py37hc8dfbb8_0    conda-forge
jinja2                    2.11.2             pyh9f0ad1d_0    conda-forge
jpeg                      9d                   h516909a_0    conda-forge
json5                     0.9.4              pyh9f0ad1d_0    conda-forge
jsonschema                3.2.0            py37hc8dfbb8_1    conda-forge
jupyter-offlinenotebook   0.1.0                    pypi_0    pypi
jupyter-rsession-proxy    1.1                      pypi_0    pypi
jupyter-server-proxy      1.4.0                    pypi_0    pypi
jupyter-shiny-proxy       1.1                      pypi_0    pypi
jupyter_client            6.1.6                      py_0    conda-forge
jupyter_core              4.6.3            py37hc8dfbb8_1    conda-forge
jupyter_telemetry         0.0.5                      py_0    conda-forge
jupyterhub-base           1.1.0                    py37_2    conda-forge
jupyterhub-singleuser     1.1.0                    py37_2    conda-forge
jupyterlab                2.2.0                      py_0    conda-forge
jupyterlab_server         1.2.0                      py_0    conda-forge
kiwisolver                1.3.1            py37h2527ec5_1    conda-forge
krb5                      1.17.1               hfafb76e_1    conda-forge
lcms2                     2.11                 hcbb858e_1    conda-forge
ld_impl_linux-64          2.34                 h53a641e_7    conda-forge
libblas                   3.9.0                8_openblas    conda-forge
libcblas                  3.9.0                8_openblas    conda-forge
libclang                  9.0.1           default_hde54327_0    conda-forge
libcurl                   7.71.1               hcdd3856_3    conda-forge
libedit                   3.1.20191231         h46ee950_1    conda-forge
libffi                    3.2.1             he1b5a44_1007    conda-forge
libgcc-ng                 9.3.0               h2828fa1_18    conda-forge
libgfortran-ng            7.5.0               h14aa051_18    conda-forge
libgfortran4              7.5.0               h14aa051_18    conda-forge
libglib                   2.66.3               hbe7bbb4_0    conda-forge
libgomp                   9.3.0               h2828fa1_18    conda-forge
libiconv                  1.16                 h516909a_0    conda-forge
liblapack                 3.9.0                8_openblas    conda-forge
libllvm9                  9.0.1                hf817b99_2    conda-forge
libopenblas               0.3.12          pthreads_hb3c22a3_1    conda-forge
libpng                    1.6.37               hed695b0_2    conda-forge
libsodium                 1.0.17               h516909a_0    conda-forge
libssh2                   1.9.0                hab1572f_4    conda-forge
libstdcxx-ng              9.3.0               h6de172a_18    conda-forge
libtiff                   4.2.0                hdc55705_0    conda-forge
libuuid                   2.32.1            h14c3975_1000    conda-forge
libwebp-base              1.2.0                h7f98852_0    conda-forge
libxcb                    1.14                 h7b6447c_0    defaults
libxkbcommon              0.10.0               he1b5a44_0    conda-forge
libxml2                   2.9.10               hee79883_0    conda-forge
lz4-c                     1.9.3                h9c3ff4c_0    conda-forge
mako                      1.1.0                      py_0    conda-forge
markupsafe                1.1.1            py37h8f50634_1    conda-forge
matplotlib                3.3.4            py37h89c1867_0    conda-forge
matplotlib-base           3.3.4            py37h0c9df89_0    conda-forge
mistune                   0.8.4           py37h8f50634_1001    conda-forge
multidict                 5.1.0                    pypi_0    pypi
nbconvert                 5.6.1            py37hc8dfbb8_1    conda-forge
nbformat                  5.0.7                      py_0    conda-forge
nbresuse                  0.3.3                      py_0    conda-forge
ncurses                   6.2                  he1b5a44_1    conda-forge
notebook                  6.0.3            py37hc8dfbb8_1    conda-forge
nspr                      4.29                 he1b5a44_1    conda-forge
nss                       3.55                 he751ad9_0    conda-forge
nteract_on_jupyter        2.1.3                      py_0    conda-forge
numpy                     1.20.0           py37haa41c4c_0    conda-forge
oauthlib                  3.0.1                      py_0    conda-forge
olefile                   0.46               pyh9f0ad1d_1    conda-forge
openssl                   1.1.1g               h516909a_0    conda-forge
packaging                 20.4               pyh9f0ad1d_0    conda-forge
pamela                    1.0.0                      py_0    conda-forge
pandas                    1.2.1            py37hdc94413_0    conda-forge
pandoc                    2.10.1               h516909a_0    conda-forge
pandocfilters             1.4.2                      py_1    conda-forge
parso                     0.7.1              pyh9f0ad1d_0    conda-forge
pcre                      8.44                 he1b5a44_0    conda-forge
pexpect                   4.8.0            py37hc8dfbb8_1    conda-forge
pickleshare               0.7.5           py37hc8dfbb8_1001    conda-forge
pillow                    8.1.0            py37he6b4880_1    conda-forge
pip                       20.1.1                     py_1    conda-forge
prometheus_client         0.8.0              pyh9f0ad1d_0    conda-forge
prompt-toolkit            3.0.5                      py_1    conda-forge
psutil                    5.7.2            py37h8f50634_0    conda-forge
ptyprocess                0.6.0                   py_1001    conda-forge
pycparser                 2.20               pyh9f0ad1d_2    conda-forge
pycurl                    7.43.0.5         py37hce7685b_2    conda-forge
pygments                  2.6.1                      py_0    conda-forge
pyjwt                     1.7.1                      py_0    conda-forge
pyopenssl                 19.1.0                     py_1    conda-forge
pyparsing                 2.4.7              pyh9f0ad1d_0    conda-forge
pyqt                      5.12.3           py37h8685d9f_3    conda-forge
pyqt5-sip                 4.19.18                  pypi_0    pypi
pyqtchart                 5.12                     pypi_0    pypi
pyqtwebengine             5.12.1                   pypi_0    pypi
pyrsistent                0.16.0           py37h8f50634_0    conda-forge
pysocks                   1.7.1            py37hc8dfbb8_1    conda-forge
python                    3.7.8           h6f2ec95_0_cpython    conda-forge
python-dateutil           2.8.1                      py_0    conda-forge
python-editor             1.0.4                      py_0    conda-forge
python-json-logger        0.1.11                     py_0    conda-forge
python_abi                3.7                     1_cp37m    conda-forge
pytz                      2021.1             pyhd8ed1ab_0    conda-forge
pyzmq                     19.0.1           py37hac76be4_0    conda-forge
qt                        5.12.5               hd8c4c69_1    conda-forge
readline                  8.0                  he28a2e2_2    conda-forge
requests                  2.24.0             pyh9f0ad1d_0    conda-forge
ruamel.yaml               0.16.6           py37h8f50634_1    conda-forge
ruamel.yaml.clib          0.2.0            py37h8f50634_1    conda-forge
send2trash                1.5.0                      py_0    conda-forge
setuptools                49.2.0           py37hc8dfbb8_0    conda-forge
simpervisor               0.4                      pypi_0    pypi
six                       1.15.0             pyh9f0ad1d_0    conda-forge
sqlalchemy                1.3.18           py37h8f50634_0    conda-forge
sqlite                    3.32.3               hcee41ef_1    conda-forge
terminado                 0.8.3            py37hc8dfbb8_1    conda-forge
testpath                  0.4.4                      py_0    conda-forge
tk                        8.6.10               hed695b0_0    conda-forge
tornado                   6.0.4            py37h8f50634_1    conda-forge
traitlets                 4.3.3            py37hc8dfbb8_1    conda-forge
typing-extensions         3.7.4.3                  pypi_0    pypi
urllib3                   1.25.10                    py_0    conda-forge
wcwidth                   0.2.5              pyh9f0ad1d_0    conda-forge
webencodings              0.5.1                      py_1    conda-forge
wheel                     0.34.2                     py_1    conda-forge
widgetsnbextension        3.5.1            py37hc8dfbb8_1    conda-forge
xz                        5.2.5                h516909a_1    conda-forge
yarl                      1.6.3                    pypi_0    pypi
zeromq                    4.3.2                he1b5a44_2    conda-forge
zipp                      3.1.0                      py_0    conda-forge
zlib                      1.2.11            h516909a_1006    conda-forge
zstd                      1.4.8                ha95c52a_1    conda-forge
```



