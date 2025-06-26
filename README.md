# Countering Side-Channel Attacks with a Dynamic S-box Based on Affine Transformations and Gold Sequences
This repository provides download links for obtaining associated trace files related to the article "Countering Side-Channel Attacks with a Dynamic S-box Based on Affine Transformations and Gold Sequences".

## We provide details on comparing four case studies:
- Unprotected or Normal AES (CS-0): The unprotected implementation is used as a baseline.
- Fixed AES-TFM (CS-1): The protected design with Mask SubBytes that was introduced in https://ieeexplore.ieee.org/document/9852062.
- Dynamic AES-TFM (CS-2): This is our ISCAS version using the enhanced TFM scheme with affine transformation-based dynamic S-boxes. The number of samples for each measured trace in the CS-0, CS-1, and CS-2 scenarios is constant and equals 1,200.
- Hiding- and masking-based countermeasures (CS-3): The final database contains measurements when running the AES core with GoldSeq signal. Therefore, the targeted implementation is protected by both hiding and masking countermeasures. This dataset provides 6M raw power traces, each trace with a length of 4,000 samples.

## Side-channel analysis datasets.
In the academic community, the most used datasets in deep learning-based SCA are ASCAD trace sets from ANSSI (France) github repository. The authors of ASCAD repository delivered source code to generate .h5 datasets according to their specific format.
Therefore, we provide our measurements in .h5 datasets with their download links.
