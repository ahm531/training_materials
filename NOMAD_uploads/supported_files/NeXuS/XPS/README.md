# FAIRmat training materials 

## Uploading, sharing, and publishing experimental data (XPS) ##
In this example we explain the NOMAD upload function, through which users can upload, share, and publish their research data and relevant files. 

This example specifically focuses on experimental data, to which a NOMAD parser is available.

The availability of a NOMAD parser means that NOMAD is able to recognize the file format, read the files, and structure their contents according to predefined schema. 


## RDM topics covered ##
1. Data storage and backup
2. Long-term preservation
2. Data documentation and metadata.
4. Open-science and licenses

## Audience ##
This example is suitable for researchers who are beginner users to NOMAD

## Learning outcomes ##
- Uploading files of XPS research data in the NeXuS format `.nxs` to NOMAD.
- Use the NOMAD nexus data converter to convert raw files in `.xml` format from SPECS instrument to `.nxs` format.
- Ensure that the uploaded data and the corresponding metadata comply with the community standard by providing ELN files.
- Modifying generic metadata of a NOMAD upload.
- Sharing and collaboration with colleauges.
- Evaluating the FAIR principles of uploaded entries in NOMAD

## Scientific use case ##
### X-ray photoelectron spectroscopy on the polymer PBTTT###
Poly(2,5-bis(3-tetradecylthiophen-2-yl)thieno[3,2-b]thiophene) (PBTTT) is a high-performance semiconducting polymer widely studied for its applications in organic electronics. Understanding its electronic structure and surface chemistry is essential for optimizing its performance in devices such as organic field-effect transistors (OFETs) and organic photovoltaics (OPVs).

**X-ray Photoelectron Spectroscopy (XPS)**
- *Purpose:* XPS is used to analyze the elemental composition, chemical states, and electronic structure of PBTTT thin films. This technique helps in identifying oxidation states, contamination, and molecular interactions at the surface.
- *Typical measurements:* XPS routine measurements typically start with running a survey scan to identify elements present in the sample. High-resolution scans are then performed in regions of specific element to reveal more information about the chemical states of the material. 

**Scientific Relevance:**

By applying XPS to PBTTT, researchers can evaluate how molecular packing, doping, and environmental factors influence the material’s electronic properties. These insights are critical for the design and optimization of organic electronic devices.

**Instrument used to perform the experiment**

These XPS measurements were preformed using a SPECS instrument. 
The raw files produced form this instrument can be stored in various formats: `.xml`, `.sle`, or `.xy`.


NOMAD has a parser for experimental data in the NeXus file format. For raw files produced from vendors that are not in the NeXus format, NOMAD offers a data converter that maps the data in these files to the `.nxs` format. To ensure compliance with community standards, the data converter allows for the inclusion of an ELN files that are filled manually by the user, which gets combined with the raw data files, and provide NOMAD entries with rich metadata. 
[View the parser here!]()

## Tasks ##
1. Create a NOMAD account. [View step-by-step guide.](step-by-step-guides/CreateaNOMADaccount.pdf)
2. Create a NOMAD upload. 
3. Add data files to your NOMAD upload. 
4. Share the upload with a colleague.
5. Explore your entires.
6. Understand the data strucutre.

## Files ##
The files used in this example can be downloaded from this [link]().

## Step-by-step guide ##
### *Direct upload of `.nxs` file* ###
### *Use NOMAD data converter to upload `.xml` file* ###
### *Use NOMAD data converter to upload `.xml` file with your ELN file* ###

## Additional resources ##

