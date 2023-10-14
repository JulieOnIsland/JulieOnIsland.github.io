---
layout: page
title: RSGDream Conference
description: Predicting gene expressions using random promoter sequences
img: assets/img/conference.jpg
importance: 1
category: work
---

We developed a transformer-based model aimed at predicting gene expression utilizing promoter sequence data. Our efforts resulted in securing the third position during the RSGDream Conference in Las Vegas, 2022.

Participating in this conference marked my first experience in such academic gatherings, and I found it thoroughly captivating. Engaging in discussions about our research during coffee breaks, attentively listening to keynote speeches, and comparing our approach with that of fellow researchers were invigorating moments that solidified my passion for academia.


Abstract:

The breakthrough high-throughput measurement of the cis-regulatory activity of millions of randomly generated promoters provides an unprecedented opportunity for us to systematically decode the cis-regulatory logic that determines the expression values. In this DREAM challenge, we developed an end-to-end Transformer encoder architecture (Proformer) to predict the expression values from DNA sequences. Proformer used a Macaron-like Transformer encoder architecture, where two half-step feed forward (FFN) layers were placed at the beginning and the end of each encoder block, and a separable 1D convolution layer was inserted after the first FFN layer and in front of the multi-head attention layer. The sliding k-mers from one-hot encoded sequences were mapped onto a continuous embedding, combined with the learnt positional embedding and strand embedding (forward strand vs reverse complement strand) as the sequence input. Along with the sequence input, we added several positions (32 in our final model) of "pseudo" expression values as the input, where all input expression values were zero's. Proformer predicted one expression value for each "pseudo" expression position and used the mean of the prediction of all positions as the final predicted expression value. We empirically found that this design had significantly better performance than the conventional design such as using the global pooling layer as the output layer for the regression task. We believe that Proformer provides a novel method of learning and characterizing how cis-regulatory sequences determine the expression values.



<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/conference.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    RSGDream 2022, Las Vegas
</div>

Journey : Data processing, Model Experimentation.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/prize.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Secured the third place
</div>


{% raw %}

{% endraw %}