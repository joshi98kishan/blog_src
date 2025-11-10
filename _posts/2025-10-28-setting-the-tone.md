---
title: Setting The Tone
layout: post
subtitle: About why I started the blog.
---

<span style="color: red;">_This blog is UNDER PROGRESS. I have overspent the time for writing this blog. And now I feel like I should first work on some more important blogs, and then I will continue this not-so-important blog. The first and last parts are almost complete. You will find grey-coloured text that is either redundant or contains ideas which I am yet to integrate with the main text. And also you will find silly grammatical mistakes because of two reasons. First, I am still learning English. Second, the mistakes which I could have avoided but still committed because I wanted to write fast and hence avoided conscious grammar checking. Later, when I continue working on this blog, I will have to use a grammar checker tool for unavoidable mistakes._</span>

### Prerequisite
I have written a blog titled - [AI - Mathematical Formulation of Intelligence]({%post_url 2025-10-27-AI-is-maths-formulation%}){:target="_blank"}. This blog explains how AI is only possible by running maths equations in the computer, which motivates me and will motivate others to first master maths in order to do AI research.

But this blog also answers three questions which will help provide some context for this blog. I have briefly explained the answers to this questions in this section below.

##### AI vs ML
AI is a concept of computers having intelligence. And ML is a way (a type of computer algorithm) to implement that concept of AI or to make that concept a reality. 

##### Short answer to why I want to become an AI researcher?
Currently, ML is only able to partially implement (which is called Narrow AI or ANI) the proper concept of AI which is Artificial General Intelligence (AGI). ANI is already super useful in some of the important applications, but **safe** AGI will be super super useful in all the applications from healthcare to all kinds of science. This fascinates me and motivates me to work on AI. AGI might be implemented solely via ML or via the hybrid of ML and Symbolic AI (another way to implement AI).

##### Mastery of maths is required
To understand, create or improve AI algorithms, one must have good understanding of the required mathematics, which is linear algebra, probability and calculus. Let's call the required maths as "maths fundamentals" of ML. Maths fundamentals is beyond the school level maths. 

### My knowledge of maths as a ML engineer
I was good at school level maths. To _properly learn_ maths fundamentals requires a _lot of effort_ (atleast for me). And back then, I didn't had _enough motivation_ to put such efforts because with minimal efforts, I was able to acquire surface-level understanding of ML and maths fundamentals, which was enough to get a job as a ML engineer in an early stage startup.

### Decided to do independent research
I decided to become an AI researcher towards the end of the second year of my job. I left the job. I tried to get in the good university but I could not. So, I decided to do independent research. I thought, as I prepare for the independent research, I might create good research profile which opens the chance for me to apply again for the desired graduate program or otherwise I would continue doing the independent research.

### Learning maths systematically for the first time
To do research, I _had to_ first master the maths fundamentals. So, for the first time I had motivation to even try to study maths systematically. After this short period of learning maths, I again ended up having surface level understanding but much better than before. This was the longest time I ever spent on learning maths.

### Gaining Motivation by understanding literature
This time, I had better motivation. But not enough to learn it properly. Because I was not sure - How exactly these mathematical tools I was learning e.g. solving linear system of equations, vector space, eigen vector, SVD, probability distributions etc. work together in harmony such that to induce intelligent behavior of the algorithm? And also how researchers came up with the idea of which tools to combine and how to combine at the first place.

After my failed attempt of understanding the maths properly, I got this idea of finding the subarea within AI which excites me a lot. That subarea in which I would love to do research and then _understanding papers_ of it. I would have more than enough motivation to properly understand those papers. And I have to do this anyway, because that is part of the preparation to become an AI researcher. I thought of using this excitement of working on that subarea to drive me to prepare for research (top-down approach of learning anything).

Without mastering the maths fundamentals, I cannot expect to understand research papers. The _only difficult part of understanding a paper is to understand answers of above questions_. My plan was to understand those answers based on my existing maths knowledge. So that atleast I have superficial understanding of those answers. I would know that . That is, I would know the importance of mathematics for AI not because someone has told me that they are important. But because I have seen how these maths tools are used to induce intelligence. I would know that maths is indeed inducing the intelligence and nothing else. I would know that whatever intelligent behaviour, algorithm is showing is only because computer is running the mathematical functions. I would clearly see the end goal of learning the maths fundamentals, i.e., I will be able to know AI algorithms in and out (answers to above questions), once I master maths.  

Knowing all these, would give me _enough motivation to understand those maths tools properly_, which in turn help me properly understand those answers. E.g., understanding each tool would help me understand how they work together such that to induce intelligent behavior of an algorithm. Once those answers are understood, then understanding the paper is very easy.

When I understand a paper, I gain two things: I understand maths corresponding to that paper and how those maths topics are used to create that AI algorithm. As I understand more and more papers of that subarea, both of these understandings will grow. First, I will understand more and more topics of maths fundamentals. Second, I would be gaining the ability to use those tools for my own AI research, (i.e. ability to use maths to better understand or improve existing algorithm, or create new algorithms). So, understanding papers make me gain all the required knowledge and skills for becoming an AI researcher.
    
<span style="color: grey;">There are inspiring papers which gives you potential ideas of creating an better AI algorithm</span>


### Defining research interest
I then began to properly define the subarea of AI which excites me. I looked at open problems in AI and I came to know the limitations of Deep Learning (a special type of ML) algorithms like robustness, continual learning, high sample complexity, interpretability etc.

Since computer vision is my favourite among other subfields of AI, so looking at the potential solutions accordingly, lead me to the seminal paper by Francesco Locatello, which proposed slot attention for object centric learning. From that paper, I came to know about object centric learning and corresponding research of Yoshua Bengio, Bernhard Scholkopf, Geoffrey Hinton and others. And finally I came to know about compositionality and causality, the subarea which excites me most. These researchers were trying to fix limitations of deep learning algorithms by inducing compositionality and causality. And among other papers, slot attention paper was the key paper in this area.

### Understanding research papers 
##### Recent papers relies on previous papers
I tried to read their recent papers but they were advanced and not an easy read for me. Although the papers were based on maths fundamentals (LA, prob, and calc) but they combined maths tools in such a complicated manner and then gave answers to the above questions with the help of jargons and cited the papers which explains those jargons. Or created new jargons whose explanations was again based on existing jargons. Citations also explains jargons with the help of other jargons. 

[explain what I mean by jargons]

Authors use jargons because paper needs to be written in limited pages and with jargons, a lot of information can be conveyed in little space (high information density).

I knew maths jargons but not the ones which are related to the subarea I selected. [Give some exmaple of jargons like representation, model, loss, latent, slot, etc. by reading slot attention paper]

##### My plan of understanding the evolution
Recent papers hide answers I was looking for, behind jargons and corresponding citations. As I was jumping from one paper to another, I got this idea of understanding all citations from which recent papers refers jargons from. That was the only way to understand recent papers because it is hard to find a course or lectures which would help me explain the papers I was trying to understand. Even if there is a course, it would rely on jargons to make the explanation concise. Now, citations will also depend on their own citations. This problem of understanding all the required jargons could only be solved by understanding all the ancesters of the recent papers in the chronological order.

To this end, I thought of finding the sequence of developements which leads to current research. Research means extending the existing knowledge about any subject. Every research paper extends the existing knowledge of the subject by proposing new knowledge. And it proposes this knowledge by relying on the existing knowledge developed by previous papers. And this is how knowledge of any subject develops over time. My idea was to first find the sequence of papers in chronological order which has developed the knowledge of the subarea of my interest over time. And then to understand each paper in that order. So that I have enough knowledge (knowing all the required jargons) to understand recent papers.

In this way, I could understand all the jargons of that subarea in a smooth manner, without any conflict because for every paper you are understanding, you know all the jargons on which that paper relies on. Authors write papers by keeping their potential readers in mind. For papers in AI, authors would assume that most of their readers would be AI researchers or students of computer science field and the readers have already gone through previous papers from where they refer jargons. Given this assumption in mind, authors provide enough explanation of knowledge they are proposing, so that most of their readers could understand it properly and easily. If the knowledge authors are proposing can not be explained through jargons, then they would provide enough explanation (by using only mathematical jargons, which is fine for me and that is what I am looking for, so that I can "connect" the mathematics with "how" it has intelligence inducing power, which AI jargons were blocking that connection. I would not understand the "how" yet but i will know that math can induce intelligence and is indeed doing it and is the only way to do it.) of the mathematics of the algorithm so that readers could understand the paper if they have already mastered maths fundamentals (would assign some name to that explanation which will be new jargon).


**The assumption I had in my mind is that knowledge proposed by each research paper is very easy to understand when you have already understood previous papers on which this paper is based on and you are familiar with the larger field in which research area of this paper lies.** Because this is what the role of any research paper is to properly explain what they are proposing, so that research community could understand and build upon it. 

So only challenge is to understand the first paper. Once it is understood, then every next paper in the sequence is easy to understand.

<span style="color: grey;">AI is a research area within a larger field of computer science. Your knowledge of the AI will grow just like how computer science researchers grew their knowledge by reading research papers in chronological order.</span>


[lets talk about the first paper]
But first paper will also be easy to understand because it is the paper which is starting a new research area. Which has two implications. First, knowledge it will be proposing will be basic. And second, it could not rely on jargons to present the knowledge because no jargons already exist. Second implication is obvious, let me elaborate the first one. 

First one is especially true in AI research. Authors of the first paper got inspired from human intelligence which is powered by brain and thought of putting this intelligence in a computer. They knew that brain is composed of large number of highly connected neurons. Function of a single neuron is very simple and human intelligence arise from complex interconnection of these simple elements. Before researchers could simulate the function of human brain, they have to _acquire knowledge of how to simulate a single neuron in a computer_. Once this is done, then only they can try to figure out how to make multiple neurons work together. Single neuron was easily simulated in a computer with a school level mathematics because it has simple function. 


So, first paper would be easy to understand because it would be based on school level maths and it would explain the knowledge it is proposing without using any jargon. And it would be introducing jargons like "neuron", "learning" for the first time to a larger field of computer science. Next natural extension of this knowledge by subsequent papers, is to acquire the knowledge of how a network of multiple neurons can learn to do simple tasks (just like how humans learn to do tasks). 

[introduce bm and hn here, and connect them with the above para by saying that these two algorithms proposed different learning algorithms - associative memory and distribution learning, or may be BM is an advanced form of HN]

[Connect the below para with HN and BM, how these models are inspired from stat mech and not directly on brain.]
<span style="color: grey;">Today we do not know, how exactly brain induces intelligence, so back then there was even less knowledge about human intelligence. But they atleast knew that brain is composed of large number of highly connected neurons. They knew how a single neuron works but they didn't knew how exactly they are connected to each other.</span>

<span style="color: grey;">Research in (any area?) always moves from simpler to more complex knowledge. Where first paper proposes the basic knowledge of AI (could be a basic algorithm or just concept), then each next paper improves the knowledge of AI by either improving the existing algorithms or explaining them better or proposing newer and better algorithms. For e.g., AI research began with perceptron (single neuron) algorithm as first AI algorithm. And then it evolved in this sequence - Multi Layer Perceptron or MLP (multiple neurons), Deep Neural Network (large number of hidden layers), and now LLMs (very very deep neural networks).</span>

Understanding chronology of papers has several advantages. You not only understand the whole AI literature. But you also understand the maths fundamentals. Both are required for becoming an AI researcher. Maths fundamentals gives you tools. And AI literature tells you how to use those tools to implement the narrow AI and also gives potential ideas of how full concept of AI (AGI) could be implemented.


##### Chronology of papers
For the subarea of my interest, these are the sequence of papers (in chronological order) I found: Boltzmann Machine (BM), Restricted BM, Variational Auto Encoder (VAE) and Slot Attention. All these were the methods on which the research of compositionality in Computer Vision was based on.

But later I found out that these were not the only papers in the chronology. I found these papers because these papers proposed some "important" knowledge, hence they became more popular and influential, and easy to find. _Only after reading them_, I came to know that there are more "unimportant" papers in between each two consecutive papers, i.e., RBM depends not only on BM paper but also on other papers between them. More on this later.


##### BM as a starting point
BM relies on two papers, one is Hopfield Network (HN) paper by John Hopfield and other is simulated annealing paper by Kirkpatrick et al. HN is a model for associative memory. And simulated annealing algorithm is based on Statistical Mechanics (or in short "Stat Mech", a branch of physics) and it is for combinatorial optimization.

HN paper relies on the knowledge of perceptron and a concept of energy from statistical mechanics. HN is a successor of perceptron because it proposed a learning algorithm for a network of neurons. (?But) it could only allow a network to do simple task of memorizing a particular set of items and to retrieve any one of that item given a partial content of that item (associative memory). BM was generalisation of HN where it could learn the whole distribution just like humans which allows it to retrieve any item in the distribution, given the partial content of that item.  

BM is a gateway into the research subarea of my interest. Or one can say BM is at the root or at the foundation of this research because BM was the first paper which proposed a learning algorithm for a network of neurons, which allows the network to learn to perform some of human-like tasks. That is, it could learn the data distribution which allows the network to interpret a given image, complete a partial image, classify a image and generate an image. It was a breakthrough.

<span style="color: grey;">BM introduced the ideas (like latent variables or hidden units and their learning algorithm)</span>

<span style="color: grey;">Also, I later came to know that apart from the gateway to the current research, it is also a gateway to deep learning research in mid 2000's. In 2006, Hinton showed that RBM (a form of BM - Restricted BM) can be used to train "deep" neural network in a better way. Before this paper, training deep network was very difficult and most of the research community was doubtful about the success of deep learning. But this paper gave new hope to the deep learning research community. After this paper, interest in deep learning only grew exponentially because from year to year, it only became better and more successful.</span>

<span style="color: grey;">The goal of BM was so ambitious as it tried to solve a broader problem of computer vision - classification, completing the partial image, imagination and understanding the content of the image. In theory, it could do all that but it was very slow and not scalable.</span> 


<span style="color: grey;">And what is more interesting is that BM was proposed in 1983, i.e., during the time when AI research was in the nascent stage. At that time, research in AI was new and risky, so there were few AI researchers and hence fewer AI papers.</span>

<span style="color: grey;">Main concept of Hopfield Network (HN) for associative memory is so simple that anyone with school level maths can understand it. And simulated annealing is just the application of metropolis algorithm, a basic version of Markov chain Monte Carlo (MCMC). MCMC is a topic of applied mathematics and it is one of the most popular method, which has many applications. Which means, there are plenty of resources explaining this. 
</span>

<span style="color: grey;">There are many advantages which make the BM paper, the best paper to start with. _First advantage_ was that, BM paper proposed a new AI algorithm, i.e., it didn't proposed any incremental developement and it didn't relied heavily on previous AI papers. It relied on the concepts of Hopfield Network (HN)(Hopfield, 1982) and on the concepts of Statistical Mechanics (or in short "Stat Mech", a branch of physics). So, I had to first understand the HN paper and concepts of Stat Mech. Which is comparitively much easier than understanding many concepts AI paper of today relies on. This is the advantage because of picking an "old" paper (In 1980s, research in AI was new and risky, so there were few AI researchers and hence few AI papers).</span>


<span style="color: grey;">_Second advantage_ was that BM paper proposed a new AI algorithm. So, authors explained the algorithm in detailed manner. Because of first and second advantage, breaking the BM paper down and finding the relatable maths topic was easier.</span>

##### Three Blogs
[Mention the difficulty of understanding HN and BM paper]
<span style="color: grey;">i.e. HN paper not only depends on perceptron and neuron but also on stat mech. Similarly, BM paper not only depended on HN paper but also on simulated annealing paper. But I thought that once I understand BM, it will be easy for me to understand rest of the papers in chronology.
</span>

To understand BM, I had to first understand HN paper and some simple concepts of StatMech. To comprehensively understand these topics, I decided to write and start my first blog site. Because as we know, in order to explain something _properly_, one should better know it. I wrote my first blogs on HN and Stat Mech and then a blog on BM. Explaining (by writing) indeed helped my understanding. This is for the first time, I took a paper seriously and tried to understand every part of it. 

Full understanding comes when you see it working, so I implemented experiments in BM and HN paper. There were multiple experiments in both the papers to show the capabilities of each technique. While there were no exact details about how those experiments are implemented, I implemented them based on my understanding.

For HN experiments, there was a very slight difference between the results I obtained vs results mentioned in the paper. For BM, I was able to perfectly reproduce all (total three) experiment's results except for the third one. I was inefficient in terms of finding the right set of hyperparameters of the algorithm for each experiment. Since the writing part of the three blogs and implementations of experiments were almost done. And I already spent a lot of time on these blogs. And I was not sure how much time the last experiment would take which made me feel stuck. So, I didn't gave enough time to the third experiment of BM. And decided to move on to the next key paper and come back to these three blogs later on.


##### Moving on to next paper: RBM 
Next key paper, I began to understand was on Restricted Boltzmann Machine (RBM). After spending some time (towards the end of June, 2025), trying to understand RBM I realized that this approach of trying to understand required maths by understanding the key papers in chronological order is not working. 

- I had already went through long challenging journey of working on these three blogs - HN, BM and Stat Mech.

- While reading RBM paper, I realized reading and understanding papers is not efficient. 
    - It involves understanding the maths 
    - and understanding experiments by running them.
    - maths presented in the paper is not very detailed, you have to spend time figuring it out (just like occurrence of sigmoid function in BM paper was not apparent). 
    - some of the jargons have no corresponding citations because they are obvious for the potential readers but not for me.
    - Researchers like Hinton try different methods and all of them do not get popular by themselve. Some of the methods when combined with future methods, comes to relevance. This is what I meant when I say "unimportant" papers. Such papers are not impactful by themselves, hence not popular and would be unknown to me and hence I would not mention such papers in the chronology. RBM relied on such unimportant papers. So, I had to first understand those papers.
        - There are new experiments. And comparison with other models, while there was no such comparison in BM paper. 
        - There are atleast four unimportant papers which RBM relies on. Each applies RBM to a particular application of Hand written digit classification, face recognition, to time series and RL.
    - 90% of the RBM paper was new to me. It proposes an almost new learning algorithm. Which is opposed to what I was assuming. I thought BM was a gateway which once entered, would allow me to understand rest of the papers in the chronology.
    - full understanding of method presented in the paper comes from running the experiment. Experiments uncover hidden insights of the algorithm. It gives you understanding which would have been hard for you to figure out. By running the experiments for yourself, you learn how to set hyperparams, you learn how to implement algorithm so that it just works because implementing algorithm which works is not straightforward. If the algorithm does not work, then by looking at the result, you should know what's the problem and be able to fix it (e.g., BM stucking in local minima, and solution was noisy update). Paper (atleast older paper like BM) only contain main parts of the algorithm, rest of the part is for you to figure out based on your knowledge. 


<span style="color: grey;">Since, RBM is an upgrade over BM, I thought reading a paper on RBM would be familiar but 90% of the paper was unfamiliar to me. I escaped a one and half decade of research from 1985 to 2001. Many different kind of AI research happened in this period. There was POE, Mnist etc. This paper didn't felt as natural to me as BM. May be because I didn't had any context of the research I missed in 1.5 decade. But RBM only uses the structure of the BM. That is, it makes many of the things of BM irrelevant and adds more new stuff to it.</span>

<span style="color: grey;">Meaning, understanding RBM again would take significant time. And then I have to repeat same thing for other papers. I realized that if i follow a plan of evolution, I would have to understand many papers than I thought. And if I skip papers in between than I wont be having comprehensive, all round understanding of the literature, I will only be having understanding from one perspective which is not enough. With the many faces of the AI literature, I will be only looking at its one face.</span>

<span style="color: grey;">RBM relied on Gibbs sampling or sequential update, POEs and how rbm is a POE (freund et al)</span>

<span style="color: grey;">This approach [understanding chronology] failed because I didn't considered the fact that number of AI researchers per year would grow because of the popularity of successful algorithms like Boltzmann Machine and others. And hence number of AI papers per year would also grow with time. Which means that every next key paper would rely not only on the paper I already understood but also on the other unimportant papers </span>

<span style="color: grey;">RBM was first introduced by Paul Smolensky in 1986. In 1992, Freund and Haussler wrote a paper, giving RBM a different perspective. They proposed that RBM is infact a Product of Experts (PoE) model, which was not apparent. Then in 2002, successful training algorithm called Contrastive Divergence (CD) for RBM was proposed in a paper by Hinton in 2002.</span>

<span style="color: grey;">This approach failed because I thought next key paper would completely depend on the previously understood paper. But it was not like that. Although RBM is an upgrade over BM and hence dependent on BM, still it was not straightforward for me to break RBM paper down and find the relatable maths topic.</span>

While working on RBM, it occurred to me that I am very inefficient in terms of understanding papers (taking long time to properly understand them). So, it would take me hell lot of time to reach to current research through this route.

##### Explosion
I thought there was only one starting point of the evolution, but in fact, it looks like different starting point and each evolving differently and sometimes intersecting in one of the paper in middle. Or may be BM has spawned different research paths.  

Also it is difficult to find most natural successor of a paper. The way I was finding the papers, was to looking at the papers published by Hinton. And reading those papers and then following the references. 
Or other way was by digging the recent papers, so by this approach, RBM was the natural successor. 

different researchers working on different aspect of AI in parallel:
- different learning algorithms for unsupervised learning - helmholtz machine, wake sleep algorithm, POEs, BM, RBM, sparse coding etc
- supervised learning via backpropagation algorithm
- difficulty of training NN, analysing NN
- CNN
- Bayesian Network and PGM
- Kernel Machines
- Representation learning - Distributed representation, 
    - non linear dimensionality reduction
- Minimum description length
- Meta learning
- difficulty of learning long term dependencies and LSTM
- language model
- speech processing


### Finally enough motivation
[Some of the points mentioned here, are already mentioned in the above section "Moving on to next paper: RBM"]

While understanding RBM paper, I decided to master maths first. THESE ARE REASONS OF NOT continuing paper understanding and mastering maths first.

There are multiple reasons:
- Understanding a paper takes time because it not only depends on previous key papers but also on other unimportant papers.
- Implementing experiments in it, is another challenge. Because full algorithm is not mentioned and you have to figure out missing parts. Those missing parts are obvious for most of the potential readers like AI researchers. Missing parts include hyperparameters and some steps of algorithm. E.g., there was no proper description of implementation of noisy clamping in BM paper. 
- And by the time, I was reading RBM paper, list of key papers to understand, grew a lot. [Explosion section above]. That is, chronology of papers got extended as I came across more and more important papers. And each new paper which I was adding in the chronology, has multiple (unknown to me) unimportant papers on which that paper depends on.
- Even after spending a lot of time understanding a paper, there are high chance that I won't have comprehensive understanding. Because there are no clear mentioning of these and these topics of maths, which once mastered, will allow you to comprehensively understand that paper. I will only guess the required maths topics.
- Finding a list of maths topics from a paper is cumbersome because I would have to parse the complex equations (all the maths topics are intermingled in one equation), which takes time. 

It is not easy to understand papers naturally without being good at maths. The top down approach of learning is hard because you have to figure out what maths topics are used by first reading the paper, struggling with the jargons, complex equations, struggling with partial or no proof of the equations, and then reading its citations. **Main problem is that maths topics are not straight forwardly listed in a simple list, you have to mine that list by reading a paper and its citations**. 

But after understanding BM and HN paper, and little bit of RBM paper, now I **very well know that maths is indeed inducing intelligence** which is _more than enough motivation_ for me to first master maths fundamentals. Mastering maths first has several advantages.

Mastering maths then would allow me to **naturally** know _how_ exactly it is inducing intelligence. I have this idea of understanding things from ground up, so that I can understand all the papers efficiently, in and out, without any efforts. I very much realized that once I understand maths, I will have so much leverage to easily understand and implement every paper (bottom up approach). That is, if I read paper after mastering maths, every maths equations will make sense naturally, everything will just click to me. Because I would know the maths blocks or topics (e.g. array, vector, probability density function) very well which builds maths equations. Then, knowing the equation would be like knowing how to bring together already known maths blocks and how they interact to induce intelligence. This is the part, papers explain it well and hence it is easy to understand. Maths of AI algorithms is just the mix of different maths blocks. **If you know maths fundamentals (all maths blocks) then understanding AI algorithms/papers is natural because you would have come up with that mix on your own if you had the same inspiration as the authors of the paper**. So, everything now boils down to inspiration. You know all tools (all the maths blocks), you can use them (or mix them), it is just that you need that inspiration of how to mix them. E.g. neocognitron model (precursor of modern CNN) was inspired from the study of vision system of cats and monkeys. 

With good maths fundamentals, I will be able to imagine the algorithm running, hence it will also be easy to implement and debug. It will help me figure out the missing description of obvious parts of the algorithm or hyperparameters which authors didn't mentioned in detail. I will have the intuition of what hidden insights would be uncovered when actually running the algorithm, differently in different experiments. This intuition will help me debug, if algorithm is not runnning the way I expect it to run. I didn't had such intuition or could not imagine the algorithm running, while reproducing the experiments of HN and BM. 

Topics of maths fundamentals are well pre-structured in a list, so you do not have to mine this list. I now realized that understanding maths from bottom up is easy then understanding it from top down (first breaking down maths equations in papers) because you would be following books or courses as opposed to the series of papers. Introductory books and courses for maths fundamentals assumes that reader are well versed with school level maths only. And then explains maths fundmentals by keeping this assumption in mind. E.g., if you are reading an introductory book on Linear Algebra, then this book is nothing but an ordered list of topics which _naturally extends_ the school level maths. **Going through this list is like going over a gentle ramp which connects school level maths knowledge to a level of maths fundamentals mastery**. If you understand LA topics in the order, right from the beginning, then for every topic (including the first one), you will have the required prerequisite to understand it. Which is unlike understanding papers in chronology because a given paper will almost always depends on some unimportant previous papers which you had not mentioned in the list and hence unknown to you. This is a recursive problem, i.e., that unknown paper will further depend on other unknown papers. Hence, paper reading feels so unnatural because there are so many unknown (to me) papers, a given paper depends on and it is time consuming task to read all of them.


<span style="color: grey;">Ever after giving this much time, I didn't had comprehensive understanding of HN and BM. There were some insights of both these papers which was not straight forward for me. E.g., I could not visualize the high dimensional energy surface the way Hinton mentioned, he could understand that high dimensional loss surface has highly degenerate energy barriers or loss surface is in the form of ravine which helped him determine the step size for each weight. In HN, it was not straight forward for me to understand difference between binary and bipolar HN. How that factor of 0.15 occurs in HN. There were many things in HN which was not straightforward for me to understand and I would have to spend much more time to understand it properly.</span>

<span style="color: grey;">There is so much thing to understand from one paper and you want to understand everything, which makes you feel that you are stuck at one paper. It is a bad feeling.</span>

<span style="color: grey;">No proper understanding of loss surface in a simplest possible case of bm. It was good opportunity. Same for mcmc. Even after spending this much time, I didn't understood this. Because I didn't studied required maths topics. It was not apparent which maths topics to understand. I could figure out the maths topics from the equation but to understand the whole equation you may require other maths topic for its analysis. And authors would not mention that, because they are expecting that readers is well versed with the maths.</span>

<span style="color: grey;"></span>
<span style="color: grey;">I could have gone through every single paper in a "detailed" (including key and non-key paper, non-key papers are those which are not successful in themselves but successful paper depends on them.) chronological list of papers. But there would be uncertainty of when everything will just click (or when maths fundamentals and skills of implementing and reproducing papers will become strong) and paper understanding will be easy for me. This would be uncertain and also a grueling task. This gave me motivation to master maths fundamentals. Because once I master it, understanding and implementing "every" paper will be easy.</span>


<span style="color: grey;">Understanding BM, and little bit of RBM realised me that learning maths is indeed superuseful. Because I would have comprehensive understanding of MCMC, rather than only knowing it from different aspects (for BM and RBM). If learning maths from papers, then there is a tendency of learning enough maths so that you can understand that paper, but not comprehensive understanding of maths.</span>

 
### Blogging 
Another important source of motivation to study maths is blogging. I already used blogging to help me properly understand BM, HN and stat mech. After writing blogs on them, now I know for sure that _**quality** blogging does help you comprehensively understand a topic_. And I strongly want to create quality blogs because it would be great feeling for me, if someone who is a beginner could gain comprehensive understanding of topics by reading my blogs.

But that is one advantage. There is another equally important advantage. When you learn maths properly, it feels like an interminable task and not worthful in itself. Interminable because although there are finite number of topics in maths fundamentals. But number of topics are large and each takes significant amount of time when you learn it properly. So, it feels like never ending story. And to make it even worse, learning maths does not feel worthful, especially in the initial weeks. Because you are just simply reading and writing equations after equations. You have to wait for your service of solving real problems by AI research until you master the maths fundamentals. But _learning by blogging allows you to provide your service from today onwards and makes you feel worthful right away_. By creating quality blogs, it not only helps you master a topic. But it allows you to contribute your part in solving a social problem of education, by sharing your comprehensive understanding to the whole world for free (no distraction by ads, no paywall of any kind). If a human do not get benefitted by the blogs, AI would definitely get benefitted by using the blogs as high quality training data. So, you are doing service all the time. You are doing service now when you are learning and you will be doing service after learning maths by doing AI research.

It is a **win-win situation** of learning the maths properly and doing service of education, both at the same time. Getting to know about blogging is a blessing. 

### Finding maths resources
To start learning maths, I looked up for the potential resources and found some of the books just perfect. 

The books which I found most perfect are actually two book series by Sir Kevin Murphy. I have written a separate [blog]({%post_url 2025-10-22-ML-books-by-KevinMurphy %}){:target="_blank"} describing why these books are perfect. In brief, this book series is perfect because it comprehensively covers mathematics in total 630 pages, which is like a maths book within another book. _All the maths is just for ML, so there is no doubt whether any topic of maths is worth reading or not_. Once you _properly understand these 630 pages of mathematics, you will be able to easily understand almost all the AI literature_. And you do not have to jump from paper to paper, almost all of AI literature is covered in rest of the pages of these books.  

Second book is "Mathematics for Machine Learning" (MML) by Faisal, Ong, and Deisenroth {% cite deisenroth2020mathematics %}. As the name suggest, it covers maths for ML. I have not read it but it covers linear algebra in detail and this book is quite popular.


### Started Learning Maths Properly
In months of July and August this year, I read the Murphy's book1 upto chapter 6. Chapter 2 to 6 covered the topics from probability, statistics, decision theory, and information theory (chapter 1 briefly explains ML). I have now much better understanding of these topics than I ever had. Chapter 7 is on linear algebra. Previously, I tried to study linear algebra multiple times, more than other subjects of maths fundamentals. So, instead of just reading chapter 7, I decided that now is the time to leverage the power of blogging (as mentioned above) to _comprehensively understand linear algebra and other subjects of maths fundamentals_. 

Plan is to write a detailed blog (with code) on every topic of maths fundamentals. I will be writing maths blogs by assuming school level maths as a prerequisite to properly understand a blog. **By blogging, I want to increase my (and reader's) school level understanding of mathematics to a level where we all have mastered maths fundamentals and become suitable for AI research**. 

But before writing such maths blogs, I thought of writing these blogs:
- A two part blog on what I have done till now, to prepare for AI research. 
    - Part 1 - [Statistical Mechanics, Hopfield Network and Boltzmann Machine]({%post_url 2025-10-21-statMech-hn-bm %}){:target="_blank"}
    - Part 2 is this blog - "Setting The Tone".
- A blog (which I have linked in the prerequisite section) to motivate me and others to first master maths in order to become AI researcher.
- A blog about how Murphy's books are perfect (link in previous section).

And some other blogs, which I think, I may post before writing maths blogs:
- A blog about how now I look at machine learning. In one line, I look it as maths equations running on data to extract intelligence out of it in term of parameters (training). And then using these intelligence to achieve goals (inference). This blog will talk about ML in a very unique and general (covering all types of ML algorithms) way, showing how tools from "maths fundamentals" are used on "data" for training and inference. 



