# Implementation for Improving Clinical Outcome Predictions Using Convolution over Medical Entities with Multimodal Learning


## Usage

1. Clone the code to local.   
```
https://github.com/tanlab/ConvolutionMedicalNer.git
cd ConvolutionMedicalNer
```
2. Run MIMIC-Extract Pipeline as explained in https://github.com/MLforHealth/MIMIC_Extract.   

3. Copy the output file of MIMIC-Extract Pipeline named `all_hourly_data.h5` to `data` folder.

4. Copy the `ADMISSIONS.csv`, `NOTEEVENTS.csv`, `ICUSTAYS.csv` files into `data` folder.

5. Run `select-notes.ipynb` and `preprocess-notes.ipynb` to select the subnotes and preprocess.

6. Run `med7.ipynb` to extract medical entities. 

7. Download pretrained embeddings into `embeddings` folder via link in given References section.

8. Run `all-models.ipynb` to apply all experiments. (timeseries baseline, multimodal baselines, proposed method)


## References

Download the MIMIC-III dataset via https://mimic.physionet.org/

MIMIC-Extract implementation: https://github.com/MLforHealth/MIMIC_Extract

med7 implementation: https://github.com/kormilitzin/med7

Download Pre-trained Word2Vec & FastText embeddings: https://github.com/kexinhuang12345/clinicalBERT

Preprocessing Script: 

