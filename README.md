# SuperResolutionWaifuNN
I wanted to build my own implementation of [waifu2x](https://github.com/nagadomi/waifu2x) using Keras and TensorFlow, but I ended up using a slightly different architecture.

Image dataset colected using [PixivUtil2](https://github.com/Nandaka/PixivUtil2).

# Training
The model was trained on about a thousand images.
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/SRNNTimelapse.gif?raw=true)
Better quality of the gif: https://youtu.be/GCOe5kMTM5E

# Test (using 8k+ images for training)
## Input/Output
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/BEFOREandAfterFin.png?raw=false)
## Tests 1
The first image is the low ressolution input, the second is the generated image and the third is the original high resolution image.
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/srwnnTest1.png?raw=true)
## Tests 2
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/srwnnTest2.png?raw=true)

# Test (using 1.5k images for training)
## Tests
The first image is the low ressolution input, the second is the generated image and the third is the original high resolution image.
### Test 1
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/BEFOREandAfter1.png?raw=true)
### Test 2
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/BEFOREandAfter2.png?raw=true)
### Test 3
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/BEFOREandAfter3.png?raw=true)
### Test 4
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/BEFOREandAfter4.png?raw=true)
### Test 5
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/BEFOREandAfter5.png?raw=true)
### Test 6
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/BEFOREandAfter6.png?raw=true)
### Test 7
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/BEFOREandAfter7.png?raw=true)
### Test using non anime picture
![alt text](https://github.com/Exusai/SuperResolutionWaifuNN/blob/master/tests/imagetest.png?raw=true)
