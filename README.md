# Exploring Multimodal Embeddings: Improving Neural Word Representations Using Vision Transformer Image Encodings

### How to run the code

## Set up data files in Google Drive

First, visit the Google Drive folder at https://drive.google.com/drive/folders/1y42BM_bK2Ugc5SKeW_FaMsN6aaVbuUZI?usp=sharing. Right-click the folder name, hover over "Organize," and choose "Add shortcut." **Add the shortcut to your home Drive folder "My Drive"**. This is important so that Google Colab can read the data from teh appropriate location later.

## Python notebooks
Note that there are two python notebooks included in this zip folder. The first, `68610_Final_Project_Image_Embedding_Sript.ipynb`, is for downloading and embedding the images in our dataset. There is no need to run this, as we have included the results in the Google Drive folder. The second notebook, `68610_Final_Project_Main.ipynb`, is the notebook which contains our modeling and evaluation, and you should run this to reproduce our results.

## Run code
Once the folder has been added to your Google Drive, the Python notebook `68610_Final_Project_Main.ipynb` should be able to import the data and run all our models. Note that in the section "Load Trained Embeddings", there is no need to run that cell if you have just trained a model. That cell is only for fetching the embeddings outputted by an already-trained model, to avoid having to re-train these models every time.

