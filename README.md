## Introduction to the Trial Agent

We present the design and implementation of a groundbreaking Trial Agent, tailored specifically for the clinical trial domain, which leverages the **LangChain** framework and harnesses the power of **GPT-4** as its underlying large language model (LLM). This innovative agent is a first-of-its-kind application in the clinical trial domain, conceived from the perspective of a statistical programmer to **autonomously** tackle complex analytical tasks. 


The Trial Agent demonstrates the ability to autonomously decompose tasks, reason, plan, and execute actions by leveraging provided tools. It represents a significant advancement in the clinical trial arena by embedding LLM functionalities into the workflow, which paves the way for a potential autonomous analysis robot. This Agent emerges as a powerful assistant to statisticians, medical professionals, and statistical programmers, collaboratively enhancing their capacity for in-depth data analysis.

## Demonstration
A demostration of a common example how the Trial Agent received a request from user, breaks down tasks, utilizes tools, and progressively finishes minor objectives to accomplish an assignment in 4 rounds is shown here:
<div align="center"> [Watch the Full Demonstration](https://youtu.be/45UtkiEX-Uw) </div>
<br>
You may see that the messages from both the agent and the user are displayed in white, the agent's reasoning process is shown in green, the results of the agent's reasoning are indicated by yellow, and the code autonomously written by the agent is also presented in white. The Agent possesses no additional contextual knowledge of clinical trials. 
