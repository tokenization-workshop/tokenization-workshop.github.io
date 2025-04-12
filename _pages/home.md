---
layout: default2
title: home
permalink: /
title: <h3  align="center">Workshop on Tokenization</h3>
nav_order: 1
---


# Call for Papers
<br>
### Important Dates

* Submission Begins:
  * Submission Portal: [OpenReview](#)
* Submission Deadline: May 30, 2025 (11:59pm, anywhere on earth)
* Notification of Acceptance: June 9, 2025
* Camera-ready papers due:  (11:59pm, anywhere on earth)
* Workshop Date: July 18, 2025.


### Topics of Interest

Tokenization---in the context of language models---defines how data are represented as input and output. Tokenization has been shown to significantly affect the utility and effectiveness of models. This finding has stirred considerable interest in tokenization as a research direction in natural language processing, multimodal learning and related fields.This workshop will focus on tokenization in a broad sense and cover the following research directions:

* **Subword Tokenization**: Examination of current tokenization techniques such as WordPiece, BPE, and UnigramLM, as well as extensions to improve their efficiency and applicability.
* **Tokenization for Various Modalities**: Techniques of tokenization for images, audio, and video. Study of representation alignment across modalities.
* **Multilingual Tokenization**: Focus on ensuring tokenization methods are effective across various languages. Identification of relevant failure modes caused by tokenization.
* **Tokenizer Modification**: Methods for updating tokenizers after model training to improve the model's efficiency or performance without retraining from scratch.
* **Alternative Approaches to Represent Input**: Investigation into alternative input representations for data such as patches, bytes, or pixels.
* **Tokenization and Statistics**: Statistical analysis of subword properties. For instance, the study of compression effectiveness of different tokenization methods.

<br>

### Guidelines

Our author guidelines follow the TBD requirements unless otherwise specified. 
* Paper submission is hosted on [OpenReview](#).
* We welcome both short (__up to 4 pages__) and long papers (__up to 8 pages__), not including references or appendix. 
  * Please use the provided LaTex template ([Style Files](https://media.icml.cc/Conferences/ICML2025/Styles/icml2025.zip)) for your submission. Please follow the paper formatting guidelines general to [ICML](https://icml.cc/Conferences/2025/AuthorInstructions) as specified in the style files. Authors may not modify the style files or use templates designed for other conferences.
  * The paper should be anonymized and uploaded to OpenReview as a single PDF. 
  * You may use as many pages of references and appendix as you wish, but reviewers are not required to read the appendix. 
  * Posting papers on preprint servers like ArXiv is permitted.
  * We encourage each submission to discuss the limitations as well as ethical and societal implications of their work, wherever applicable (but neither are required). 
* This workshop offers both archival and non-archival options for submissions. Archival papers will be indexed with proceedings, while non-archival submissions will not.
* The review process will be double-blind.
<br>


## Organizers
<html>
    <div class="team-container">
        <div class="team-member">
            <img src="/assets/img/organizers/tomasz.jpeg" alt="Name 1">
            <a href="https://tomlimi.github.io/">Tomasz Limisiewicz</a>
            <p>Charles University</p>
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
            <p>Charles University</p>
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