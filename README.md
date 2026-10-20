# Ahoy there

Molecular biologist and entrepreneur in Basel. I'm working on agentic lab automation and drug discovery. I make open-source instrument drivers and bioinformatics tools that I use in my work and my own lab. I also help build peptide drug discovery pipelines for myself and [SP2TX](https://www.sp2tx.com). Even though I don't have formal training in software development, I enjoy tinkering and building things. I use AI, but I remain in the driver's seat as much as possible. See the AI code quality disclosure below. 

### Current focus

- Building [Lambda Biolab](https://www.lambconsulting.bio/lambda-biolab), a BSL-1 shared lab and open
  tooling for bioengineering, since 2022.
- Reverse-engineering lab instruments into open Python APIs, from PCR machines to plate
  readers to electronic pipettes.
- Running local LLM inference and agent tooling for wet-lab workflows.

### Projects I'm working on

**Affordable, low-cost, distributed computing in genomics and structural biology**

- [**deepvariant-linux-arm64**](https://github.com/Lambda-Biolab/deepvariant-linux-arm64):
  Google's DeepVariant, rebuilt to run on cheap Arm64 processors.
- [**vastai-gpu-runner**](https://github.com/Lambda-Biolab/vastai-gpu-runner): Scalable structural biology batch GPU orchestration on Vast.ai with robust R2 storage and crash recovery.

**Instrument control and lab automation**

- [**bentolab**](https://github.com/Lambda-Biolab/bentolab): reverse-engineered BLE/Wi-Fi
  protocol for Bento Lab PCR workstations, with async client, FastAPI wrapper, and CLI.
- [**wallac-victor2-api**](https://github.com/Lambda-Biolab/wallac-victor2-api): REST/JSON
  API for a PerkinElmer Victor2 multimode plate reader, driven from Linux.
- [**dpette-usb-driver**](https://github.com/Lambda-Biolab/dpette-usb-driver): open USB
  driver for DLAB dPette electronic pipettes.
- [**i3mega-pipettebot**](https://github.com/Lambda-Biolab/i3mega-pipettebot): an Anycubic
  i3 Mega turned into a sub-$150 disposable-tip pipetting robot (collaboration with [**qte77**](https://github.com/qte77)).

**Structure prediction**

- [**biolab-runners**](https://github.com/Lambda-Biolab/biolab-runners): modular runners for
  Boltz-2 structure prediction and OpenMM MD.

### Code quality, and a note to haters

I don't get the idiotic elitist takes from a lot of developers who block any AI generated code at all. Slop can come from humans too, so it doesn't really matter who produces it. Judge contributions by their **quality**, not whether they are AI-generated. I strive to ship robust, working software that I feel confident my collaborators and I can use. Even if I don't understand how every component works, I have taken the time to validate the **behavior**. Every repository has quality gates designed to catch most obvious defects, unsafe changes, and shallow implementations. For instance:

- `ruff` and `pyright` with tests treated as first-class code
- `pytest` with coverage, plus branch coverage on changed files
- cognitive-complexity limits and mutation testing on changed code
- `bandit`, secret scanning, `actionlint`, `markdownlint`
- actions pinned to commit SHAs

### How to reach me

- Lab and org: [Lambda-Biolab](https://github.com/Lambda-Biolab)
- Consulting: [lambconsulting.bio](https://www.lambconsulting.bio)
- LinkedIn: [in/antoniolamb](https://www.linkedin.com/in/antoniolamb/)
- Email: contact@lambconsulting.bio
