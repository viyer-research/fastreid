# fastreid
Tracking using cosine metric

Test case: Using video input file

python Vehicle-Re-Id-test.py -vid input.mp4

Error:
[14442C1051AFC3D200] [176.371] [NeuralNetwork(5)] [warning] Number of inference threads assigned for network is 1, assigning 2 will likely yield in better performance
[14442C1051AFC3D200] [176.371] [NeuralNetwork(5)] [warning] Network compiled for 4 shaves, maximum available 16, compiling for 8 shaves likely will yield in better performance
[14442C1051AFC3D200] [176.371] [DetectionNetwork(0)] [warning] Network compiled for 4 shaves, maximum available 16, compiling for 8 shaves likely will yield in better performance
[14442C1051AFC3D200] [176.380] [NeuralNetwork(5)] [warning] The issued warnings are orientative, based on optimal settings for a single network, if multiple networks are running in parallel the optimal settings may vary
[14442C1051AFC3D200] [176.380] [DetectionNetwork(0)] [warning] The issued warnings are orientative, based on optimal settings for a single network, if multiple networks are running in parallel the optimal settings may vary
[14442C1051AFC3D200] [176.842] [NeuralNetwork(5)] [error] Input tensor 'input' (0) exceeds available data range. Data size (13824B), tensor offset (0), size (129792B) - skipping inferenc
