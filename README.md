# Sentiment-Analysis-For-Amazon-Reviews
![image](https://github.com/aditids/Sentiment-Analysis-For-Amazon-Reviews/assets/64319552/0cf24d7f-cde3-438f-951f-33649bb964aa)

# Introduction
As the volume of customer reviews on Amazon continues to grow exponentially, analyzing this wealth of feedback has become increasingly difficult. However, with the power of machine learning algorithms, sentiment analysis offers an efficient solution to automate this process, enabling businesses to gain valuable insights from customer opinions and enhance their products to boost customer satisfaction. Our primary objective is to address the challenges associated with sentiment analysis of Amazon reviews. Manual analysis of such a vast number of reviews has become both time-consuming and arduous, especially with the surge in online shoppers. By harnessing the capabilities of machine learning, we aim to automate sentiment analysis, providing businesses with actionable insights to improve their products and cater to the evolving needs and preferences of their customers.

# Algorithms 
1. Logistic Regression
![image](https://github.com/aditids/Sentiment-Analysis-For-Amazon-Reviews/assets/64319552/3efe0657-91dd-4272-bb84-cfb4559c28c9)
![image](https://github.com/aditids/Sentiment-Analysis-For-Amazon-Reviews/assets/64319552/7ff65853-e750-44eb-8f2e-f6fa1e8e095a)
Logistic gave good results for simple texts identifying correct connotations but it failed to analyze complex sentences. As logistic regression assumes a linear relationship, it doesn’t quite well match the word relations in a single sentence which would flip the connotations. 

2. Recurrent Neural Network -
RNNs are essential for sentiment analysis tasks involving sequential data, as they excel at capturing dependencies between words in a sentence. They effectively model non-linear relationships through non-linear activation functions. RNNs can also be adapted to transfer learning, enabling pre-training on large corpora and fine-tuning on smaller datasets. Additionally, RNNs are superior in capturing long-term dependencies and contextual information, which is crucial in sentiment analysis compared to Logistic Regression.



3. Fine-tuning BERT
   ![image](https://github.com/aditids/Sentiment-Analysis-For-Amazon-Reviews/assets/64319552/329e366b-ffe3-448a-add5-2afd03339e8f)

BERT uses a transformer-based architecture that allows it to capture the contextualized meaning of words in a sentence. This ability to capture contextualized meaning is crucial for sentimental classification, where the meaning of a word or phrase depends heavily on the surrounding context.
BERT is a bidirectional model that can capture long-range dependencies between words in a sentence. Unlike traditional models such as recurrent neural networks (RNNs) that are limited to processing sequences in one direction, BERT processes sequences in both directions, allowing it to capture relationships between words that are far apart in the sentence.
By fine-tuning on a custom dataset specific to the task, the model can learn task-specific features and improve its performance on that task. During training, the model's parameters are updated using backpropagation to minimize a task-specific loss function.
   
# Result
<img width="663" alt="image" src="https://github.com/aditids/Sentiment-Analysis-For-Amazon-Reviews/assets/64319552/2ce70c46-89d7-41db-97d4-16c506190092">

The results of sentiment analysis indicate that fine-tuning BERT outperforms both Logistic Regression and RNN models. The accuracy percentages demonstrate that Logistic Regression achieves 90.50%, RNN achieves 92.5%, while BERT achieves an impressive accuracy of 99%. These findings emphasize the superior performance of BERT in accurately predicting sentiment in text data, showcasing its ability to capture intricate patterns and nuances for sentiment analysis tasks.
