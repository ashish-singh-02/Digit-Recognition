# Digit-Recognition

TensorFlow is an open source software library for numerical computation using dataflow graphs. Nodes in the graph represents mathematical operations, while graph edges represent multi-dimensional data arrays (aka tensors) communicated between them. The flexible architecture allows you to deploy computation to one or more CPUs or GPUs in a desktop, server, or mobile device with a single API.”

TensorFlow follows a lazy approach. The usual workflow of running a program in TensorFlow is as follows:

    Build a computational graph, this can be any mathematical operation TensorFlow supports.
    Initialize variables, to compile the variables defined previously
    Create session, this is where the magic starts!
    Run graph in session, the compiled graph is passed to the session, which starts its execution.
    Close session, shutdown the session.



About Practice Problem: Identify the Digits
Automatic digit recognition is of popular interest today. Deep Learning techniques makes it possible for object recognition in image data . This practice problem is meant to give you a kick start in deep learning. As usual, we will not only provide you with the challenge and a solution checker, but also a set of tutorials to get you off the ground!
 
The data set used for this problem is from the populat MNIST data set. Developed by Yann LeCun, Corina Cortes and Christopher Burger for evaluating machine learning model on the handwritten digit classification problem. It is a widely used data set in the machine learning community.
