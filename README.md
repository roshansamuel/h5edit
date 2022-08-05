# h5edit

h5edit is a Python-based command-line tool to edit HDF5 files on the fly.
The tool allows to add/edit/remove scalar datasets with floating-point values to and from the HDF5 file.
This is useful for adding metadata to existing HDF5 files.

## Installing h5edit

To install ``h5edit``, you need to only clone the git repository into your local machine

`git clone https://github.com/roshansamuel/h5edit.git`

The executable Python script can be moved to a folder which is included in the PATH environment variable, so that the tool is available at the command-line.

The following modules need to be installed for the app to work:

* numpy
* h5py

## Using h5edit

The command-line arguments used by h5edit are:

```
h5edit [-h] [-e attr val] [-a attr val] [-d attr] f

positional arguments:
  f            input hdf5 file

optional arguments:
  -h, --help   show this help message and exit
  -e attr val  edit attribute (attr) of hdf5 file to value (val)
  -a attr val  add attribute (attr) of hdf5 file to value (val)
  -d attr      delete attribute (attr) from the hdf5 file
```


## License

``h5edit`` is an open-source package made available under the New BSD License.
