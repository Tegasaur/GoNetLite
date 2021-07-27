How To:

1. Training GAN:
	a. Open GANs_trainer and pass location folder for positive GAN images in specified 
	location (2nd cell of notebook).

	b. Run GANs_trainer. It should output an encoder.yaml file and an encoder.h5 file.

2. Training Classifiers:
	a. Pass the path to encoder.yaml and encoder.h5 files to GAN_CNN, GAN_CNN_ensemble,
	Decision Tree Revised and SVM in the specified locations for each file.

	b. Pass data paths (train_annotation, test_annotation and vali_anotation) to specified
	locations in the each classifier file.

	c. Run the code for each file. Metrics show up in the later cells of the files mentioned above.



