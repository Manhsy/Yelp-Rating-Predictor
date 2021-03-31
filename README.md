# Yelp-Rating-Predictor
Neural Network model that can predict a business's Yelp rating based on the reviews that they receieved. 

## Technologies & frameworks used:
- Python's Pandas, Tensorflow,  sci-kit-learn,  & NumPy libaries 

## How it works: 
- 8 million reviews of different businesses were retrieved from Yelp's website in the form of JSON files
- converted JSON to Pandas Dataframe
- performed dataframme clean 
- split data into training & testing set 
- defined neural network model with all possible combinations of activation functions and optimizers
- kept track of the best model using sci-kit-learn's Early Stopping
- After model was trained, tested the model performance by passing it 5 random business review and compare it against the actual VS predicted rating 
