
Facial Recognition verifies if two faces are same. The use of facial recognition is huge in security, bio-metrics, entertainment, personal safety, etc. The same python library face_recognition used for face detection can also be used for face recognition. Our testing showed it had good performance. Given two faces match, they can be matched with each other giving the result as True or False. The steps involved in facial recognition are

Find face in an image
Analyze facial feature
Compare features for the 2 input faces
Returns True if matched or else False.


Humans are used to taking in non verbal cues from facial emotions. Now computers are also getting better to reading emotions. So how do we detect emotions in an image? We have used an open source data set — Face Emotion Recognition (FER) from Kaggle and built a CNN to detect emotions. The emotions can be classified into 7 classes — happy, sad, fear, disgust, angry, neutral and surprise.
