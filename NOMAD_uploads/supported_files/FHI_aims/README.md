# FAIRmat training materials 

## Uploading, sharing, and publishing computation data ##
In this example we explain the NOMAD upload function, through which users can upload, share, and publish their research data and relevant files. 

This example specifically focuses on theory and computation data, to which a NOMAD parser is available.

The availability of a NOMAD parser means that NOMAD is able to recognize the file format, read the files, and structure their contents according to predefined schema. 


## RDM topics covered ##
1. Data storage and backup
2. Long-term preservation
2. Data documentation and metadata.
4. Open-science and licenses

## Audience ##
This example is suitable for researchers who are beginner users to NOMAD

## Learning outcomes ##
- Preparing and uploading files of computation research data.
- Modifying generic metadata of a NOMAD upload.
- Sharing and collaboration with colleauges.
- Evaluating the FAIR principles of uploaded entries in NOMAD

## Scientific use case ##
### DFT Calculation for Iron(III) Oxide using *FHI-aims* code###

Iron(III) oxide (Fe₂O₃) is a widely studied material due to its significance in catalysis, energy storage, and electronic applications. Its complex electronic structure and strong correlation effects make it an important test case for computational methods.

**Density Functional Theory (DFT):**

 - DFT is used to investigate the structural, electronic, and magnetic properties of Fe₂O₃. It provides insights into its crystal structure, density of states, and charge distribution.

 - DFT calculations of Fe₂O₃ help in understanding its electronic and optical properties, which are essential for applications in photocatalysis, battery materials, and spintronics. Accurately modeling its band structure and magnetic behavior is crucial for predicting its performance in technological applications.

**Program used to perform the calculation**

These calculations were preformed using the *FHI-aims* code. 

*FHI-aims* an all-electron density-functional-theory package that employs numeric atom-centered basis functions. It is designed for accurate and efficient simulations of molecules, clusters, surfaces, and bulk materials across the periodic table. Its advanced treatment of electronic structure allows for precise calculations of material properties, including band structures, total energies, and magnetic properties. [More information](https://fhi-aims.org/)

NOMAD has a parser for the *FHI-aims* code. This means it can read FHI-aims input and output files and provide all information in NOMAD's unified Metainfo-based Archive format.
[View the parser here!](https://github.com/nomad-coe/electronic-parsers/tree/develop/electronicparsers/fhiaims)

## Tasks ##
1. Create a NOMAD account. [View step-by-step guide.](step-by-step-guides/CreateaNOMADaccount.pdf)
2. Prepare the input and output files in .zip file.[View step-by-step guide.](step-by-step-guides/prepare_files_exciting.md)
3. Create a NOMAD upload. 
4. Add data files to your NOMAD upload. 
4. Share the upload with a colleague.
5. Explore your entires.
6. Understand the data strucutre.

## Files ##
The files used in this example can be downloaded from this [link](files/FHI-aims.zip).

## Additional resources ##

