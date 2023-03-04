# Large Scale Video Categorisation Research

Initial research into videos and compression types for thesis

----

Intitial plan:

- create notebook/script which downloads UCF101 data to gcp storage
    - should only be 20p a month per GB
    - store video index list in BigQuery
    - how to https://stackoverflow.com/questions/51111611/using-google-cloud-storage-files-with-jupyter-notebook-on-cloud-compute
- create notebook/script which converts videos to feature frame format (chops oit certain number of frames per video)
- create notebook which utilises transfer learning to train imagenet on this frame level data
- create a notebook which creates some sort of model which utilises the whole data set