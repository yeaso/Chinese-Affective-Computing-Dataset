集MBTI（人格类型）+情绪+微情绪+情绪强度的大型数据集。
数据集分两个：1. 基于真实微博信息的集MBTI（人格类型）+情绪+微情绪+情绪强度的大型数据集（CMACD）（该数据集仅开放小样本免费使用）。
2. GPT学习真实微博用户帖子后，生成模拟用户风格的内容作为数据集样本。集MBTI（人格类型）+情绪+微情绪+情绪强度的数据集（CPME）（该数据集完全开放，免费学习研究使用）。
CPME数据集下载地址：https://drive.google.com/file/d/1Ymbd0drln6JcyiT93bMYVW5O4hjdkBft/view?usp=sharing
两种数据集优缺点：
1. CMACD 真实风格，数据噪音大，分类效果不如CPME。适于商业化应用。
2. CPME 模拟用户风格，数据规范、质量高，分类效果显著优于 CMACD。但在语言灵活表达和话题的丰富多样方面，存在局限。适合科学研究和模型训练。

A large-scale dataset integrating MBTI (personality types) + emotion + micro-emotion + emotion intensity.

The dataset is divided into two parts:
CMACD: A large-scale dataset based on real Weibo posts, containing MBTI (personality types) + emotion + micro-emotion + emotion intensity. (This dataset is only partially open to the public, with a small sample available for free use.)
CPME: A dataset generated by GPT after learning from real Weibo user posts, simulating user-style content as sample data. It includes MBTI (personality types) + emotion + micro-emotion + emotion intensity. (This dataset is fully open and free for academic research and learning purposes.)
CPME Dataset Download Link: https://drive.google.com/file/d/1Ymbd0drln6JcyiT93bMYVW5O4hjdkBft/view?usp=sharing

Pros and Cons of the Two Datasets:
CMACD: Reflects authentic user styles but contains more noise, and its classification performance is not as strong as CPME. Suitable for commercial applications.
CPME: Simulates user styles with standardized and high-quality data, and significantly outperforms CMACD in classification tasks. However, it has limitations in flexible language expression and topic diversity. Best suited for scientific research and model training.

The first personality emotion computing dataset: a large-scale dataset combining MBTI (personality types), emotions, micro-emotions, and emotion intensity.
A Chinese Multi-label Affective Computing Dataset Based on Social Media Network Users.
This paper at https://arxiv.org/pdf/2411.08347


![Fig-1](https://github.com/user-attachments/assets/125dc94e-4ee0-4867-aaed-8f06e48e4617)

A Chinese Multi-label Affective Computing Dataset Based on Social Media Network Users
![figure1](https://github.com/user-attachments/assets/8c747260-635e-4f8c-aad1-78b49bc5e5d7)
CMACD
Emotion and personality are central elements in understanding human psychological states. 
Existing affective computing datasets often annotate emotion and personality traits separately, lacking fine-grained labeling of micro-emotions
and emotion intensity in both single-label and multi-label classifications.
Chinese emotion datasets are extremely scarce, and datasets capturing Chinese users’ personality traits are even more limited. 
To address these gaps, this study collected data from the major social media platform Weibo, 
screening 11,338 valid users from over 50,000 individuals with diverse MBTI personality labels and acquiring 566,900 posts along with the users’ MBTI personality tags.
Using the EQN method, we compiled a multi-label Chinese affective computing dataset that integrates the same users' personality traits with six emotions and micro-emotions, 
each annotated with intensity levels. Validation results across multiple NLP classification models demonstrate the dataset’s strong utility.
![GitHub Logo](https://github.com/yeaso/Chinese-Affective-Computing-Dataset/blob/main/Fig-2.jpg)
CPME
In this study, we introduce CPME, the first Chinese dataset that integrates Myers-Briggs Type Indicator (MBTI) personality types with multi-level emotion annotations, addressing several longstanding limitations in the field of affective computing and computational social science, especially for the Chinese language. By simulating stylistically rich, user-specific Weibo posts via a large language model (GPT) trained on real user data, and annotating each post with one of six basic emotions and corresponding intensity levels using our Chinese emotion analysis toolkit, CPME offers a novel and valuable benchmark for emotion and personality modeling.
Our dataset comprises 80,000 GPT-generated Weibo posts, covering all 16 MBTI types, each with stylistic consistency, emotional diversity, and quantified intensity. Importantly, because the data is machine-generated, it avoids ethical and privacy concerns while still maintaining linguistic and psychological realism. Empirical evaluations show that CPME achieves high performance in both personality classification and emotion recognition tasks, and our factor analysis reveals that the emotion-personality relationships in the dataset align with established psychological theory. Notably, the simulated data outperformed real user data in classification experiments, further supporting its robustness and applicability.



CMACD and CPME were designed to advance machine recognition of complex human emotions and provide data support for research in psychology, education, marketing, finance, and politics.



Welcome to use our datas CMACD or CPME, and please cite our paper：
【Jingyi Zhou, Senlin Luo and Haofan Chen. "A Chinese Multi-label Affective Computing Dataset Based on Social Media Network Users." arXiv preprint 	arXiv:2411.08347 (2024).
https://doi.org/10.48550/arXiv.2411.08347
】

【Jingyi Zhou, Senlin Luo and Haofan Chen. "CPME:A Chinese Weibo Text Dataset with Personality and Multi-Emotion Labels for Computational Social Science"       】





