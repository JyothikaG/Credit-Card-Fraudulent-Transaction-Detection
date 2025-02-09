**INTRODUCTION**
Credit cards are most widely used in onsite payment process and card-not-present transactions such as internet or online shopping. 
With their rising popularity of online payment transaction, credit card transactions are getting highly vulnerable to threats called credit card frauds such as 
eavesdropping, phishing, intrusion, denial-of-service (DoS), database stealing, etc.Credit card fraud can be defined as the illegal use of any system or, criminal activity. 
Increase in e-commerce and the ease of online transactions and payments has led to an exponential increase in the number of people opting for online purchases. 
The most common method of payment for online purchase is credit card. Credit-card-based purchases can be categorized into two types: 
1) physical card and 2) virtual card. When the user is present physically with the card during the transaction, it is categorized as Physical purchasing.
2) Especially all credit card operations are performed by web payment gateways, e.g., PayPal and Alipay.
   
**PROBLEM AND SOLUTION OF THE PROJRCT**
• The popularization of online shopping transaction fraud is growing seriously.
• First, we totally order the attributes of transaction records, and then classify the
values of every attribute.
• Behavior Profiles based on their transaction records, which is used to detect
transaction fraud in the online shopping scenario.
• Logical graph of Behavior Profiles which is a total order-based model to
represent the logical relation attributes of transaction records.
• We compare OM with other two anomaly detection methods: Bayesian learningbased fraud detection and self-organizing maps-based fraud detection. The two methods
are called phase Modulation (PM).
• Transactions labeled as fraudulent. True negative (TN)is the total number of
legal transactions labeled as legal. False negative (FN) is the total number of fraud
transactions which are not detected.
• OM automatically classifies the values of transaction attributes so that our model
can characterize the user’s personalized behavior more precisely.
• Detection of the fraudulent transactions will be made by using supervised and
unsupervised machine learning techniques IForest, SVM and Gradient Boost those
models will be used on a credit card transaction dataset.
• Outlier detection the computation and memory required for the credit card fraud
detection is much less in addition to its working faster and better in online large datasets.
But their work and results showed that IForest was more accurate and efficient.

**SYSTEM REQUIREMENTS**
The system requirement is a main part in the analyzing phase of the project. The
of the project must properly analyze the hardware and the software requirements,
otherwise in future the project designer will face more trouble with the hardware and
software required. Below specified are the project hardware and software requirements.

**SYSTEM ANALYSIS**
Python features a dynamic type of system and automatic memory management. It
supports multiple programming paradigms, including object oriented, imperative,
functional, and procedural, and has a large and comprehensive standard library. Python
interpreters are available for many operating systems.
Keras High-Level API handles the way we make models, defining layers, or setup
multiple input-output models. In this level Kerasal compiles our model with loss and
optimizes functionstraining process with fit function. Keras doesn't handle Low-Level API
such as making the computational graph, making tensors or other variables because it has
been handled by the "backend" engine.
Anaconda is a Python-based data processing and scientific computing platform.
It has built in many very useful third-party libraries. Installing Anaconda is equivalent
to automatically installing Python and some commonly used libraries such as NumPy,
Pandas, Scrip, and Matplotlib, so it makes the installation so much easier than regular
Python installation.

**TESTING PROCESS**
The purpose of testing is to discover errors. Testing is the process of trying to discover
every conceivable fault or weakness in a work product. It provides a way to check the
functionality of components, sub-assemblies, assemblies and/or a finished product It is the
process of exercising software with the intent of ensuring that the Software system meets
its requirements and user expectations and does not fail in an unacceptable manner.

**CONCLUSION**
The model that we built helps the authorities to get notified of the fraud in credit-cards and
take the further necessary steps over the transaction and label the transaction as fraud or legitimate transaction. 
We used supervised and unsupervised algorithms like IForest, SVM and GB to select the features
from our transaction dataset which uses correlation and variance as parameters to select the features. 
The scores of each model were 99.77%, 99.08%, 99.71% for the Iforest, support vector machine and gradient
boosting classifier algorithms respectively. These models have high accuracy and get the best results with high
precision in determining the fraud detections in credit card transaction records. 

