---


---

<h2 id="principles-of-ai--machine-learning">Principles of AI &amp; Machine Learning</h2>
<p>In this article i’ll go over the basic fundamentals of artificial intelligence and machine learning (what is AI &amp; ML), various fields of AI, models used in AI, coupled with a short summary of the features we’ll use in Python.</p>
<h2 id="ai--machine-learning---an-overview">AI &amp; Machine Learning - An Overview</h2>
<p><strong>What is AI?</strong></p>
<blockquote>
<p>Artificial Intelligence (AI) is a science that’s used to construct<br>
intelligence using hardware and software solutions.<br>
Artificial intelligence (AI) is the simulation of human intelligence processes by machines, especially computer systems.</p>
</blockquote>
<p>At a high level, AI is a sub-field of computer science that enables computers to do things normally done by people – in particular, things associated with people acting intelligently. AI’s goal is to make computer programs smart enough to imitate the human mind behavior.</p>
<p><strong>What is ML?</strong></p>
<blockquote>
<p>Machine learning is a field of study concerned with giving<br>
computers the ability to learn without being explicitly programmed.</p>
</blockquote>
<p>Machine Learning is one of the enablers behind AI, it gives machines the ability to learn by themselves and improve their own performance – hence acting intelligently. ML do not rely on rule-based programming, but instead on algorithms that identify patterns in data and then predict similar patterns in new data. Importantly, the software can continually improve the quality of the predictions they make as time goes on. Therefore, in Machine Learning, artificial knowledge is generated on the basis of experience.</p>
<p>AI &amp; ML <a href="https://images.app.goo.gl/8LyrAxAAaPZFSQCY7">https://images.app.goo.gl/8LyrAxAAaPZFSQCY7</a></p>
<h2 id="fields-and-applications-of-artificial-intelligence">Fields and Applications of Artificial Intelligence</h2>
<p>Now that we know what Artificial Intellignce is, we should explore different fields in which AI is applied.</p>
<ol>
<li>Simulation of Human Intelligence</li>
<li>Simulating Intelligence - The Turing Test</li>
</ol>
<p><strong>Simulation of Human Intelligence</strong></p>
<p>Humans have five basic senses, which is divided into visual, auditory, kinesthetic, olfactory, and gustatory, however for the purposes of understanding how to create an intelligent machine, we can separate these desciplines into:</p>
<ul>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Listening and Speaking</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Understanding Language</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Remembering Things</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Thinking</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Seeing</li>
<li class="task-list-item"><input type="checkbox" class="task-list-item-checkbox" disabled=""> Moving</li>
</ul>
<p><strong>Listening and Speaking</strong></p>
<p>AI uses speech recognition system to collect information, it then uses speech synthesis, to turn internal data into understandable sounds. Speech recognition and speech synthesis techniques deal with the recognition and construction of sounds humans emit or that humans can understand.<br>
For instance you are on a trip to a country where you don’t speak the local language. You can speak into the microphone of your phone, expect it to “understand” what you say, then translate it into the local language and the same can happen in reverse. Speech recognition and speech synthesis make this possible.</p>
<p><em>An example of speech synthesis is Google Translate. You can navigate to <a href="https://translate.google.com/">https://translate.google.com/</a> and make the translator speak words in a non-English language by clicking the loudspeaker button below the translated word</em></p>
<p><strong>Understanding Language (NLP)</strong></p>
<p>We can understand natural language by processing it, thi field is called natural language processing (NLP). It is defined as the automatic manipulation of natural language, like speech and text, by software. One of the well-known examples of this is email spam detection as we can see how it has improved in our mail system.</p>
<p><strong>Remembering Things (Machine Learning)</strong></p>
<p>In ML we need to represent things we know about the world, this is where creating knowlwdge bases and hierarchical representations comes into play. Knowledge bases categorizize things and ideas in our world and contain relations between these categories. This gives machines the ability to learn by themselves and improve their own performance – hence acting intelligently.</p>
<p><strong>Thinking (Expert Systems)</strong></p>
<p>AI systems have to be an expert in a certain domain by using an expert system. An expert system can be based on mathematical logic in a deterministic way, as well as in a non-deterministic way. The knowledge base of an expert system is represented using different techniques, as the problem domain grows, we create hierarchical ontologies. We can replicate this structure by modeling the network on the building blocks of the brain. These building blocks are called neurons, and the network itself is called a neural network.<br>
There is another key term for neural networks: deep learning. Deep learning goes beyond pattern recognition and categorization. Learning is imprinted into the neural structure of the network. One special deep learning task, for instance, is object recognition using computer vision.</p>
<p><strong>Seeing (Computer Vision)</strong></p>
<p>We interact with the real world through our senses, now we have only touched upon auditory senses so far, in regard to speech recognition and synthesis. What if we had to see things? Then, we would have to create computer vision techniques to learn about our environment. Computer vision depends on image processing, although image processing is not directly an AI discipline, it is a required discipline for AI.</p>
<p><strong>Moving (Robotics)</strong></p>
<p>Moving and touching are natural to humans, but they are complex tasks for computers, moving is handled by robotics. This is a very math-heavy topic. Robotics is based on control theory, where you create a feedback loop and control the movement of your object based on the feedback gathered.<br>
Interestingly enough, control theory has applications in other fields that have absolutely nothing to do with moving objects in space. This is because the feedback loops required are similar to those modeled in economics.</p>
<p><strong>Simulating Intelligence - The Turing  Test</strong></p>
<p>Alan Turing, the inventor of the Turing machine, an abstract concept that’s used in algorithm theory, suggested a way to test intelligence. This test is referred to as the Turing test in AI literature.<br>
Using a text interface, an interrogator chats to a human and a chatbot. The job of the chatbot is to mislead the interrogator to the extent that they cannot tell whether the computer is human or not.<br>
What disciplines do we need to pass the Turing test?<br>
First, we need to understand a spoken language to know what the interrogator is saying, by using Natural Language Processing (NLP).<br>
We need to be an expert on things that the human mind tends to be interested in, by building an Expert System of humanity, involving the taxonomy of objects and abstract thoughts in our world, as well as historical events and even emotions.</p>
<h2 id="ai-tools-and-learning-models">AI Tools and Learning Models</h2>
<p>In the previous section, we have learnt what AI is, and one of the core tasks for artificial intelligence is learning.</p>
<p><strong>Intelligent Agents</strong></p>
<p>In solving AI problems, we create an actor in the environment that can gather data from its surroundings and influence its surroundings and that actor is called an intelligent agent.</p>
<p>An intelligent agent:</p>
<ul>
<li>Is autonomous</li>
<li>Observes its surroundings through sensors</li>
<li>Acts in its environment using actuators</li>
<li>Directs its activities toward achieving goals</li>
</ul>
<p>Agents may also learn and have access to a knowledge base.<br>
An agent is a function that maps perceptions to actions and if the agent has an internal knowledge base, perceptions, actions, and reactions may alter the knowledge base.</p>
<p>Actions may be rewarded or punished, and setting up a correct goal and implementing a carrot and stick situation enables the agent to learn. If goals are set up correctly, agents have a chance of beating the often more complex human brain, because the number one goal of the human brain is survival, regardless of<br>
the game, whilist an agent’s number one motive is reaching the goal itself.</p>
<p><strong>Classification and Prediction</strong></p>
<p>In AI different goals require different processes. Let’s explore the two most popular types of AI reasoning: classification and prediction.</p>
<p><strong>Classification</strong></p>
<p>Classification is a process for figuring out how an object can be defined in terms of another object. For instance, a father is a male who has one or more children. If Jane is a parent of a child and Jane is female, then Jane is a mother. Also, Jane is a human, a mammal, and a living organism. We know that Jane has a nationality as well as a date of birth.</p>
<p><strong>Prediction</strong></p>
<p>Prediction is the process of predicting things, based on patterns and probabilities. For instance, if a customer in a standard supermarket buys organic milk, the same customer is more likely to buy organic yoghurt than the average customer.</p>
<p><strong>Learning Models</strong></p>
<p>The process of AI learning can be done in a supervised or unsupervised way. Supervised learning is based on labeled data and inferring functions from training data, for example linear regression. Unsupervised learning is based on unlabeled data and often works on cluster analysis.</p>
<h2 id="the-role-of-python-in-artificial-intelligence">The Role of Python in Artificial Intelligence</h2>
<p>In order to put AI concepts into practice, we need a programming language that supports artificial intelligence, and for the purpose of this article we have chosen Python. There are a few reasons why Python a good choice for AI:</p>
<ul>
<li>Python is a high-level programming language, which means that you don’t have to worry about memory allocation, pointers, or machine code in general. Python is also cross-platform compatible.</li>
<li>The strong emphasis on developer experience makes Python a very popular choice among software developers. In fact, according to a 2018 developer survey by <a href="https://www.hackerrank.com">https://www.hackerrank.com</a>, across all ages, Python ranks as the number one preferred language of software developers. This is because Python is easily readable and simple. Therefore, Python is great for rapid application development.</li>
<li>Despite being an interpreted language, Python is comparable to other languages used in data science such as R. Its main advantage is memory efficiency, as Python can handle large, in-memory databases.</li>
</ul>
<p><strong>Why is Python Dominant in ML, Data Science, and AI?</strong></p>
<p>To understand why Python dominate in machine learning, data science, and AI, we have to compare Python to other languages also used in these fields.</p>
<p>One of the main alternatives is R, the advantage of Python compared to R is that Python is more general purpose and more practical.</p>
<p>Compared to Java and C++, writing programs in Python is significantly faster and also provides a high degree of flexibility.</p>
<p>There are some languages that are similar in nature when it comes to flexibility and convenience: Ruby and JavaScript. Python has an advantage over these languages because of the AI ecosystem available for Python. Python’s third-party AI library support is excellent.</p>
<p><strong>Python Libraries for Artificial Intelligence</strong></p>
<p>The list of libraries i mentioned here is not complete as there are more than 700 available in Anaconda, however, these specific ones will get you off to a good start, because they will give you a good foundation to be able to implement fundamental AI algorithms in Python:</p>
<ol>
<li>NumPy: NumPy is a computing library for Python. As Python does not come with a built-in array data structure, we have to use a library to model vectors and matrices efficiently. In data science, we need these data structures to perform simple mathematical operations. We will extensively use NumPy in future modules.</li>
<li>SciPy: SciPy is an advanced library containing algorithms that are used for data science, it is a complementary library to NumPy, because it gives all the advanced algorithms you need, whether it be a linear algebra algorithm, image processing tool, or a matrix operation.</li>
<li>pandas: pandas provides fast, flexible, and expressive data structures such as one-dimensional series and two-dimensional DataFrames. It efficiently loads, formats, and handles complex tables of different types.</li>
<li>scikit-learn: scikit-learn is Python’s main machine learning library. It is based on the NumPy and SciPy libraries. scikit-learn provides you with the functionality required to perform both classification and regression, data preprocessing, as well as supervised and unsupervised learning.</li>
<li>NLTK:  NLTK this library is the main natural language toolkit of Python. You can perform classification, tokenization,<br>
stemming, tagging, parsing, semantic reasoning, and many other services using this library.</li>
<li>TensorFlow: TensorFlow is Google’s neural network library, and it is perfect for implementing deep learning artificial intelligence. The flexible core of TensorFlow can be used to solve a vast variety of numerical computation problems. Some real-world applications of TensorFlow include Google voice recognition and object identification</li>
</ol>
<p><strong>Python for Game AI</strong></p>
<p>AI game player is nothing but an intelligent agent with a clear goal: to win the game and defeat all other players.</p>
<p><strong>Intelligent Agents in Games</strong></p>
<p>An intelligent agent plays according to the rules of the game, the agent can sense the current state of the game through its sensors and can evaluate the utility of potential steps. Once the agent finds the best possible step, it performs the action using its actuators. The agent finds the best possible action to reach<br>
the goal based on the information it has. Actions are either rewarded or punished. The carrot and stick are excellent examples of rewards and punishment.</p>

