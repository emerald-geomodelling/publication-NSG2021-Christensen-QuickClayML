# NSG2021_QuickClayPublication

## Overview
This repository is an area for storing and sharing supplementary materials related to a publication submitted to Near Surface Geophysics on using AEM, geotechnical data, and machine learning to model occurences of sensitive glaciomarine clay. The main things we share are example 3D models of our results discussed in the publication. 

Three versions corresponding to the 3 subfigures in Figure 10 of the publication: 
1. Where 10 boreholes are used as training, and only spatial attributes (i.e., horizontal and vertical coordinates) are used for making predictions 
2. Where 10 boreholes are used as training, and both spatial attributes and resistivity attributes are used for making predictions 
3. Where all boreholes available are used as training, and both spatial attributes and resistivity attributes are used for making predictions. 

![image](https://user-images.githubusercontent.com/61405744/117419265-a9f0ae80-af1c-11eb-8843-a0387aa609f4.png)


## Scene contents
These scenes all contain 5 to 6 objects in them: 
1. Red isovolume of material where our algorithm predicts > 60% probability of brittle clay
2. White/light grey isovolume of material where our algorithm predicts 40 to 60% probability of brittle clay
3. Dark grey isovolume representing bedrock 
4. thick columns representing training boreholes, coloured by the interpreted sediment type
5. thin columns representing boreholes unused in training, coloured by the interpreted sediment type 
6. Sediment data from the Norwegian Geological Survey (NGU) draped over terrain.  

### Legends
The sediment maps are coloured using this legend, similar to Figure 1 of our publication:
![image](https://user-images.githubusercontent.com/61405744/117419307-b4ab4380-af1c-11eb-9cd4-36e5134b9ad2.png)

The boreholes are coloured according to the following colorscheme. Note that 
![image](https://user-images.githubusercontent.com/61405744/117419326-bb39bb00-af1c-11eb-84db-ad29eae860bb.png)

All scenes have a vertical exaggeration of 3x. 

## How to open
The files herein can be opened in any GLTF viewer, but we recommend https://sandbox.babylonjs.com/. With this free online viewer, you can drag in and drop a GLTF file, navigate in 3D, toggle the visibility of layers, and adjust the transparency of each object's texture:

![image](https://user-images.githubusercontent.com/61405744/117421273-ae1dcb80-af1e-11eb-8d66-67305ad82b22.png)


## Sources
NGU, 2020. Norges Geologiske Undersøkelse. Løsmasser N250. https://kartkatalog.geonorge.no/metadata/loesmasser/3de4ddf6-d6b8-4398-8222-f5c47791a757
