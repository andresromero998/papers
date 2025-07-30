Replication of Tellez (2021): "Land, Opportunism, and Displacement in Civil Wars: Evidence from Colombia"
Candidate ID: 42433
Course: MY457 – Causal Inference for Observational and Experimental Studies
LSE, 2025
Software
platform x86_64-w64-mingw32
arch x86_64
os mingw32
crt ucrt
system x86_64, mingw32
status
major 4
minor 5.0
year 2025
month 04
day 11
svn rev 88135
language R
version.string R version 4.5.0 (2025-04-11 ucrt) nickname How About a Twenty-Six

Project Description
This project replicates and reinterprets parts of the analysis in Tellez (2021), focusing on the causal relationship between palm oil expansion and displacement in Colombian municipalities.

The paper authored by Téllez (2021) investigates a critical yet underexplored dimension of civil war dynamics: the role of opportunism in driving forced displacement. Téllez argues that, in a context of weak property rights and following an economic shock in this case, the rise in the value of African palm oil driven by international market prices an ideal scenario emerged in which rural elites colluded with armed groups to forcibly displace civilians and seize their land. He tests this theory using data from Colombia between 1993 and 2005, a period marked by both the rapid expansion of the palm oil industry and intense land-related conflict. I replicate the main tables and figures, did my critical evaluation and finally manage to inlcude new data regardling instituions and the link with with displacement

The analysis is conducted using R and LaTeX, and implemented in a single R Markdown file: 42433_MY457.Rmd.

How to Replicate
Install required packages
Download the dataset as instructed below and place it in the correct folder.
Knit 42433_MY457.Rmd to generate the final PDF output.
Data Access
The dataset used in this replication is not included due to licensing/restrictions. To replicate the analysis:

Visit the Dataverse link from Tellez (2021).
Download the .dta files corresponding to municipal panel data.
Change the directory to your own directory where your data is placed.
Additional data used
The dataset was provided by the Center for Economic Development Studies (CEDE) at the Faculty of Economics, Universidad de los Andes, Colombia, under strict confidentiality conditions. The diccionaries of the data-based are placed on the repositroy in the folder "New data diccionaries".

BG<-PANEL_BUEN_GOBIERNO(2021).dta that gathers information related to revenues, expenses, investment, and performance of local administrations. The main sources of consolidated information are the National Planning Department (DNP) and the Office of the Attorney General.

POB <- ANEL_CARACTERISTICAS_GENERALES(2022).dta for municipal general data, like population, zone

AGRI <- PANEL_AGRICULTURA_Y_TIERRA(2021).dta for annual measures of palm oil cultivation,

C_A <- PANEL_CONFLICTO_Y_VIOLENCIA(2021).dta for indicators of conflict dynamics,
