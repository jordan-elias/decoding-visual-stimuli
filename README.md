# decoding-visual-stimuli
SVM and multinomial logistic regression models to classify functional brain data from the Haxby dataset

It consists of 6 subjects with 12 runs per subject. In each run, 
the subjects passively viewed greyscale images of eight object categories, 
grouped in 24s blocks separated by rest periods. Each image was shown for 500ms 
and was followed by a 1500ms inter-stimulus interval. Full-brain fMRI data were 
recorded with a volume repetition time of 2.5s, thus, a stimulus block was covered 
by roughly 9 volumes.

Here I used a linear SVM and a multinomial logistic regression model and compared the decoding 
accuracy of each approach in classifying brain image data for each image being viewed.

Following that, corss validation was used to find the best C parameter and weights were found to minimize the error function.
