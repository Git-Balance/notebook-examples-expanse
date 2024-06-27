## Overview
- run local: partial
- progress: ran locally
- todo: test on Expanse
## Review
I was able to run [hello_world_cpu.ipynb](./hello_world_cpu.ipynb) locally with no problems

I was able to run most of [hello_world_gpu.ipynb](./hello_world_gpu.ipynb) locally with no problems. However, the code cell that tests if a GPU is present (`!nvidia-smi`) does not work if your local device has no GPU. Since my laptop has no nvidia GPU, I was not able to test if the notebook runs with a GPU. This is the expected outcome for a computer with no GPU
## Changes
- fixed minor spelling mistake in README.md
- removed empty cells in notebooks
- removed unneeded newlines in notebooks