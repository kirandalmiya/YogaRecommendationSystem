The goal of Mood based yoga recommendation system is to create a system that uses sentiment analysis from text input to suggest personalized yoga routines based on the user's mood. Here are the major steps outlined in the notebook:
Step 1: Problem Understanding & Approach
•	Problem: Yoga routines need to align with a user’s emotional state for effectiveness.
•	Approach:
o	Use text input to detect mood.
o	Map moods (e.g., stressed, happy, tired) to suitable yoga routines.
o	Include mindfulness or breathing exercises where relevant.
Step 2: Data Selection
•	Datasets:
1.	Emotion Detection Dataset: tweet_emotions_1.csv for sentiment classification.
2.	Yoga Routine Dataset: final_asan1_1, a yoga dataset mapped to moods based on yoga benefits.
Step 3: Model Development
•	Steps:
o	Preprocess the data.
o	Train an emotion detection model (likely a sentiment analysis model).
o	Implement a recommendation engine to suggest yoga sessions based on the detected mood.
Step 4: Integration with a Yoga App (Optional)
•	Simulated Interface:
o	A simple web app (using Flask or Streamlit) can take text input, identify the user's mood, and recommend corresponding yoga sessions.
