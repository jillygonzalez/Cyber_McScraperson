# Cyber_McScraperson
Open-Source Web Scraping for Building Cyber Operations Database using the 'clip-ViT-L-14' of OpenAI CLIP Neural Network and The GDELT Project Database. This project begins by identifying a list of key terms that are searched on [RelatedWords.io](https://relatedwords.io/). For each term, their related words from the site are scraped and appended to a list for later use. The main function scrapes [The GDELT Project](https://www.gdeltproject.org/) based on news station and date. Note: the function can be resource-intensive and time-consuming without a GPU. Once webpages are pulled, videos and images are extracted and processed using the 'clip-ViT-L-14' model of the CLIP Neural Network and the generated list of related words. The final output is a .pkl file for each matched image, including query (term), image name, image URL, and a confidence score.

## Technicals

- Python version 3.11.3
- Reference requirements.txt for libraries/modules for project.

## References
### The GDELT Project
The GDELT Project is an open platform for research and analysis of global society and thus all datasets released by the GDELT Project are available for unlimited and unrestricted use for any academic, commercial, or governmental use of any kind without fee. You may redistribute, rehost, republish, and mirror any of the GDELT datasets in any form. However, any use or redistribution of the data must include a citation to the GDELT Project and a link to their [website](https://www.gdeltproject.org/).

### CLIP (Contrastive Language–Image Pretraining)
CLIP, developed by OpenAI, is a neural network trained on a variety of images and corresponding text descriptions. This innovative model learns visual concepts from natural language supervision, enabling it to understand and perform a wide range of image-related tasks with high flexibility. CLIP's unique approach allows it to generalize from the training data to a wide array of unseen tasks during inference, making it a significant advancement in the field of AI and computer vision.

For more information, see the original work by Radford, Alec, et al. (2021) on the [OpenAI Research page](https://openai.com/research/clip).

### Relatedwords.io

[RelatedWords.io](https://relatedwords.io/) is an intuitive online tool designed for discovering words related to a specific term or phrase. It extends beyond traditional thesaurus functions by using an algorithm to analyze text data and generate a list of words and phrases frequently found in similar contexts. This makes it an invaluable resource for writers, marketers, and content creators seeking inspiration or varied language. It's especially useful for expanding vocabulary and brainstorming ideas, offering insights into the broader usage of words beyond direct synonyms.
