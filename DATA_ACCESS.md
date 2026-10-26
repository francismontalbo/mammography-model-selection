# Dataset sources and attribution

Original mammograms are not distributed here. The repository provides study-generated predictions, numerical evidence and code. Dataset identifiers refer to the existing benchmark records, not independently verified personal identities.

## CBIS-DDSM

R. Sawyer-Lee, F. Gimenez, A. Hoogi and D. Rubin. *Curated Breast Imaging Subset of Digital Database for Screening Mammography (CBIS-DDSM).* The Cancer Imaging Archive, 2016. [Dataset DOI](https://doi.org/10.7937/K9/TCIA.2016.7O02S9CY). The [TCIA collection](https://www.cancerimagingarchive.net/collection/cbis-ddsm/) lists the images and description tables under [CC BY 3.0](https://creativecommons.org/licenses/by/3.0/). See also [A curated mammography data set for use in computer-aided detection and diagnosis research](https://doi.org/10.1038/sdata.2017.177).

This study selected the indexed full mammograms from the mass cohort, consolidated repeated image records and retained the official test cohort. Derived records and labels preserve the documented mass-cohort eligibility and grouping rules. They do not represent a normal-versus-cancer screening sample.

## MIAS

J. Suckling, J. Parker, D. R. Dance, S. Astley, I. Hutt, C. R. M. Boggis, I. Ricketts, E. Stamatakis, N. Cerneaz, S.-L. Kok, P. Taylor, D. Betal and J. Savage. *The Mammographic Image Analysis Society Digital Mammogram Database.* International Congress Series 1069, 375–378, 1994.

The study used the documented MIAS v1.21 PGM inputs and bilateral pairing. The [Cambridge custodian record](https://www.repository.cam.ac.uk/handle/1810/250394) and [Cambridge's release account](https://unlockingresearch-blog.lib.cam.ac.uk/2020/08/26/data-sharing-and-reuse-case-study-the-mammographic-image-society-database/) provide provenance and describe the CC BY release, linking [CC BY 2.0](https://creativecommons.org/licenses/by/2.0/). These links identify the custodian record and reuse basis, not a claim that the experiments used a different acquisition source. Derived domains reflect this study's preprocessing. The source annotations were consolidated under the reported label rules.

## INbreast

I. C. Moreira, I. Amaral, I. Domingues, A. Cardoso, M. J. Cardoso and J. S. Cardoso. *INbreast: Toward a Full-field Digital Mammographic Database.* Academic Radiology 19, 236–248, 2012. [Article DOI](https://doi.org/10.1016/j.acra.2011.09.014). Obtain original data and applicable terms from the dataset custodians identified by that publication.

The study predicts assessment categories rather than uniformly pathology-confirmed malignancy. The public release retains study-generated numerical evidence. Spatial inputs with an unverified redistribution basis are omitted from the two documented public subsets. This does not assert that all INbreast derivatives are restricted. See PUBLIC_RELEASE.md for the precise omissions.

Dataset and software citations remain necessary when reusing the corresponding material. This repository does not grant rights to excluded original images, annotations or upstream weights.
