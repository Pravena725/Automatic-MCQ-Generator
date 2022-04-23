# Automatic-MCQ-Generator
Automatic generation of questions and distractors based on a given piece of text

# Project ID 8

# Team:
B Pravena -PES2UG19CS076

Varna Satyanarayana - PES2UG19CS448

Spoorthi R - PES1UG19CS500

## Prerequisites
1. Switch on GPU mode on google colab
2. Download baking.txt and upload onto google colab folders

## Libraries to be installed (automatically installed when run on google colab)
!pip install neuralcoref

!pip install flashtext

!pip install datasets==1.0.2

!pip install tqdm==4.55.1

!pip install --quiet transformers==4.1.1

!pip install --quiet tokenizers==0.9.4 

!pip install --quiet sentencepiece==0.1.94

!pip install --quiet tqdm==4.56.0

!pip install --quiet pytorch-lightning==1.2.10

!pip install scikit-learn

!pip install multi_rake

!pip install tensorflow

!pip install keras

!pip install sense2vec

!pip install -U wn==0.0.22

!pip install transformers

!pip install spacytextblob

!python -m textblob.download_corpora

!python -m spacy download en_core_web_sm

!wget https://github.com/explosion/sense2vec/releases/download/v1.0.0/s2v_reddit_2015_md.tar.gz

!tar -xvf s2v_reddit_2015_md.tar.gz

## Execution
1. Create a folder called NLP on your google drive and upload baking.txt onto it.
2. Run the Automatic_MCQ_Generator.ipynb file on GPU runtime type
3. It produces files: keywords.txt, QandA.txt, context.txt
4. Run the DistractorGeneration.ipynb file which will produce MCQ.txt file with the generated questions and distractors

(Note: 2 seperate colab files were created for question generation and distractor generation due to conflicting dependencies)





