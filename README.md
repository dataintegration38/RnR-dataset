# RnR-dataset

(아직 수정 중입니다. Ver.07.15.)


1. continuous
 - Compustat: HDDT
 - Glass
 - Oil: HDDT
 - Mammography
 - Wine
 - Yeast

The Oil dataset was provided by Robert Holte and is used in their paper (Kubat et al., 1998). This dataset has 41 oil slick samples and 896 non-oil slick samples.

The Mammography dataset (Woods et al., 1993)h as 11,183 samples with 260 calcifications. If we look at predictive accuracy as a measure of goodness of the classifier for this case, the default accuracy would be 97.68% when every sample is labeled noncalcification. But, it is desirable for the classifier to predict most of the calcifications correctly. Mammography is highly unbalanced and records information on calcification in a mammogram.

Oil dataset contains information about oil spills; it is relatively small and very noisy.
(Kubat, M., Holte, R.C., Matwin, S.: Machine Learning for the Detection of Oil Spills in Satellite Radar Images. Machine Learning 30, 195–215 (1998))

2. categorical
 - Boundary: HDDT
 - cam: HDDT
 - car good
 - led
 - phosS: HDDT

Boundary and PhosS are various biological datasets.
PhosS is a dataset of phosphorylation sites for the amino acid serine (S). A phosphorylation site represents a single amino acid (S, T or Y) to/from which
the phosphate group can be attached/detached during cell regulation. A set of examples was constructed by combining PhosphoBase with 832 phosphorylatable proteins extracted from Swiss-Prot. Positive examples were created from 25-residue long fragments centered at all serine residues annotated as phosphorylation sites (the central residue was later excluded from the feature construction process). The remaining serine sites from the same set of proteins were included in the negative set, as phosphorylation was not observed despite assaying the protein. All fragments with sequence identity 30% or more with any other fragments were removed thus making the dataset non-redundant. In cases where one negative and one positive fragment were similar, the negative fragment was eliminated as less reliably labeled.

Positive examples of the Boundary dataset were constructed using a set of 24-residue long sequence fragments around order/disorder boundaries extracted from a set of 151 proteins containing 161 disordered regions at least 30 residues in length. One half of the negative set was built from a set of 290 non-redundant completely ordered proteins while the other half was built using non-boundary fragments from the existing set of 161 disordered regions. Balance of completely ordered and disordered segments in the negative set was maintained in order to prevent the predictor from adapting to protein disorder anywhere in the sequence.

The CAM dataset was built from 40 non-redundant proteins containing 42 calmodulin binding regions selected from the Calmodulin Target Database. The set of positive instances was built using 42 regions that represent three classes of calmodulin targets whose binding activity depends on the concentration of calcium. The negative set consists of all residues not involved in calmodulin binding from the same set of 40 proteins. A sliding window of length 15 was used to create data examples. Seven terminal residues were excluded from all proteins.

Predrag Radivojac, Nitesh V. Chawla, A. Keith Dunker, Zoran Obradovic, Classification and knowledge discovery in protein databases, Journal of Biomedical Informatics, Volume 37, Issue 4, 2004, Pages 224-239, ISSN 1532-0464, https://doi.org/10.1016/j.jbi.2004.07.008.

3. Mixed
 - Abalone
 - Flare-F
 - Hypo: HDDT
 - Sick
 - Vowel0

![initial](https://user-images.githubusercontent.com/54100174/124717040-b787dc00-df3f-11eb-8e5d-4ea2ddc0806b.PNG)
