# Benchmarking CE-Symm 2.2, SymD 1.6, AnAnaS, EncoMPASS and BioJava/PDB
---

To benchmark the algorithms, download the MemSTATS dataset and pdb files, the scripts in this folder, as well as 
the raw output of the symmetry-detection algorithms stored on [Zenodo](https://doi.org/10.5281/zenodo.3228540) and using Python 3.5, run:

> python benchmarking_with_MemSTATS.py

Results are written in the **results/** subfolder.


Prepare for running the analysis by the following:

```bash
pip install -r ../requirements.txt

wget 'https://zenodo.org/record/3228540/files/symmetry_algorithms_data_on_MemSTATS.tar.gz?download=1'                                                                                                                                   
tar xzf symmetry_algorithms_data_on_MemSTATS.tar.gz
tar xzf ../MemSTATS_pdbs.tar.gz

# then run `benchmarking_with_MemSTATS.py`
```

