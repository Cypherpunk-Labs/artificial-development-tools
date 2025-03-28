# Opensource code generation models

here's a breakdown of notable open-source models that demonstrate strong programming capabilities, especially when compared to leading proprietary models like Claude 3.7:

Key Open-Source Contenders:

DeepSeek R1:
This model has shown impressive performance in competitive coding benchmarks.   
It's designed with a focus on efficiency and performance, making it a strong contender for various coding tasks.   
A key strength is that it is fully open source, which allows for greater flexibility and customization.   
It has shown very strong results in coding benchmarks, and has been shown to be on par with models such as OpenAI's O1.   
Meta Llama 3:
Meta's Llama models have been significant contributors to the open-source LLM landscape.   
Llama 3, in its various sizes, offers strong coding abilities and is actively being developed and improved.   
It's versatility and open-source nature make it a valuable tool for developers.
Mistral AI Models:
Mistral's models, particularly Mixtral, have gained recognition for their efficiency and performance.   
They offer competitive coding capabilities and are known for their speed.
These models are also availible for download, increasing their usefullness.   
Factors to Consider:

Benchmark Performance:
Models are often evaluated on benchmarks like SWE-bench and competitive coding platforms.   
It's crucial to consider the specific benchmarks used and their relevance to your coding needs.
Context Window:
A larger context window allows the model to process more code, which is essential for complex projects.   
Open-Source Flexibility:
Open-source models offer greater customization and control, allowing developers to fine-tune them for specific tasks.   
Community Support:
A strong community can provide valuable resources, tools, and support for using and improving open-source models.
Important Notes:

The AI landscape is rapidly evolving, with new models and updates constantly emerging.
"Open-source" can have varying degrees, so it's essential to understand the licensing and accessibility of each model.
Keep in mind that even though some models are open source, that running them can require significant computing power.
While Claude 3.7 demonstrates strong coding capabilities, these open-source models offer viable alternatives, especially for those seeking flexibility, customization, and community-driven development.

# Opensource code execution models

When looking for open-source code execution models that focus on running code rather than generating it, the emphasis shifts to tools that provide secure and isolated execution environments. Here's a key option:

Judge0:
Judge0 is an open-source online code execution system. It's designed to allow you to execute code in a secure and scalable way.   
It's particularly useful for applications that require running user-submitted code, such as:
Competitive programming platforms.   
Online coding editors.   
E-learning platforms.
Candidate assessment tools.
Key features include:
Sandboxed execution: This is crucial for security, as it isolates the executed code from the host system.   
Support for many programming languages.   
A robust API for integration into other applications.
Judge 0 is designed to take code that is submitted to it, and then execute that code in a secure enviroment. That is it's primary function.
Key Considerations:

Sandboxing:
Security is paramount when executing arbitrary code. Look for systems that provide strong sandboxing capabilities.   
Language Support:
Ensure the system supports the programming languages you need.
API and Integration:
If you plan to integrate the execution system into your own applications, a well-documented API is essential.
Judge0 is a very strong open source option, when the goal is to execute code, and not generate it


It's tricky to pinpoint an "open-source AI code execution model" that solely executes and completely avoids any generation aspects. AI in this space often blends analysis, understanding (which is a form of "generation" of understanding), and then execution. However, we can focus on tools that prioritize safe, controlled execution, and analysis of code, with AI assistance. Here's a breakdown:

Key areas and tools:

Secure Execution Environments:
Judge0:
As previously mentioned, Judge0 excels at securely executing code. While not an "AI model" itself, it's a foundational tool for any AI-driven code execution system. It provides the crucial sandboxed environment.   
The importance of docker and other containerization technologies is very important here. These tools allow for code to be run in a very controlled enviroment.
AI-Powered Code Analysis and Security:
Tools that use AI to analyze code for vulnerabilities and potential issues are relevant. While they might generate reports or suggestions, their core function is analysis.   
There are also tools that are beginning to use AI to help with the analysis of open source AI models themselves, to find potential security risks.
Tools that Facilitate AI agent code execution:
SWE-kit:
SWE-kit is a opensource head-less IDE for coding agents. This tool allows for the creation of agents that can interact with code, and execute it. While the agents themselves may use LLM's for planning, SWE-kit allows for the controlled execution of the code the agents produce.   
Tools that help with the creation of AI agents that can interact with code, are becoming more popular. These tools help to provide a framework for the safe execution of code, that AI agents create.
Important Considerations:

The Blurring Lines:
AI is about understanding and processing information. Even "execution" often involves some level of AI-driven analysis of the code's behavior.   
Security:
Running arbitrary code is inherently risky. Any system must prioritize security through sandboxing and robust access controls.   
In summary, while a pure "AI execution-only" model is rare, tools like Judge0 and frameworks that help with AI agents, provide strong foundations for secure and controlled code execution within AI-driven workflows.


# Model costs

## Claude

- input per million $3
- output per million $15

  
# Tokens Per Second (TPS)

## Estimate model size

- FP64(NA) 8 bytes
- FP32(std) 4 bytes
- int8(Q8) 1 bytes
- int4(Q4) 0.5 bytes

- Model size (GB) = X ( X Billion Parameters x bytes )
- 15b model with standard fp32 15 * 4 = 60gb

## Rough formulae

- GPU Ram speed / Model size = TPS

- Apple M2 100GBs / Deepseek R1 7B Q4 3.5(4.7) = 28TPS 1680TPM 100800TPH
- Apple M2 100GBs / Deepseek R1 70B Q4 35(43) = 2TPS
- Nv P40 347GBs / DSR1 7B 3.5 = 99TPS
- Nv P40 347GBs / DSR1 70b 35 = 9TPS
- Nv H100 3350GBs / DSR1 70b = 95TPS

# API aggregation/access services

- openrouter.ai
- 

# AI-IDE Prompting 

- https://github.com/nickbaumann98/cline_docs
- https://github.com/instructa/ai-prompts
- https://github.com/Tjeker61/Cline-custom-prompt
