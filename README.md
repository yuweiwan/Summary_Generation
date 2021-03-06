# Summary_Generation  
data/   
 data_utils.py: functions or classes used in data processing.  
 process.py: Process a raw dataset into a sample file.  
model/  
 config.py: Define configuration parameters.  
 dataset.py: Define the format of samples used in the model.  
 evaluate.py: Evaluate the loss in the dev set.  
 model.py: Define the model.  
 predict.py: Generate a summary.  
 test_vocab.py: Testing vocab.  
 train.py: Train the model.  
 utils.py: Helper functions or classes used for the model.  
 vocal.py: Define the vocabulary object. 
 
 file folder may need:  
 saved_model/: Save trained model object  
 runs/: Save logs for TensorboardX  
 
 Refer to   
 "Get to the point: Summarization with pointer-generator networks"  
 The code uses the baseline model in it.
 
 The structure:  
 Encoder: Embedding + BiLSTM  
 Attention:  
 decoder: Embedding + LSTM + feed forward + softmax  
 
