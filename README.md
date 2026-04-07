# OKEANOS256 - A CPU architecture and emualtor designed for low level local integration with LLMs and embedded systems

OKEANOS256 is a pet project of mine to create a CPU architecture that is supposed to meet the industry of "AI" -- LLM models -- and the growing integration mixed with the data center epidemic. Instead of prompting large servers, integrated language models can offer a LLM implementation that can be run on cheap single board computers or other architectures in order to implementation relatively fast AI. This is achieved by making optmization instructions specifcally for the processes LLMs can use in order to process and respond to prompts

## Status

Started project April 6 2026.

## Q&A

- Is it any good?
  - I hope so, but this is really more of a proof of concept then a real architecture at the moment. This is a real idea being worked on, and I wanna try and contribute to the idea and learn how LLMs and CPU math works by doing this project
- Are you buying into the AI hype train?
  - Kinda. I don't think that AI will replace programmers or critical thinking just yet (you should see Claude try and do Calculus) however, I still think that there will be real and useful implementations of language models. Only, as with the difference between an IBM mainframe and personal computing in the late 70s, the power ought to be in the hands of those who use it. Not trying to make this a manifesto, but if LLMs are going to dominate our lives, they ought to at least be ours.
- What does this repository actually set out to do? Is there a CPU I can buy?
  - Nope! But I hope to at least make a digital logic design for the CPU at some point. In terms of actual content, I will be making:
    - A full assembler for my set architecture
    - A emulator, written in Rust, for optimized math and preformance to demonstrate its efficiency
    - A C compilier and linker to convert into assembly for said assembler
- This seems ambitious
  - It is. This project might die, but I wanna learn and have fun on it
- What is the design consideration on your architecture?
  - There already exist "language processing units" or LPUs which are dedicated chips for LLMs. However, this blends to be both capable of executing small/medium AI models _and_ run embedded level programming. This allows for a strong blend between the two that will allow for a blend of both. Cost effective matters here the most. I also plan to do RISC
