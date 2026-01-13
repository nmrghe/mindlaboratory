---
title: Research
nav:
  order: 1
---

# {% include icon.html icon="fa-solid fa-microscope" %}Research

The focus of the M!ND Lab is to advance knowledge on a specific, yet multifaceted question: **what is so special about the brain, down at the neuronal level, that endows us and other animals with the capacity to abstract away from our environment, think and plan ahead?** Said differently, how do populations of interconnected neurons generate intelligent, thoughtful behavior? While there are many paths towards addressing this issue, we firmly believe that a potentially fruitful approach and a satisfying answer to this question is to be found in the establishment of mathematical mappings between, on the one hand, neural activity and on the other, behaviorally-relevant variables used by the brain to perform complex computations. The main goal of the lab, therefore, is to search for such mappings in relation to various high-level cognitive processes, including but not limited to motor planning, introspection, anticipation, mental simulation, problem-solving, and learning. 

Further, we think that for such mappings to be useful, they ought to fulfill the 3 properties below: 

1. Be predictive: neuroscience is notoriously correlational [Jazayeri and Afraz], and is bound to remain so until further conceptual and/or technological breakthroughs occur. While our lab does not aspire to directly contribute to these methodological advances, our approach is to develop models that go beyond simple correlations and are instead quantitative enough to make accurate predictions about the exact relationship between neural signals and behavioral variables of interest. In other words, we trade causation for prediction, until better tools become available. Examples of previous attempts at finding such predictive mappings can be found here: [Meirhaeghe 2021, 2023].  

2. Be generalizable: we are not interested in overfitting data to develop models that won’t be usable by others. Instead, we seek an understanding that ideally does not depend on the particular task or individual at hand, and can generalize to new settings and experiments [Beiran et al]. Naturally, failure to generalize becomes inevitable at some point, so we actively look for these breaking points and use them to refine or even completely revisit our underlying hypotheses. With this approach, we constantly evaluate our work in light of how much new data is required to refute our current model.   

3. Be interpretable: this last property is perhaps the most difficult to fulfil, but we (try to) restrict our search to models that involve tractable and “intuitive” operations. In practice, it means for example that we avoid the traditional “decoding approach” using black-box models or giant GLMs to predict behavioral variables from neural activity. Instead, we try to guess the underlying logic by which those variables might be encoded in the first place, and build decoders accordingly. The virtue of this approach is that interpretability often makes it easier to design tests of generalizability, and boosts the creative process of generating ideas for the next round of experiments. 

Lastly, we complement our empirical approach with theoretical considerations that pushes us to formulate novel predictions based on our current understanding, and move forward using “prediction errors” to update our hypotheses and design new experiments. 

{% include section.html %}

## Highlighted

{% include citation.html lookup="Open collaborative writing with Manubot" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
