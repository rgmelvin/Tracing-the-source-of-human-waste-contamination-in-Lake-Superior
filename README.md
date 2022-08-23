# Tracing-the-source-of-human-waste-contamination-in-Lake-Superior
This project traced the source of sewage contamination into Lake Superior by quantifying levels of PMMoV in Lake water samples during summer 2021.

Summer 2020 I monitored water collected at Lake Superior beaches in Duluth, MN for the presence of SARS-CoV-2. At the time it was known that SARS-CoV-2 is shed in the feces of infected individuals but it was unknown if infection could occur via a waterborne route. Since swimming beach frequently become contaminated with coliform bacteria, there was concern over the possiblity of SARS-CoV-2 infection at swimming beaches. 

I collected water samples from 8 beaches every weekend during Summer 2020 and tested for the presence of SARS-CoV-2. I also tested for the presence of the Pepper Mild Mottle Virus (PMMoV), the most common virus found in human waste, as a way to show that we can detect the presence of humans in the water. 

No virus was detected in beach water during the peak tourism months of July and August. In September I began to detect higher levels of PMMoV along with the presence of SARS-CoV-2 at one beach located within the city. This was an odd result as the peak of tourism was over and lake temperatures were now decreasing to where swimming would be very uncomfortable. Sewage contamination was a likely source but there are no streams or stormwater outlets at the beach where SARS-CoV-2 was detected. Later SARS-CoV-2 was detected at other beaches along with increased PMMoV levels.

In 2021 we set out to trace the source of PMMoV. We samppled water from beaches that covered 6miles of lake shore in Duluth, MN. We found that PMMoV levels were higher at sites where streams entered Lake Superior and that the highest PMMoV levels were logged at the mouth of a stream that enters Lake Superior 0.2 miles East of the beach where high levels of PMMoV and SARS-CoV-2 were detected in 2020. This strongly implicates the stream as the source of contamination.

The code that is depostied in this repository loads a .csv file of log(genome_copies of PMMoV/ L of lake water) for each of the monitored sites during Summer 2021 into a Pandas data frame and maps the mean Summer levels to each site.

For publication, we will develop time-course mapping and statistical comparison of PMMoV levels between sites.

Technologies:
Quantitative reverse transcription - polymerase chain reaction (qRT-PCR) using MyGo Pro instrument and analysis software.
JMP to compile data.
Jupyter Notebooks
Python
hvplot

Authors: Emily N. Hendrickson (Biomedical Sciences, U of MN Medical School, Duluth/ La Trobe University, Melbourne), Kennedy Johnson (Bridges to Baccalaureate Program, U of MN Medical School Duluth), Andrea Sutton (Genetics and Environment, La Trobe University, Melbourne), Richard G. Melvin (Biomedical Sciences, Univerisity of Minnesota Medical School, Duluth).

Project was funded by Sea Grant to R.G.Melvin, a Sea Grant Summer Internship to E.N.Hendrickson, and Bridges to Baccalaureate Program to K.Johnson. A.Sutton researched applications of monitoring in sea water and specific monitoring of noro and rotaviruses.

## Files
Jupyter Notebook that maps Log(genome copies of PMMoV/ L)
Helper functions that convert geoposition data in D:M:S to decimal and decimal to D:M:S

