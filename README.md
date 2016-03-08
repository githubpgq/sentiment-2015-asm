# Diving Deep into Sentiment: Understanding Fine-tuned CNNs for Visual Sentiment Prediction


| ![Víctor Campos][VictorCampos-photo]  | ![Amaia Salvador][AmaiaSalvador-photo]  | ![Brendan Jou][BrendanJou-photo] | ![Xavier Giro-i-Nieto][XavierGiro-photo]  |
|:-:|:-:|:-:|:-:|:-:|
| Víctor Campos | [Amaia Salvador](https://imatge.upc.edu/web/people/amaia-salvador) |  [Brendan Jou](Brendan Jou-web) | [Xavier Giro-i-Nieto](XavierGiro-web)   |

(*) Equal contribution

[AmaiaSalvador-web]: https://imatge.upc.edu/web/people/amaia-salvador
[BrendanJou-web]: http://www.ee.columbia.edu/~bjou/
[XavierGiro-web]: https://imatge.upc.edu/web/people/xavier-giro

[VictorCampos-photo]: ./figures/authors/VictorCampos.jpg "Víctor Campos"
[AmaiaSalvador-photo]: ./figures/authors/AmaiaSalvador.jpg "Amaia Salvador"
[BrendanJou-photo]: ./figures/authors/BrendanJou.png "Brendan Jou"
[XavierGiro-photo]: ./figures/authors/XavierGiro.jpg "Xavier Giro-i-Nieto"



## Abstract
Visual media are powerful means of expressing emotions and sentiments. The constant generation of new content in social networks highlights the need of automated visual sentiment analysis tools. While Convolutional Neural Networks (CNNs) have established a new state-of-the-art in several vision problems, their application to the task of sentiment analysis is mostly unexplored and there are few studies regarding how to design CNNs for this purpose. In this work, we study the suitability of fine-tuning a CNN for visual sentiment prediction as well as explore performance boosting techniques within this deep learning setting. Finally, we provide a deep-dive analysis into a benchmark, state-of-the-art network architecture to gain insight about how to design patterns for CNNs on the task of visual sentiment prediction.


## Publication

Please cite with the following Bibtex code:

````
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

*Campos, V., Salvador, A., Giro-i-Nieto, X., & Jou, B. (2015, October). Diving Deep into Sentiment: Understanding Fine-tuned CNNs for Visual Sentiment Prediction. In Proceedings of the 1st International Workshop on Affect & Sentiment in Multimedia (pp. 57-62). ACM.*



## Models

(Link to the .caffemodel file)


### Deep Network on Caffe

The deep network was developed over [Caffe](http://caffe.berkeleyvision.org/) by [Berkeley Vision and Learning Center (BVLC)](http://bvlc.eecs.berkeley.edu/). You will need to follow [these instructions](http://caffe.berkeleyvision.org/installation.html) to install Caffe.


## Acknowledgements

We would like to especially thank Albert Gil Moreno and Josep Pujal from our technical support team at the Image Processing Group at the UPC.



## Contact

If you have any general doubt about our work or code which may be of interest for other researchers, please use the [public issues section](https://github.com/imatge-upc/sentiment-2015-asm/issues) on this github repo. Alternatively, drop us an e-mail at <mailto:xavier.giro@upc.edu>.


<!---
Javascript code to enable Google Analytics
-->

<script>

  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-7678045-3', 'auto');
  ga('send', 'pageview');

</script>