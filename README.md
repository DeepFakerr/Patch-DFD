# Patch-DFD
[Patch-DFD: Patch-based end-to-end DeepFake discriminator](https://dl.acm.org/doi/abs/10.1016/j.neucom.2022.06.013)

## The code is coming

## Experiments Result
### Performance (AUC(%)) of various models on the DeepfakeTIMIT and Celeb-DF datasets.
| Approaches              | TIMIT-LQ | TIMIT_HQ | Celeb-DF |
| ----------------------- | -------- | -------- | -------- |
| Patch-DFD(Resnet-50)    | 99.67    | 99.96    | 99.43    |
| Patch-DFD(Inception-v3) | 98.52    | 98.89    | 98.33    |



### ACC scores of various models on the FaceForensics++ dataset with three quality settings.

| Approaches               | Raw   | C23   | C40   |
| ------------------------ | ----- | ----- | ----- |
| Patch-DFD (Resnet-50)    | 98.15 | 95.65 | 86.52 |
| Patch-DFD (Inception-v3) | 98.28 | 96.82 | 88.20 |

### AUC scores of various models on the FaceForensics++ dataset with three quality settings.

| Approaches               | Raw   | C23   | C40   |
| ------------------------ | ----- | ----- | ----- |
| Patch-DFD (Resnet-50)    | 99.12 | 96.75 | 88.42 |
| Patch-DFD (Inception-v3) | 99.14 | 97.05 | 89.01 |

### Cross-dataset evaluation between TIMIT-HQ, TIMIT-LQ, and Celeb-DF datasets.

| Training Set | Testing Set | ACC   |
| ------------ | ----------- | ----- |
| TIMIT-HQ     | TIMIT-LQ    | 99.70 |
| TIMIT-LQ     | TIMIT-HQ    | 98.15 |
| TIMIT-HQ     | Celeb-DF    | 57.80 |
| Celeb-DF     | TIMIT-HQ    | 49.10 |
| TIMIT-LQ     | Celeb-DF    | 52.14 |
| Celeb-DF     | TIMIT-LQ    | 56.40 |



### Cross-dataset evaluation on Celeb-DF by training on FaceForensics++

| Methods                  | AUC   | Acc   |
| ------------------------ | ----- | ----- |
| Meso-4                   | 54.80 | 52.75 |
| Meso-Inception4          | 53.60 | 55.18 |
| XceptionNet              | 65.30 | 61.58 |
| DSP-FWA                  | 64.60 | 69.72 |
| Multi-Attentional        | 67.44 | 66.29 |
| Patch-DFD (ResNet-50)    | 69.59 | 64.29 |
| Patch-DFD (Inception-v3) | 72.92 | 71.17 |



### Cross-dataset evaluation on DFDC by training on FaceForensics++

| Methods                  | AUC   | Acc   |
| ------------------------ | ----- | ----- |
| Meso-4                   | 59.78 | 51.47 |
| Meso-Inception4          | 58.62 | 54.23 |
| XceptionNet              | 66.75 | 60.74 |
| DSP-FWA                  | 62.78 | 54.76 |
| Multi-Attentional        | 69.14 | 62.75 |
| Patch-DFD (ResNet-50)    | 68.09 | 61.54 |
| Patch-DFD (Inception-v3) | 72.28 | 63.89 |



