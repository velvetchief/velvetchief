# Prithvi Datla

I ran KiloByte Collective, an applied AI lab that built agent systems for small businesses and the trades. I also wrote The RAG Book. Before that I owned digital product P&Ls at Verizon and AT&T. I take on contract delivery work, scoped per project or on a weekly block.

## The RAG Book

[theragbook.com](https://theragbook.com) covers retrieval, agents and multi-agent systems, from first principles to production. The [companion repo](https://github.com/velvetchief/the-rag-book) has three labs and a multi-agent capstone.

## Evals

Each repo holds the tasks, the answer keys, the runner and the graded outputs, so you can check every number. The write-ups are on [prithvidatla.com/evals](https://prithvidatla.com/evals/).

- [rfp-extraction-bakeoff](https://github.com/velvetchief/rfp-extraction-bakeoff) compares Claude few-shot, three LoRA-tuned open models and Jev sentence selection on extracting requirements from public Texas RFPs. The answer keys are hand-checked. [Write-up](https://prithvidatla.com/evals/jev/).
- [payroll-llm-eval](https://github.com/velvetchief/payroll-llm-eval) gives Claude Opus, Sonnet and Haiku 5.5 ten tasks a senior payroll specialist would get. A 13-point rubric with legal sources grades each answer by hand. [Write-up](https://prithvidatla.com/evals/payroll/).
- [agent-eval-harness](https://github.com/velvetchief/agent-eval-harness) is a three-layer harness for tool-calling agents: deterministic checks, a rubric-anchored LLM judge calibrated against human labels, and struggle detection.

## Grounded RAG

- [civicllm](https://github.com/velvetchief/civicllm) answers questions from city codes. Every answer cites its section, and the system refuses when the code does not cover the question. It runs on local weights through Ollama or on Claude.

## Agent tools

- [jev-airbag](https://github.com/velvetchief/jev-airbag) is a Claude Code hook that reads every shell command and blocks the ones that would delete something that matters.
- [pskills](https://github.com/velvetchief/pskills) holds the skills I use to run a business on agents.
- [momito](https://github.com/velvetchief/momito) is fully local hold-to-talk dictation for macOS on Apple silicon.

## Elsewhere

[prithvidatla.com](https://prithvidatla.com) · [LinkedIn](https://www.linkedin.com/in/pvd5)
