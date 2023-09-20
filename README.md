# VCF_filter
This project is a deep learning model aiming to filter VCF files. There are three models so far: SNPs model, INDELs model, and mixed model. 
The model is based on TRANSFORMERS with inner workings and structure differences. 
We have 6 layers with 6 neural networks inside each layer. We added words to the vocabulary list that are variant calling related. 
The hyperparameters, including optimizers, activation function, dropout rate, etc., were tuned and optimized until the model reached the best performance
