This is the readme file to the files songs_to_classify.csv and
training_data.csv.

The files contain the (unlabeled) test data and the (labeled)
training data, respectively.

The columns represent features, as specified by the header and
documented in the instructions. The column "label"
(training_data.csv. only) is encoded as 1 = like, 0 = dislike.

The files can be loaded as a data frame into R using the command
data <- read.csv('training_data.csv',header<-T), etc.

The files were created by Andreas Svensson in November 2016 using
Spotipy (https://spotipy.readthedocs.io/)