# dmp

I am not completely sure what stands behind "Quantitative dataset". If it is the actual data collected from the telescope, the size is, depending on the telescope, tens of Tb to some of Pb.

The data management is outsourced to archives (of ESA, ESO, etc). Archives for some of the key observatories in our work are following the OAIS standard http://www.oais.info/  . This would fall in the "Existing datasets" (some of them grow with time), first part of section 3.1 .

If "Quantitative dataset" is rather high-level data products (outputs of workflows, including likely those made by galaxy) - they would be, to a degree, also ingested to these archives.

In some cases we will prefer to publish them in zenodo or similar national infrastuctures  (e.g. https://olos.swiss/).

Selecting, handling, and describing data formats is also responsibility of the archives. It is typically FITS, HDF5, and in some cases perhaps indeed ROOT (as written in the DMP).

It is a subject of some needed work, how to reconcile astrophysical data preservation in archives with RO-Crate and other aspects of our project.

On the other hand, the volume of the metadata describing these quantitative data is probably going to be within 10Gb (a wild guess) and the formats are like those in the other parts of the project.

This whole business with archives is deep tradition and long history in astronomy, as it is sometimes still useful to look into centuries-old data: we can not really ever repeat the experiments since the Universe just happens to us. 
