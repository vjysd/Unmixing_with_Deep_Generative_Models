#  Deep Generative Endmember Modeling: An Application to Unsupervised Spectral Unmixing    #



This is the authors' implementation of [1].

The code is implemented in MATLAB and includes:  
-  example1.m                - a demo script comparing the algorithms (DC1)  
-  example2.m                - a demo script comparing the algorithms (DC2)  
-  ./DeepGUn/                - contains the MATLAB files associated with the DeepGUn algorithm
-  ./python/                 - contains the Python files associated with the DeepGUn algorithm
-  ./other_methods/          - contains the ELMM, GLMM and PLMM methods
-  ./utils/                  - useful functions
-  ./data/                   - images used in the examples
-  README                    - this file  



## IMPORTANT:
If you use this software please cite the following in any resulting
publication:

    [1] Deep Generative Endmember Modeling: An Application to Unsupervised Spectral Unmixing
        R.A. Borsoi, T. Imbiriba, J.C.M. Bermudez.
        IEEE Transactions on Computational Imaging, 2019.



## INSTALLING & RUNNING:
Just start MATLAB and run example1.m or example2.m.



### Requirements
The variational autoencoders are trained in Python using the Keras package. 

## NOTES:
1.  The ELMM algorithm was provided by Lucas Drumetz.
    Drumetz, L., Veganzones, M.-A., Henrot, S., Phlypo, R., Chanussot, J., & Jutten, C.
    Blind hyperspectral unmixing using an extended linearmixing model to address spectral variability.
    IEEE Transactions on Image Processing, 2016.

2.  The GLMM algorithm was provided by Tales Imbiriba at https://github.com/talesimbiriba/GLMM.
    Imbiriba, T., Borsoi, R.A. & Bermudez J.C.M.
    Generalized linear mixing model accounting for endmember variability.
    IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2018.

3.  The PLMM algorithm was provided by Pierre-Antoine Thouvenin.
    Thouvenin, P.-A., Dobigeon, N., & Tourneret, J.-Y.
    Hyperspectral unmixing with spectral variability using a perturbed linear mixing model.
    IEEE Transactions on Signal Processing, 2016.



