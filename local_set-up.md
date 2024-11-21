# Local Set-Up

Install the following applications:

- VsCode: https://code.visualstudio.com/
- MicroMamba: https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html

After installing mamba, and adding it to the PATH, create a new conda environment with the following command:

```bash
conda create -n llmops python=3.11
```

After having the the environment created, activate it with the following command:

```bash
conda activate llmops
```

install the dependencies with the following command:

```bash
pip install -r requirements.txt
```

I suggest to install the following extensions in VsCode:

- Supermaven: https://supermaven.com/
- Continue: https://www.continue.dev/

If you can pay, use github copilot.

Recommended Free APIs for LLMs:

- Groq: https://console.groq.com/
- Cerebras: https://cerebras.ai/
- GLHF: https://glhf.chat/
