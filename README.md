# NLPlay-with-Transformers--SoC-2021

<h2> By- Akash Chodankar</h2> 

<h3> Week 2 Task:-</h3>



<p> This week's task was <i>Sentiment Analysis</i> based on an IMDB review dataset which consisted of 50,000 samples equally distibuted amongst positive and negative sentiment.</p>

<ol type="1">
<li><h4>BOW implementation</h4></li>

<p> The major proportion of preprocessing was done with the popular NLP library; nltk with some assistant of functions from other libraries. For predictions, a Feedforward Neural Network was implemented using pytorch. The Neural Network consisted of 2 hidden layers each of which was made up of 200 neurons. Activation functions like ReLU and Softmax were used. The loss was evaluated using Cross Entropy function and the algorithm was optimized using Stochastic Gradient Descent. The training was conducted for 26 iterations on a batch size of 1.The test set accuracy turned out to be 0.88.</p>

<li><h4>Tf-Idf implementation</h4></li>

<p>The preprocessing was done with nltk. Considering Zipf's law, I kept on decreasing the number of features and evaluated the corresponding logistic regression error. A significant observation which was made was that the accuraccy didn't decrease much when the number of features were decreased from 70,000+ to 10,000. This helped in reducing the dimensions of training data before feeding it to the neural network, which contributed to a significant decrease in the training time. The sigmoid fucntion was used along with BCEloss and SGD. A batch size of 512 was used for traning the neural network with 2 hidden layers of 500 neurons each. Similar accuracy of 0.88 was achieve here with a much lesser training time.</p>
  
</ol>

<h3> Week 3 Task:-</h3>


<p> In this week I implemented neural network architectures like RNN,GRU and LSTM. The results were very good in case of LSTM with an accuracy of above 80% on the test data. In case of RNN and GRU the network took a slightly longer time to train. An accuracy of 70%+ was achieved.</p>



<h3> Week 4-6 Tasks:-</h3>


<p> This week's focus was to improve the scores on the testset using state-of-the-art transformers models. I implemented Bert and Distilbert model using the Huggingface library. The results achieved had accuracies above 85% in case of bert and around 60% in case of Distilbert</p>

<h3> Week 7-8 Tasks:-</h3>

<p> Created a 3 custom datasets using wikipedia library to scrape text data from the articles in the domain of science, finance and entertainment. Used GPT-2 and T5 transformer models to generate articles corresponding to the input. Evauated the performance using bleu score matrix.
