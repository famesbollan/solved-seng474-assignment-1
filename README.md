Download Link: https://assignmentchef.com/product/solved-seng474-assignment-1
<br>
<ol>

 <li> Construct the root and the first level of a decision tree for the contact lenses data. Use the ID3 algorithm. Show the details of your construction. Then, check your solution with Weka (the data file is included with Weka).</li>

 <li> Construct two rules using PRISM for the weather data. Show the details of your construction. Then, check your solution with Weka (the data file is included with Weka).</li>

 <li> Classify using Naïve Bayes method (on contact lenses data) the data item:</li>

</ol>

<em>pre-presbyopic, hypermetrope, yes, reduced, ?</em> Then, check your solution with Weka (the data file is included with Weka).

<strong>Note</strong>: You can download Weka from: <a href="http://www.cs.waikato.ac.nz/ml/weka">http://www.cs.waikato.ac.nz/ml/weka</a>

<ol start="4">

 <li></li>

</ol>

Implement a Naive Bayes classifier for text classification. This classifier will be used to classify fortune cookie messages into two classes: messages that predict what will happen in the future and messages that just contain a wise saying. We will label messages that predict what will happen in the future as class 1 and messages that contain a wise saying as class 0. For example,

    “Never go in against a Sicilian when death is on the line” would be a message in class 0.            “You will get an A in SENG 474” would be a message in class 1.

You can use any language you wish. There are two sets of data files provided:

<ol>

 <li>The training data:

  <ul>

   <li><strong>txt</strong>: This is the training data consisting of fortune cookie messages.</li>

   <li><strong>txt</strong>: This file contains the class labels for the training data.</li>

  </ul></li>

 <li>The testing data:

  <ul>

   <li><strong>txt</strong>: This is the testing data consisting of fortune cookie messages.</li>

   <li><strong>txt</strong>: This file contains the class labels for the testing data. These are only used to determine the accuracy of the classifier.</li>

  </ul></li>

</ol>

Your results must be stored in a file called results.txt.

<ol>

 <li>Run your classifier by training on traindata.txt and trainlabels.txt then testing on traindata.txt and trainlabels.txt. Report the accuracy in results.txt (along with a comment saying what files you used for the training and testing data). In this situation, you are training and testing on the same data. This is a sanity check: your accuracy should be very high i.e. &gt; 90%</li>

 <li>Run your classifier by training on traindata.txt and trainlabels.txt then testing on testdata.txt and testlabels.txt. Report the accuracy in results.txt (along with a comment saying what files you used for the training and testing data). We will not be letting you know beforehand what your performance on the test set should be.</li>

</ol>