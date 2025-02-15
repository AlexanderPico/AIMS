# AIMS - An Automated Immune Molecule Separator

# Description
The primary goal of AIMS is to identify discriminating factors between two distinct sets of immune molecules. Currently the software can be applied to
immunoglobulin (Ig) molecules such as T cell receptors and antibodies, and major histocompatibility complex (MHC) and MHC-like molecules. 
AIMS is a python package distributed in both a notebook and GUI format. An example of an application of AIMS can be seen in
this peer-reviewed article: https://elifesciences.org/articles/61393

When publishing analysis from this software, please cite:

Boughter CT, Borowska MT, Guthmiller JJ, Bendelac A, Wilson PC, Roux B, Adams EJ. Biochemical Patterns of Antibody Polyreactivity Revealed Through a Bioinformatics-Based Analysis of CDR Loops. eLife. 2020. DOI: 10.7554/eLife.61393

# Documentation

Rather than have all of the instructions on this GitHub page, all information on installation and usage (and more!) has been moved to a separate, more readable documentation page. Please follow this link:

https://aims-doc.readthedocs.io/en/latest/

For the comprehensive AIMS user guide.

# Acknowledgements
This initial stable build has only been possible through a highly collaborative effort focused on creating a functional pipeline with the incorporated features necessary for thorough repertoire analysis. The following people have made major contributions to this project:

#### Anna Borowska - UX/UI Designer
As the sole graphic designing consultant on the project, Anna helped ensure the initial application was functional, efficient, and as easy to use as possible. Multiple quality control features within the application were added based on suggestions from Anna, and her comprehensive user testing reports ensured critical functionalities were improved. To contact Anna or view her portfolio, see her website: https://annazofiaborowska.com/

#### Marta Borowska - Scientific Consultant/Beta Tester
The initial scientific inquiry behind this project was initiated by Marta, looking at the biochemical mechanisms behind antibody polyreactivity. In addition to her scientific insights, Marta was an early tester of the antibody/TCR software module.

#### Caitlin Castro - Scientific Consultant/Beta Tester
Caitlin, the resource for all things immunology, helped with the initial design and testing of the MHC-like software module. Caitlin also helped with interpretation of results and had critical insights for the improvement of the user experience.

#### Jay Pittman - Beta Tester
Jay was responsible for the earliest tests of the GUI, helping to resolve critical bugs in GUI function on Windows OS. Conversations with Jay helped solidify the application of this approach to more diverse molecules beyond those involved in immune recognition.

#### Erin Adams & Lab - Mentorship/Funding
Erin's expertise and helpful mentoring allowed this project to reach its full potential. Erin was fully supportive of the addition of a new project to the lab, and had great comments for making the analysis pipeline more accessible to experimentalists. Erin's advice has been invaluable throughout. For more information on Erin's lab, see http://ejadamslab.bsd.uchicago.edu/. This project was supported with funding from Erin's National Institutes of Health NIAID grants R01 AI115471 and R01 AI147954.

#### Benoit Roux & Lab - Mentorship/Funding
Benoit provided consistent feedback throughout the project, providing his expertise and insights for all matters biophyscial. Specifically, his insights into the general biophysics of protein-protein interactions helped guide this project. More information on Benoit's lab can be found at http://thallium.bsd.uchicago.edu/RouxLab/. This project was supported with funding from Benoit's National Science Foundation grant MCB-1517221.

#### Martin Flajnik & Lab - MHC Module Collaborators
The MHC module of this project was started due to a collaboration with the Flajnik lab, and sequences used in the mhc_testData directory were isolated by this research group. More information on the Flajnik lab can be found at: https://www.medschool.umaryland.edu/profiles/Flajnik-Martin/ . If utilizing any of the MHC data provided in the mhc_testData directory, please cite:

Almeida T., Esteves P.J., Flajnik M.F., Ohta Y., and Veríssimo A. An Ancient, MHC-Linked, Nonclassical Class I Lineage in Cartilaginous Fish. Journal of Immunology. 2020
