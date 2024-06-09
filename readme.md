
HumanAI Foundation
https://humanai.foundation/ 
https://humanai.foundation/gsoc/2024/proposal_OCR2.html 
Tests: https://bama365-my.sharepoint.com/:w:/g/personal/xgranja_ua_edu/Ee6S21QpgmxFj4szyRXqMAsBnMIs1TqsiPC4vP6-kRxrRw?e=zkxpoU 

Specific Test II. Transformer Architectures
**Task**: Build a model based on transformer architectures for optically recognizing the text for the two image datasets: General and Specific. Pick the most appropriate approach and discuss your strategy.
**Evaluation Metrics**: discuss which evaluation metrics you are using to evaluate your model performance


## METHODOLOGY
Data type: PDF or image

I. Tokenization into words or subwords
II. Encoding
* Encode the tokenized text into numerical representations that can be understood by the model.
One-hot encoding or more advanced techniques like WordPiece or Byte Pair Encoding (BPE) can be used for this purpose.
III. Transformer Architecture Selection
* General Mode 
* BERT 
* GPT 
* Specific Model
* LayoutLM
* ELECTRA (Efficiently Learning an Encoder that Classifies Token Replacements Accurately by GOOGLE)

IV. Model Training
* Split the preprocessed data into training, validation, and test sets.
Initialize the transformer model and train it on the training set.
Fine-tune the model on the validation set, adjusting hyperparameters if necessary.
Evaluate the model's performance on the test set using appropriate metrics such as accuracy, precision, recall, and F1-score.
Hyperparameter Tuning
Experiment with different hyperparameters such as learning rate, batch size, and model architecture to optimize performance.
Utilize techniques like grid search or random search for hyperparameter tuning.
Post-processing
Deployment on unseen data


	
