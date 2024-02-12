# Traning_Artificail_neural_network_with_keras

#### Dataset for Classification- Churn_Modelling.csv
#### Dataset for Regression - Real_Combine.csv

Part_1 - Training_Artificial_Neural_Network.ipynb


part_2 - Find_no_of_Hidden_Layers_And_Hidden_Neurons_by_Keras_Tuner_library.ipynb   

      i) dropout layers can be added in Keras_Tuner
  
      ii) we ask best optimizer from multiple by using - optimizeractivation_choice = hp.Choice('activation_' + str(i), ['sigmoid', 'relu'])
  
      iii) multiple layers can be asked to chose from by passisng as list- num_layers = hp.Choice('num_layers', values=[[20], [2, 25], [22, 11, 15]]))
