#1.Concept of machine Learning
##1.0 what is ML?
~~~
the system improves performance P at task T ,following experiences
~~~
##1.1 data sample
~~~
(x,y) -->(feature,lable or target) single features may not yield good performance ,we could use multiple Features
~~~
##1.2 Classifier (分类器)
~~~
decision boundary (stright line,more complex boundaries ,
~~~
##1.3 Terms
~~~
1.Accuracy
    of correctly classified samples/total number of samples
2.Error
    Error =1-accuracy
3.Training
    Learning process using dada we have in hand (usually with lable ,which also called ground truth)
4.Testing(Inference)
    Test the unknown data(lable unknown) to the system
~~~    
##1.4 Three types of ML
~~~
监督学习（Supervised Learning）：有lable 
        Classification 分类问题（离散点）
        Regression回归问题（连续点）
        Ranking
非监督学习（unSupervised Learning）：无lable，不知道是哪个类，通过feature来自动分类
        clustering（聚类）
        Autoencoder(自编码)
        Mixture Model
        
强化学习（reinforcement learning）：通过 reward function
        Decison Process
        Reward System
~~~
##1.5 Roadmap for machine learning system
~~~
following steps:
    Preprocessing
            data cleaning（数据清洗）
            data augmentation(数据增广，通过造数据或者找数据)
            Split dataset
                training Set
                Validation Set
                Test Set
             Feature Extraction（特征提取）
                get useful features
                    hand craffted features(手工分特征)
                    learned features（自己学习得到feature）
                 Reducing dimensions（降维）
    Training and Selecting Model 
        Training
        Model Select
            Overfitting(过拟合)
            Under fitting（不拟合）
    Evaluating models
        Performance Measure
            Classification Loss
            Accuracy（准确率）
            Confusion Matrix（混淆矩阵）
                Recall(召回率)
                Precision（精确率）
            ROC Curve(ROC曲线)
         Cross Validation(交叉验证)
            k-fold cross validation（分几份）
            Leave-one-out cross validation   
    Predicting unseen data
    
    
 数据量非常大深度学习比较合适，少量的话普通的比较好
~~~