[![LinkedIn][linkedin-shield]][linkedin-url]
# Deep_Music_Generator
I implemented a deep neural network for music generation integrating a variational auto-encoder approach with transformers. Starting from a first idea of the architecture and a first dataset, I tried to emulate the current state of the art models. I gave importance to the comparison of different models trained on different datasets with the aim to understand if one genre or one instrument could generalize in a good way also the other genres and instruments. At the end of the experiment, I noticed how regularization techniques and the amount of available data could impact the results. In the end, good results were achieved. However they are not comparable with the state of artresults.

More information about regarding the project can be found in the [report](https://github.com/GiovanniSorice/Deep_Music_Generator/blob/main/report/report.pdf) and in the [slides](https://github.com/GiovanniSorice/Deep_Music_Generator/blob/main/slide/ISPR-Slide.pdf) .

## Usage

### Running the project
Take a look at the Music_Generation_Transformer.ipynb notebook. You need a discrete number of midi files to achieve good training results.

## Results
Here we show some plots we obtained during the optimization phase. 
 
<img src="/report/img/Plot/full/plot_full_64_0_drop.png" width="350"><img src="/report/img/Plot/full/plot_full_64_0.1_drop.png" width="350">

<img src="/report/img/Plot/piano/plot_piano_64_0_drop.png" width="350"><img src="/report/img/Plot/piano/plot_piano_64_0.1_drop.png" width="350">

<img src="/report/img/Plot/pop_rock/plot_pop_rock_64_0_drop.png" width="350"><img src="/report/img/Plot/pop_rock/plot_pop_rock_64_0.1_drop.png" width="350">

## Acknowledgments
This project was developed for the course of [Intelligent Systems for Pattern Recognition](https://esami.unipi.it/esami2/programma.php?c=42278&aa=2019&docente=BACCIU&insegnamento=&sd=0) at the University of Pisa under the guide of [Prof. Davide Bacciu](http://pages.di.unipi.it/bacciu/).

## Authors
* **Giovanni Sorice**  - [Giovanni Sorice](https://github.com/GiovanniSorice)

### References

1. Colin Raffel.  ["Learning-Based Methods for Comparing Sequences, with Applications to Audio-to-MIDI Alignment and Matching"](http://colinraffel.com/publications/thesis.pdf). PhD Thesis, 2016.

1. Phil Wang.  ["compressive-transformer-pytorch"](https://github.com/lucidrains/compressive-transformer-pytorch). GitHub repo.


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/giovanni-sorice/
