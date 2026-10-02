# Week 1 Assessment Questions

## Q1

Machine Learning (ML) is a subset of AI in which systems learn patterns from data instead of being explicitly programmed for every situation.

Deep Learning (DL) is a subset of ML that uses multi-layer neural networks to learn complex patterns from large amounts of data. It is widely used for tasks such as image recognition and speech recognition.

Generative AI (GenAI) is a type of AI that can generate new content such as text, images, audio, video, or code based on learned patterns. Large language models are an example of generative AI.

AI agents are systems that can use AI models to pursue a goal by planning or deciding actions, using tools or external systems when needed, and responding to the results.

The relationship can be viewed as:

AI
└── Machine Learning
    └── Deep Learning
        └── Generative AI
            └── AI applications and agents

These categories can overlap in real systems. For example, an AI agent may use a large language model based on deep learning and may use tools such as a search system or calculator.

### E - Evidence

I compared the definitions of AI, machine learning, deep learning, and generative AI with explanations from IBM. The sources describe AI as a broad field concerned with machines performing tasks associated with human intelligence. Machine learning is described as a subset of AI that enables systems to learn from data. Deep learning is a type of machine learning based on multi-layer neural networks, while generative AI can create new content such as text, images, audio, and code.

Sources:

1. IBM - Artificial Intelligence
2. IBM - Machine Learning
3. IBM - Deep Learning
4. IBM - Generative AI
### V - Verification

I verified the main definitions by comparing my explanation with the IBM reference material. I checked whether the relationship between AI, machine learning, deep learning, and generative AI was consistent with the source descriptions. I also checked the examples to make sure they matched the capabilities described for each technology.

The comparison supported the main concepts in my answer. I also noted that real-world AI systems can combine multiple techniques, so the hierarchy shown in the diagram is a simplified way of understanding the relationship rather than a strict representation of every AI system.

### R - Reflection

I learned that AI is the broader field and that machine learning and deep learning are approaches used within AI. I also understood that generative AI focuses on producing new content, while an AI agent can use an AI model together with tools and actions to accomplish a goal.

One important lesson is that simplified diagrams are useful for learning, but real AI systems can contain several technologies at the same time. Therefore, I should verify definitions and not assume that every AI system fits into one simple category.

## Q2
### A - Answer
The following examples can be classified based on how the system produces its output:

| Example | Classification | Reason |
|---|---|---|
| Calculator performing 25 × 8 | Traditional Software | It follows explicitly programmed mathematical rules. |
| Email spam filter that learns from examples | Machine Learning | It learns patterns from labelled or historical email data to classify messages. |
| Face recognition system identifying a person | Machine Learning / Deep Learning | It uses a trained model to recognize patterns in images and classify or identify faces. |
| Chatbot generating a new paragraph from a prompt | Generative AI | It generates new text based on patterns learned during training. |
| Code-generation assistant creating Verilog from a prompt | Generative AI | It generates new code based on the user's natural-language instruction. |

### E - Evidence
I classified the examples by considering how each system produces its output. Traditional software follows explicitly defined instructions, while machine-learning systems use patterns learned from data. Generative AI produces new content such as text or code.

### V - Verification
I checked each example against the definitions of traditional software, machine learning, and generative AI. I specifically considered whether the system follows fixed programmed rules, learns a prediction or classification from data, or generates new content.

### R - Reflection
This activity helped me understand that the presence of automation alone does not make a system AI. The important difference is how the system produces its result. A fixed rule-based program can automate a task without using machine learning, while ML systems learn patterns from data and generative AI creates new content.

## Q3
### A - Answer

When I enter a question into a Large Language Model (LLM), the text is first processed and divided into smaller units called tokens. These tokens are converted into numerical representations that the model can process.

The model uses its trained neural network to analyze relationships and patterns in the input. It then calculates probabilities for possible next tokens based on the context of the prompt and the tokens already generated.

The model selects a next token and continues this process repeatedly. Each newly generated token becomes part of the context used to predict the following token. This continues until the response is complete or a stopping condition is reached.

The important point is that an LLM does not simply look up a complete answer from a database. It generates a response token by token using patterns learned during training.

### Conceptual Flow

```text
User Prompt
     ↓
Tokenization
     ↓
Numerical Representation
     ↓
Neural Network Processing
     ↓
Probability Distribution
     ↓
Next-Token Selection
     ↓
More Tokens Generated
     ↓
Final Response

### E - Evidence
The explanation is based on the general operating principles of large language models: text is tokenized, processed by a neural network, and used to predict subsequent tokens. The generated response is produced sequentially rather than retrieved as one complete stored answer.

### V - Verification
I verified the main concepts by comparing the explanation with educational material describing tokenization and next-token prediction in language models. I also checked that the explanation did not describe an LLM as simply searching a database for a pre-written answer.

### R - Reflection
I learned that an LLM's response is generated step by step. The model uses the context available to it to determine probable next tokens. This also helped me understand why an AI-generated answer can sound confident while still containing incorrect information. The generation process itself does not guarantee that every statement is factually correct.


## Q4
### A - Answer
I asked the same question to two AI assistants, ChatGPT and Gemini, and compared their responses. Both assistants provided explanations of artificial intelligence, machine learning, deep learning, and generative AI, along with examples.

The responses were similar in their main concepts, but the wording, structure, and level of detail differed. This comparison showed me that different AI assistants can produce different responses to the same prompt.

### E - Evidence
I used the same prompt in both AI assistants:

"Explain the difference between artificial intelligence, machine learning, deep learning, and generative AI. Give one simple example of each."

I saved the actual responses from both ChatGPT and Gemini in `ai-comparison.md`.
### V - Verification
I compared the main claims from both responses with reliable reference material. I checked the definitions and examples rather than assuming that the AI-generated responses were automatically correct.

The main concepts in the two responses were consistent with the reference material. I also learned that important AI-generated claims should be independently verified.

### R - Reflection
This activity helped me understand that different AI assistants can give similar answers while using different wording and explanations. I learned that using the same prompt makes it easier to compare AI responses fairly. I also learned that getting an answer from an AI assistant does not remove the need for verification.

## Q5
### A - Answer
An AI assistant generates an answer based on patterns learned by its model and the information available to it. It is useful for explaining concepts, summarizing information, and helping me explore a topic.

A search engine helps me find information from different websites. I can inspect the search results and open the original webpages to find supporting information.

An authoritative source is a reliable source produced by an organization or person with responsibility or expertise in that subject. Examples include official documentation, government websites, standards organizations, universities, and research papers.

The three can be used together:

AI Assistant
      ↓
Initial explanation
      ↓
Search for information
      ↓
Authoritative source
      ↓
Verify the claim

### E - Evidence
I compared the roles of AI assistants, search engines, and authoritative sources. AI assistants are useful for generating explanations, while search engines help locate information and authoritative sources provide information that can be independently checked.

### V - Verification
I verified the main idea by checking whether important information provided by an AI assistant could be traced back to reliable external sources. I learned that I should check the original source instead of depending only on an AI-generated response.

### R - Reflection
I learned that an AI assistant should be treated as a useful starting point rather than automatically treating every response as a verified fact. Searching for the original information and checking reliable sources gives me a way to verify important claims.

## Q6
### A - Answer
An LLM (Large Language Model) is an AI model trained on large amounts of text and other data. It can understand prompts and generate responses such as explanations, summaries, or code.

An AI application is a software application that uses an AI model to provide a useful feature to the user. For example, a chatbot application can use an LLM to answer questions.

RAG (Retrieval-Augmented Generation) combines an LLM with a retrieval system. Before generating an answer, the system retrieves relevant information from an external knowledge source and provides that information to the LLM as context. This can help the model answer using more relevant and up-to-date information.

A tool-using assistant is an AI assistant that can call external tools to perform tasks that the model cannot reliably perform by itself. Examples include using a calculator, search system, database, or software API.

An AI agent is a system designed to accomplish a goal by deciding and carrying out actions, observing the results, and continuing the process when necessary. An agent may use an LLM, external tools,
retrieved information, and other software components.

Concept Diagram
                 User
                   │
                   ▼
            AI Application
                   │
                   ▼
                 LLM
              /    |    \
             /     |     \
            ▼      ▼      ▼
          RAG    Tools   Memory
            │      │
            ▼      ▼
     External     Search /
     Knowledge    Calculator /
     Sources      APIs
            \      /
             \    /
              ▼  ▼
          AI Agent
              │
              ▼
       Goal / Task Completion
### E - Evidence
I studied the roles of LLMs, AI applications, RAG systems, tool-using assistants, and AI agents. I focused on the difference between the AI model itself and the software components that allow the model to retrieve information or interact with external tools..

### V - Verification
I verified the concepts by comparing their definitions with reliable technical learning material. I specifically checked that RAG retrieves external information before generation, that tool-using assistants can interact with external tools, and that an agent can perform multiple actions toward a goal.

I also checked that an AI application is not necessarily the same thing as the underlying LLM. An application can combine an LLM with interfaces, retrieval systems, tools, databases, and other software components.

### R - Reflection
I learned that an LLM is only one part of a complete AI system. An application can add RAG to provide external information and tools to perform actions. An agent can coordinate these capabilities to work toward a particular goal.
This helped me understand why modern AI systems are more than just a language model generating text.

## Q7
### A - Answer
AI can be useful for generating information and recommendations, but there are situations where a human should verify the output before taking action.

Five examples are:

Medical decisions
AI-generated medical information should be checked by a qualified healthcare professional before making treatment or medication decisions.
Legal decisions
Legal information generated by AI should be verified using official laws, regulations, or qualified legal professionals.
Financial decisions
AI-generated financial advice or calculations should be checked against reliable financial information before making important financial decisions.
Engineering and safety-critical systems
AI-generated designs, calculations, RTL code, or technical recommendations should be reviewed and tested by qualified engineers before being used in a real system.
Important personal or professional decisions
AI-generated information about employment, education, contracts, or other important decisions should be independently verified before relying on it.

### E - Evidence
I considered situations where an incorrect AI output could cause significant consequences. In these cases, AI can assist with research or explanation, but a qualified human should review the information and make or approve the final decision.

### V - Verification
I verified this approach by considering whether the AI output could directly affect health, legal rights, money, safety, or other important outcomes. I also checked that AI-generated information should not automatically be treated as a verified fact.
For engineering examples, I would verify generated code through simulation, testing, assertions, and review before using it in an actual design.

### R - Reflection
I learned that AI is a useful assistant, but it should not replace human responsibility in high-impact situations. The amount of verification required depends on the consequences of an incorrect answer.

As a VLSI student, I especially understood the importance of verifying AI-generated RTL or verification code through simulation, testing, and engineering review instead of assuming that code generated by AI is automatically correct.

## Q8
### A - Answer
I encounter AI-powered systems and features in many everyday activities. Five examples are:

YouTube recommendations
AI analyzes viewing behavior and recommends videos that may be relevant to the user.
Google Maps route recommendations
AI and data-driven systems can analyze traffic and other information to help suggest routes and estimate travel time.
Email spam filtering
Machine-learning systems can identify patterns in emails and classify messages as spam or legitimate.
Face unlock on smartphones
AI-based computer vision can analyze facial features to recognize an authorized user.
Voice assistants
Voice assistants use AI technologies such as speech recognition and language processing to understand spoken requests and provide responses or perform actions.

### E - Evidence
I identified AI systems based on features I regularly encounter in applications and electronic devices. These systems use different AI techniques depending on the task, such as recommendation, classification, computer vision, and language processing.

### V - Verification
I checked the purpose of each feature and identified the type of task it performs. I distinguished AI-based features from simple fixed-rule functions by considering whether the system uses learned patterns or AI models to process information and produce its output.

### R - Reflection
This activity helped me realize that AI is already present in many systems I use every day. Before this exercise, I mostly associated AI with chatbots and generative AI. I now understand that recommendation systems, spam filters, computer vision, and voice assistants are also examples of AI applications

## Q9
### A - Answer
AI systems can perform different types of tasks. Three common categories are prediction, classification, and generation.

Example	Task Type	Reason
Predicting tomorrow's temperature	Prediction	The system estimates a future value using available data.
Detecting whether an email is spam	Classification	The system assigns the email to a category such as spam or not spam.
Predicting the price of a house	Prediction	The system estimates a numerical value based on factors such as location, size, and other data.
Identifying whether an image contains a cat or dog	Classification	The system assigns the image to one of the given categories.
Generating a paragraph using an AI chatbot	Generation	The system creates new text based on the user's prompt.
Generating an image from a text prompt	Generation	The AI creates new visual content from the provided description.
Predicting whether a customer will cancel a subscription	Prediction	The system estimates a future outcome based on available information.
Generating Verilog code from a natural-language description	Generation	The AI creates new code based on the user's requirements,

### E - Evidence
I classified each example according to the type of output produced. Prediction estimates a future or unknown value or outcome. Classification assigns an input to a category. Generation creates new content such as text, images, or code

### V - Verification
I verified each example by asking what the AI system is expected to produce. If the output is an estimated value or future outcome, I classified it as prediction. If the output is a category or label, I classified it as classification. If the system creates new content, I classified it as generation.

### R - Reflection
This activity helped me understand that different AI systems can have different purposes even when they use similar underlying technologies. I learned to identify the task type by looking at the expected output rather than simply calling every AI system generative AI.

As a VLSI student, the Verilog example also helped me connect the concept of AI generation with a technical task that I may encounter in my field.

## Q10
### A - Answer
I created the following seven-step protocol to verify AI-generated information before relying on it:

Understand the claim
Identify exactly what the AI is claiming or recommending.
Check the source
Look for the original or authoritative source that supports the claim.
Compare multiple sources
Compare the information with other reliable sources to identify differences or inconsistencies.
Check the date
Confirm that the information is current and has not become outdated.
Test when possible
If the AI provides code, calculations, or technical information, test the result using appropriate tools or experiments.
Review for errors
Check the output for incorrect assumptions, missing information, contradictions, or unsupported statements.
Human approval
For important or high-impact decisions, have a qualified person review and approve the final result before using it.
E - Evidence

I developed this protocol based on the limitations of AI-generated information and the verification methods used throughout this assessment. The main idea is to treat AI output as information that needs to be checked rather than automatically assuming it is correct.

### V - Verification
I applied the protocol to AI-generated information by checking claims against reliable sources and considering whether the information could be tested or independently confirmed.

For technical work, such as Verilog or SystemVerilog code, verification can include compilation, simulation, assertions, test cases, and waveform analysis. For factual information, verification can include checking authoritative documentation or reliable reference sources.

### R - Reflection
This protocol taught me that using AI effectively requires both generation and verification. AI can help me learn concepts, write initial drafts, generate ideas, and assist with technical tasks, but I remain responsible for checking the final result.

In the future, I will avoid accepting an AI answer simply because it sounds confident or detailed. I will verify important claims before using them, especially when they can affect engineering decisions or other important outcomes.
