###Many of the ideas presented here are from FaceNet.

##Face Verification
 "Is this the claimed person?" For example, at some airports, you can
 pass through customs by letting a system scan your passport and then
 verifying that you (the person carrying the passport) are the correct person.
 A mobile phone that unlocks using your face is also using face verification.
 This is a 1:1 matching problem.

##Face Recognition
  "Who is this person?" For example, employees entering the office without
  needing to otherwise identify themselves. This is a 1:K matching problem.



 FaceNet learns a neural network that encodes a face image into a vector of
 128 numbers. By comparing two such vectors, you can then determine if two
 pictures are of the same person.
