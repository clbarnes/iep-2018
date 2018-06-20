# N5 export of L1 0111-8

- Full resolution, lossless volumetric image store
- [Open source script](https://gist.github.com/clbarnes/b6e51ab4a52700158b6585ee7e74ca39)

notes:

To make the raw data more amenable to volumetric synapse detection methods,
exported to the Saalfeld lab's N5 format
(solves a number of issues with HDF5, while having a similar design)

Parallel writes, sharing raw datasets among projects, usage with tools like
paintera, bigdataviewer, gunpowder

Allows usage of uncompressed data - JPEG compression artifacts can harm output
