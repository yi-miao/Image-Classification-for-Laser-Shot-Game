# Image-Classification-for-Laser-Shot-Game
Applying a Tensorflow Image Classification Model to Laser Shot Game: Simple, Lightweight and Accurate 

Inspired by the Image Classification example from Google TensorFlow Tutorial, I setup a simple LaserShot experient which scoring laser shots on a dartboard.

Test environment:
1. A dartboard (9 classes of scores: 0, 10, 20, 30, 40, 50, 60, 80, 100)
2. A laser transmitter (KY-008 650nm): about 50 cm away from dartboard
3. A breadboard with power supply: signal, vcc = 5v, gnd = 0v
4. A video camera: capture the images for training and testing
5. python code: lasershot in jupter notebook
6. Windows 11 pc: 
	ASUS ExpertCenter Business Desktop 2024 
	CPU: Intel Core i5-13400 10-Core 
	Integrated Graphics Card: Intel Iris Xe Graphics 
	Memory: 32GB DDR4 
	Storage: 512GB SSD
7. train dataset: shape of (257, 224, 224, 3)
8. test dataset: shape of (30, 224, 224, 3)

Summary of test conditions and results:
1. Simple model with ~6.5 Million parameters
2. Training epochs = 45
3. Test loss: 0.23, Test accuracy: 0.94
4. Visualize test results with 25 samples, two shots with 10 treated as 0.

Further improvements:
1. adding more training data for 10.
2. adding more training data for 0.

Review:
I am happy with the test and results. It provides a simple, effective, accurate and affordable solution to a real world issue.
