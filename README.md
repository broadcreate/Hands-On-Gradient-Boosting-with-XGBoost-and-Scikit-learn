

# 梯度提升算法实战
这是清华大学出版社出版的 《梯度提升算法实战》 一书的代码库。

## 内容摘要
本书首先介绍了scikit-learn中的机器学习和XGBoost技术，然后探讨了梯度提升背后的理论知识。包括决策树、装袋技术及XGBoost超参数。

本书将从头开始构建梯度提升模型，并将梯度提升扩展到大数据领域。

本书重点探讨XGBoost的细节，着重于速度增强和通过数学推导导出参数。

通过详细案例研究，练习使用 scikit-learn 、原始的 Python API 构建、以及微调 XGBoost 分类器和回归器。

利用XGBoost超参数来提高评分、纠正缺失值、缩放不平衡数据集以及微调备选基学习器。

最后，应用高级 XGBoost 技术，如构建非相关的集成模型、堆叠模型，并使用稀疏矩阵、定制的转换器和管道为行业部署准备模型。

全书共分3篇：
* 第1篇（第1～4章）为入门篇，介绍XGBoost背后的实用理论，包括装袋和提升模型结构、数据预处理、回归和分类模型、XGBoost基本模型及超参数微调；
* 第2篇（第5～7章）为进阶篇，介绍XGBoost框架构成及超参数优化；
* 第3篇（第8~10章）为进阶篇，着重讨论微调备选基学习器、创新技巧、特征工程，并使用稀疏矩阵、定制转换器和管道，练习构建适合行业部署的模型。全书提供了大量应用实例。
  
本书适合作为高等院校计算机、软件工程专业高年级本科生、研究生的教材，同时适合有一定机器学习基础的数据科学家、机器学习工程师和研究人员阅读，为解决复杂问题提供实用指导。

使用以下软件和硬件清单，您可以运行本书中所有代码文件（第1-10章）。

### 软件和硬件清单

| 章节  | 所需软件                   | 所需操作系统                        |
| -------- | ------------------------------------| -----------------------------------|
| 1        |Anaconda: Jupyter Notebbok/ sklearn 0.23                    | Windows, Mac OS X, and Linux (Any) |
| 2        | Anaconda: Python 3.7           | Windows, Mac OS X, and Linux (Any) |
| 3        | xgboost 1.2            | Windows, Mac OS X, and Linux (Any) |

# Hands-On Gradient Boosting with XGBoost and scikit-learn
<a href="https://www.packtpub.com/product/hands-on-gradient-boosting-with-xgboost-and-scikit-learn/9781839218354"><img src="https://static.packt-cdn.com/products/9781839218354/cover/smaller" alt="Hands-On Gradient Boosting with XGBoost and scikit-learn" height="256px" align="right"></a>

This is the code repository for [Hands-On Gradient Boosting with XGBoost and scikit-learn](https://www.packtpub.com/product/hands-on-gradient-boosting-with-xgboost-and-scikit-learn/9781839218354), published by Packt.

**Perform accessible machine learning and extreme gradient boosting with Python**

## What is this book about?
XGBoost is an industry-proven, open-source software library that provides a gradient boosting framework for scaling billions of data points quickly and efficiently.

This book covers the following exciting features: <First 5 What you'll learn points>
* Build gradient boosting models from scratch
* Develop XGBoost regressors and classifiers with accuracy and speed
* Analyze variance and bias in terms of fine-tuning XGBoost hyperparameters
* Automatically correct missing values and scale imbalanced data
* Apply alternative base learners like dart, linear models, and XGBoost random forests

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/10DigitISBN) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" 
alt="https://www.packtpub.com/" border="5" /></a>


## Instructions and Navigations
All of the code is organized into folders. For example, Chapter02.

The code will look like the following:
```
cross_val(LogisticRegression()) 
```

**Following is what you need for this book:**
This book is for data science professionals and enthusiasts, data analysts, and developers who want to build fast and accurate machine learning models that scale with big data. Proficiency in Python, along with a basic understanding of linear algebra, will help you to get the most out of this book.

With the following software and hardware list you can run all code files present in the book (Chapter 1-10).

### Software and Hardware List

| Chapter  | Software required                   | OS required                        |
| -------- | ------------------------------------| -----------------------------------|
| 1        |Anaconda: Jupyter Notebbok/ sklearn 0.23                    | Windows, Mac OS X, and Linux (Any) |
| 2        | Anaconda: Python 3.7           | Windows, Mac OS X, and Linux (Any) |
| 3        | xgboost 1.2            | Windows, Mac OS X, and Linux (Any) |


We also provide a PDF file that has color images of the screenshots/diagrams used in this book. [Click here to download it](https://static.packt-cdn.com/downloads/9781839218354_ColorImages.pdf).


### Related products   
* Hands-On Machine Learning with scikit-learn and Scientific Python Toolkits [[Packt]](https://www.packtpub.com/product/hands-on-machine-learning-with-scikit-learn-and-scientific-python-toolkits/9781838826048) [[Amazon]](https://www.amazon.com/dp/1838826041)  

* Mastering Machine Learning Algorithms- Second Edition [[Packt]](https://www.packtpub.com/product/mastering-machine-learning-algorithms-second-edition/9781838820299) [[Amazon]](https://www.amazon.com/dp/1838820299)

## Get to Know the Author
**Corey Wade**
M.S. Mathematics, M.F.A. Writing and Consciousness, is the founder and director of Berkeley Coding Academy, where he teaches machine learning and AI to teens from all over the world. Additionally, Corey chairs the Math Department at the Independent Study Program of Berkeley High School, where he teaches programming and advanced math. His additional experience includes teaching natural language processing with Hello World, developing data science curricula with Pathstream, and publishing original statistics (3NG) and machine learning articles with Towards Data Science, Springboard, and Medium. Corey is co-author of the Python Workshop, also published by Packt.

### Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSdy7dATC6QmEL81FIUuymZ0Wy9vH1jHkvpY57OiMeKGqib_Ow/viewform) if you have any feedback or suggestions.
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781839218354">https://packt.link/free-ebook/9781839218354 </a> </p>
