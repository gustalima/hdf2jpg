# hdf2jpg
Convert HDF5 diffraction to JPG 


Simple tool to create JPG from H5 master file. 

## Requires:

[eiger2cbf] (https://github.com/biochem-fan/eiger2cbf)
[diff2jpeg] (http://www.ccp4.ac.uk/html/DiffractionImage.html)


## Running 

add to your path or run full file path 

hdf2jpg <master.h5> [fragmeNumber]

### Example

```hdf2jpg protein_master.h5 45```

This will create a JPG of frame 45 from protein_master file. 
