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

### Brief Recurrent Neural Network explanation:

The conexion of the nodes that form the neural network form a graph along a tempopral sequence.  
This helps the model behave according to a given time instance.  
The key that makes them good for speech and hand written digits recognition is the fact that they use a special kind of their own memory.

There are two different types:
* Finite impulse -> can be easily converted to feedforward
* Inifinite impulse -> Can not be converted to feedforward as they form a cyclick graph.

The most simple form of it, is organised as a feedforward would be , but the connections are represented as in a graph. Each neuron can be activated or deactivated.  

