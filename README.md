# Face_Detection

Face recognition problems commonly fall into two categories

1) Face Verification - "is this the claimed person?". For example, at some airports, you can pass through customs by letting a system scan your passport and then verifying that you (the person carrying the passport) are the correct person. A mobile phone that unlocks using your face is also using face verification. This is a 1:1 matching problem.
2) Face Recognition - "who is this person?". For example, the video lecture showed a face recognition video (https://www.youtube.com/watch?v=wr4rx0Spihs) of Baidu employees entering the office without needing to otherwise identify themselves. This is a 1:K matching problem.

Goal:

1) Implement the triplet loss function
2) Use a pretrained model to map face images into 128-dimensional encodings
3) Use these encodings to perform face verification and face recognition
