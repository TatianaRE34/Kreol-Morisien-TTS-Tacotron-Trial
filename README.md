**Tacotron TTS For mauritian creole**
The main code was slightly edited to allow trainig of the mauritian creole. 

**Dataset**
KreolDataset currently has 1k sentences, is approximately 2hrs.

**run in conda**
   -Python Conda 
   conda activate python3.7
   cd D:\tacotron
   python preprocess.py --dataset kmtts
   python train.py