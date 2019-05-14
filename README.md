# MexCulture142

## Technical parameters

The MexCulture142 dataset contains images of Mexican Cultural heritage recorded during ANR PI Mexculture by IPN CITEDI and gaze fixations data recorded with an eye-tracker at LABRI UMR 5800 CNRS/University of Bordeaux/IPN. The goal of psycho-visual experiment is to record gaze fixations of subjects executing a visual task of recognition of architectural styles of Mexican Cultural heritage. Each category represents different views of the same architectural structure.

The dataset contains 142 subclasses of Prehispanic, Colonial, Modern buildings, we provide 2 examples for each class and the corresponding *.txt* files of gaze fixations. Also, the saliency map of each image and *.txt* scanpath files where we have the coordinates and duration of fixations per subject.

Samples count:
* Number of categories: 142 
* Images per category: 2
* Total: 284

To recognize the architectural styles of Mexican buildings, the participants read instructions first with examples of images of target classes shown.  Then, the eye-tracker system is callibrated for each participant. Then, they then visualize images of the buildings on the experimental screen. Each image is shown for 3 seconds, then a gray frame is shown to reset their attention.

Timing for gaze recordings:
* Time for image displaying: 3 seconds
* Time for gray frame displaying: 1 second
* Time for calibration: 60 seconds
* Time to read instructions: 180 seconds
* Total time: 28 minutes


## Content description

The dataset contains 4 folders:
* Images: contains 142 categories of Prehispanic, Colonial and  Modern styles.
* Fixations: holds *.txt* files which are the corresponding fixations of source images.
* Density Maps: contains the subjective saliency maps of each category, calculated as in [2].
* Scanpaths: includes 6532 (284x23 participants) *.txt* files with fixation coordinates (in pixels) and fixations length (in seconds).


The identifier for each filename is composed as follows:
* Images:      SSS_XXX_YYY_N_#.png
* Fixations:   SSS_XXX_YYY_GazeFix_N_#.txt
* Density Maps: SSS_XXX_YYY_GFDM_N_#.png
* ScanPath: SSS_XXX_YYY_ScanPath_N_#_P_*.txt

Here some examples of filenames:
* Prehispanic_Yaxchilan_Chiapas_N_2.png
* Prehispanic_Yaxchilan_Chiapas_GazeFix_N_2.txt
* Prehispanic_Yaxchilan_Chiapas_GFDM_N_2.png
* Prehispanic_Yaxchilan_Chiapas_ScanPath_N_2_P_1.txt

## Download
To download files: [https://www.nakala.fr/nakala/data/11280/2752cdec](https://www.nakala.fr/nakala/data/11280/2752cdec "Download Dataset")








## References

[1] A. Montoya, J. Benois-Pineau, M. S. Vázquez, A. R. Acosta, K. Guissous and V. Gouet-Brunet, **Comparative study of visual saliency maps in the problem of classification of architectural images with deep CNNs**, in 2018 Eighth International Conference on Image Processing Theory, Tools and Applications (IPTA), China, 2018.

[2] D. S. Wooding, **Eye movements of large populations:II. Deriving regions of interest, coverage,and similarity using fixation maps**, in Behavior Research Methods, Instruments, & Computers, 2002.



