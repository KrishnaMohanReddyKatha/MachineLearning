•	ID3 implementation is done in Java
•	Implemented by 
              Name: Krishna Mohan Reddy Katha
•	Compilation:
         javac Node.java.
         java Node trainingDataPath validationDataPath testingDataPath prunningFactor.
•	Assumptions:
         1.	If a leaf node has no data Instances then we labeled the node as 0 (negative class label).
         2.	After splitting with all the attributes, if the data is still not pure then we labelled the node as 1 if no of positive data instances greater than equal to negative data instances else as 0.
         3.	Root node of the decision tree is not considered for pruning.
•	Accomplished: 
                    Implemented ID3 for decision tree model and did post pruning for improving accuracy in case of over fitting.
					Based on random number selected pruned nodes post pruned accuracies vary.
•	Learned:
                Learnt how to construct decision tree training model and how pruning avoids over fitting and improves accuracy provided the nodes chosen to prune are good potential ones