# TorchFly

TorchFly is a PyTorch Fast Development Kit. The purpose is to learn the pipelines of the SOTA algorithms in Deep Learning areas like CV, NLP and RL. The utilities provided in this kit will shorten the time needed to rebuild some basic functions. Now, the kit is mainly for personal use, but will be updated from time to time. 

## Installation

### Installing via pip:
Installing is simple using `pip`.

   ```bash
   pip install torchfly
   ```
   
### Installing from source
You can clone the repository.
    ```bash
    git clone https://github.com/qywu/TorchFly.git
    ```

### Docker
It is recommended to run on Nvidia Docker for better performance.

    ```bash
    FROM nvcr.io/nvidia/pytorch:18.12.1-py3
    RUN apt-get update
    
    RUN pip install torchfly
    ```
 
 ## TODOS
 
 Lots of todos.
 
 ## Code References
 
 [FastAI](https://github.com/fastai)
 
 [AllenNLP](https://github.com/allenai/allennlp/)
