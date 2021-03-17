<p align="center" style="font-size:24px">
<a href="https://tobyperrett.github.io/">Toby Perrett</a>, <a href="https://www.alessandromasullo.com/">Alessandro Masullo</a>, <a href="http://people.cs.bris.ac.uk/~burghard/">Tilo Burghardt</a>, <a href="http://people.cs.bris.ac.uk/~majid/">Majid Mirmehdi</a> and <a href="https://dimadamen.github.io/">Dima Damen</a>
</p>

<p align="center">
<img src="vis10.jpg" width="400">
</p>


## Abstract

We propose a novel approach to few-shot action recognition, finding temporally-corresponding frame tuples between the query and videos in the support set. Distinct from previous few-shot works, we construct class prototypes using the CrossTransformer attention mechanism to observe relevant sub-sequences of all support videos, rather than using class averages or single best matches. Video representations are formed from ordered tuples of varying numbers of frames, which allows sub-sequences of actions at different speeds and temporal offsets to be compared.

Our proposed Temporal-Relational CrossTransformers~(TRX) achieve state-of-the-art results on few-shot splits of Kinetics, Something-Something V2 (SSv2), HMDB51 and UCF101.  Importantly, our method outperforms prior work on SSv2 by a wide margin (12%) due to the its ability to model temporal relations. A detailed ablation showcases the importance of matching to multiple support set videos and learning higher-order relational CrossTransformers.



## Paper

[PDF](main.pdf)

[ArXiv](https://arxiv.org/abs/2101.06184)

## Code

[GitHub](https://github.com/tobyperrett/trx)

## Bibtex

```markdown
@InProceedings{perrett21trx,
    author    = {Perrett, Toby and Masullo, Alessandro and Burghardt, Tilo and Mirmehdi, Majid and Damen, Dima},
    title     = {Temporal-Relational CrossTransformers for Few-Shot Action Recognition},
    booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
    year      = {2021}
}
```

## Acknowledgements
This research is supported by EPSRC SPHERE Next Steps (EP/R005273/1). Damen is supported by EPSRC Fellowship UMPIRE~(EP/T004991/1).
