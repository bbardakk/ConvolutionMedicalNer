# Implementation for Improving Clinical Outcome Predictions Using Convolution over Medical Entities with Multimodal Learning


## Usage

1. Clone the code to local.   
```
https://github.com/tanlab/ConvolutionMedicalNer.git
cd ConvolutionMedicalNer
```
2. Run experiment on Simulated Data.   
```
python deepTrust.py --dataset simulated
```   
3. Run experiment on Biological Data.   
```
python deepTrust.py --dataset biological
```  

## References

Download the MIMIC-III dataset via https://mimic.physionet.org/

MIMIC-Extract implementation: https://github.com/MLforHealth/MIMIC_Extract

med7 implementation: https://github.com/kormilitzin/med7

Download Pre-trained Word2Vec & FastText embeddings: https://github.com/kexinhuang12345/clinicalBERT

Preprocessing Script: 

