## Requirement
* Tested on Python3.7
* numpy
* pickle
* librosa
* soundfile
* progressbar2
* chainer (7.0.0 was tested) (for MNMF-DP, FastMNMF-DP, ILRMA-DP)
* cupy (7.8.0 was tested) (for GPU accelaration)

## Usage
```
python3 FastMNMF.py [input_filename] --gpu [gpu_id]
```
Input is the multichannel observed signals.  
If gpu_id < 0, CPU is used, and cupy is not necessary.
