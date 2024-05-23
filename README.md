# 动手实战人工智能 AI By Doing

## 自序

我从 2015 年开始了解机器学习，最早从李航教授编写的《统计学习方法》入门，陆陆续续看了很多学习资料。在学习的过程中，我逐渐发现了一些痛点。

例如，很多由大学老师编写的书籍，偏理论研究，对于数学基础要求很高，对于初学者来说很难理解，同时缺少必要的代码实现。而部分由工程师编写的书，偏实践应用，往往只是介绍了一些工具和库的使用，而没有深入的讲解原理。另外，还有很多书籍都是在介绍算法的基础上，给出了一些代码例子，但是往往过程不完整，无法相互对应，理论和代码很割裂，同时读者很难复现。

入门机器学习的过程中，如果你只会调包，而不深入原理，可能连参数的作用都看不懂，更别说调参了。如果你只会理论，而不会实践，可能连最简单的模型都写不出来，学完似乎毫无实际用处。因此，我希望能够帮助你，既能够理解原理，又能够实践应用，学懂、吃透机器学习。

从 2018 年开始，我陆续使用 Jupyter Notebook 来编写这些内容。Jupyter Notebook 能够将文字和代码结合在一起，方便阅读和理解。同时，它也能够将代码和运行结果一起展示，方便读者复现。

动手实战人工智能系列教程，希望从监督学习开始，带你入门机器学习和深度学习。我尝试剖析和推导每一个基础算法的原理，将数学过程写出来，同时基于 Python 代码对公式进行实现，做到公式和代码的一一对应。与此同时，我也会利用主流的开源框架重复同样的过程，帮助读者看出手动实现和主流框架实现之间的区别。

当然，任何创作都离不开巨人的肩膀，在此特别感谢李航教授编写的《统计学习方法》，斋藤康毅编写的《深度学习入门》，西瓜书，花花书等对我的帮助。也希望我编写的内容，能够帮助到你。

## 协议

该作品由 huhuhang 创作，基于 [署名-非商业性使用-禁止演绎 4.0 国际](https://creativecommons.org/licenses/by-nc-nd/4.0/deed.zh-hans) 授权协议许可。如果你要使用，请严格遵循许可协议。

我并不建议你无意义地转载，存档这些内容，这对于你真正学懂知识毫无帮助，而且会浪费你的时间。如果你真的想要转载，可以在转载的同时，参考许可协议要求附上原文链接，方便读者可以跳转阅读到最新的内容。

---

## 监督学习：回归

- [环境说明](https://aibydoing.com/lab-env.html)
- [机器学习综述及示例](https://aibydoing.com/notebooks/chapter01-01-lab-machine-learning-overview-and-examples.html)
- [线性回归实现与应用](https://aibydoing.com/notebooks/chapter01-02-lab-linear-regression-implementation-and-applications.html)
- [北京市住房价格预测](https://aibydoing.com/notebooks/chapter01-03-challenge-housing-price-prediction-in-beijing.html)
- [多项式回归实现与应用](https://aibydoing.com/notebooks/chapter01-04-lab-polynomial-regression-implementation-and-applications.html)
- [比特币价格预测及绘图](https://aibydoing.com/notebooks/chapter01-05-challenge-bitcoin-price-prediction-and-visualization.html)
- [岭回归和 LASSO 回归实现](https://aibydoing.com/notebooks/chapter01-06-lab-implementation-of-ridge-regression-and-lasso-regression.html)
- [使用矩阵计算岭回归系数](https://aibydoing.com/notebooks/chapter01-07-challenge-computing-ridge-regression-coefficients-with-matrix-operations.html)
- [回归模型评价与检验](https://aibydoing.com/notebooks/chapter01-08-lab-evaluation-and-validation-of-regression-models.html)
- [回归方法综合应用练习](https://aibydoing.com/notebooks/chapter01-09-challenge-comprehensive-practical-application-of-regression-methods.html)

## 监督学习：分类

- [逻辑回归实现与应用](https://aibydoing.com/notebooks/chapter02-01-lab-logistic-regression-implementation-and-applications.html)
- [梯度下降法实现与应用](https://aibydoing.com/notebooks/chapter02-02-challenge-gradient-descent-method-implementation-and-applications.html)
- [K 近邻算法实现与应用](https://aibydoing.com/notebooks/chapter02-03-lab-implementation-and-applications-of-the-k-nearest-neighbors-algorithm.html)
- [K 近邻回归算法实现与应用](https://aibydoing.com/notebooks/chapter02-04-challenge-implementation-and-application-of-k-nearest-neighbors-regression-algorithm.html)
- [朴素贝叶斯实现及应用](https://aibydoing.com/notebooks/chapter02-05-lab-naive-bayes-implementation-and-applications.html)
- [高斯分布函数实现及绘图](https://aibydoing.com/notebooks/chapter02-06-challenge-implementation-and-visualization-of-the-gaussian-distribution-function.html)
- [分类模型评价方法](https://aibydoing.com/notebooks/chapter02-07-lab-evaluation-methods-for-classification-models.html)
- [支持向量机实现与应用](https://aibydoing.com/notebooks/chapter02-08-lab-support-vector-machines-implementation-and-applications.html)
- [支持向量机实现人像分类](https://aibydoing.com/notebooks/chapter02-09-challenge-support-vector-machine-for-human-portrait-classification.html)
- [决策树实现与应用](https://aibydoing.com/notebooks/chapter02-10-lab-decision-tree-implementation-and-applications.html)
- [决策树模型参数优化及选择](https://aibydoing.com/notebooks/chapter02-11-challenge-optimization-and-selection-of-decision-tree-model-parameters.html)
- [装袋和提升集成学习方法](https://aibydoing.com/notebooks/chapter02-12-lab-integrated-learning-method-for-bagging-and-boosting.html)
- [异质集成投票方法应用](https://aibydoing.com/notebooks/chapter02-13-challenge-application-of-heterogeneous-ensemble-voting-methods.html)
- [使用交叉验证快速选择模型](https://aibydoing.com/notebooks/chapter02-14-challenge-model-selection-with-cross-validation.html)

## 无监督学习：聚类

- [划分聚类方法实现与应用](https://aibydoing.com/notebooks/chapter03-01-lab-clustering-methods-implementation-and-applications.html)
- [使用 K-Means 完成图像压缩](https://aibydoing.com/notebooks/chapter03-02-challenge-image-compression-using-k-means-clustering.html)
- [层次聚类方法实现与应用](https://aibydoing.com/notebooks/chapter03-03-lab-implementation-and-applications-of-hierarchical-clustering-methods.html)
- [主成分分析原理及应用](https://aibydoing.com/notebooks/chapter03-04-lab-principle-and-applications-of-principal-component-analysis.html)
- [层次聚类应用及聚类树绘制](https://aibydoing.com/notebooks/chapter03-05-challenge-hierarchical-clustering-applications-and-dendrogram-visualization.html)
- [密度聚类方法实现与应用](https://aibydoing.com/notebooks/chapter03-06-lab-implementation-and-applications-of-density-based-clustering-algorithms.html)
- [密度聚类标记异常共享单车](https://aibydoing.com/notebooks/chapter03-07-challenge-density-based-clustering-for-anomaly-detection-in-shared-bike-systems.html)
- [谱聚类及其他聚类方法应用](https://aibydoing.com/notebooks/chapter03-08-lab-application-of-spectral-clustering-and-other-clustering-methods.html)
- [常用聚类算法对比评估](https://aibydoing.com/notebooks/chapter03-09-challenge-comparative-evaluation-of-common-clustering-algorithms.html)

## 无监督学习：关联规则

- [Apriori 关联规则学习方法](https://aibydoing.com/notebooks/chapter04-01-lab-apriori-association-rule-learning-algorithm.html)
- [购物数据关联规则分析](https://aibydoing.com/notebooks/chapter04-02-challenge-analysis-of-association-rules-in-shopping-data.html)
- [时间序列数据分析处理](https://aibydoing.com/notebooks/chapter04-03-lab-time-series-data-analysis-and-processing.html)
- [股票时间序列数据处理](https://aibydoing.com/notebooks/chapter04-04-challenge-stock-time-series-data-processing.html)
- [时间序列数据建模分析](https://aibydoing.com/notebooks/chapter04-05-lab-modelling-and-analysis-of-time-series-data.html)
- [农业生产指数建模分析](https://aibydoing.com/notebooks/chapter04-06-challenge-modeling-and-analysis-of-agricultural-production-index.html)

## 机器学习工程：模型部署和推理

- [自动化机器学习综述](https://aibydoing.com/notebooks/chapter05-01-lab-a-comprehensive-review-of-automated-machine-learning.html)
- [自动化机器学习实践应用](https://aibydoing.com/notebooks/chapter05-02-lab-automated-machine-learning-practices-and-applications.html)
- [AutoML 完成手写字符分类](https://aibydoing.com/notebooks/chapter05-03-challenge-automl-for-handwritten-character-classification.html)
- [机器学习模型推理与部署](https://aibydoing.com/notebooks/chapter05-04-lab-machine-learning-model-inference-and-deployment.html)
- [蘑菇分类模型部署和推理](https://aibydoing.com/notebooks/chapter05-05-challenge-mushroom-classification-model-deployment-and-inference.html)
- [机器学习模型动态增量训练](https://aibydoing.com/notebooks/chapter05-06-lab-dynamic-incremental-training-of-machine-learning-models.html)
- [在线学习及云端模型部署](https://aibydoing.com/notebooks/chapter05-07-challenge-online-learning-and-cloud-model-deployment.html)

## 深度学习原理：人工神经网络

- [深度学习综述和示例](https://aibydoing.com/notebooks/chapter06-01-lab-a-concise-review-and-exemplification-of-deep-learning.html)
- [感知机和人工神经网络](https://aibydoing.com/notebooks/chapter06-02-lab-perceptron-and-artificial-neural-networks.html)
- [手写字符识别神经网络](https://aibydoing.com/notebooks/chapter06-03-challenge-handwritten-character-recognition-neural-network.html)

## 深度学习框架：TensorFlow & PyTorch

- [TensorFlow 基础概念语法](https://aibydoing.com/notebooks/chapter07-01-lab-tensorflow-fundamentals-and-syntax.html)
- [TensorFlow 加州房价预测](https://aibydoing.com/notebooks/chapter07-02-challenge-tensorflow-california-housing-price-prediction.html)
- [TensorFlow 构建神经网络](https://aibydoing.com/notebooks/chapter07-03-lab-building-neural-networks-with-tensorflow.html)
- [TensorFlow 汽车评估分类](https://aibydoing.com/notebooks/chapter07-04-challenge-tensorflow-automotive-rating-classification.html)
- [TensorFlow 高阶 API 使用](https://aibydoing.com/notebooks/chapter07-05-lab-advanced-tensorflow-api-usage.html)
- [TensorFlow 时尚物品分类](https://aibydoing.com/notebooks/chapter07-06-challenge-tensorflow-fashion-item-classification.html)
- [PyTorch 基础概念语法](https://aibydoing.com/notebooks/chapter07-07-lab-pytorch-fundamentals-and-syntax.html)
- [PyTorch 构建神经网络](https://aibydoing.com/notebooks/chapter07-08-lab-building-neural-networks-with-pytorch.html)
- [PyTorch 实现线性回归](https://aibydoing.com/notebooks/chapter07-09-challenge-linear-regression-implementation-with-pytorch.html)

## 深度学习应用：计算机视觉

- [卷积神经网络原理](https://aibydoing.com/notebooks/chapter08-01-lab-principles-of-convolutional-neural-networks.html)
- [卷积神经网络构建](https://aibydoing.com/notebooks/chapter08-02-lab-convolutional-neural-network-construction.html)
- [构建 LeNet-5 Estimator](https://aibydoing.com/notebooks/chapter08-03-challenge-building-lenet5-estimator.html)
- [图像分类原理与实践](https://aibydoing.com/notebooks/chapter08-04-lab-principles-and-practices-of-image-classification.html)
- [迁移学习完成动物分类](https://aibydoing.com/notebooks/chapter08-05-challenge-animal-classification-via-transfer-learning.html)
- [生成对抗网络原理及构建](https://aibydoing.com/notebooks/chapter08-06-lab-principles-and-construction-of-generative-adversarial-networks.html)
- [DCGAN 动漫人物图像生成](https://aibydoing.com/notebooks/chapter08-07-challenge-anime-character-image-generation-using-dcgan.html)
- [自动编码器原理及构建](https://aibydoing.com/notebooks/chapter08-08-lab-autoencoder-principles-and-construction.html)
- [卷积自动编码器图像去噪](https://aibydoing.com/notebooks/chapter08-09-challenge-denoising-convolutional-autoencoders-for-image-denoising.html)
- [目标检测原理与实践](https://aibydoing.com/notebooks/chapter08-10-lab-principles-and-practices-of-object-detection.html)
- [YOLO 图像目标检测应用](https://aibydoing.com/notebooks/chapter08-11-challenge-yolo-image-object-detection-application.html)

## 深度学习应用：自然语言处理

- [循环神经网络原理](https://aibydoing.com/notebooks/chapter09-01-lab-principles-of-recurrent-neural-networks.html)
- [循环神经网络构建](https://aibydoing.com/notebooks/chapter09-02-lab-construction-of-recurrent-neural-networks.html)
- [LSTM 预测股票价格](https://aibydoing.com/notebooks/chapter09-03-challenge-stock-price-prediction-with-lstm.html)
- [文本分类原理与实践](https://aibydoing.com/notebooks/chapter09-04-lab-principles-and-practices-of-text-classification.html)
- [深度学习完成假新闻分类](https://aibydoing.com/notebooks/chapter09-05-challenge-deep-learning-for-fake-news-classification.html)
- [自然语言处理框架拓展](https://aibydoing.com/notebooks/chapter09-06-lab-extension-of-natural-language-processing-frameworks.html)
- [Google BERT 预训练技术](https://aibydoing.com/notebooks/chapter09-07-challenge-application-of-bert-pretraining-techniques.html)
- [神经机器翻译和对话系统](https://aibydoing.com/notebooks/chapter09-08-lab-neural-machine-translation-and-conversational-systems.html)

## 深度学习工程：模型部署和推理

- [自动化深度学习综述](https://aibydoing.com/notebooks/chapter10-01-lab-a-concise-review-of-automated-deep-learning.html)
- [自动化深度学习实践](https://aibydoing.com/notebooks/chapter10-02-lab-automated-deep-learning-practice.html)
- [仙人掌航拍照片分类识别](https://aibydoing.com/notebooks/chapter10-03-challenge-aerial-cactus-image-classification.html)
- [深度学习模型推理和部署](https://aibydoing.com/notebooks/chapter10-04-lab-deep-learning-model-inference-and-deployment.html)
- [构建图像分类推理服务](https://aibydoing.com/notebooks/chapter10-05-challenge-building-image-classification-inference-service.html)
- [深度学习云端服务实践](https://aibydoing.com/notebooks/chapter10-06-lab-deep-learning-cloud-service-practice.html)
- [云服务识别增值税发票](https://aibydoing.com/notebooks/chapter10-07-challenge-cloud-service-vat-invoice-recognition.html)

## 强化学习基础

- [强化学习介绍与示例](https://aibydoing.com/notebooks/chapter11-01-lab-introduction-and-examples-of-reinforcement-learning.html)
- [Q-Learning 强化学习方法实现](https://aibydoing.com/notebooks/chapter11-02-lab-implementation-of-the-q-learning-reinforcement-learning-method.html)
- [实现 Sarsa 学习算法走出迷宫](https://aibydoing.com/notebooks/chapter11-03-challenge-implementing-the-sarsa-learning-algorithm-to-navigate-a-maze.html)
