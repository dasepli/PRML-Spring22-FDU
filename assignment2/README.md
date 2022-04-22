你好，欢迎来到第二次作业！
Hello and welcome to the second assignment!

In this assignment, you will work on a Chinese to English machine translation (MT) task with neural networks. Different from assignment1, this is a generation task in the field of NLP. The bilingual parallel corpus you will play with is the News Commentary v13 dataset from the Third Conference on Machine Learning (WMT18). There are about 252700 training samples, 2000 validation samples and 2000 test samples in the dataset. And the Chinese sentences have been processed by word segmentation. You have to design a Sequence to Sequence (Seq2Seq) model to complete this translation task. The Attention mechanism must be used in your model but you are free to design other modules with CNNs, RNNs and so on. You have to evaluate your model on the test set with Bilingual Evaluation Understudy (BELU) score and Perplexity. Besides, you have to visualize the attention matrix to help you understand your model.

After you building your model, in the second part, you have to attack it : ) AI safety is nowadays a popular research point and many kind of attack methods have been developed during the the past few years. These methods include adversarial attack, data poisoning attack, training data leakage attack and so on [1]. In this assignment, you just need to conduct one type of attack. You can choose a simplest one or just analyze what kind of samples the model will predict incorrectly. The important thing is to understand the behavior of the neural models.

You can use the deep learning frameworks like paddle, pytorch, tensorflow in your experiment but not more high-level libraries like Huggingface. Please write down the version of them in the './requirements.txt' file.

The following links may be useful:
- Machine Translation: Foundations and Models,Tong Xiao and Jingbo Zhu, link: https://github.com/NiuTrans/MTBook
- PyTorch Seq2Seq Tutorial @ Ben Trevett, link: https://github.com/bentrevett/pytorch-seq2seq
Certainly, our exercises in the PaddlePaddle AI Studio Platform will be helpful.

[1] Must-read Papers on Textual Adversarial Attack and Defense, GitHub: https://github.com/thunlp/TAADpapers