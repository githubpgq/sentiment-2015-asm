# Diving Deep into Sentiment: Understanding Fine-tuned CNNs for Visual Sentiment Prediction


| ![Víctor Campos][VictorCampos-photo]  | ![Amaia Salvador][AmaiaSalvador-photo]  |  ![Xavier Giro-i-Nieto][XavierGiro-photo]  | ![Brendan Jou][BrendanJou-photo] |
|:-:|:-:|:-:|:-:|
| Víctor Campos | [Amaia Salvador](https://imatge.upc.edu/web/people/amaia-salvador) |   [Xavier Giro-i-Nieto](https://imatge.upc.edu/web/people/xavier-giro)   | [Brendan Jou](http://www.ee.columbia.edu/~bjou/) |


[VictorCampos-photo]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/authors/VictorCampos.jpg "Víctor Campos"
[AmaiaSalvador-photo]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/authors/AmaiaSalvador.jpg "Amaia Salvador"
[XavierGiro-photo]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/authors/XavierGiro.jpg "Xavier Giro-i-Nieto"
[BrendanJou-photo]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/authors/BrendanJou.png "Brendan Jou"



A joint collaboration between:

|  ![logo-upc] | ![logo-etsetb] | ![logo-gpi] | ![logo-columbia] | ![logo-dvmmlab] |
|:-:|:-:|:-:|:-:|:-:|
| [Universitat Politecnica de Catalunya (UPC)](http://www.upc.edu/?set_language=en)   | [UPC ETSETB TelecomBCN](https://www.etsetb.upc.edu/en/)  | [UPC Image Processing Group](https://imatge.upc.edu/web/) | [Columbia University](https://www.columbia.edu/ ) | [Digital Video and Multimedia Lab (DVMM)](www.ee.columbia.edu/dvmm)  |

[logo-upc]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/logos/upc.jpg "Universitat Politècnica de Catalunya"
[logo-etsetb]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/logos/etsetb.png "ETSETB TelecomBCN"
[logo-gpi]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/logos/gpi.png "UPC Image Processing Group"
[logo-columbia]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/logos/columbia.png "Columbia University"
[logo-dvmmlab]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/logos/dvmm.gif "Digital Video and Multimedia Lab"


## Abstract
Visual media are powerful means of expressing emotions and sentiments. The constant generation of new content in social networks highlights the need of automated visual sentiment analysis tools. While Convolutional Neural Networks (CNNs) have established a new state-of-the-art in several vision problems, their application to the task of sentiment analysis is mostly unexplored and there are few studies regarding how to design CNNs for this purpose. In this work, we study the suitability of fine-tuning a CNN for visual sentiment prediction as well as explore performance boosting techniques within this deep learning setting. Finally, we provide a deep-dive analysis into a benchmark, state-of-the-art network architecture to gain insight about how to design patterns for CNNs on the task of visual sentiment prediction.


## Publication

Please cite with the following Bibtex code:

```
@inproceedings{campos2015diving,
  title={Diving Deep into Sentiment: Understanding Fine-tuned CNNs for Visual Sentiment Prediction},
  author={Campos, Victor and Salvador, Amaia and Giro-i-Nieto, Xavier and Jou, Brendan},
  booktitle={Proceedings of the 1st International Workshop on Affect \& Sentiment in Multimedia},
  pages={57--62},
  year={2015},
  organization={ACM}
}
```

You may also want to refer to our publication with the more human-friendly APA style:

*Campos, V., Salvador, A., Giro-i-Nieto, X., & Jou, B. (2015, October). [Diving Deep into Sentiment: Understanding Fine-tuned CNNs for Visual Sentiment Prediction](http://dl.acm.org/citation.cfm?id=2813530). In Proceedings of the 1st International Workshop on Affect & Sentiment in Multimedia (pp. 57-62). ACM.*

A [preprint](http://arxiv.org/abs/1508.05056) of the paper is publicly available on arXiv.
More details can be found in [our slides](http://www.slideshare.net/xavigiro/diving-deep-into-sentiment-understanding-finetuned-cnns-for-visual-sentiment-prediction) at ASM 2015, and the related [bachelor thesis report and video](https://imatge.upc.edu/web/publications/layer-wise-cnn-surgery-visual-sentiment-prediction) by Victor Campos at ETSETB TelecomBCN in July 2015.

## Slides

<iframe src="//www.slideshare.net/slideshow/embed_code/key/83vW3d0dYwJkSv" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/xavigiro/diving-deep-into-sentiment-understanding-finetuned-cnns-for-visual-sentiment-prediction" title="Diving deep into sentiment: Understanding fine-tuned CNNs for visual sentiment prediction" target="_blank">Diving deep into sentiment: Understanding fine-tuned CNNs for visual sentiment prediction</a> </strong> from <strong><a target="_blank" href="//www.slideshare.net/xavigiro">Xavier Giro</a></strong> </div>

## Models

The weights for the best CNN model can be downloaded from [here](https://imatge.upc.edu/web/sites/default/files/projects/affective/public_html/2015-asm/twitter_finetuned_test4_iter_180.caffemodel) (217 MB).

The deep network was developed over [Caffe](http://caffe.berkeleyvision.org/) by [Berkeley Vision and Learning Center (BVLC)](http://bvlc.eecs.berkeley.edu/). You will need to follow [these instructions](http://caffe.berkeleyvision.org/installation.html) to install Caffe.


## Acknowledgments

We would like to especially thank Albert Gil Moreno and Josep Pujal from our technical support team at the Image Processing Group at  UPC.

| ![AlbertGil-photo]  | ![JosepPujal-photo]  |
|:-:|:-:|
| [Albert Gil](https://imatge.upc.edu/web/people/albert-gil-moreno)  |  [Josep Pujal](https://imatge.upc.edu/web/people/josep-pujal) |

[AlbertGil-photo]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/authors/AlbertGil.jpg "Albert Gil"
[JosepPujal-photo]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/authors/JosepPujal.jpg "Josep Pujal"

|   |   |
|:--|:-:|
|  We gratefully acknowledge the support of [NVIDIA Corporation](http://www.nvidia.com/content/global/global.php) with the donation of the GeForce GTX [Titan Z](http://www.nvidia.com/gtx-700-graphics-cards/gtx-titan-z/) and [Titan X](http://www.geforce.com/hardware/desktop-gpus/geforce-gtx-titan-x) used in this work. |  ![logo-nvidia] |
|  The Image Processing Group at the UPC is a [SGR14 Consolidated Research Group](https://imatge.upc.edu/web/projects/sgr14-image-and-video-processing-group) recognized and sponsored by the Catalan Government (Generalitat de Catalunya) through its [AGAUR](http://agaur.gencat.cat/en/inici/index.html) office. |  ![logo-catalonia] |
|  This work has been developed in the framework of the project [BigGraph TEC2013-43935-R](https://imatge.upc.edu/web/projects/biggraph-heterogeneous-information-and-graph-signal-processing-big-data-era-application), funded by the Spanish Ministerio de Economía y Competitividad and the European Regional Development Fund (ERDF).  | ![logo-spain] | 

[logo-nvidia]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/logos/nvidia.jpg "Logo of NVidia"
[logo-catalonia]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/logos/generalitat.jpg "Logo of Catalan government"
[logo-spain]: https://raw.githubusercontent.com/imatge-upc/sentiment-2015-asm/master/figures/logos/MEyC.png "Logo of Spanish government"



## Contact

If you have any general doubt about our work or code which may be of interest for other researchers, please use the [public issues section](https://github.com/imatge-upc/sentiment-2015-asm/issues) on this github repo. Alternatively, drop us an e-mail at <mailto:xavier.giro@upc.edu>.
