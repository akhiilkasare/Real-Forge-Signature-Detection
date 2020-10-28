# Real-Forge-Signature-Detection

![image](https://assetsds.cdnedge.bluemix.net/sites/default/files/styles/very_big_1/public/feature/images/port_signature.jpg?itok=GazzUq75)



**In this project we have implemented a deep learning research paper it can be found** [here](https://philarchive.org/archive/ALAHSV)


# 1. Introduction

#### What is Signature  verification  and  forgery  detection ?

- Signature  verification  and  forgery  detection  is  the  process  of  verifying  signatures  automatically  and  instantly  to determine  whether  the  signature  is  real  or  not.  There  are  two  main  kinds  of  signature  verification:  static  and dynamic.  Static,  or  offline  verification  is  the  process  of  verifying  a document  signature  after  it  has  been  made, while  dynamic  or  online  verification takes  place  as  a  person  creates  his/her  signature  on  a  digital tablet  or  a similar  device.  The  signature  in  question  is  then  compared  to previous  samples  of  that  person's  signature,  which set  up  the  database.  In the  case  handwritten  signature  on  a  document,  the  computer  needs  the samples  to  be scanned  for  investigation,  whereas  a  digital  signature  which  is  already  stored  in  a  data  format  can  be  used  for signature  verification.  Handwritten  signature  is  one  of  the  most  generally  accepted  personal  attributes for verification with identity whether it may for banking or business.

# 2. Importance of signature verification

* Signature verification is an important biometric technique that aims to detect whether a given signature is genuine or forged. It is essential in preventing falsification of documents in numerous financial, legal, and other commercial settings. This is a comparative analysis of different already known deep learning architectures to check which of those performs the best on the classification. It was solely for offline handwritten signatures.

# 3. Datasets Used :
The datasets are not available publicly . But you can mail the publisher and they would provide the download links orelse you can you the dataset available on kaggle.

# 4. Proposed Methodology

- The  handwritten  signature  is  a  behavioral  biometric  which  is  not  based  on  any  physiology  characteristics  of  the individual signature but on the behavior that change over time. Since an individual's signature alters over time the verification and authentication for the signature may take a long  period which includes the errors to be higher in some  cases.  Inconsistent  signature  leads  to higher  false  rejection  rates  for  an  individual·  who  did  not  sign  in  a consistent way.

# 5. Training The Model

- In  this  application,  we  use  CNNs(or  ConvNet)  which  is  a  class  of  deep,  feed forward  artificial  neural  networks that  has  successfully  been  applied  to analyzing  visual  imagery.  CNNs  were  inspired  by  biological  processes  in that the connectivity pattern between neurons resembles the organization of the animal visual cortex. In our work, 

# 6. Implementation

- In this work, the signature images are stored in a file directory structure which the Keras Python library can work with.  Then the  CNN has  been implemented in python using the  Keras  with the  TensorFlow backend as suggested in the research paper to learn the patterns associated with the signature.

# 8. Model Architecture

![image](https://github.com/akhiilkasare/Real-Forge-Signature-Detection/blob/main/Screenshot%20from%202020-10-29%2002-09-27.png)

# 9.RESULTS 

- In this implementation we were able to **95.5%** accuracy on our validation dataset with 10 epochs 

# 10. Web App Demo

![alt-text](https://github.com/akhiilkasare/Real-Forge-Signature-Detection/blob/main/Animated%20GIF-downsized.gif)

# 11. Motivation

- A model that can learn from signatures and make predictions as to whether the signature in question is a forgery or
not, has been successfully implemented. This model can be deployed at various government offices where handwritten signatures are used as a means of approval or authentication. While this method uses CNNs to learn the signatures,the structure  of our fully connected layer is not optimal. This implementation may be considered extreme. In the model created in this work, two classes are created for each user (Real and forgery).The best accuracy we got was **95.5%**.

