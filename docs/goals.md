Some goals:  
 - work alongside existing Toit tooling
 - at least delivered as a docker or similar image, to minimize setup friction for firmware compilation
 - utilize a fine-tuned Small Language Model (SLM), to enable inference to be run locally on more common GPUs
 - the SLM will be proficient in the Toit language and documentation, C and CircuitPython
 - support a service interface to existing C code
 - support for connection to hardware, for logging and debug
 - ideally the developer would assemble the various artifacts describing the project, including:
    - Product Requirements Document
    - hardware description
    - hardware datasheets
    - test assembly
    and sedaris would be responsible for writing the code, test suites, benchmarks, documentation and then handling product lifecycle

References:
- [Why AI Agents Replaced the Arduino IDE in My ESP32 Projects (Claude Code, Gemini CLI, Codex)](https://youtu.be/5DG0-_lseR4)
- [Communicating with C code](https://docs.toit.io/tutorials/misc/c-service)
- [Me Talk Pretty One Day](https://www.amazon.com/Me-Talk-Pretty-One-Day-David-Sedaris/dp/B0000547MZ)