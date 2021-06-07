# Behavioral Cloning For Self Driving Cars

Implementation of the paper "End to End Learning for Self-Driving Cars"

## Citing

If you find this code useful in your research, please consider citing the blog:

```
@misc{sagardriving,
  Author = {Abhinav Sagar},
  Title = {How to Train Your Self Driving Car Using Deep Learning},
  Year = {2019},
  Journal = {Towards Data Science},
}
```

## IMPORTANT

Absolutely, under NO circumstance, should one ever pilot a car using computer vision software trained with this code (or any home made software for that matter).

This code is purely for research and statistics, absolutley NOT for application or testing of any sort.

Check out the corresponding medium blog post [https://towardsdatascience.com/how-to-train-your-self-driving-car-using-deep-learning-ce8ff76119cb](https://towardsdatascience.com/how-to-train-your-self-driving-car-using-deep-learning-ce8ff76119cb).

## Goal

Train a end-to-end deep learning model that would let a car drive itself around the track in a driving simulator.

## Data collection

In this project Udacity driving simulator has been used which has two different tracks. One of them was used for collecting training data, and the other one — never seen by the model — as a substitute for test set.

The driving simulator would save frames from three front-facing "cameras", recording data from the car's point of view; as well as various driving statistics like throttle, speed and steering angle. We are going to use camera data as model input and expect it to predict the steering angle in the [-1, 1] range.

## Results

<p align="center">
  <img src="run.gif" alt="Driving"/>
</p>

## References

1. https://arxiv.org/pdf/1604.07316.pdf

2. http://cs231n.stanford.edu/reports/2017/pdfs/626.pdf

## License

```
MIT License

Copyright (c) 2019 Abhinav Sagar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```
