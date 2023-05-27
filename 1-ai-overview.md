# AI Overview

## Foreword
Mankind is welcoming the fourth industrial revolution represented by intelligent technology. New technologies such as AI, IoT, 5G and bioengineering are integrated into all aspects of human society; driving changes in global macro trends, such as sustainable social development and economic growth. New kinetic energy, smart city upgrading, industrial digital transformation, consumer experience, etc.

As the world‘s leading provider of ICT (information and communications) infrastructure and smart terminals, Huawei actively participates in the transformation of artificial intelligence and proposes Huawei’s full-stack full-scenario AI strategy. This chapter will mainly introduce AI Overview, Technical Fields and Application Fields of AI, Huawei's AI Development Strategy, AI Disputes, Future Prospects of AI.

## Objectives
Upon completion of this course, you will be able to:
- Understand basic concepts of AI.
- Understand AI technologies and their development history.
- Understand the application technologies and application fields of AI.
- Know Huawei's AI development strategy.
- Know the development trends of AI.

## Contents
1. [AI Overview](#first)
2. [Technical Fields and Application Fields of AI](#second)
3. [Huawei's AI Development Strategy](#third)
4. [AI Disputes](#fourth)
5. [Future Prospects of AI](#fifth)

### AI Overview <a name="first"></a>

#### AI in the Eyes of the Society
- People get to know AI through news, movies, and actual applications in daily life. What is AI in the eyes of the public?
  > (2021) There is a study of 1018 samples of educated people with access to the internet in Taiwan regarding their perceptions of AI and its connections to the Sustainable Development Goals (SDGs). The respondents showed high conﬁdence in their AI knowledge. They had a very positive attitude toward AI but at the same time thought AI was risky. In general, people in Taiwan could be "rational optimists" regarding AI. The study also provides examination result of how people think of the linkages between AI and the SDGs, and found that SDG 4, SDG 9, and SDG 3 had the highest "synergy" and lowest rates of "trade-off". According to the data analysis, education played as the base to construct a sustainable AI-aided town with an embedded innovative circular economy and high-quality water and energy services, making the residents live healthier lives. The ﬁndings of this study can be referred to when the perceptions of AI and sustainability issues are of interest for an emerging high-tech economy such as Taiwan and other Asian countries. [Public Perception of Artiﬁcial Intelligence and Its Connections to the Sustainable Development Goals](https://doi.org/10.3390/su13169165)
  
  > (2022) There is a study that conducts an online public perception survey with the residents of Sydney, Melbourne, and Brisbane, and explores the collected survey data through statistical analysis. The analysis reveals that: (a) the public is concerned of AI invading their privacy, but not much concerned of AI becoming more intelligent than humans; (b) the public trusts AI in their lifestyle, but the trust is lower for companies and government deploying AI; (c) the public appreciates the benefits of AI in urban services and disaster management; (d) depending on the local context, public perceptions vary; and (e) the drivers behind the public perception include gender, age, AI knowledge, and AI experience. The findings inform authorities in developing policies to minimise public concerns and maximise AI awareness. [Drivers Behind the Public Perception of Artificial Intelligence: Insights from Major Australian Cities](https://doi.org/10.1007/s00146-022-01566-0)

#### AI in the Eyes of Researchers
- _"I propose to consider the question, 'Can machines think?'"_ — Alan Turing in 1950 (An English mathematician, computer scientist, logician, cryptanalyst, philosopher, and theoretical biologist.)
- _"The branch of computer science concerned with making computers behave like humans."_ — John McCarthy in 1956 (An American computer scientist and cognitive scientist. He was one of the founders of the discipline of artificial intelligence.)
- _"The science of making machines do things that would require intelligence if done by men."_ — Marvin Minsky in 1968 (An American cognitive and computer scientist concerned largely with research of artificial intelligence, co-founder of the Massachusetts Institute of Technology's AI laboratory, and author of several texts concerning AI and philosophy.)

#### What are Intelligences?
- Howard Gardner defines intelligence as a _"biopsychological potential to process information that can be activated in a cultural setting to solve problems or create products that are of value in a culture"_ (Gardner, H. E. (2000). Intelligence reframed: Multiple intelligences for the 21st century. Hachette UK., p.28).
- Howard Gardner's theory of multiple intelligences proposes that people are not born with all of the intelligence they will ever have. 
- Human intelligences can be divided into seven categories:
  - Verbal/Linguistic \
    Deals with sensitivity to the spoken and written language, ability to learn languages, and capacity to use language to accomplish certain goals.
  - Logical/Mathematical \
    Refers to the capacity to analyze problems logically, carry out mathematical operations, and investigate issues scientifically.
  - Visual/Spatial \
    The potential to recognize and manipulate the patterns of wide space (those used, for instance, by navigators and pilots) as well as the patterns of more confined areas, such as those of importance to sculptors, surgeons, chess players, graphic artists, or architects.
  - Bodily/Kinesthetic \
    The potential of using one's whole body or parts of the body (like the hand or the mouth) to solve problems or to fashion products.
  - Musical/Rhythmic \
    Refers to the skill in the performance, composition, and appreciation of musical patterns.
  - Inter-personal/Social \
    To understand the intentions, motivations, and desires of other people and consequently to work effectively with others. 
  - Intra-personal/Introspective \
    To understand oneself, to have an effective working model of oneself-including own’s desires, fears, and capacities—and to use such information effectively in regulating one’s own life.

#### What is AI?
- Artificial Intelligence (AI) is a new technical science that studies and develops theories, methods, techniques, and application systems for simulating and extending human intelligence.
- In 1956, the concept of AI was first proposed by John McCarthy, who defined the subject as _"science and engineering of making intelligent machines, especially intelligent computer program"_.
- AI is concerned with making machines work in an intelligent way, similar to the way that the human mind works. At present, AI has become an interdisciplinary course that involves various fields.

![What is AI?](https://forum.huawei.com/enterprise/en/data/attachment/forum/202101/28/143621kbprxjh19rlj8ez6.png?%E6%88%AA%E5%9B%BE.PNG)

#### Relationship of AI, Machine Learning and Deep Learning
- AI: A new technical science that focuses on the research and development of theories, methods, techniques, and application systems for simulating and extending human intelligence.
- Machine learning: A core research field of AI. It focuses on the study of how computers can obtain new knowledge or skills by simulating or performing learning behavior of human beings, and reorganize existing knowledge architecture to improve its performance. It is one of the core research fields of AI.
- Deep learning: A new field of machine learning. The concept of deep learning originates from the research on artificial neural networks. The multi-layer perceptron (MLP) is a type a deep learning architecture. Deep learning aims to simulate the human brain to interpret data such as images, sounds, and texts.

#### Three Major Schools of Thought
##### 1. Symbolism
- Basic thoughts
  - The cognitive process of human beings is the process of inference and operation of various symbols.
  - A human being is a physical symbol system, and so is a computer. Computers, therefore, can be used to simulate intelligent behavior of human beings.
  - The core of AI lies in knowledge representation, knowledge inference, and knowledge application. Knowledge and concepts can be represented with symbols.
  - Cognition is the process of symbol processing while inference refers to the process of solving problems by using heuristic knowledge and search.
- Representative of symbolism: inference, including symbolic inference and machine inference

##### 2. Connectionism
- Basic thoughts
  - The basis of thinking is neurons rather than the process of symbol processing.
  - Human brains vary from computers. A computer working mode based on connectionism is proposed to replace the computer working mode based on symbolic operation.
- Representative of connectionism: neural networks and deep learning

![Apple in The Eyes of Connectionism](https://github.com/exemuel/hcia-ai-training/blob/main/images/apple-in-the-eyes-of-connectionism.png)

##### 3. Behaviorism
- Basic thoughts:
- Intelligence depends on perception and action. The perception-action mode of intelligent behavior is proposed.
- Intelligence requires no knowledge, representation, or inference. AI can evolve like human intelligence. Intelligent behavior can only be demonstrated in the real world through the constant interaction with the surrounding environment.
- Representative of behaviorism: behavior control, adaptation, and evolutionary computing

### Brief Development History of AI
![Brief Development History of AI](https://github.com/exemuel/hcia-ai-training/blob/main/images/brief-development-history-of-ai.png)

### Overview of AI Technologies
- AI technologies are multi-layered, covering the application, algorithm mechanism, toolchain, device, chip, process, and material layers.

![Overview of AI Technologies](https://github.com/exemuel/hcia-ai-training/blob/main/images/ai-related-technology-overview.PNG)


### Types of AI
- Strong AI
  - The strong AI view holds that it is possible to create intelligent machines that can really reason and solve problems.
  - Such machines are considered to be conscious and self-aware, can independently think about problems and work out optimal solutions to problems, have their own system of values and world views, and have all the same instincts as living things, such as survival and security needs.
  - It can be regarded as a new civilization in a certain sense.
- Weak AI
  - The weak AI view holds that intelligent machines cannot really reason and solve problems.
  - These machines only look intelligent, but do not have real intelligence or self-awareness.

### Classification of Intelligent Robots
- Currently, there is no unified definition of AI research. Intelligent robots are generally classified into the following four types:
  - **"Thinking like human beings"**: weak AI, such as Watson and AlphaGo
  - **"Acting like human beings"**: weak AI, such as humanoid robot, iRobot, and Atlas of Boston Dynamics
  - **"Thinking rationally"**: strong AI (Currently, no intelligent robots of this type have been created due to the bottleneck in brain science.)
  - **"Acting rationally"**: strong AI

### AI Industry Ecosystem
- The four elements of AI are data, algorithm, computing power, and scenario.
- To meet requirements of these four elements, we need to combine AI with cloud computing, big data, and IoT to build an intelligent society.

![AI Industry Ecosystem](https://github.com/exemuel/hcia-ai-training/blob/main/images/ai-industry-ecosystem.PNG)

### Sub-fields of AI
![Sub-fields of AI]([https://github.com/exemuel/hcia-ai-training/blob/main/images/ai-industry-ecosystem.PNG](https://github.com/exemuel/hcia-ai-training/blob/main/images/subfields-involved-in-ai.PNG))

### Technical Fields and Application Fields of AI <a name="second"></a>
a

### Huawei's AI Development Strategy <a name="third"></a>
a

### AI Disputes <a name="fourth"></a>
a

### Future Prospects of AI <a name="fifth"></a>
a

