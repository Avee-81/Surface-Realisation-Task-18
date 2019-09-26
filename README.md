
# Surface Realization Shared Task 2018

Overview: 
This repository contains the implementation of our approach proposed in the paper

> Avi Chawla, Ayush Sharma, Shreyansh Singh and A.K. Singh: "[IIT (BHU) Varanasi at MSR-SRST 2018: A Language Model Based Approach for Natural Language Generation](https://www.aclweb.org/anthology/W18-3603)". ACL 2018. 

The first workshop on [Surface Realisation](http://taln.upf.edu/pages/msr2018-ws/) organised at ACL 2018 posed the challenge of converting genuine UD structures from which word order information has been removed and the tokens have been lemmatized into their correct sentential form. 

We propose an LSTM-based Encoder-Decoder approach to first reinflect the inflected words in the UD structure. The output is fed to a Language Model based approach which helps us regain the word order information. 

To get an overall understanding of our approach, please go through our final  [report](https://github.com/shreyansh26/SRST-18/blob/master/Reports/srst_report.pdf)  and  [paper](https://github.com/shreyansh26/SRST-18/blob/master/Reports/camera-ready-iit-bhu-varanasi.pdf).

Project File Structure
----------------------

* **Approaches** - The approaches used to solve the problem
	* Best PoS Sequence
	* Language Model
	* Reinflection-Baseline

* **dataset** - The dataset of the shared task

* **resources** - Collection of resources used for reference
