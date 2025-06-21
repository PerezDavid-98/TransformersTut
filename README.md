# Transformers Tutorial

This is a repository following the tutorial by Umar Jamil on [YouTube](https://www.youtube.com/watch?v=ISNdQcPhsts&ab_channel=UmarJamil).

I changed the languages to use Spanish instead of Italian for the translation task.
I also added some type annotation in some of the classes and functions to make them more understandable.

The model was trained and used to inference using an NVIDIA 4070 with 12GBs of VRAM, so some changes had to be made to be able to run the model without running out of memory and in a reasonable time. 
Only a 10% of the original dataset was used for this reason.

The project was developed inside a DevContainer using Docker and VisualStudio Code. The `.devcontainer` folder contains the `devcontainer.json` file, so opening the project with VSCode should prompt to reopen in container and build the container. (I used Docker Desktop to provide the Docker engine) 
The image used was an NVIDIA image with Pytorch with GPU support. (It is a heavy image ~29 GBs so enough disk space is needed if used on a personal computer).

The weights were not added to the repo because they are several GBs each.

## Motivation
After reading the paper where Transformers were introduced: [Attention Is All You Need](https://arxiv.org/abs/1706.03762), I wanted to improve my understanding of the Transformer architecture by 
building one from scratch, Umar's video was very helpful and helped me understand the Transformer better.

