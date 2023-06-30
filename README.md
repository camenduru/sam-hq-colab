🐣 Please follow me for new updates https://twitter.com/camenduru <br />
🔥 Please join our discord server https://discord.gg/k5BwmmvJJU <br />
🥳 Please join my patreon community https://patreon.com/camenduru <br />

## 🦒 Colab

# 🚦 WIP 🚦

| Colab | Info
| --- | --- |
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/camenduru/sam-hq-colab/blob/main/sam_hq_colab.ipynb) | sam_hq_colab

## Tutorial
Usage
You may check the instruction below, or check our github page about more details.

Details
You may select an example image or upload your image to start, we support 4 prompt types:
automatic: Automaticly generate text prompt and the corresponding box input with BLIP and Grounding-DINO.

scribble_point: Click an point on the target instance.

scribble_box: Click on two points, the top-left point and the bottom-right point to represent a bounding box of the target instance.

text: Send text prompt to identify the target instance in the Text prompt box.

We also support a hyper-paramter hq_token_only. False means use hq output to correct SAM output. True means use hq output only. Default: False.

To achieve best visualization effect, for images contain multiple objects (like typical coco images), we suggest to set hq_token_only=False. For images contain single object, we suggest to set hq_token_only = True.

## Main Repo
https://github.com/SysCV/sam-hq <br />
https://huggingface.co/spaces/sam-hq-team/sam-hq/tree/main <br />

## Paper
https://arxiv.org/abs/2306.01567

## Output
![Screenshot 2023-06-30 130347](https://github.com/camenduru/sam-hq-colab/assets/54370274/56424271-02c7-42cd-92b7-deb8ad148d30)