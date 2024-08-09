  # Project Title

One-Shot Power Line Localization for Live-Line Robots with LEO-DCE and MSIO-SAM .


## Introduction
We introduces a novel approach combining the Lightweight Encoder-Only DCE (LEO-DCE) for low-light enhancement and the Multi-Scale Interactive Object Segmentation with SAM (MSIO-SAM) for precise power line segmentation and localization. LEO-DCE, a state-of-the-art low-light enhancement network with only 2.7k parameters and a processing speed of 1000 fps on 2k images, addresses sunlight interference by significantly improving the visibility of power lines. MSIO-SAM, building on the large-data Segment Anything Model (SAM), incorporates multi-scale similarity analysis and iterative optimization to achieve optimal performance across multiple dimensions, including IoU and False Negative Rate (FNR).

## low-light images enhancement

<div align="center">
  <img src="Figs/LEO-DCE.jpg"/ width="97%"> <br>
</div>

## msio-SAM

<div align="center">
  <img src="Figs/MSIO-SAM.jpg"/ width="97%"> <br>
</div>
