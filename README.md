# DeepSARA
DeepSARA is a project that applies Deep Learning to Southern African Rock Art (SARA).

## Getting started

### Labeler
To start the labelling service, run the following command
```
docker-compose up labeler
```
And then the web front-end will be accessible at `http://localhost:8080`

## Goals

 - Annotate and curate the large dataset of images (labels and bounding boxes).
 - Classify the figures in the artwork as a multi-class multi-label problem (i.e. only output labels).
    - Start off with transfer learning and fine tuning
    - Then try out learning from scratch
    - And possibly self supervised learning?
 - Additionally, approach the task as a multi-class object detection and localisation problem (i.e. output labels and bounding boxes).
 - Create classifiers invariant to orientation (the figures are painted at arbitrary rotations, the reason for which carried significance to the artists).
 - Create classifiers invariant to deterioration (the artwork is thousands of years old and weathered).
 - Apply in-painting techniques to restore deteriorated artworks.

## History

This project is quite personal to me as it is an extension of my Masters research topic and a problem I tackled for almost two years between 2013 and 2014. Given the advances that have been made in Computer Vision as well as the maturity of the tools available in the years since has given me new energy to revisit this topic again. Additionally I think I've grown both as an engineer and (applied) researcher and so I'm curious what results I can come up with this time with my new found powers, I mean skills :P
