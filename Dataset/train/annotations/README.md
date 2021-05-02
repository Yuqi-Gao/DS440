If you checked some of the annotation files you will found that the path of the annotation pointed to the different image input paths\\
That is because I trained the model using both local environment and cloud environment(Google Colab, for testing purpose)
Because the client may not have a complete python environment installed on their devices, so make sure this can be compiled on the cloud environment is important
If you read the report carefully, you shall found that I mentioned when I tried to train the model in the cloud environment,
because the input path is not set to the path in the google drive, so they are defined as junk annotation by the code and skipped for using in the model training.
