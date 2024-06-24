---
layout: about
title: about
permalink: /
subtitle: <a href='https://www.usc.edu/'>University of Southern California</a> •  <a href='https://www.cs.usc.edu/'>Viterbi CS</a> •  <a href='https://nlp.usc.edu/'>USC NLP</a>

profile:
  align: right
  image: dill-canva-transp.png
  image_circular: false # crops the image to make it circular
  more_info:

news: true # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page
---

The _**D**ata_, _**I**nterpretability_, _**L**anguage_ and _**L**earning_, (**DILL**) lab, led by [Swabha Swayamdipta](https://swabhs.com), explores questions at the intersection of language models, NLP and machine learning.

<span class="emphasized">Check out our [latest publications](/publications/) and [open positions](/opportunities).</span>

Here are some questions we have worked on recently:

- What do we understand about the geometries of language models?
  : Has language model generation reached a performance saturation or do language models still make systematic errors owing to their design? We studied the [softmax bottleneck](https://arxiv.org/abs/2310.01693) as one concrete limitation and how that affects language generation and justifies truncation sampling. Can we build better language generators? The softmax bottleneck also leads [logits leaking information in closed LLM APIs](https://arxiv.org/abs/2403.09539).

- What are the limits of the generative capabilities of LLMs?
  : How do language models handle specific distributions of language, such as [ambiguous language](https://arxiv.org/abs/2304.14399), [comparative language](https://arxiv.org/abs/2305.04978) or the language of [explanations](https://arxiv.org/abs/2112.08674)? Can language models generate [structured data](https://arxiv.org/abs/2406.04834)?

- How reliable is comparative generative evaluation?
  : What cannot be measured, cannot be improved. Can we [reliably compare the generative performance](/publications) of two different models, in either close-ended generation tasks such as summarization or in open-ended generation? What makes model A better than model B, or are our test sets somewhat misleading us?

- What does our data tell us about our models?
  : What makes a data collection valuable for instruction tuning or finetuning large language models? Is all human feedback equally valuable under PPO or DPO? Our [Dataset Cartography](https://arxiv.org/abs/2009.10795) offers point estimates, and [V-Information](https://arxiv.org/abs/2110.08420) offers both point and aggregate estimates of data quality. How can we build similar estimates for generative models? Are all modalities and all data necessary in [multimodal settings](https://arxiv.org/abs/2309.09405)?

- How can our models help us understand our society?
  : How far can language models go in helping us understand [complex social phenomena such as homelessness](https://dill-lab.github.io/oath-frames/)? Is it possible to create [collaborative setups between humans and generative models](https://arxiv.org/abs/2201.05955) to this end? What role does [conversational and social context](https://arxiv.org/abs/2306.01985) play in this understanding? Can socio-technical solutions [work well for all](https://arxiv.org/abs/2111.07997)?


<!-- How can we make our [models explain their decisions](https://arxiv.org/abs/2112.08674) to human users, [_intuitively_](https://arxiv.org/abs/2103.01378)? Moreover, as tasks previously considered extremely difficult are getting easier, how do we best [adapt our evaluation methods](https://arxiv.org/abs/2102.01454) to ensure fair evaluation? -->
<!-- Can we use the lessons above to create high quality datasets, more suitable for modern NLP models? Our work on [Generative Data Augmentation](https://arxiv.org/abs/2004.11546) showed that this is possible to automate to some extent, either via [controlled generation](https://arxiv.org/abs/2105.03023) or [selection](https://arxiv.org/abs/2004.10964). -->
<!-- Current large scale models tend to [rely on spurious biases to make the correct predictions](https://arxiv.org/abs/1803.02324). The reduction of undesirable biases could be done via data selection, as in [AFLite](https://arxiv.org/abs/2002.04108) or by altering the [learning objectives](https://arxiv.org/abs/1909.03683). However, the discovery of such biases is much trickier and task-dependent.
Going beyond solutions presented in [AFLite](https://arxiv.org/abs/2002.04108), how can we find spurious correlations automatically? -->
<!--
Particularly harmful are social biases in models, such as those which correlate surface markers of certain dialects with subjective attributes such as toxicity. [Social biases cannot be mitigated easily](https://arxiv.org/abs/2102.00086) and require rethinking data collection and task design, as we show in our [latest paper](https://arxiv.org/abs/2111.07997). -->
<!-- DILL is focused on automatically estimating the quality of datasets for models, efficient pretraining, and semi-automatically building datasets that help models learn better. We also emphasize on special aspects of language that affect dataset quality, such as subjectivity and ambiguity. -->
<!-- - How can we rigorously evaluate the generative capabilities of language models?
- Do language models have the ability to generate text with specific properties and what does that reveal about them?
- What roles do different kinds of data play in the successes or failures of language models?
- How can we use language models to understand our society better? -->