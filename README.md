# Participation
133 Entrants

111 Participants

111 Teams

745 Submissions


# Description
In this competition, there are three set of files presented:

x_train: The main training data comprising of 1713 multispectral images.
y_train: The corresponding masked images; ground truth for the above training data samples.
x_test: The test data of 183 multispectral images. The objective is to be come up with a semantic segmentation model where the corresponding pixel is classified based on the label of interest. In short, the input is a multispectral image, and the output is a segmented mask corresponding to the particular label.


# Evaluation
The metric used for evaluation is the mean Intersection over Union (mIoU).

Submission File
Generate a submission.csv file, with the columns; ID, usage and pixels. The pixels columns is a flatten version of the predicted 2D mask.
