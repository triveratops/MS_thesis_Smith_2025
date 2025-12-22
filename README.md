# MS_thesis_Smith_2025
Data files associated with the MS thesis of Alexander Smith, Mizzou, 2025.

Explanation of Files:
-----------------------------------------------------------------

**Geochemistry of the Black Mtn. Gravity Slide** -> file contains all of the major oxide geochemistry in weight percent. Analyses performed using XRF.
- [Major Element Geochemistry](major_elements.csv)
- [Minor and Trace Geochemistry](trace_elements.csv)

**trace_elements.csv** -> File contains all of the minor and trace element geochemistry in ppm. Analyses performed using LA-ICP-MS.

**BGS_####_geochron.csv** -> Files contain the results of LA-ICP-MS spot analyses on Zircons. The data are abundances of U and Pb and Th isotopes, their ratios, and the best age calculated from these isotopes. The `csv` also contains information such as concordance and rejected analyses which may be found at the bottom of the table. For future usage of these data, it is recommended to separate the rejected analyses before manipulating the dataset. 
- The 'Type' column indicates either detrital or igneous zircons
- On import to excel, 7/35 or 6/38 column ID may auto-format to a date. 

**PST_####_geochem.csv** -> Files contain the results of various geochemical methods (written in the file name) performed on the glass or plagioclase portion of pseudotachylyte specimens from this research. 
