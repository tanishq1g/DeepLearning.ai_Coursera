## Week 1 Quiz - Introduction to Deep Learning

1. What does the analogy “AI is the new electricity” refer to?

    - [ ] AI is powering personal devices in our homes and offices, similar to electricity.
    - [x] Similar to electricity starting about 100 years ago, AI is transforming multiple industries.
    - [ ] Through the “smart grid”, AI is delivering a new wave of electricity.
    - [ ] AI runs on computers and is thus powered by electricity, but it is letting computers do things not possible before.
    
    Note:  AI is transforming many fields from the car industry to agriculture to supply-chain...

2. Which of these are reasons for Deep Learning recently taking off? (Check the two options that apply.)

    - [x] We have access to a lot more computational power.
    - [x] We have access to a lot more data.
    - [ ] Neural Networks are a brand new field.
    - [x] Deep learning has resulted in significant improvements in important applications such as online advertising, speech recognition, and image recognition.
    
    Note: The digitalization of our society has played a huge role in this. Development of harware(GPU) has helped a lot to improve performance of deep learning algo.

3. Recall this diagram of iterating over different ML ideas. Which of the statements below are true? (Check all that apply.)

    - [x] Faster computation can help speed up how long a team takes to iterate to a good idea. 
    - [x] Being able to try out ideas quickly allows deep learning engineers to iterate more quickly.
    - [x] Recent progress in deep learning algorithms has allowed us to train good models faster (even without changing the CPU/GPU hardware).
    - [ ] It is faster to train on a big dataset than a small dataset.

    Note: In lecture 4

4. When an experienced deep learning engineer works on a new problem, they can usually use insight from previous problems to train a good model on the first try, without needing to iterate multiple times through different models. True/False?

    - [ ] True
    - [x] False
    
    Note: Finding the characteristics of a model is key to have good performance. Although experience can help, it requires multiple iterations to build a good model.

5. Which one of these plots represents a ReLU activation function?

    compare with what discussed in lectures
    
6. Images for cat recognition is an example of “structured” data, because it is represented as a structured array in a computer. True/False?
    
    - [ ] True
    - [x] False
    
7. A demographic dataset with statistics on different cities' population, GDP per capita, economic growth is an example of “unstructured” data because it contains data coming from different sources. True/False?
    
    - [ ] True
    - [x] False
    
8. Why is an RNN (Recurrent Neural Network) used for machine translation, say translating English to French? (Check all that apply.)

    - [x] It can be trained as a supervised learning problem.
    - [ ] It is strictly more powerful than a Convolutional Neural Network (CNN).
    - [x] It is applicable when the input/output is a sequence (e.g., a sequence of words).
    - [ ] RNNs represent the recurrent process of Idea->Code->Experiment->Idea->....
    
    Note: We can train it on many pairs of sentences x (English) and y (French). An RNN can map from a sequence of english words to a sequence of french words.

9. In this diagram which we hand-drew in lecture, what do the horizontal axis (x-axis) and vertical axis (y-axis) represent?

    - x-axis -> amount of data
    - y-axis -> performance of the algorithm.

10. Assuming the trends described in the previous question's figure are accurate (and hoping you got the axis labels right), which of the following are true? (Check all that apply.)

    - [x] Increasing the training set size generally does not hurt an algorithm’s performance, and it may help significantly.
    - [x] Increasing the size of a neural network generally does not hurt an algorithm’s performance, and it may help significantly.
    - [ ] Decreasing the training set size generally does not hurt an algorithm’s performance, and it may help significantly.
    - [ ] Decreasing the size of a neural network generally does not hurt an algorithm’s performance, and it may help significantly.