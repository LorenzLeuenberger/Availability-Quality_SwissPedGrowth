# Availability and Quality - SwissPedGrowth
This GitHub repository shares the analysis code used for the manuscript "Availability and Quality of Anthropometric Data in Swiss Children’s Hospitals: The SwissPedGrowth Project".

# Analysis scripts

00_data-cleaning.Rmd was used to clean the data. Prior to this, RDF graph data was received from the SwissPedHealth National Data Stream ([www.swisspedhealth.com](https://www.swisspedhealth.com/)) and was flattened into tabular .csv format using SPARQL queries. SwissPedHealth used a standard operating procedure to link the Swiss-SEP to the NDS: [LorenzLeuenberger/Transforming-addresses-to-Swiss-SEP_Standard-operating-procedure](https://github.com/LorenzLeuenberger/Transforming-addresses-to-Swiss-SEP_Standard-operating-procedure)

01_data-availability-quality.Rmd was used to analyze the data and create the figures and tables for the manuscript.
