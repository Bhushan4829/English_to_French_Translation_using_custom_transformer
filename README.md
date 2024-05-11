Welcome to our language translation service project, developed for the CSE676 course. This project utilizes the Europarl Parallel Corpus to perform English to French translations. The data is initially processed using our dedicated preprocessing script.

Training is carried out on a pretrained model, details and scripts of which are available in the 'pretrained model' directory. Our project further explores custom transformers employing various positional encodings, both relative and absolute; these can be reviewed in the 'model combination' directory, containing four distinct script files.

Upon evaluating various combinations, we identified two main models that were further enhanced by training them with an expanded dataset. The scripts for these models are located in the 'main model' directory. Additionally, the trained models' weights are stored in the 'model weights' directory, which can be directly utilized to produce translated texts.

For deployment, refer to the 'hosting website' notebook. Note that some paths may require modifications to suit specific deployment needs.

Dataset Link: https://huggingface.co/datasets/ashwinradhe/dl_dataset