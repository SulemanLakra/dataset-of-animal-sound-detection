# Created by

Ines Nolasco(1), Shubhr Singh(1), Vincent Lostanlen(2), Ari Strandburg-Peshkin(3)(4), Lisa Gill(5), Hanna Pamula(6), Joe Morford(7), Michael Emmerson(8), Frants Jensen(11), Ester Vidana Vila(12), Ivan Kiskin(13), Veronica Morfi(1), Dan Stowell(9)(10)

(1) Centre for Digital Music (C4DM), EECS, Queen Mary University of London, London, UK
(2) Laboratoire des sciences du numérique de Nantes (LS2N), CNRS, Nantes, France
(3) Biology Department, University of Konstanz, Konstanz, Germany
(4) Department for the Ecology of Animal Societies, Max Planck Institute of Animal Behavior, Konstanz, Germany
(5) Dawn Chorus project, Biotopia, Munich, Germany
(6) Department of Mechanics and Vibroacoustics, AGH University of Science and Technology, Kraków, Poland
(7) Oxford Navigational Group (OXNAV), Department of Zoology, University of Oxford, Oxford, UK
(8)  School of Biological and Behavioral sciences (SBBS), Queen Mary University of London, London, UK
(9) Department of Cognitive Science and AI, Tilburg University, Netherlands
(10) Evolutionary Ecology Research Group, Naturalis Biodiversity Centre
(11) Bioacoustics and Behavioral Ecology Lab, Syracuse University, New York, USA
(12) La Salle, Universitat Ramon Llull, Spain
(13) University of Surrey, UK

# DCASE 2021 Task 5: Few-shot Bioacoustic Event Detection Development Set - version2

The development set for task 5 of DCASE 2022 "Few-shot Bioacoustic Event Detection" consists of 192 audio files acquired from different bioacoustic sources. The dataset is split into training and validation Sets. 

Multi-class annotations are provided for the training set with positive (POS), negative (NEG) and unkwown (UNK) values for each class. UNK indicates uncertainty about a class. 

Single-class (class of interest) annotations are provided for the validation set, with events marked as positive (POS) or unkwown (UNK) provided for the class of interest. 

this version (3):
* fixes issues with annotations from HB set


## Folder Structure:

Development_Set.zip

|_Development_Set/

    |__Training_Set/

        |___JD/

            |____*.wav

            |____*.csv

        |___HT/

            |____*.wav

            |____*.csv

        |___BV/

            |____*.wav

            |____*.csv

        |___MT/

            |____*.wav

            |____*.csv

        |___WMW/

            |____*.wav

            |____*.csv



    |__Validation_Set/

        |___HB/

            |____*.wav

            |____*.csv

        |___PB/

            |____*.wav

            |____*.csv

        |___ME/

            |____*.wav

            |____*.csv



## Dataset statistics

Some statistics on this dataset are as follows, split between training and validation set and their sub-folders:

-----------------------------------------------------
TRAINING SET
-----------------------------------------------------
Number of audio recordings			|	174
Total duration					|	21 hours
Total classes					|	47
Total events					|	14229
-----------------------------------------------------
TRAINING SET/BV
-----------------------------------------------------
Number of audio recordings			|	5
Total duration					|	10 hours
Total classes 					|	11
Total events 					|	9026
Ratio event/duration				|	0.04
Sampling rate					|	24000 Hz
-----------------------------------------------------
TRAINING SET/HT
-----------------------------------------------------
Number of audio recordings			|	5
Total duration					|	5 hours
Total classes 					|	5
Total events 					|	611
Ratio event/duration				|	0.05
Sampling rate					|	6000 Hz
-----------------------------------------------------
TRAINING SET/JD
-----------------------------------------------------
Number of audio recordings			|	1
Total duration					|	10 mins
Total classes					|	1
Total events					|	357
Ratio event/duration				|	0.06
Sampling rate					|	22050 Hz
-----------------------------------------------------
TRAINING SET/MT
-----------------------------------------------------
Number of audio recordings			|	2
Total duration					|	1 hour and 10 mins
Total classes					|	4
Total events					|	1294
Ratio event/duration				|	0.04
Sampling rate					|	8000 Hz
-----------------------------------------------------
TRAINING SET/WMW
-----------------------------------------------------
Number of audio recordings			|	161
Total duration					|	4 hours and 40 mins
Total classes					|	26
Total events					|	2941
Ratio event/duration				|	0.24
Sampling rate					|	various sampling rates
-----------------------------------------------------

-----------------------------------------------------
VALIDATION SET
-----------------------------------------------------
Number of audio recordings			|	18
Total duration					|	5 hours and 57 minutes
Total classes					|	5
Total events 					|	1077
-----------------------------------------------------
VALIDATION SET/HB
-----------------------------------------------------
Number of audio recordings			|	10
Total duration					|	2 hours and 38 minutes
Total classes 					|	1
Total events 					|	712
Ratio event/duration				|	0.7
Sampling rate					|	44100 Hz
-----------------------------------------------------
VALIDATION SET/PB
-----------------------------------------------------
Number of audio recordings			|	6
Total duration					|	3 hours
Total classes					|	2
Total events 					|	292
Ratio event/duration				|	0.003
Sampling rate					|	44100 Hz
-----------------------------------------------------
VALIDATION SET/ME
-----------------------------------------------------
Number of audio recordings			|	2
Total duration					|	20 minutes
Total classes					|	2
Total events 					|	73
Ratio event/duration				|	0.01
Sampling rate					|	48000 Hz
-----------------------------------------------------


## Annotation structure

TRAINING SET
------------
Audiofilename, Starttime, Endtime, CLASS_1, CLASS_2, ...CLASS_N

VALIDATION SET
--------------
Audiofilename, Starttime, Endtime, CLASS_Q

## Open Access

This dataset is available under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.


## Contact info

Please send any feedback or questions to:
Ines Nolasco: i.dealmeidanolasco@qmul.ac.uk
