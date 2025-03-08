# PAPIE
This repository contains code for the paper [Robust Weakly Supervised Bird Species Detection via Peak Aggregation and PIE]() (under review) by Houtan Ghaffari and Paul Devos.

## What's this?
Peak-Aggregation (PA) is a simple and robust training strategy that alleviates the problem of misleading input-output pairs in very long and weakly labeled audio recordings. You can train your audio classifier using PA if the recordings are challenging. Partial Instance Exchange (PIE) is a data augmentation technique that complements PA to further enhance the model by increasing the fidelity of input-output pairs regarding their weakly assigned labels. PAPIE has nothing to do with your favorite audio classifier or data augmentation. It tackles the stated problem in challenging and long recordings, similar to bird recordings on Xeno-Canto. My work is about bird species classification, so let me know if you tried it on other tasks and it helped.

I never found a paper to address this problem adequately while writing this paper. If you know of any similar method, please let me know. Cheers.

## Code
I left everything in the papie.ipynb.

## Dataset
Run the code in xc_download to get the dataset directly from Xeno-Canto. The metadata file is already curated and contains the peaks and other stuff like labels, train-val-test splits, and lengths. Please do not change the code for parallel or faster downloading in any way, do not remove the sleep timer between the download, and do not spread it for misuse. They will punish you quickly if you start downloading fast and a lot, so don't get curious to lose your access. If your IP got blocked but you were downloading with good intentions and with this same slow single process code, mail Xeno-Canto and ask for help. Good luck!

## Libraries
Main libraries that we used are:
* python: 3.11.9
* pytorch: 2.3.0
* torchaudio: 2.3.0
* torchvision: 0.18.0
* numpy: 1.26.4
* pandas: 2.2.1
* matplotlib: 3.7.1
* tqdm: 4.66.4
* scikit-learn: 1.5.0
* requests: 2.32.2

# Citation
Kindly consider citing the following paper if our results were helpful to your work:

```
```
