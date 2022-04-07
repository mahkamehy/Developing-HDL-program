# Developing-HDL-program
Studying the Challenges of Developing Hardware Description Language Programs
# Objectives
Modern computer systems typically consist of two indispensable components: general-purpose 
hardware (e.g., CPU) and highly-versatile software (e.g., web applications). In this context, 
turing award winners John Hennessy and David Patterson, in their recent turing lecture, 
declared that computer architectures are at the point of shifting from a general-purpose 
approach to a hardware/software co-design approach. This work makes an initial attempt to 
understand the challenges of developing HDL programs and explore opportunities for the 
Software Engineering community to support the practices of HDL program development. 
Developers usually ask and answer technical questions on technical forums such as Stack 
Exchange forums.These questions may communicate challenges faced by developers when 
developing HDL programs. Therefore, this research identifies and analyzes over 16, 000
HDL-related questions from two Stack Exchange forums: Stack Overflow (SO) and Electrical 
Engineering (EE) Stack Exchange. We analyze these HDL-related questions using a 
combination of qualitative analysis and automated topic modelling, in order to understand the 
challenges faced by developers when developing HDL programs. 
# Method
To understand the challenges of developing HDL programs, we study Stack Exchange forums 
where developers ask and answer technical questions, including HDL-related questions. We 
manually examined all the Stack Exchange forums to identify the ones that contain HDL-related 
questions. We used SOTorrent to download a dataset of Stack Overflow and Stack Exchange online
explore to downlowd Electrical 
engineering forum containing questions, their associated answers, and the associated metadata. 
Then, we identify the tags related to HDL and the corresponding questions and their 
answers. A random sample of the questions is used to study the categories of HDL-related 
questions. Then, we preprocess all the HDL-related questions and their answers and use topic 
modeling to extract topics from these questions and answers and manually label the topics. 
Finally, we analyze the level of difficulty of the HDL questions related to different topics to 
understand how challenging and demanding the topics may be to developers, the difficulty level 
of each topic was estimated by two widely used heuristics. the percentages of questions of the 
topic receiving an accepted answer and the time taken for these questions to receive an 
accepted answer. Intuitively, a more difficult topic is the one of which the related questions 
receives fewer accepted answers and after a long period of waiting time. 
# Folder Description
This repo contains the data and the source code used in our paper On Hardware Description Languages
The data folder contains the data files used in our paper and the Jupyter contains the jupyter notebooks
for reproducing the results. The SQL query folder contains sql codes for reproducing result from Stack Exchange forums.

# Data description
The data can be found in the data directory, which contains four files:

*Dataset SO*: the file contains all the extracted data from Stack Overflow forum. It used for topic modeling implementation 

*Dataset EE*: the file contains all the extracted data from Electrical Engineering forum. It used foe topic modeling implementation.

*Topic_modeling_result_HDL_SO*: the file contains topic modeling result for SO. It used for the difficulty level of topic as well.

*Topic_modeling_result_HDL_EE*: the file contains topic modeling result for EE. It used for the difficulty level of topic as well.




