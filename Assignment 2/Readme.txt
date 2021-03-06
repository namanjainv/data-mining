How to run the program

For BATCH
    $ python main.py batch [learning-rate] [training-size] [roc]
    Eg: $ python main.py batch 0.1

For ONLINE
    $ python main.py online [learning-rate] [training-size] [roc]
    Eg: $ python main.py online 0.01

Parameters:
        learning-rate should be a number
        training-size should be an integer
        roc is written if an ROC graph needs to be generated

Note: 
There exists one more method which would run both batch and online for learning rates on 0.01, 0.1 and 1
To use the same, use the following command:
        $ python main.py [roc]

Output:
The program generates the following results for processing:
    Type                    : This says the method type along with learning rate
    Iteration(s)            : Interations that the training data set took
    Time(s)                 : Time taken to train the perceptron on a given dataset
    Weights                 : Weight Array generated by the agent
    Accuracy                : Accuracy of the result produced based on given testing data set
    Graph                   : A graph representing ROC curve is generated
    Area under the curve    : Area under the ROC curve

Referneces

https://pythonprogramming.net/reading-csv-files-python-3/
https://stackoverflow.com
https://www.geeksforgeeks.org
https://docs.scipy.org/doc/numpy-1.15.1/reference/generated/numpy.argsort.html
