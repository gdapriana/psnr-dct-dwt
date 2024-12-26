## PSNR Comparison of MFCC's features extraction using Discrete Wavelet Transform (DWT) and Discrete Cosine Transform (DCT)

This research was conducted to explore and compare the results of Mel Frequency Cepstral Coefficient (MFCC) feature extraction using Discrete Wavelet Transform (DWT) and Discrete Cosine Transform (DCT) based on the Peak Signal-to-Noise Ratio (PSNR) obtained. By comparing the Peak Signal-to-Noise Ratio (PSNR) results of these two methods, it is expected to provide new insights into the advantages and disadvantages of each method in the audio feature extraction process.

### Dataset

dataset used is guitar chord audio sample from a to g major, downloaded from: https://freesound.org/people/danglada/packs/1011/

| title       | sampling rate | duration (s) |
| ----------- | ------------- | ------------ |
| a-major.wav | 22050         | 18.60        |
| e-major.wav | 22050         | 17.52        |
| g-major.wav | 22050         | 20.39        |
| b-major.wav | 22050         | 16.12        |
| d-major.wav | 22050         | 18.56        |
| c-major.wav | 22050         | 19.82        |
| f-major.wav | 22050         | 15.26        |

From the test results that have been carried out using the Peak Signal-to-Noise Ratio (PSNR) against the Discrete Wavelet Transform (DWT) and Discrete Cosine Transorm (DCT) methods at the Mel Frequency Cepstral Coefficient (MFCC) feature extraction stage, it can be concluded that the Discrete Cosine Transorm (DCT) method is better than Discrete Wavelet Transform (DWT) with the highest average value of 168.67.
