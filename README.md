Download Link: https://assignmentchef.com/product/solved-cs584-assignment-1-classify-text-paragraphs-into-three-categories
<br>



<ol>

 <li><strong>Document Classification </strong>(100 points) In this homework, you need to classify text paragraphs into three categories: <em>Fyodor Dostoyevsky</em>, <em>Arthur Conan Doyle</em>, and <em>Jane Austen </em>by building your own classifiers. The data provided is from Project Gutenberg. Please follow a few steps as below:</li>

</ol>

<ul>

 <li>(5pts) <strong>Preprocess data</strong>: remove punctuations, irrelevant symbols, and common words etc.</li>

 <li>(5pts) <strong>Construct examples</strong>: Divide each document into multiple paragraphs. Each paragraph will be one example.</li>

 <li>(5pts) <strong>Data split</strong>: Sample these paragraphs into training and testing data.</li>

 <li>(5pts) <strong>Feature extraction</strong>: Build a vocabulary to represent each paragraph using only training data. Consider <a href="https://en.wikipedia.org/wiki/Tf%E2%80%93idf">TF-IDF</a> features for each input example.</li>

 <li>(60pts) <strong>Build </strong>two classifiers (described below).</li>

 <li>(5pts) <strong>Plot </strong>training loss and validation loss at each epoch.</li>

 <li>(5pts) Using <strong>cross-validation </strong>on the training data, report the classification test/validation error (or accuracy) for each category.</li>

 <li>(10pts) <strong>Compare </strong>both classifiers and provide an analysis for the results.</li>

 <li>Implement a Logistic Regression model using both gradient descent and stochastic gradient descent.</li>

 <li>Implement a Multilayer Perceptron (MLP) model using backpropagation and mini-batch gradient descent.</li>

</ul>