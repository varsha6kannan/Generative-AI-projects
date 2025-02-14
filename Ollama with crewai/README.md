# Project Name - PDF search tool using agentic AI
> Reading pdfs when you have a time crunch can be a tedious and troublesome task, we can leverage the use of agentic AI to read the pdf content and perform any additional task like write it in short bullet points for quick understanding. In this project i have taken a research paper based on deepseek - "DeepSeek-VL: Towards Real-World Vision-Language Understanding" and built a local pdf search tool model that does not require any api key for usage.


## Table of Contents
* [Introduction](#introduction)
* [Brief process](#brief-process)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->
## Introduction
What is agentic AI?

- AI agents are autonomous units that perform the custom task that we provide and they execute and adapt to these tasks. Agents act like a team of engineers, they are given tasks to perform. In this project i have used crew ai to create an agent based system. So going back to the analogy given before, agents are like engineers and crew is the upper management that provides the tasks and monitors the flow. Crew ai also has many in-built tools to perform actions based on the usecase.

## Brief process
- I have firstly used ollama model phi3:3.8B to create a local system AI. This model i have used it for embedding the pdf content as well as for performing the search.
- Embedchain is used with ollama to create the embeddings of the pdf and these embeddings are stored in the chroma db by default.
- Then there are two agents created:
    1. Researcher: goes through the document and searches for the relevant topics and creates a summary
    2. Writer: Writes down the content in form of short bullet points in less than 20 words.


<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Technologies Used
- crewai - version 0.100.0
- crewai_tools - version 0.33.0
- langchain - version 0.3.17
- ollama - version 0.4.7
- embedchain - version 0.1.126

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Understood about agentic AI framework through this course- https://www.oreilly.com/library/view/modern-automated-ai/9780135414965/
- This tutorial on youtube helped me understand about the installation and steps of ollama- https://www.youtube.com/watch?v=UtSSMs6ObqY
- Got hands on with crew ai using YouTubeSearchTool with this video- https://www.youtube.com/watch?v=UV81LAb3x2g


## Contact
Created by [@varsha6kannan] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
