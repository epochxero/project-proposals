### Using Deep Learning to Predict Outcomes for GBM Cancer Patients

## Summary:
Glioblastoma Multiforme (GBM) is a cancer of the glial cells in the Central Nervous System that is graded as the highest grade tumor of all gliomas, with the worst prognosis (just over 1 year). The primary treatment of a GBM is surgery followed by a combination of chemotherapy and radiation therapy. Unfortunately, prognosis is poor even with treatment. MRI scans of the brain, pathology (stained slides of the tumor from surgery viewed under a microscope to help evaluate aggressiveness), and certain genetic tests are done in the primary work-up of a GBM and used to help determine who will benefit from treatment and what that treatment should be. For example, a certain gene profile that is overexpressed in GBM may then become a target of drug therapy, or if we can identify an area on the MRI that is the most suspicious, we could increase the dose of radiation we give to that spot. Through the use of deep learning methods, various "radiomic" signatures can be found using convolutional neural networks (https://www.nature.com/articles/s41598-017-10649-8), "pathomic" signatures (https://www.nature.com/articles/s41698-017-0022-1), or radiogenomic signatures (https://onlinelibrary.wiley.com/doi/epdf/10.1111/jcmm.14328) which can be used to predict prognosis and treatment responses. 

The TCGA-GBM dataset (https://wiki.cancerimagingarchive.net/display/Public/TCGA-GBM) from the Cancer Imaging Archive is a great open source resource that could be used to replicate and extend many of these previously built models. The goals of this project would be to first build a DL/ML model for each type of data (MRIs, pathology and genome) and then try to find overlapping signatures between these models. So for example, seeing if certain signatures in the MRIs correlate with signatures seen in the pathology, and then using these overlapping signatures to predict prognosis and treatment benefit. Another area of interest of mine would be to see if it is possible to match the 2-dimensional pathology data into the 3-dimensional MRI data, as knowing the location the pathology came from can be very important in determining radiation dose (if you had a "positive margin" from surgery which tells you some tumor was left behind, you would want to make sure you get a high dose to the area with a positive margin) - this may not be possible but interested to see if there is anyone with expertise in deep learning to see if we could make such a model.

The overall goal of this proposal would be to publish articles in academic cancer journals. Depending on the expertise of the people who get involved, we could start small (mirror some of the CNNs on the articles listed above and relate to simple questions of treatment) which would certainly get published in lower impact journals, or if there is anyone with higher expertise we can certainly brainstorm on bigger ideas that could be high impact (like the path 2D -> MRI 3D if that was possible) in terms of journals like Nature or high impact in terms of producing software/product. Im definitely open to a long term commitment on these projects, and interested in finding collaborators with various areas of expertise that could help out. My area of expertise is on the medical side and I can certainly provide direction there in terms of brainstorming on what would be helpful for cancer care and of interest to various academic journals.

## Areas of Study
Cancer, Radiation, Radiomics, Genomics, Pathology

## Minimum Required Skills
Python and PyTorch/Tensorflow

## List of Participants
- Nick (PI) - Radiation Oncology Resident Physician
- Sanjay Nagaraj - Participant

