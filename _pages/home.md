---
layout: default2
title: home
permalink: /
title: <h3  align="center">Tokenization Workshop</h3>
nav_order: 1
---


# Call for Papers
<br>
### Important Dates

* Submission begins: April 14, 2025
  * Submission portal: [OpenReview](https://openreview.net/group?id=ICML.cc/2025/Workshop/TokShop#tab-recent-activity)
* Submission deadline: ~~May 30~~ May 31, 2025 (11:59pm, anywhere on earth)
* Notification of acceptance: June 9, 2025
* Camera-ready papers due: June 18 (11:59pm, anywhere on earth)
* Workshop date: July 18, 2025


### Topics of Interest

Tokenization—the process of converting raw data into discrete units for model input and output—has emerged as a critical component across machine learning domains. Originally central to natural language processing (NLP), tokenization is now equally essential in multimodal learning, computer vision, speech processing, and other areas. Recent research has shown that tokenization strategies significantly impact model utility, efficiency, and generalization, sparking a surge of interest in this foundational topic.

The Tokenization Workshop (TokShop) at ICML aims to bring together researchers and practitioners from all corners of machine learning to explore tokenization in its broadest sense. We will discuss innovations, challenges, and future directions for tokenization across diverse data types and modalities. Topics of interest include:

* **Subword Tokenization in NLP**: Analysis of techniques such as BPE, WordPiece, and UnigramLM, as well as improvements for efficiency, interpretability, and adaptability.
* **Multimodal Tokenization**: Tokenization strategies for images, audio, video, and other modalities, including methods to align representations across different types of data.
* **Multilingual Tokenization**: Development of tokenizers that work robustly across languages and scripts, and investigation into failure modes tied to tokenization.
* **Tokenizer Modification Post-Training**: Methods for updating tokenizers after model training to boost performance and/or efficiency without retraining from scratch.
* **Alternative Input Representations**: Exploration of non-traditional tokenization approaches, such as byte-level, pixel-level, or patch-based representations.
* **Statistical Perspectives on Tokenization**: Empirical analysis of token distributions, compression properties, and correlations with model behavior.

By broadening the scope of tokenization research beyond language, this workshop seeks to foster cross-disciplinary dialogue and inspire new advances at the intersection of representation learning, data efficiency, and model design.

<br>

### Guidelines

Our author guidelines follow the ICML requirements unless otherwise specified. 
* Paper submission is hosted on [OpenReview](https://openreview.net/group?id=ICML.cc/2025/Workshop/TokShop#tab-recent-activity).
* Each submission should contain __up to 9 pages__, not including references or appendix (shorter submissions also welcome). 
  * Please use the provided LaTeX template ([Style Files](https://media.icml.cc/Conferences/ICML2025/Styles/icml2025.zip)) for your submission. Please follow the paper formatting guidelines general to [ICML](https://icml.cc/Conferences/2025/AuthorInstructions) as specified in the style files. Authors may not modify the style files or use templates designed for other conferences.
  * The paper should be anonymized and uploaded to OpenReview as a single PDF. 
  * You may use as many pages of references and appendix as you wish, but reviewers are not required to read the appendix.
  * Posting papers on preprint servers like ArXiv is permitted.
  * We encourage each submission to discuss the limitations as well as ethical and societal implications of their work, wherever applicable (but neither are required). These sections do not count towards the page limit.
* This workshop offers both archival and non-archival options for submissions. Archival papers will be indexed with proceedings, while non-archival submissions will not.
* The review process will be double-blind.
<br>


## Organizers
<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/organizers/tomasz.jpeg" alt="Name 1">
            <a href="https://tomlimi.github.io/">Tomasz Limisiewicz</a>
            <p>Meta<br>University of Washington</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/valentin.jpeg" alt="Name 4">
            <a href="https://valentinhofmann.github.io/">Valentin Hofmann</a>
            <p>Allen Institute for AI<br>University of Washington</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/sachin.png" alt="Name 5">
            <a href="https://sites.google.com/view/sachinkumar">Sachin Kumar</a>
            <p>The Ohio State University</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/libovicky.jpg" alt="Name 3">
            <a href="https://ufal.mff.cuni.cz/jindrich-libovicky">Jindřich Libovický</a>
            <p>Charles University</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/jindra.jpg" alt="Name 2">
            <a href="https://ufal.mff.cuni.cz/jindrich-helcl">Jindřich Helcl</a>
            <p>University of Oslo</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/oreva.jpeg" alt="Name 6">
            <a href="https://orevaahia.github.io/">Orevaoghene Ahia</a>
            <p>University of Washington</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/liz.jpg" alt="Name 7">
            <a href="https://esalesky.github.io/">Elizabeth Salesky</a>
            <p>Google Deepmind</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/samir.png" alt="Name 8">
            <a href="https://farhansamir.notion.site/samir">Farhan Samir</a>
            <p>University of British Columbia</p>
        </div>
    </div>
</html>
<br>

<!-- <div class="team-member">
            <img src="/assets/img/organizers/jindra.jpg" alt="Name 2">
            <a href="https://ufal.mff.cuni.cz/jindrich-helcl">Jindřich Helcl</a>
            <p>Charles University</p>
        </div> -->

<style>
    /* Style for the team container */
.team-container {
    display: grid;
    grid-template-columns: repeat(5, 1fr); /* Display 3 members per row */
    gap: 5px;
    max-width: 1000px;
    padding: 20px;
}

@media (max-width: 768px) {
    .team-container {
        grid-template-columns: repeat(2, 1fr); /* Display 2 members per row on smaller screens */
    }
}

/* Style for each team member */
.team-member {
    text-align: center;
    background-color: #fff;
    padding: 0px;
    width: 150px; /* Set a fixed width for consistent circle appearance */
    height: 260px; /* Set a fixed height for consistent circle appearance */
    /* box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1); */
    overflow: hidden; /* Hide any image overflow */
}


.team-member h3 {
    font-size: 16px;
    color: #333;
}

.team-member img {
  object-fit: cover;
  border-radius:50%;
  width: 150px;
  height: 150px;
  padding: 10px;
}

.sponsor-container {
    display: flex;
    gap: 5px;
}

.sponsor {
    flex: 1;
    margin: 10px;
    text-align: center;
    box-sizing: border-box;
    height: 50px;
    width: 50px;
}

.sponsor img {  
    width: 100%; /* Make the image take up 100% of the figure's width */
    height: 100%;
    object-fit: contain; 
}

.caption {
    margin-top: 12px; /* Adjust the margin to control the gap between the figure and the caption */
}

.right-half {
    flex: 1; /* Each figure takes up 50% of the available width */
    height: 500px; /* Set a fixed height for all figures (adjust the value as needed) */
}

.news-box {
    border: 1px solid #ccc;
    padding: 10px;
    width: 600px;
    margin: 0 auto;
    background-color: #f9f9f9;
}

@media (max-width: 600px) {
    .news-box {
        width: 100%; /* Adjust width to fit the screen */
    }
}
</style>

<br><br> 
