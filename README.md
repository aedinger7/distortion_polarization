# Cognitive distortions in political polarization.
by Andy Edinger, Johan Bollen, Hernán A. Makse, and Matteo Serafino

https://arxiv.org/abs/XYZXYZ

By using this code, you agree to the following terms:

1) The code is provided "as is" without any warranties or guarantees of any kind.
2) We assume no responsibility for errors or omissions in the results or interpretations derived from using this code.
3) You agree to cite our paper (linked above) in any publications that utilize this code.

The folder CDS/translations contains content-free n-grams representing 12 types of cognitive distortions.
The file _CDS_.py helps identify these n-grams within a given text or dataframe of texts. 
Please note that this step requires access to the raw data. The 'Intermediate_data' folder contains the
users' information after this step has been completed.

In the 'Intermediate_data' folder, we include users' IDs and their classifications in terms of latent ideology and CDS (Cognitive Distortion Score) prevalence, as explained in the main paper.
The raw dataset, which contains the tweet IDs referenced in the article, can be accessed here: https://osf.io/e395q/.

The notebook "cds_prevalence.ipynb" contains the code to produce initial CDS measures from the raw tweet data, as well as to produce the values and sample tweets in Table 1. CDS_category_bootstrap contains the analysis code relevant to Fig. 2. Both of these notebooks require raw Tweet data that is not included in this Git repository, but is accessible above.

By running the notebook distortion_polarization.ipynb, you can reproduce all the statistical tests and plots featured in the main paper.

Please refer to the paper for further clarifications. 
