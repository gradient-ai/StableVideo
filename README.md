# StableVideo

Official implementation of StableVideo: Text-driven Consistency-aware Diffusion Video Editing.

    Diffusion-based methods can generate realistic images and videos, but they struggle to edit existing objects in a video while preserving their geometry over time. This prevents diffusion models from being applied to natural video editing. In this paper, we tackle this problem by introducing temporal dependency to existing text-driven diffusion models, which allows them to generate consistent appearance for the new objects. Specifically, we develop a novel inter-frame propagation mechanism for diffusion video editing, which leverages the concept of layered representations to propagate the geometry and appearance information from one frame to the next. We then build up a text-driven video editing framework based on this mechanism, namely StableVideo, which can achieve consistency-aware video editing. Extensive qualitative experiments demonstrate the strong editing capability of our approach. Compared with state-of-the-art video editing methods, our approach shows superior qualitative and quantitative results.

This implementation is built partly on [Text2LIVE](https://github.com/omerbt/Text2LIVE) and [ControlNet](https://github.com/lllyasviel/ControlNet).

## Getting Started

### Installation
```
git clone https://github.com/rese1f/StableVideo.git
conda env create -f environment.yaml
```

### Download sample videos
```
TODO
```
It will create a folder data:
```
StableVideo
├── ...
├── data
│   ├── car-turn
│       ├── checkpoint # NLA models are stored here
│       ├── car-turn # contains video frames
│       ├── ...
│   ├── blackswan
│   ├── ...
└── ...
```

### Download Pretrained Model

All models and detectors can be downloaded from ControlNet Hugging Face page. [Download Link](https://huggingface.co/lllyasviel/ControlNet)

## Sample Results

## Citation