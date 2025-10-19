---
layout: default
twitter_card:
  type: summary_large_image
---

{% include title.html %}

## Overview

Over the past decade, the advent of machine learning and large-scale computing
has immeasurably changed the ways we process, interpret, and predict with data
in imaging and computer vision. The "traditional" approach to algorithm
design, based around parametric models for specific structures of signals and
measurements---say sparse and low-rank models---and the associated optimization
toolkit, is now significantly enriched with data-driven learning-based
techniques, where large-scale networks are pre-trained and then adapted to a
variety of specific tasks. Nevertheless, the successes of both modern
data-driven and classic model-based paradigms rely crucially on correctly
identifying the low-dimensional structures present in real-world data, to the
extent that we see the roles of learning and compression of data processing
algorithms---whether explicit or implicit, as with deep networks---as
inextricably linked.

As such, this tutorial provides a timely tutorial that
uniquely bridges low-dimensional models with deep learning in imaging and
vision. This tutorial will show how:

1. Low-dimensional models and principles provide a valuable lens for
   formulating problems and understanding the behavior of modern deep models in
   imaging and computer vision; and how
2. Ideas from low-dimensional models can provide valuable guidance for
   designing new parameter efficient, robust, and interpretable deep learning
   models for computer vision problems in practice.

We will begin by introducing
fundamental low-dimensional models (e.g., basic sparse and low-rank models)
with motivating computer vision applications.
Based on these developments, we
will discuss strong conceptual, algorithmic, and theoretical connections
between low-dimensional structures and deep models, providing new perspectives
to understand state-of-the-art deep models in terms of learned representations
and generative models.
Finally, we will demonstrate that these
connections can lead to new principles for designing deep networks and learning
low-dimensional structures in computer vision, with both clear interpretability
and practical benefits.
We will conclude with a **panel discussion** with expert researchers from academia
and industry on what role low-dimensional models can and should play in our
current age of generative AI and foundation models for computer
vision.

## Speakers

<div style="clear: both; display: flex; flex-wrap: wrap; justify-content:
  space-evenly; ">

{% assign orgs = site.organizers %}
{% for organizer in orgs %}
{{ organizer }}
{% endfor %}

</div>

## Panelists

<div style="clear: both; display: flex; flex-wrap: wrap; justify-content:
  space-evenly; ">

{% assign pans = site.panelists %}
{% for panelist in pans %}
{{ panelist }}
{% endfor %}

</div>

## Schedule

The tutorial will take place at **ICCV 2025**, on October 19th at the [Hawai'i Convention
Center, Room
324](https://map.concept3d.com/?id=1107#!ce/24709?ct/25427,24748,24747,24709,24708,22261,0?m/231569?s/?sbc/).

<table>
<colgroup>
<col width="69%" />
<col width="17%" />
<col width="14%" />
</colgroup>
<thead>
<tr>
<th>Lecture</th>
<th>Speaker</th>
<th>Time</th>
</tr>
</thead>
<tbody>
<tr>
<td class="title" colspan="3" markdown="span">
**Session I:** Introduction of Basic Low-dimensional Models
</td>
</tr>
<tr>
<td>
Introduction of Basic Low-dimensional Models
<br>
<a class="abstract btn btn-sm z-depth-0" role="button" style="color:#959396;">(Lecture Abstract)</a>
<br>
<div class="abstract hidden">
<p>
The first part will introduce fundamental properties and results for sensing, processing, analyzing, and learning low-dimensional structures from high-dimensional data. We will first discuss classical low-dimensional models, such as sparse coding and low-rank matrix sensing, and motivate these models by applications in computer vision. Based on convex relaxation, we will characterize the conditions, in terms of sample/data complexity, under which the learning problems of recovering such low-dimensional structures become tractable and can be solved efficiently, with guaranteed correctness or accuracy.
</p>
</div>
</td>
<td markdown="span">
  <a href="https://people.eecs.berkeley.edu/~yima/">Yi Ma</a>
</td>
<td markdown="span">
9:00-10:00 am
</td>
</tr>
<tr>
<td class="title" colspan="3" markdown="span">
**Session II:** Understanding Low-Dimensional Structures in Representation Learning
</td>
</tr>
<tr>
<td>
Bridging Symbolic Abstraction and Low-Dimensionality in Machine Reasoning: Algebraic and Geometric Perspectives
<br>
<a class="abstract btn btn-sm z-depth-0" role="button" style="color:#959396;">(Lecture Abstract)</a>
<br>
<div class="abstract hidden">
<p>In this talk, we will reveal the dual process between low-dimensional representations and symbolic abstraction in deep neural networks, emphasizing the essential role of low-dimensional models in machine reasoning. Specifically, we introduce a theoretical framework that explains how “symbols" are represented and learned in deep neural networks through gradient descent in weight space. Our theory shows that dimension reduction occurs spontaneously alongside the emergence of symbolic representations, offering practical guidance for designing interpretable deep networks based on the principle of low-dimensionality.
</p>
</div>
</td>
<td markdown="span">
  <a href="https://vita-group.github.io/">Peihao Wang</a>
</td>
<td markdown="span">
10:00-10:45 am
</td>
</tr>
<tr>
<td>
Emergence of Low-dimensional Representations in Deep Models
<br>
<a class="abstract btn btn-sm z-depth-0" role="button" style="color:#959396;">(Lecture Abstract)</a>
<br>
<div class="abstract hidden">
<p>
The session focuses on the strong conceptual connections between low-dimensional structures and deep models in terms of learned representation. We start with the introduction of an intriguing Neural Collapse phenomenon in the last-layer representation and its universality in deep network, and lay out the mathematical foundations of understanding its cause by studying its optimization landscapes. We demonstrate the practical algorithmic implications of Neural Collapse on training deep neural networks. We then study the hidden representations in generative models, like multimodality large language models (MLLMs) and introduce layerwise compression-expression phenomenon: early layers progressively produce compact and discriminative representations that encode task information from the input demonstrations, while later layers express these representations to incorporate the query and generate the prediction.
</p>
</div>
</td>
<td markdown="span">
  <a href="https://cse.osu.edu/people/zhu.3440">Zhihui Zhu</a>
</td>
<td markdown="span">
11:00 am-12:00 pm
</td>
</tr>
<tr>
<td class="title" colspan="3" markdown="span">
**Session III:** Understanding Low-Dimensional Structures in Diffusion Generative Models
</td>
</tr>
<tr>
<td>
Low-Dimensional Models for Understanding Generalization in Diffusion Models
<br>
<a class="abstract btn btn-sm z-depth-0" role="button" style="color:#959396;">(Lecture Abstract)</a>
<br>
<div class="abstract hidden">
<p>
We will establish a thorough understanding of the generalization of diffusion models by investigating when and why they are capable of learning the low-dimensional structure of target distributions. We will study the sample complexity to learn these low-dimensional distributions and how they scale with the intrinsic dimensionality of data. We will also show how diffusion models transit from memorization to generalization in terms of model capacity and data size.
</p>
</div>
</td>
<td markdown="span">
  <a href="https://qingqu.engin.umich.edu/">Qing Qu</a>
</td>
<td markdown="span">
1:00-2:00 pm
</td>
</tr>
<tr>
<td>
Explore Low-Dimensional Structures for Constrained and Controllable Diffusion Models in Scientific Applications
<br>
<a class="abstract btn btn-sm z-depth-0" role="button" style="color:#959396;">(Lecture Abstract)</a>
<br>
<div class="abstract hidden">
<p>
We will enhance diffusion models for scientific imaging by improving their efficiency, robustness, and controllability in solving general inverse problems. Our approach focuses on latent-space and patch-based models for efficiency, novel techniques for data consistency in reverse sampling—especially for 3D imaging—and controllable sampling to enforce desired constraints while maintaining sample quality.
</p>
</div>
</td>
<td markdown="span">
  <a href="https://liyueshen.engin.umich.edu/">Liyue Shen</a>
</td>
<td markdown="span">
2:00-2:45 pm
</td>
</tr>
<tr>
<td class="title" colspan="3" markdown="span">
**Session IV:** Designing Deep Networks for Pursuing Low-Dimensional Structures
</td>
</tr>
<tr>
<td>
ReduNet: A White-box Deep Network from the Principle of Maximizing Rate Reduction
<br>
<a class="abstract btn btn-sm z-depth-0" role="button" style="color:#959396;">(Lecture Abstract)</a>
<br>
<div class="abstract hidden">
<p>
We focus on learning data distribution and transforming it into a linear discriminative representation (LDR). Using information-theoretic and statistical principles, we design a loss function called coding rate reduction, which is optimized at such a representation. By unrolling gradient ascent on this loss, we construct ReduNet, a deep network where each operator has a mathematically precise, interpretable role in transforming data toward an LDR. Notably, ReduNet can be built layer-wise through forward propagation, eliminating the need for back-propagation.
</p>
</div>
</td>
<td markdown="span">
  <a href="https://people.eecs.berkeley.edu/~yima/">Yi Ma</a>
</td>
<td markdown="span">
3:00-3:45 pm
</td>
</tr>
<tr>
<td>
White-Box Transformers via Sparse Rate Reduction
<br>
<a class="abstract btn btn-sm z-depth-0" role="button" style="color:#959396;">(Lecture Abstract)</a>
<br>
<div class="abstract hidden">
<p>
Finally, we introduce sparse linear discriminative representations by combining sparse coding with rate reduction, optimizing an objective called sparse rate reduction. This leads to CRATE, a deep network derived by unrolling the optimization and parameterizing feature distributions layer-wise. CRATE's operators are mathematically interpretable, with each layer corresponding to an optimization step, making it a white-box model. Despite its distinct design from ReduNet, both share a common goal, highlighting the flexibility of unrolled optimization. Interestingly, CRATE closely resembles transformer architectures, suggesting that such interpretability advances could enhance our understanding of modern deep networks.
</p>
</div>
</td>
<td markdown="span">
  <a href="https://sdbuchanan.com">Sam Buchanan</a>
</td>
<td markdown="span">
3:45-4:30 pm
</td>
</tr>
<tr>
<td class="title" colspan="2" markdown="span">
**Session V:** Panel Discussion (led by Liyue Shen)
</td>
<td markdown="span">
4:45-5:45 pm
</td>
</tr>
</tbody>
</table>

## Materials

Materials for the tutorial will be made available closer to the conference date.

{% include funding_acknowledgements.html %}
