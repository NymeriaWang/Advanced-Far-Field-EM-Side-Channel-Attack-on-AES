# Advanced-Far-Field-EM-Side-Channel-Attack-on-AES

This repository provides the code and database used in paper 《Advanced-Far-Field-EM-Side-Channel-Attack-on-AES》, which is published in 7th ACM Cyber-Physical System Security Workshop (CPSS 2021), held in conjunction with ACM AsiaCCS'21, Hong Kong, China, 7 June 2021

Several attacks on AES using far field electromagnetic (EM)emission as a side channel have been recently presented.Unlike power analysis or near filed EM analysis, far fieldEM attacks do not require a close physical proximity to thedevice under attack. However, in all previous attacks tracesfor the profiling stage are also captured at a distance (fixedor variable) from the profiling devices. This degenerates thequality of profiling traces due to noise and interference. Inthis paper, we train deep learning models on "clean" traces,captured through a coaxial cable. Our experiments show thatthe resulting models can extract the AES key from less than500 traces on average captured at 15 m from the victim devicewithout repeating each encryption more than once. This is a 20-fold improvement over the previous attacks which requireabout 10K traces for the same conditions.

The data we used in the experiment can be found in https://drive.google.com/drive/folders/1MdnUKqpKVfrs-lHoO7i0QuLIJyFqmHvd?usp=sharing  
