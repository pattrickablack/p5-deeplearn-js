# p5ML

**_This project is currently in development._**

p5ML is a high level javascript library for machine learning. The main idea of this project is to further reduce the barriers between lower level machine learning and creative outputs using javascript.

p5ML provides two main functionalities:
  - A wrapper around [deeplearn.js](https://github.com/PAIR-code/deeplearnjs) providing a simplier interface, that makes it easier to work with GPU accelerated machine learning in javascript.
  - Custom ML methods.

## Usage 

Import the library and [deeplearn.js](https://github.com/PAIR-code/deeplearnjs):

```html
<script src="https://unpkg.com/deeplearn"></script>
<script src="p5ML.js"></script>
```

To use with ES6

```bash
npm install deeplearn
npm install p5ML
```

## Examples

- [Mnist](examples/es6/mnist)
- [LSTM](examples/es6/lstm)

## API Reference
 
- [Neural Network]()
- [Bayes Classifier]()
- [Word2Vec]()
- [LSTM]()

### Neural Network

```javascript
new p5ML.NeuralNetwork();
```

### Bayes Classifier

```javascript
new p5ML.Bayes();
```

### Word2Vec

```javascript
new p5ML.Word2Vec();
```

### LSTM

```javascript
new p5ML.LSTM();
```

## Develop

First clone the repo and install dependencies
```bash
git clone https://github.com/ITPNYU/p5ML.git
cd p5ML
yarn
```

To devolop and run a server
```bash
webpack-dev-server
```

To build:
```bash
yarn build
```








