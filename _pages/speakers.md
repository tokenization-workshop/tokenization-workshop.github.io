---
layout: page
permalink: /speakers/
title: Speakers
nav: true
nav_order: 2
---

## Keynote Speakers

Friday, October 9, 2026. All times are in San Francisco local time (PDT, UTC-7).

<div class="keynote-container">
  <section class="keynote-speaker" id="tiago-pimentel">
    <img src="{{ '/assets/img/speakers/tiago-pimentel.jpeg' | relative_url }}" alt="Tiago Pimentel" width="150" height="150">
    <div class="keynote-details">
      <h3><a href="https://tpimentelms.github.io/">Tiago Pimentel</a></h3>
      <p>ETH Z&uuml;rich</p>
      <p><strong>9:10 a.m. - 10:00 a.m.</strong><br>
      <em>How much does tokenisation impact language models?</em></p>
      <p class="abstract"><strong>Abstract:</strong>
        Tokenisers are the foundation on which most modern language models are built, transforming raw, human-readable text—sequences of characters—into the sequences of tokens our models actually process. Despite this central role, much about tokenisation remains poorly understood. In this talk, I will present recent results that begin to close this gap. I will first discuss how distributions over characters or words can be correctly recovered from language models, which natively assign probabilities to token sequences. This analysis reveals that, in theory, tokenisation should not matter: a perfectly optimised language model would yield the same character- and word-level distributions regardless of its tokeniser. In practice, however, I will show that tokenisation choices do change these distributions and that, indeed, tokenisers have a substantial impact on language models' outputs. Given this impact, we should choose our tokenisers well—ideally, optimally. However, I will show that the problem of obtaining (compression-)optimal tokenisers is NP-complete, justifying the widespread use of heuristic algorithms for their selection. I will then analyse what makes these heuristics more or less effective, and how they can be improved. Finally, I will close the talk with tokenisation's role in multilingual language modelling, showing that a tokeniser can reveal a text's language.
      </p>
      <p>Tiago Pimentel is a Postdoctoral Researcher at ETH Z&uuml;rich, working at the intersection of natural language processing, interpretability, and psycholinguistics. His long-term goal is to understand how humans and machines process language. To that end, he takes an interdisciplinary approach, drawing on information theory and causality to study the mechanisms behind both model behaviour and human cognition.</p>
    </div>
  </section>

  <section class="keynote-speaker" id="amir-zamir">
    <img src="{{ '/assets/img/speakers/amir-zamir.jpeg' | relative_url }}" alt="Amir Zamir" width="150" height="150" loading="lazy">
    <div class="keynote-details">
      <h3><a href="https://vilab.epfl.ch/zamir/">Amir Zamir</a></h3>
      <p>EPFL</p>
      <p><strong>10:10 a.m. - 11:00 a.m.</strong><br>
      <em>(Multimodal) Flexible-Length Tokenization</em></p>
      <p class="abstract"><strong>Abstract:</strong>
        I will discuss flexible-length tokenization and the intriguing structures that emerge as its byproduct. Most visual tokenizers map an image or video to a fixed number of tokens, regardless of its content. I will describe simple learning mechanisms, e.g., a latent PCA-like constraint, for developing flexible-length tokenization, where the same input can be represented by a variable number of tokens (FlexTok and VideoFlexTok). I will show the interesting structures that emerge in the representation as a result of the flexible-length compression – e.g., a coarse-to-fine semantic order in FlexTok and object-motion disentanglement in VideoFlexTok. I will then discuss multimodal learning (models like 4M and its extensions to 3D, videos, and decoder-only architectures), how we can move toward multimodal tokenization, and what we want from a multimodal tokenizer in the first place.
      </p>
      <p>Amir Zamir is an Assistant Professor of Computer Science at the Swiss Federal Institute of Technology in Lausanne (EPFL). His research is on computer vision, multimodal learning, and machine learning. Before joining EPFL in 2020, he was at UC Berkeley, Stanford, and UCF. He has received paper awards at SIGGRAPH 2022, CVPR 2020, CVPR 2018, CVPR 2016, and the NVIDIA Pioneering Research Award 2018, the PAMI Everingham Prize 2022, and the ECCV/ECVA Young Researcher Award 2022. He was the chief scientist of Aurora Solar, a Forbes AI 50 company, from 2015 to 2022 and is currently a scientific advisor to Metamorphic Labs and Duranta.</p>
    </div>
  </section>

  <section class="keynote-speaker" id="alexandre-defossez">
    <img src="{{ '/assets/img/speakers/alexandre-defossez.jpg' | relative_url }}" alt="Alexandre D&eacute;fossez" width="150" height="150">
    <div class="keynote-details">
      <h3><a href="https://ai.honu.io/">Alexandre D&eacute;fossez</a></h3>
      <p>Kyutai</p>
      <p><strong>1:40 p.m. - 2:30 p.m.</strong><br>
      <em>Discrete and continuous tokenization for audio-text modeling</em></p>
      <p class="abstract"><strong>Abstract:</strong>
        Audio signals are inherently stochastic. Naive representations would require tens of thousands of auto-regressive steps per seconds, make them incompatible with LM based methods. We will see how using adversarial auto-encoder with a discrete information bottleneck, one can reduce that drastically to a few hundred, making audio language modeling tractable with custom architectures. Yet such discrete tokenizations have limits: higher quality requires more tokens, which accounting for more computation time than the content itself. We will thus open up on recent advances in continuous tokenization and generation for audio.
      </p>
      <p>Alexandre is a co-founder of Kyutai, a non profit lab for research in artificial intelligence based in Paris committed to open science. His work covers generative speech and multimodal AI (Moshi, Hibiki, DSM) with a strong focus on handling multiple streams jointly across modalities in a streaming and low latency fashion. He is also a co-founder and Chief Science Officer at Gradium, a startup launched in 2025 whose mission is to commercialize the best possible voice AI experience. Before that, Alexandre was a scientist for 3 years at Facebook AI Research in Paris, where he led the development of models for audio compression and modeling (AudioCraft, MusicGen, EnCodec).</p>
    </div>
  </section>
  
  <section class="keynote-speaker" id="artidoro-pagnoni">
    <img src="{{ '/assets/img/speakers/artidoro-pagnoni.jpg' | relative_url }}" alt="Artidoro Pagnoni" width="150" height="150" loading="lazy">
    <div class="keynote-details">
      <h3><a href="https://artidoro.github.io/">Artidoro Pagnoni</a></h3>
      <p>University of Washington / Meta</p>
      <p><strong>2:40 p.m. - 3:30 p.m.</strong><br>
      <em>Tokenization as Resource Allocation</em></p>
      <p class="abstract"><strong>Abstract:</strong>
        Tokenization is usually treated as preprocessing. This talk argues it is better understood as a resource allocation policy: the choice of input unit, from single bytes to long patches, determines how computation, memory, and data are distributed. Recent work has shown this allocation need not be uniform or fixed, whether through entropy-based byte patching, learned hierarchies, or coarser subword schemes. What it controls depends on the objective. In training, the compression rate is a scaling-law variable. At inference, it sets how often parameters are streamed per unit of output, a binding constraint for current hardware. In distillation, it need not match between teacher and student, and finer-grained students are more data-efficient.
      </p>
      <p>Bio: Artidoro Pagnoni is a research scientist on the FAIR team at Meta Superintelligence. His work focuses on making language models more efficient and scalable by rethinking assumptions that are usually taken as given, such as fixed tokenization and uniform computation per token. He is the lead author of the Byte Latent Transformer (BLT), a byte-level architecture that replaces fixed tokens with dynamically sized patches, and a co-creator of QLoRA. His research has received a best paper award and orals at ACL and NeurIPS, and the Madrona Prize. He holds a PhD from the University of Washington.</p>
    </div>
  </section>
</div>

<style>
.keynote-container {
  display: flex;
  flex-direction: column;
  gap: 2rem;
  margin-top: 2rem;
}

.keynote-speaker {
  display: flex;
  align-items: flex-start;
  gap: 1.5rem;
  border-bottom: 1px solid #ccc;
  padding-bottom: 1.5rem;
  scroll-margin-top: 6rem;
}

.keynote-speaker img {
  flex: 0 0 150px;
  width: 150px;
  height: 150px;
  object-fit: cover;
  border-radius: 8px;
}

.keynote-details {
  min-width: 0;
  overflow-wrap: break-word;
}

.keynote-details h3 {
  margin-top: 0;
  font-size: 1.5rem;
}

.keynote-details p:last-child {
  margin-bottom: 0;
}

@media (max-width: 576px) {
  .keynote-speaker {
    flex-direction: column;
    gap: 1rem;
  }
}
</style>
