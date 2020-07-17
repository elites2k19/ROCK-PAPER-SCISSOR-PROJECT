# ROCK-PAPER-SCISSOR-PROJECT
# rock-paper-scissors
 

An AI to play the Rock Paper Scissors game

## Requirements
- Python 3
- Keras
- Tensorflow
- OpenCV



Install the dependencies
```sh
$ pip install -r versions.txt
```
Gather Images for each gesture (rock, paper and scissors and None):
In this example, we gather 200 images for the "rock" gesture
```sh
$ python3 gather_images.py rock 200
```
Train the model
```sh
$ python3 train.py
```

Test the model on some images
```sh
$ python3 test.py <path_to_test_image>
```
Play the game with your computer!
```sh
$ python3 play.py
```
