# HalloWeek
SciData's activity for the Halloween Week 2019 at FDI UCM

### Relevant links:
* P5 editor project: https://editor.p5js.org/david_ucm/sketches/mHT4YDhnN
* my own artifical intelligence github repo: https://github.com/dlgeraghty/artificial_intelligence
* octopudna: https://dlgeraghty.github.io/artificial_intelligence/drawNeuralNetwork/draw_nn.html
* magenta sketch rnn game: https://magenta.tensorflow.org/assets/sketch_rnn_demo/index.html
* google quick draw game: https://quickdraw.withgoogle.com/#
* tutorial reference for this example: https://www.youtube.com/watch?v=GMaKcRkiNoM
* wikipedia RNN: https://en.wikipedia.org/wiki/Recurrent_neural_network
* Ml5 docs: https://ml5js.org/
* p5 docs: https://p5js.org/
* quick draw dataset github (categories): https://github.com/googlecreativelab/quickdraw-dataset/blob/master/categories.txt
* RDP algorithm: https://www.youtube.com/watch?v=nSYw9GrakjY

### Brief Recurrent Neural Network explanation:

The conexion of the nodes that form the neural network form a graph along a tempopral sequence.  
This helps the model behave according to a given time instance.  
The key that makes them good for speech and hand written digits recognition is the fact that they use a special kind of their own memory.

There are two different types:
* Finite impulse -> can be easily converted to feedforward
* Inifinite impulse -> Can not be converted to feedforward as they form a cyclick graph.

The most simple form of it, is organised as a feedforward would be , but the connections are represented as in a graph. Each neuron can be activated or deactivated.  

### Brief code explanation (keys):

* Ml5 library! This makes it super easy to do this otherwise complex task and allows to represent it in the browser which is a good thing. 
* P5 js! This allows for easy drawing and manipulation of drawings in the canvas, it is also super easy to use!
* In this example, we want to do something similar to the magenta sketch rnn , but as we will see, there will be some key differences. 
* Key functions and values:
  1. Preload function: value in the ```ml5.sketchRNN('value')``` is the object that we will be moldelling.
  2. sketchRNNstart: ```sketchRNN.generate(prevPath, newPath)``` allows us to give it a certain path and then it continues from there.
  3. All the drawing stuff is handled in the draw loop (this is all p5 js and some magic).
