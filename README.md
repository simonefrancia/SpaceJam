# Basketball Dataset for Action Recognition


This repo contains two datasets (clips->.mp4 files and joints -> .npy files) of basketball single-player actions. In Figure below, a histogram of the number of examples is shown for every class. The size of the two final annotated datasets is about 32'560 examples, which can represent the basis for the subsequent training and testing phases for a classification of basket-like actions through Deep Neural Networks.



Each example of the first dataset (called clip Dataset) consists of 16frame in RGB focused on one player, while each of the second (called joint Dataset) consists of the coordinates (x, y) on the image plane of the player's joints. The identifier of "parallel" examples will be the same, while what identifies them is the extension of the files on which they are stored; each clip is compressed into a mp4 file (namefile.mp4), while the joints are stored as sufile vectors numpy (namefile.npy).

