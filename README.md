# Resources for Morphing Attack
## Code, data, and model collections publicly available.

> [!NOTE]
> Cite the original paper if you use the implementation on this page!

> [!IMPORTANT]
> It is forbidden to use the following S-MAD and D-MAD models on FVC and NIST benchmarks without the consent of the authors.


### D-MAD models
- *A double siamese framework for differential morphing attack detection* (Borghi et al., Sensors 2021)
  - [Original paper](https://www.mdpi.com/1424-8220/21/10/3466)
  - [Resource](https://github.com/ndido98/siamese)
  - Code: Python, PyTorch
  - Training datasets: PMDB, MorphDB, Idiap-morph datasets 
  - Notes: official implementation, tested on FVC (SOTAMD_D-1.0 EER = 23.37%)
 
- *Combining identity features and artifact analysis for Differential Morphing Attack Detection* (Di Domenico et al., ICIAP 2023)
  - [Original paper](https://github.com/gdubrg/morphing-attack-resources/blob/main/ICIAP_2023.pdf)
  - [Resource](https://github.com/ndido98/iciap-2023)
  - Training datasets: PMDB, MorphDB, Idiap-morph
  - Notes: official implementation, tested on FVC (on going)
    
- *Deep Face Representations for Differential Morphing Attack Detection* (Scherag et al., TIFS 2020)
  - [Original paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9093905)
  - [Resource](https://github.com/gdubrg/MAD-Tools)
  - Code: Python, PyTorch, MXNet
  - Training datasets: PMDB
  - Notes: unofficial implementation, tested on FVC (MORPHDB_D-1.0 EER = 0.0%)

### S-MAD models
- *UBO-SMAD-R3: an Inception-ResNet-based model for Single-image Morphing Attack Detection*
  - [Resource](https://github.com/ndido98/ubo-smad-r3)
  - Code: Python, PyTorch
  - Training datasets: PMDB, MorphDB, Idiap-morph, Chimo
  - Notes: tested on FVC-onGoing (SOTAMD_D-1.0 EER = 10.33%) 

### Frameworks, Scripts and other resources
- *Revelio* framework
  - Revelio is a framework to simplify D-MAD and S-MAD model development
  - [Resource](https://github.com/ndido98/revelio)
  - [Documentation](https://ndido98.github.io/revelio/)
- FVC-onGoing platform
  - [Link](https://biolab.csr.unibo.it/fvcongoing/UI/Form/Home.aspx)
  - S-MAD and D-MAD evaluations on sequestered datasets. 
- FRVT MORPH
  - [Link](https://pages.nist.gov/frvt/html/frvt_morph.html)
  - S-MAD and D-MAD evaluations on sequestered datasets. 

### Datasets
- Public
  - Idiap-morph
    - [Idiap-FRLL](https://www.idiap.ch/en/dataset/frll-morphs)
    - [Idiap-FRGC](https://www.idiap.ch/en/dataset/frgc-morphs)
    - [Idiap-FERET](https://www.idiap.ch/en/dataset/feret-morphs)
- Private
  - PMDB
  - MorphDB (only for evaluation on the FVC platform)  
