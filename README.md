# Basketball Dataset for Action Recognition 
[Demo Video](https://www.youtube.com/watch?v=PEziTgHx4cA).


<p align="center">
    <img src=".github/clip.jpg?raw=true" width="700">
</p>

This repo contains two datasets (clips->.mp4 files and joints -> .npy files) of basketball single-player actions. In Figure below, a histogram of the number of examples is shown for every class. The size of the two final annotated datasets is about 32'560 examples, which can represent the basis for the subsequent training and testing phases for a classification of basket-like actions through Deep Neural Networks.



You can download the entire Dataset (both joints and clips) from [here](https://drive.google.com/open?id=1hLpbLmLFK2-GIvsmpJelGlEx94yQM2Ts).
Inside ```dataset.zip``` you can find the annotations of all examples and labels annotations, both in JSON format. 

Thesis is available at this [link](https://www.researchgate.net/publication/330534530_Classificazione_di_Azioni_Cestistiche_mediante_Tecniche_di_Deep_Learning/stats). [Soon available also in English]


<p align="center">
    <img src=".github/histogram.jpg?raw=true" width="700">
</p>


Each example of the first dataset (called clip Dataset) consists of 16frame in RGB focused on one player, while each of the second (called joint Dataset) consists of the coordinates (x, y) on the image plane of the player's joints. The identifier of "parallel" examples will be the same, while what identifies them is the extension of the files on which they are stored; each clip is compressed into a mp4 file (namefile.mp4), while the joints are stored as sufile vectors numpy (namefile.npy).


