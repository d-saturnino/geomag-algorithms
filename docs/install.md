Installation
============



1) Install Python and dependencies (obspy and pycurl)

    Using Anaconda is recommended ( https://conda.io/miniconda.html ).

        conda config --add channels conda-forge
        conda create --name geomagenv obspy pycurl
        source activate geomagenv


2) Install **geomagio**

        pip install git+https://github.com/usgs/geomag-algorithms.git


3) Use **geomagio**

    - Use the main script, `geomag.py -h`
    - In python scripts, `import geomagio`
    - Interactively with Jupyter notebooks ( http://jupyter.org/install.html )
