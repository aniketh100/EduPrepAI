# EduPrepAI
Transcription-based Quiz Authoring System


![Screenshot 2024-01-28 110403](https://github.com/thisisgagangupta/EduPrepAI/assets/93258623/3220f406-3aa8-478c-b266-69fe12386c32)

Problem Research: We reached out to teachers and students and what we felt as a major problem is, students don't have much time to find questions relevant to the topic leading to lack of practice and also teachers are not able to create enough personalized content for students as they have to do it manually.
Students in colleges usually watch summary video of the whole topics (preferably YouTube or the college AV summaries) and go for the examination which doesn't help them much. What if! You get interactive quizzes with the video you watch, that might help you with the questions that are more likely to be asked and get a better practice and confidence.

Turn educational video lectures into engaging MCQ based quizzes and automatic assessment.
Introducing our revolutionary Transcription-based Quiz Authoring System. A cutting-edge tool designed to enhance the learning experience for both teachers and students. This innovative project will empower educators to effortlessly create engaging quizzes that cater to their unique teaching objectives, saving valuable time and effort. With an intuitive interface, our quiz generator enables teachers to customize questions, select diverse question types, and set parameters to meet the specific needs of their curriculum. Students, in turn, benefit from a dynamic and interactive learning environment, where they can reinforce their understanding of course material in a fun and challenging way. This tool not only streamlines the quiz creation process but also provides instant grading and performance analytics, allowing teachers to identify areas for improvement and tailor their instructional approach accordingly. A transformative solution for efficient and effective learning.

RoadMap:
Data Collection and Selection:
Take educational videos from 3rd party like (YouTube , https://paperswithcode.com/dataset/eduvsum)
Explore transfer learning opportunities using pre-trained models if applicable.

Video Conversion to Audio:
Extract audio from video files using appropriate tools or libraries.
Use ML-based audio processing techniques if beneficial and needed.
VX2TEXT: End-to-End Learning of Video-Based Text Generation from Multimodal Inputs at later updates for adding visual features of the videos aswell

Audio to Transcript Generation:
Explore automatic speech recognition (ASR) models, possibly leveraging existing ML-based solutions.

Data Cleaning and Preprocessing:
Utilize natural language processing (NLP) for text cleaning and normalization.
SpaCy

Text Summarization (Optional):
Apply extractive or abstractive summarization using ML models to condense text.
Tokenization

Question Generation:
Implement T5 (transformer-based architectures) question generation models varying the number of models to use according to the types of question patterns.
Or 
Using LLMs BERT preferably for this task and Naive Bayes Classifier

Quiz/Answer Key Generation:
Sense2vec wordvectors that are used for generation of multiple choices.
Research about giving similar options which are not correct as options.

Assessment Mechanism:
Incorporating natural language understanding (NLU) model.
Score Reinforcement Learning

Integration of Multimedia Elements (Optional):
Explore computer vision models for extracting information from video frames.

Database Integration:
Using data indexing and retrieval, improving efficiency.

Make an internal AI to help navigating through the portal.


*This gives just the basic idea of the implementation and we will be changing/enhancing a lot of things here.*


Future Adds:
*~* Create AI generated notes From PDFs, PowerPoints, and Lecture Videos, automatically!
~ Chat with your AI tutor about your course materials to help you study better!
~ Search for a term from the video and jump to instances where it was used.

https://github.com/thisisgagangupta/EduPrepAI
