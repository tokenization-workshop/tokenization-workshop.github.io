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

* Submission begins: May 20, 2026
  * Submission portal: [OpenReview](https://openreview.net/group?id=colmweb.org/COLM/2026/Workshop/TokShop#tab-your-consoles)
* Submission deadline: June 23, 2026 (11:59pm, anywhere on earth)
* Notification of acceptance: July 24, 2026
* Camera-ready papers due: TBA (11:59pm, anywhere on earth)
* Workshop date: TBA


### Topics of Interest

Tokenization--the process of converting raw data into discrete units for model input and output--has emerged as a critical component across machine learning domains. Originally central to natural language processing (NLP), tokenization is now equally essential in multimodal learning, computer vision, speech processing, and other areas. Recent research has shown that tokenization strategies significantly impact model utility, efficiency, and generalization, sparking a surge of interest in this foundational topic.

The Second Tokenization Workshop (TokShop) at COLM 2026 aims to bring together researchers and practitioners from all corners of machine learning to explore tokenization in its broadest sense. We will discuss innovations, challenges, and future directions for tokenization across diverse data types and modalities. Topics of interest include:

* **Subword Tokenization**. Examination of current techniques such as WordPiece, BPE, and UnigramLM, as well as extensions to improve their efficiency and applicability.
* **Tokenization for Various Modalities**. Techniques of tokenization for images, audio, and video. Study of representation alignment across modalities.
* **Multilingual Tokenization**. Focus on ensuring tokenization methods are equitable and effective across various languages. Identification of relevant failure modes caused by tokenization.
* **Tokenizer Modification**. Methods for updating tokenizers after model training to improve the model’s efficiency or performance without retraining from scratch.
* **Alternative Approaches to Represent Input**. Investigation into alternative input representations for data such as patches, bytes, or pixels.
* **Tokenization and Statistics**. Statistical analysis of subword properties. For instance, the study of compression effectiveness of different tokenization methods.

By broadening the scope of tokenization research beyond language, this workshop seeks to foster cross-disciplinary dialogue and inspire new advances at the intersection of representation learning, data efficiency, and model design.

<br>

### Guidelines

Our author guidelines follow the COLM requirements unless otherwise specified. 
* Paper submission is hosted on [OpenReview](https://openreview.net/group?id=colmweb.org/COLM/2026/Workshop/TokShop).
* Each submission should contain __up to 9 pages__, not including references or appendix (shorter submissions also welcome). 
  * Please use the provided LaTeX template ([Style Files](https://github.com/COLM-org/Template/releases/tag/2026)) for your submission. Please follow the paper formatting guidelines general to [COLM](https://colmweb.org/cfp.html) as specified in the style files. Authors may not modify the style files or use templates designed for other conferences.
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
            <p>University of Washington<br>Meta</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/valentin.jpeg" alt="Name 4">
            <a href="https://valentinhofmann.github.io/">Valentin Hofmann</a>
            <p>LMU Munich</p>
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
            <img src="/assets/img/organizers/yuki.jpg" alt="Name 7">
            <a href="">Yuki Asano</a>
            <p>University of Technology Nuremberg</p>
        </div>
        <div class="team-member">
            <img src="/assets/img/organizers/yuval.jpg" alt="Name 7">
            <a href="">Yuval Pinter</a>
            <p>Ben-Gurion University of the Negev</p>
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
