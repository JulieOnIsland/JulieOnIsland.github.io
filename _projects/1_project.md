---
layout: page
title: RSGDream Conference
description: Predicting gene expressions using random promoter sequences
img: assets/img/conference.jpg
importance: 1
category: work
---

**Our paper has been published in BMC Bioinformatics!** <a href="https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-024-05645-5">[paper]</a>

We developed a transformer-based model aimed at predicting gene expression utilizing promoter sequence data. Our efforts resulted in securing the third position during the RSGDream Conference in Las Vegas, 2022. <a href="https://github.com/gongx030/dream_PGE">[code]</a>

Participating in this conference marked my first experience in such academic gatherings, and I found it thoroughly captivating. Engaging in discussions about our research during coffee breaks, listening to keynote speeches, and comparing our approach with that of fellow researchers were invigorating moments that solidified my passion for academia.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/conference.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    RSGDream 2022, Las Vegas
</div>

We commenced with data preprocessing. I identified the repetition of specific segments at the start and end of DNA sequences. Removing these repetitions led to a 5% performance improvement. Our approach began with experimenting with N-gram models, followed by exploring RNN, LSTM, GRU, and transformer-based models. Subsequently, we delved into efficient models for DNA sequence analysis. To mitigate variance, we adopted the masking technique from BERT models. While abundant embeddings are available for language tasks, the same does not hold for DNA sequence data. Consequently, we needed to construct embeddings from scratch.
    

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/prize.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Secured the third place
</div>

    A small insight unfolded: the essence of theoretical understanding 
    as well as the art of practical execution holds equal importance.

{% raw %}

{% endraw %}