# ReCCoVER: Recognizing Causal Confusion for Explainable Reinforcement Learning


Code accompanying our paper [ReCCoVER: Detecting Causal Confusion for Explainable RL](https://arxiv.org/abs/2203.11211).

## Installation 

Necessary packages can be installed directly from the requirements.txt file:

```{bash}
pip install -r requirements.txt
```


## Running the code

ReCCoVER has been evaluated in two environments: [OpenAI taxi environment](https://www.gymlibrary.ml/environments/toy_text/taxi/) and [Minigrid traffic environment](https://github.com/maximecb/gym-minigrid). 

To train and evaluate ReCCoVER in the taxi environment:

```{bash}
python main.py --task taxi --train
```

To train and evaluate ReCCoVER in the minigrid traffic environment:

```{bash}
python main.py --task traffic --train
```
