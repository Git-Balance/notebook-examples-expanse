## Overview
- run local: partial
- progress: ran locally
- todo: test on Expanse
## Review
I was able to run [hello_world_cpu.ipynb](./hello_world_cpu.ipynb) locally with no problems

I was able to run most of [hello_world_gpu.ipynb](./hello_world_gpu.ipynb) locally with no problems. However, the code cell that tests if a GPU is present (`!nvidia-smi`) does not work if your local device has no GPU. Since my laptop has no nvidia GPU, I was not able to test if the notebook runs with a GPU. This is the expected outcome for a computer with no GPU

Both of the notebooks are separated into two distinct sections, basic python tests and hardware tests. Adding headers will help users navagate the notebooks easier and make it more clear what each section does. Currently the headers are `Test Python` and `Test Hardware`. The names of these headers are not final
## Changes
- fixed minor spelling mistake in README.md
- removed empty cells in notebooks
- removed unneeded newlines in notebooks
- added headers to notebooks
- changed final python cell in GPU notebook to a markdown cell, since it only contained comments

**Note**: listing all the changes inside of a NOTES.md file takes a lot of time and is redundent because of `git diff`, so other NOTES.md files will not have a changes sections