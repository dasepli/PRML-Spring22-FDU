Congratulations, you have come to the last challenge!

Having finished the past two assignments, we think all you gugs already have a solid foundation in the field of machine learning and deep learning. And now you are qualified to apply machine learning algorithms to the real-world tasks you are interested in, or start your machine learning research.

In this final project, you are free to choose a topic you are passionate about. The project can be an application one, a theoretical one or implementing your own amazing machine learning/deep learning framework like a toy pytorch. If you don't have any idea, we will also provide you with a default one you can play with.

! Notice: If you want to work on your own idea, you have to email the TA (lip21[at]m.fudan.edu.cn) to give a simple project proposal first before May 22, 2022.

**Default Project: Natural Language Inference**

The default final project this semester is a NLP task called "Natural Language Inference". Though deep neural networks have demonstrated astonishing performance in many tasks like text classification and generation, you might somehow think they are just "advanced statistics" but far from intelligent machines. One intelligent machine must be able to reason, you may think. And in this default final project, your aim is to design a machine which can conduct inference. The machine can know that "A man inspects the uniform of a figure in some East Asian country" is contradictory to "The man is sleeping", and "a soccer game with multiple males playing." entails "some men are playing a sport".

The dataset we use this time is the Original Chinese Natural Language Inference (OCNLI) dataset[1]. It is a chinese NLI dataset with about 50k training data and 3k development data. The sentence pairs in the dataset are labeled as "entailment", "neutral" and "contradiction". Due to they release the test data without its labels, we select 5k data pairs from the training data as labeled test data, and leave the other 45k data as your training data. You can visit the GitHub link for more information.

After you finished the NLI task with the full 45k training set, you have to complete an advanced challenge. You have to select at most 5k data from the training set as labeled training set, leaving the other training data as unlabeled training set, then use these labeled and unlabeled data to finish the same NLI task. You can randomly choosing the 5k training data but can also think up some ideas to select more important data as labeled training data. Like assignment1, you may have to think how to use the unlabeled training data.

You can use the deep learning frameworks like paddle, pytorch, tensorflow in your experiment but not more high-level libraries like Huggingface. Please write down the version of them in the './requirements.txt' file.

! Notice: You CAN NOT use any other people's pretrained model like 'bert-base-chinese' in this default project. You are encouraged to design your own model and algorithm, no matter it looks naive or not.

NLI is a traditional but promising NLP task, and you can search the Google/Bing for more information. Some key words can be "natural language inference with attention", "training data selection", "semi-surpervised learning", "unsupervised representation learning" and so on.


**DDL of Final PJ: June 17 23:59, 2022.**

**Reference**
[1] OCNLI: Original Chinese Natural Language Inference, arxiv: https://arxiv.org/abs/2010.05444