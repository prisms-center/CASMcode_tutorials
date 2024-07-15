<img alt="Shows the CASM logo" src="https://raw.githubusercontent.com/prisms-center/CASMcode_global/main/python/doc/_static/logo.svg" width="600" />

#### casm-tutorials

This provides CASM tutorials. 

#### Install

Create and activate a conda environment:

    conda create -n casm-tutorials --override-channels -c conda-forge python=3.12 ccache 
    conda activate casm-tutorials

Install:

    git clone https://github.com/prisms-center/CASMcode_tutorials.git
    cd CASMcode_tutorials
    pip install -r requirements.txt


### Getting started

Set `CASM_PREFIX` and start a Jupyter notebook:

    conda activate casm-tutorials
    export CASM_PREFIX=$(python -m libcasm.casmglobal --prefix)
    jupyter notebook

From the Jupyter notebook page, choose one of the tutorial notebooks under the `notebooks` directory (e.g. "Enumeration/SiGe_occ/SiGe_occ.ipynb") to get started.


#### CASM Documentation

See:

- the [CASM online documentation](https://prisms-center.github.io/CASMcode_docs/),
- the [libcasm package docs](https://prisms-center.github.io/CASMcode_pydocs/libcasm/overview/latest/),
- the [casm package docs](https://prisms-center.github.io/CASMcode_pydocs/casm/overview/latest/).


#### About CASM

The repository contains tutorials for the [CASM](https://prisms-center.github.io/CASMcode_docs/) open source software package, which is designed to perform first-principles statistical mechanical studies of multi-component crystalline solids.

CASM is developed by the Van der Ven group, originally at the University of Michigan and currently at the University of California Santa Barbara.

For more information, see the [CASM homepage](https://prisms-center.github.io/CASMcode_docs/).


#### License

GNU Lesser General Public License (LGPL). Please see the file LICENSE for details.

