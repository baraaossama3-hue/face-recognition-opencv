# face-recognition-opencv
Face detection and recognition using OpenCV and LBPH
Built a face detection and recognition system in Python using OpenCV.

- Detected faces using a Haar Cascade classifier and cropped them to build the training data
- Prepared a labeled dataset with one folder per person
- Trained an LBPH (Local Binary Patterns Histograms) face recognizer and saved the trained model for reuse
- Tested the model on unseen images and displayed the predicted name with a confidence score
- Debugged real issues along the way: unsupported image formats, dataset structure errors, and NumPy pickle loading errors
- Learned that testing on training images gives misleading results, so I validated on separate test photos

Tech: Python, OpenCV, NumPy, Matplotlib

Potential applications (with further improvement):
- Home security cameras that recognize family members and flag unknown visitors
- Smart door locks and access control for homes, offices, and apartment buildings
- Elevator cameras that identify residents or restrict access to authorized floors
- Automatic attendance systems for schools, universities, and workplaces
- Personalized smart-home settings that adjust to who enters the room
- Retail and event check-in systems for faster, contactless entry
- Assisting in finding missing persons from camera footage

Limitations: LBPH is sensitive to lighting and angle, and accuracy was limited with a small dataset. Next step: experiment with a larger dataset or a deep learning approach.
