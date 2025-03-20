# artificial-development-tools
Document to Review Artificial Development Tools(SDLC) on the market.

Ideally one would continue to use Gitops SDLC practices, create feature requests, hand over to AI-Driven toolchain > tag Agents, Agent works on problem, Hand back to human > Review Agents work and merge acceptable outcomes else iterate with further prompting. 
These Agents should have the capability to ascertain requirements and constraints, Generate the code, Create a test environment, Execute and test the code, Iterate until the feature compiles executes and passes tests.
For scenarios where a human needs to troubleshoot a failing process, Toolchains integrated into the IDE are ideal so if cooperating with AI to pair program then the ability to keep focus and get feedback within the IDE are key.

## What type of capabilities have we seen?:

- WWW: Prompt Inline Code Completion
- AI-IDE: Intellisense code completion
- MCP: https://modelcontextprotocol.io/clients 
- KVM: based computer use
- EC: Executes Code
- ISC: Iterative Self correction
- SB: Sandboxes
- GO: Git Ops (Clone/forks/Branches > merge requests/PR)

## Capability Evaluation 

| WWW | AI-IDE | MCP | KVM | EC | ISC | SB | GO |	OSS |	URL |	Notes |
|---  |---     |---  |--- |--- |---  |---  |---  |---  |---   |---  |
| £$€| £$€| £$€| £$€| £$€| £$€	| £$€	| £$€ |	£$€	| Commercial Tools |
| Y | Y | N | N | ? | ? | N | N | N | https://github.com/features/copilot | |
| ? | Y | Y | N | Y | Y | Y | N | N | https://www.cursor.com/ | |
| Y | ? | ? | Y | Y | Y | Y | Y | N | https://manus.im/ | |
| Y | N | Y | N | Y | Y | Y | N | N | https://docs.anthropic.com/en/docs/agents-and-tools/computer-use | |
| N | Y | Y | N | Y | Y | N | N | N | https://codeium.com/windsurf | Can select a few models |
| Y | ? | ? | Y | ? | ? | ? | N | N | https://openai.com/index/computer-using-agent/ | |
| Y | N | N | N | N | N | N | N | N | https://ai.google/get-started/gemini-ecosystem/#BuildWithGemini | |
| ? | ? | ? | ? | ? | ? | ? | ? | ? | https://www.crewai.com/ | |
| ? | ? | ? | ? | ? | ? | ? | N | ? | https://www.bitte.ai/ | |
| OSS | OSS| OSS|OSS |OSS| OSS | OSS | OSS | OSS| OSS| OSS	| OSS |	OSS |	OSS | Open Source |
| N | Y | ? | ? | ? | ? | ? | N | Y | https://github.com/nikmcfly/ANUS | inspired by manus |
| N | Y | Y | N | ? | ? | ? | N | Y | https://cline.bot/ | uses MCP |
| N | Y | Y | N | N | N | N | N | Y | https://www.continue.dev/ | |
| Y | N | N | N | Y | Y | Y | P | Y | https://github.com/All-Hands-AI/OpenHands | can choose model, runs in jupyter |
| N | N | N | Y | Y | Y | N | N | Y | https://github.com/OpenInterpreter/open-interpreter | NLM to Computer Use |

## Other efforts to list/assess tools

- https://github.com/jamesmurdza/awesome-ai-devtools
- https://github.com/ranpox/awesome-computer-use
- https://github.com/eltociear/awesome-AI-driven-development

## Benchmarking tools

- https://github.com/xlang-ai/OSWorld
- https://www.swebench.com/

## Problems 

- Hallucinations
- Non existant dependancies
- Echoing back same code
- Broken code
- Old/deprecated dependancies selected
- Adding dependancies outside of your stack
- Dropping/deleteing code not part of prompt
- Not upto date
- Errors introduced due to lacking context
- Biases

## Search terms used

- Artificial Development Tools
- software artificial development
- artificial SDLC
- Gitops ai-driven
