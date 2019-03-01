# hdf2jpg
Convert HDF5 diffraction to JPG 


Simple tool to create JPG from H5 master file. 

## Requires:

[eiger2cbf](https://github.com/biochem-fan/eiger2cbf)

[diff2jpeg](http://www.ccp4.ac.uk/html/DiffractionImage.html)

Python 2.x or 3.x


## Running 

add to your path or run full file path 

hdf2jpg <master.h5> [frameNumber/frameList]

### Example

```hdf2jpg protein_master.h5 0 45 90 135 180```

This will create a JPG of frames 0 45 90 135 180 from protein_master file. 
