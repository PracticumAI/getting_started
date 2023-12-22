---
title: "What is AI?"
image: 'https://github.com/PracticumAI/practicumai.github.io/blob/main/images/icons/practicumai_beginner.png?raw=true'
image-width: 80px
image-height: 80px
layout: page_no_title
---

![What is AI Banner](/images/what_is_ai_header.png)

## Topics

* [Defining AI](#defining-ai)
* [AI, Machine Learning, Deep Learning, and Computer Science](#ai-machine-learning-deep-learning-and-computer-science)
* [An Abridged History of AI](#an-abridged-history-of-ai)
* [High Performance Computing and You](#high-performance-computing-and-you)
* [It's Not All Ray Tracing and Upscaling](#its-not-all-ray-tracing-and-upscaling)
* [The Python Supremacy](#the-python-supremacy)

## Objectives

By the end of this module, students will be able to:

* Define AI and explain what it is.
* Distinguish between AI and other related fields, such as machine learning and computer science.
* Recognize the major events in the history of AI development. 
* Describe the benefits of using a high-performance computing environment to develop AI applications.
* Identify the challenges of developing AI applications in a high-performance computing environment.
* Recognize that Python is the predominant programming language in AI application development.

## Topic Details

### Watch



[![Thumbnail screenshot of a Practicum AI video](/images/video_thumbnail.png)](https://mediasite.video.ufl.edu/Mediasite/Play/e8eb0be8bdde4418aee51a583b3344f01d) [Video: What is AI?](https://mediasite.video.ufl.edu/Mediasite/Play/e8eb0be8bdde4418aee51a583b3344f01d)

### Defining AI

<img src='/images/question_marks.png' alt='Three question marks in an arc' width=150 align='right'> By now, you’ve almost definitely heard someone ask, “What is AI?”. Answering that question is very difficult for at least a couple of reasons: 

1. To truly define “Artificial” Intelligence, we would have to have a good, thorough working definition of normal intelligence. We, uh, don’t currently (but a lot of smart people are working on this right now!) [1]
1. The scope of what we consider AI has changed considerably over time. From the pioneering days of the 1950’s and Alan Turing’s work on thinking computers to the intense marketing hype of today’s ChatGPT, our expectations of what a “thinking” computer looks like continue to evolve.

Because of this, definitions tend to be vague and/or recursive (“Intelligence demonstrated by a machine as opposed to a human or other animal” [2]). Russell & Norvig’s description of AI from their 2003 textbook, *Artificial Intelligence: A Modern Approach*, is:

> “the study of ‘rational agents’: any system that perceives its environment and takes actions that maximizes its ability to achieve its goals.”

Another way to look at this is if a computer is using information to make the kinds of inferences or decisions a human would make, that computer is probably using an application of AI. Another *other* way to look at it is… fancy math. AI applications are typically algorithms that use much more data than a person can comfortably compute by hand (during this course and other *Practicum AI* courses, you’ll see what we mean by a lot of data).
 
#### References

[1] Sternberg, Robert J. "human intelligence". Encyclopedia Britannica, 11 Apr. 2022, Britannica.comLinks to an external site.. Accessed 19 May 2023.

[2] Hauser, Larry. "Artificial Intelligence." Internet Encyclopedia of Philosophy, Internet Encyclopedia of PhilosophyLinks to an external site., Accessed 19 May 2023.

[Back to the topic list](#topics)

### AI, Machine Learning, Deep Learning, and Computer Science

 <center><figure style="width: 500px; max-width: 100%;"><img src='/images/ai_ma_dl_cs.png'  alt="Relationship of Artificial Intelligence, Machine Learning, and Deep Learning">
            <figcaption style="text-align: center;">Relationship of Artificial Intelligence, Machine Learning, and Deep Learning. [1]</figcaption>
        </figure></center>

There is another barrier to defining AI: the term is often used interchangeably with other disciplines. Commonly, AI will be confused with its subdisciplines, Machine Learning and Deep Learning. Here’s a quick and dirty comparison of AI, Machine Learning, Deep Learning, and their parent field, Computer Science: 

Term | Summary | Examples
-----|---------|---------
Artificial intelligence (AI) | The ability of a computer or machine to learn and perform tasks that are typically associated with human intelligence, such as reasoning, learning, and problem-solving. | Self-driving cars, virtual assistants, and spam filters. 
Machine learning (ML)| A type of AI that allows computers to learn without being explicitly programmed. ML algorithms are trained on data and can then use that data to make predictions or decisions.| Netflix's recommendation engine, spam filters, and fraud detection systems. 
Deep learning (DL) | A subset of ML that uses artificial neural networks to learn from data. Neural networks are inspired by the human brain, and they can learn to recognize patterns in data that would be difficult for humans to identify. | Image recognition, speech recognition, and natural language processing. 
Computer science (CS) | The study of computing. CS encompasses a wide range of topics, including algorithms, data structures, programming languages, and artificial intelligence. | Software engineering, web development, and cybersecurity.

As you can see, AI is a broad term encompassing a wide range of methods and techniques. Machine learning and deep learning are two specific types of AI used to create systems that can learn and make predictions from data. Computer science is the field of study that encompasses all these disciplines. 

#### References

[1] [What’s the Difference Between Artificial Intelligence, Machine Learning and Deep Learning?](https://blogs.nvidia.com/blog/2016/07/29/whats-difference-artificial-intelligence-machine-learning-deep-learning-ai/)

[Back to the topic list](#topics)

### An Abridged History of AI

The history of AI spans nearly 80 years and involves countless technological innovations brought about by thousands of scientists and engineers. This entire module is only supposed to last about an hour, so we will stick to the highlights.

In the Beginning (1955), the first "artificial intelligence" conference was held at Dartmouth College.  It was attended by many of the leading computer science researchers of the day, including John McCarthy, Marvin Minsky, Nathaniel Rochester, and Claude Shannon.



<center>
<figure style="width: 500px; max-width: 100%;">
    <img id="79167104" src="/images/Proposal-that-coined-AI.png" alt="The first page of McCarthy's proposal called &quot;Dartmouth Summer Research Project on Artificial Intelligence&quot;" width="500" height="322">
    <figcaption style="text-align: center;">The 1st page of McCarthy's proposal called <i>"Dartmouth Summer Research Project on Artificial Intelligence"</i></figcaption>  
</figure><br>
</center>
 
1. McCarthy coined the phrase "artificial intelligence" when he wrote the funding proposal for the Rockefeller Foundation. This is where modern AI began.​
2. McCarthy also provided a short definition. "The study is to proceed on the basis of the conjecture that every aspect of learning or any other feature of intelligence can, in principle, be so precisely described that a machine can be made to simulate it."​

   > “The study is to proceed on the basis of the conjecture that every aspect of learning or any other feature of intelligence can, in principle, be so precisely described that a machine can be made to simulate it.”​

In early 1955, John McCarthy accepted a position as an Assistant Professor of Mathematics at Dartmouth College.  Soon after, he organized a group to discuss the future of thinking machines.  In September, he, Marvin Minsky, Nathaniel Rochester, and Claude Shannon submitted a proposal to the Rockefeller Foundation, requesting funds to host the *Dartmouth Summer Research Project on Artificial Intelligence*. Fortunately, the foundation funded the proposal.  Today, this conference is credited with introducing the term' artificial intelligence' to the world.​

<center><figure style="width: 300px; max-width: 100%; ">
    <img id="79715089" src="/images/Alan_Turing_Aged_16.jpg" alt="Alan Turing at age 16" width="288" height="392">
    <figcaption class="" style="text-align: center;">Alan Turing, at age 16</figcaption>
</figure><br></center>

Any historical survey of AI would be complete with Alan Turing.  Turing is a towering figure in AI.  He was a mathematical genius who thought a lot about the question of intelligence.  Turing first proposed a test of intelligence in 1950 in an article entitled, Computing Machinery and Intelligence. This has become a foundational document in the field.​

The Turing Test (designed, of course, by Turing) of intelligence has been hugely influential since it was first described in 1950.  

1. Turing got the idea from a Victorian parlor game where a man and a woman sat in a separate room.  The other players then passed a series of written questions to them and would try to guess the respondent's gender by the answers they gave.​
1. The Turing Test is a computer version of that game.  In the following image, we see a Human questioner in the middle, sending questions to a computer and another human.  The interaction is purely in the form of text and answers: the human questioner types a question, and a response is displayed.  Now, that person's task is to determine whether the thing being interrogated is a person or a computer program.
1. Now, suppose that the thing being interrogated is indeed a computer program.  But after some reasonable amount of time, the questioners cannot tell whether they are interacting with a program or a person.  Then surely, Turing argued, you should accept that the program has some sort of human-level intelligence because the system is doing something that makes it **indistinguishable** from the real thing.  The key word here is indistinguishable…​

![A schematic of the Turing test](/images/Turing_test.png)

Then, in 1958, Frank Rosenblatt created the first perceptron. Perceptrons, also known as McCullogh-Pitts neurons after the researchers that theorized them, are algorithms for supervised learning of binary classifiers, making them the first implementation of what we'd come to call 'Machine Learning.' We'll review perceptrons, supervised learning, and binary classifiers later in Module 2 of this course.

In the 1960's, in response to Turing's article, Joseph Weizenbaum – a computer scientist at MIT – created one of the first conversational AI programs.  ELIZA mimics a psychiatrist or psychologist having a conversation with a patient.  Strangely, Weizenbaum discovered that many preferred talking with ELIZA rather than a real human being.​

ELIZA's legacy lives on to this day.  In 1990, Hugh Loebner created the Loebner Prize.  Each year, the Loebner Prize invited (the last contest appears to have been in 2019) the submission of computer programs to engage in the Turing test, attempting to convince a panel of judges that they are, in fact, people. Steve Worswick won the prize five years in a row with his AI bot, Kuki AI.

Deep Blue was a chess-playing computer developed by IBM. It was first announced in 1996 and designed to defeat world chess champion Garry Kasparov. Deep Blue used a combination of brute force and expert knowledge to play chess. It could search through millions of possible moves in a fraction of a second, and it could also draw on the expertise of human chess grandmasters. In 1997, Deep Blue defeated Kasparov in a six-game match. The match was closely contested, but Deep Blue ultimately won by a score of 3.5 to 2.5. Deep Blue's victory was a breakthrough for AI, and it showed that computers could now compete with humans at the highest levels of chess.

<center><figure style="width: 300px; max-width: 100%;">
    <img id="79711634" src="/images/IBM_Deep_Blue_at_Computer_History_Museum_(9361685537).jpg" alt="IBM Deep Blue computer photo from the Computer History Museum" width="298" height="447">
    <figcaption>IBM Deep Blue computer photo from the Computer History Museum</figcaption>
</figure><br></center>

Watson is a question-answering computer also developed by IBM. It was designed to compete on the *Jeopardy!* quiz show. Watson used a combination of natural language processing and machine learning to answer questions. It could 'understand' the meaning of questions and search through vast amounts of data to find the correct answers. In 2011, Watson won the *Jeopardy!* quiz show against two of the show's most experienced champions. Watson's victory showed both the power and potential of AI and natural language processing.

In 2012, a Google Brain computer cluster used deep learning techniques to teach itself to recognize cats. The team that created it had expected the system to need more training data, but it learned to recognize cats with just a few million images. They believe that this is because the system could generalize from the data. In other words, it could learn the features common to all cats, even if the images it was trained on were not all the same cat. While it did make some interesting errors, such as misidentifying a toaster and a shoe as a cat, it was accurate over 90% of the time.

In a stunning upset in 2014, Eugene Goostman, a chatbot developed by Ukrainian programmers, passed the Turing Test. Despite claiming to be a 13-year-old Ukrainian schoolboy from Crimea, saying that it had a girlfriend named Linda, and asking the judges if they could help it with its homework, Goostman was able to fool 33% of the judges into thinking it was a human (the minimum required to pass the Turing Test). Goostman's success was an incredible milestone for AI, so much so that new, stricter rules for the Turing Test were drafted the following year.

AlphaGo is a Go-playing computer developed by Google. It was designed to defeat world Go champion Lee Sedol. Go is a complex board game that is one of the most challenging games for computers to play, given the ridiculous number of possible moves in a game (estimates put the number of possible moves around 10<sup>360</sup>). AlphaGo uses a combination of deep learning and other AI techniques to play Go. It could learn from its mistakes and explore millions of possible moves in a fraction of a second. AlphaGo defeated Lee Sedol in a five-game match. The match was closely contested, but AlphaGo ultimately won by a score of 4 to 1. AlphaGo showed that a program could solve problems that we had believed were too complicated for computers.

Finally, we have the star of the day, ChatGPT. ChatGPT (which stands for Chat Generative Pre-trained Transformer) was released as version 3.5 in November 2022. It is a language model that can create (or generate) conversational language as a response to language inputs. The language model used for ChatGPT was not explicitly taught the rules of the English language but instead picked up grammar simply by looking at many examples of complete sentences (about 1 petabyte worth).

#### Exercise

* Circling back to the study of intelligence (artificial or otherwise), we will give you time to chat with a bot. While there are many AI chatbots, most require an account and possibly a paid subscription. One exception, hosted by a popular repository of AI models and datasets, Hugging Face, is their HuggingChat.

* Go to the [HuggingChat website](https://huggingface.co/chat/) and talk with the bot. (You can use the Try as Guest option if you don't want to register)

* Well, what do you think? Is HuggingChat exhibiting intelligent behavior? Is this intelligence?

#### Optional Exercise

Now let’s try ChatGPT, the newest (as of May 2023) thing in AI agents. 

* Go to the [ChatGTP website](https://chat.openai.com/auth/login), create an account, and ask ChatGPT some questions.
* Is ChatGPT exhibiting intelligent behavior?
* Is this intelligence?

#### References

McCarthy, John; Minsky, Marvin L.; Rochester, Nathaniel; Shannon, Claude E. 2006. A proposal for the Dartmouth summer research project on artificial intelligenceLinks to an external site.. AI magazine, Vol 27 (4), p.12-14.

St. George, Benjamin & Gillis, Alexander S. What is the Turing Test?Links to an external site. Tech Accelerator "A guide to artificial intelligence in the enterprise", Tech Target.

Tate, Karl. 2014. History of Artificial Intelligence Timeline (Infographic)Links to an external site., Live Science.

[Back to the topic list](#topics)

### High Performance Computing and You

You have probably noticed at this point that the ideas behind artificial intelligence have been around for a long time. So why has it taken us so long to implement them? For the most part, the answer is computing power. Artificial intelligence can now do things once thought impossible, like beating humans at chess and Go, and driving cars without any human input. Realize, however, that AIs are only as smart as they are because of high-performance computing (HPC) environments.

HPC systems are typically large supercomputers that can quickly crunch massive amounts of data. This is essential for AI because AI algorithms need to be trained on huge datasets to learn how to make predictions. Without HPC, AI would take years to train, and it would never be able to learn as much as it can with HPC.

What is a “supercomputer”? A supercomputer is multiple computers networked (or clustered, as IT nerds like to say) together. The number of computers in a cluster can be anywhere from two to thousands. Special software and networking equipment allow the machines to work as one large computer.

We need a way to measure computer “speed” to give some perspective. This is usually measured in FLOPS (Floating Point Operations Per Second). Without getting into the weeds, this measures how fast a computer can do mathematical calculations. A modern desktop computer (with a graphics card) can process 6.1*10<sup>12</sup> FLOPS (6.1 trillion floating point operations per second), though this varies widely (and gets higher all the time!).

Year | Computer	| Speed in FLOPs
-----|----------|---------------
1997 | IBM's Deep Blue | 11.38*10<sup>9</sup> FLOPs (~11 GigaFLOPS)
2016 | Google's AlphaGo | 180*10<sup>12</sup> FLOPs  (180 TeraFLOPS)
2021 | UF's HiPerGator | 13.75*10<sup>15</sup> FLOPs  (13 PetaFLOPS)
2022 | The computer that trained ChatGPT 3.5 | 100.7*10<sup>15</sup> FLOPs (100 PetaFLOPS)
2023 | World's fastest computer in May 2023 | 2*10<sup>18</sup> FLOPs (2 ExaFLOPS)

As you can see, supercomputers are getting pretty FLOPpy—we are now in As you can see, supercomputers are getting pretty FLOPpy—we are now in what is known as the era of ExaScale computing. The main reason is the advent of GPUs (graphic processing units). CPUs are designed for general-purpose computing tasks. They excel at tasks requiring high single-threaded performance and are designed to handle a wide range of applications, from operating systems to complex software. Conversely, GPUs have a massively parallel architecture with hundreds or even thousands of smaller cores. These cores are optimized for simultaneous execution of multiple tasks, making GPUs ideal for parallel processing. Initially developed for rendering graphics, GPUs have evolved into highly efficient processors for handling repetitive, data-parallel computations common in graphics rendering, scientific simulations, and machine learning.

Here are some case studies showing the benefits of HPC:

* [17 High-Performance Computing Applications and Examples](https://builtin.com/hardware/high-performance-computing-applications).

The [top500 list](https://www.top500.org/) tracks the top 500 (publicly announced) supercomputers twice a year.

[Back to the topic list](#topics)

### It's Not All Ray Tracing and Upscaling

While supercomputers offer significant computational power and performance advantages, they also come with a few downsides. Here are some potential drawbacks associated with using supercomputers:

1. **Cost:** Supercomputers are expensive to develop, build, and maintain. They require substantial investments in hardware, software, cooling systems, power infrastructure, and skilled personnel. The initial procurement costs, as well as ongoing operational expenses, can be prohibitive for many organizations.
1. **Power Consumption:** Supercomputers consume a tremendous amount of electricity. This high power consumption translates into substantial energy costs and environmental impact. Cooling the systems can also be challenging, as supercomputers generate a significant amount of heat that must be efficiently dissipated.
1. **Complexity:** Supercomputers are complex machines that require specialized expertise to operate and program effectively. Developing software and algorithms that can fully utilize supercomputers' massive parallel processing capabilities is challenging. The complexity can result in longer development cycles and increased debugging efforts.
1. **Limited Accessibility:** Due to their high cost and complexity, access to supercomputers is limited to a relatively small number of organizations or research institutions with the necessary resources and expertise. This limitation can hinder broader participation and collaboration in research or other computationally demanding endeavors.

[Back to the topic list](#topics)

### The Python Supremacy

<img alt='The Python Logo' src='/images/Python-logo.svg' align='right'> The last piece of the AI puzzle is the Python programming language. Python has become the predominant programming language in the field of artificial intelligence (AI) for several reasons: 

1. **Simplicity and Readability:** Python is known for its simplicity and readability. Its clean syntax and straightforward structure make writing and understanding code more accessible for developers. This characteristic makes Python an ideal language for prototyping and experimenting with AI algorithms and models.
1. **Large and Active Community:** Python has a vast and active community of developers. This community has contributed to developing numerous libraries, frameworks, and tools specifically tailored for AI and machine learning (ML) tasks. Popular libraries like TensorFlow, PyTorch, and scikit-learn have extensive Python support, making implementing AI algorithms and models easier.
1. **Integration and Interoperability:** Python offers excellent integration capabilities, allowing developers to combine AI with other technologies and systems seamlessly. Python can easily interact with other popular programming languages like C/C++, Java, and R, making incorporating AI functionality into existing software systems convenient.
1. **Data Analysis and Data Science:** Python is widely used in the field of data analysis and data science. It offers powerful tools and libraries for data manipulation, exploration, and preprocessing. This aligns well with AI, as AI relies on large datasets and requires those same tools for working with data. Python's popularity in data science has contributed to its dominance in the AI landscape.
1. **Education and Learning Resources:** Python is often the programming language of choice for introductory AI and ML courses. Its simplicity and readability make it accessible to beginners, allowing them to grasp fundamental AI concepts quickly. The abundance of learning resources, tutorials, and documentation available for Python facilitates the learning process for aspiring AI developers.
1. **Industry Adoption:** Python's popularity in AI is also driven by its widespread adoption in the industry. That’s right; Python is popular partly because… it's popular. Many organizations and companies have embraced Python as their primary language for AI development. This adoption has led to a virtuous cycle, with more resources, tools, and talent invested in Python-based AI research and development.

While Python's dominance in AI is significant, it's worth noting that other programming languages like R, Java, and C++ are also used in AI applications. That said, Python's simplicity, extensive libraries, and strong community support have made it the go-to language for AI development.

[Back to the topic list](#topics)

## Practice and Apply

Once you have reviewed each of the topics in this module, check your learning by completing this self-check quiz:

Module 1 Quiz **Quizzes are only available within Canvas courses**

***

[Back to course home](/getting_started/README) or on to [Module 2: Understanding AI Models](/getting_started/02_understanding_ai_models) 