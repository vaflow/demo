---
layout: default
title: LoVA
---

<div class="post">
	<h2 class="pageTitle">LoVA:</h2>
	<h2 class="pageTitle">Long-Form Video-to-Audio Generation</h2>
    <p align="center">
	<img src="{{ '/assets/img/arch_LoVA.png' | relative_url }}" alt="">
    </p>
	<p>Video-to-audio (V2A) generation is important for video editing and post-processing, enabling the creation of semantics-aligned audio for silent video. However, most existing methods focus on generating short-form audio for short video segment (less than 10 seconds), while giving little attention to the scenario of long-form video inputs. For current UNet-based diffusion V2A models, an inevitable problem when handling long-form audio generation is the inconsistencies within the final concatenated audio. In this paper, we first highlight the importance of long-form V2A problem. Besides, we propose LoVA, a novel model for Long-form Video-to-Audio generation. Based on the Diffusion Transformer (DiT) architecture, LoVA proves to be more effective at generating long-form audio compared to existing autoregressive models and UNet-based diffusion models.
	<br>Extensive objective and subjective experiments demonstrate that LoVA achieves comparable performance on 10-second V2A benchmark and outperforms all other baselines on a benchmark with long-form video input.</p>

</div>
