# Countering Side-Channel Attacks with a Dynamic S-box Based on Affine Transformations and Gold Sequences
This repository provides download links for obtaining associated trace files related to the article "Countering Side-Channel Attacks with a Dynamic S-box Based on Affine Transformations and Gold Sequences".

We provide details on comparing four case studies:
- Unprotected or Normal AES (CS-0): The unprotected implementation is used as a baseline.
- Fixed AES-TFM (CS-1): The protected design with Mask SubBytes that was introduced in https://ieeexplore.ieee.org/document/9852062.
- Dynamic AES-TFM (CS-2): This is our ISCAS version using the enhanced TFM scheme with affine transformation-based dynamic S-boxes. The number of samples for each measured trace in the CS-0, CS-1, and CS-2 scenarios is constant and equals 1,200.
- Hiding- and masking-based countermeasures (CS-3): The final database contains measurements when running the AES core with GoldSeq signal. Therefore, the targeted implementation is protected by both hiding and masking countermeasures. This dataset provides 12M raw power traces (i.e., distinguishes two groups of measurements, one for fixed and one for random inputs), each trace with a length of 4,000 samples.
