# An Attack on High Rate McEliece Cryptosystems Using Generalized Reed Solomon Codes with Weight 2 Mask



## Overview

This repository contains code to execute the attack on McEliece type cryptosystems using GRS codes with a weight 2 mask. It is meant as a supplement to our paper. This repository contains a SageMath implementation of our method which attacks the variation of the McEliece cryptosystem as proposed in [1]. 

## Description

We include a brief overview of the description of the files included in the repo. 
- [Coding_Crypto_Lib](Coding_Crypto_Lib.ipynb) : Contains functions necessary for the other files.
- [GRS_classical_square_code_attack_Lib](GRS_classical_square_code_attack_Lib.ipynb) : Contains an implementation of the classical attack on GRS code based McEliece cryptosystems using a square code distinguisher.
- [GRS_Functions_Attack](GRS_Functions_Attack.ipynb): Contains functions necessary for the final attack, and contains implementatins of Algorithms 1 through 4 of our paper. 
- [Run_Attack](Run_Attack.ipynb) : It takes as input public keys from the high rate regime of the scheme described in [1], and runs our attack on each of them, recovering the secret key.
- [masked_grs_mats](masked_grs_mats.txt) : Contains public keys from the high rate regime of the scheme described in [1].



## References

<a id="1">[1]</a> Violetta Weger. “A Code-Based Cryptosystem using GRS codes”. MA thesis. University of Zurich, 2016 [https://user.math.uzh.ch/weger/mathesis.pdf](https://user.math.uzh.ch/weger/mathesis.pdf)
