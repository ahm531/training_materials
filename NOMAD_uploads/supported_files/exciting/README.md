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
### DFT and GW Calculations for Silicon using *exciting* code###
Silicon is a fundamental material in the semiconductor industry and a model system for condensed-matter physics. Its electronic structure and properties are well understood, making it an excellent test case for advanced computational methods.

**Density Functional Theory (DFT):**
- *Purpose:* DFT is widely used to calculate the ground state electronic properties of materials. For silicon, DFT provides insight into its crystal structure, band structure, and charge density.
- *Limitations:* While DFT is computationally efficient and accurate for many ground-state properties, it often underestimates the bandgap of semiconductors due to its approximate treatment of exchange-correlation effects.

**GW Approximation:**
- *Purpose:* The GW method corrects the band gap underestimation in DFT by incorporating many-body interactions between electrons. This is critical for accurately predicting the quasiparticle energies and optical properties of materials such as silicon.
- *Key output:* GW calculations provide more accurate band gaps and quasiparticle energies, which are essential for the design and understanding of electronic and optoelectronic devices.

**Scientific Relevance:**

Together, these methods allow researchers to predict and validate material properties critical to applications in electronics, photovoltaics, and quantum technologies.

The calculated properties of silicon, such as band gap and effective mass, directly affect the performance of transistors and solar cells.

**Program used to perform the calculation**

These calculations were preformed using the *exciting* code. 

*exciting* is a full-potential all-electron density-functional-theory package implementing linearized augmented planewave methods. It can be applied to all kinds of materials, irrespective of the atomic species involved and allows for exploring the physics of core electrons. [More information on this link](https://exciting-code.org/)

NOMAD has a parser for the *exciting* code. This means it will read exciting input and output files and provide all information in NOMAD's unified Metainfo based Archive format.
[View the parser here!](https://github.com/nomad-coe/nomad-parser-exciting)
## Tasks ##
1. Create a NOMAD account. [View step-by-step guide.](step-by-step-guides/CreateaNOMADaccount.pdf)
2. Prepare the input and output files in .zip file.[View step-by-step guide.](step-by-step-guides/prepare_files_exciting.md)
3. Create a NOMAD upload. 
4. Add data files to your NOMAD upload. 
4. Share the upload with a colleague.
5. Explore your entires.
6. Understand the data strucutre.

## Files ##
The files used in this example can be downloaded from this [link](files/Si_gw.zip).

## Additional resources ##

