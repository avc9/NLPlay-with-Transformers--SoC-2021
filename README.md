# NLPlay-with-Transformers--SoC-2021

<h2> By- Akash Chodankar</h2> 

<h3> Week 2 Task:-</h3>

<p> This week's task was <i>Sentiment Analysis</i> based on an IMDB review dataset which consisted of 50,000 samples equally distibuted amongst positive and negative sentiment.</p>

<p> The major proportion of preprocessing was done with the popular NLP library; <b>nltk</b> with some assistant of functions from other libraries. For predictions, a Feedforward Neural Network was implemented using <b>pytorch</b>. The Neural Network consisted of 2 hidden layers each of which was made up of 200 neurons. Activation functions like ReLU and Sigmoid were used. The loss was evaluated using Binary Cross Entropy function and the algorithm was optimized using Stochastic Gradient Descent. The training was conducted for 26 iterations on a batch size of 1.</p>

<p> The test set accuracy turned out to be <b>0.88</b> . </p>
