# largescale-video-categoriation

## Intro

This repo contains starter code for training and evaluating machine learning models for video categorisation utilising the [YouTube-8M](https://research.google.com/youtube8m/) dataset. 

### Download Dataset Locally

Please see our
[dataset website](https://research.google.com/youtube8m/download.html) for
up-to-date download instructions.

In this document, we assume you download all the frame-level feature dataset to
`~/yt8m/2/frame` and segment-level validation/test dataset to `~/yt8m/3/frame`.
So the structure should look like

```
~/yt8m/
 - ~/yt8m/2/frame/
   - ~/yt8m/2/frame/train
 - ~/yt8m/3/frame/
   - ~/yt8m/3/frame/test
   - ~/yt8m/3/frame/validate
```