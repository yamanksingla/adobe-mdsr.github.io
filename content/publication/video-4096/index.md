---
title: "A Video Is Worth 4096 Tokens: Verbalize Videos To Understand Them In Zero Shot"
authors:
- Aanisha Bhattacharyya
- Yaman Kumar Singla
- Balaji Krishnamurthy
- Changyou Chen
- Rajiv Ratn Shah

date: "2023-12-01T00:00:00Z"
doi: ""

publishDate: "2023-12-01T00:00:00Z"

publication_types: ["conference"]

publication: "Empirical Methods in Natural Language Processing"
publication_short: "EMNLP"

abstract: "Multimedia content, such as advertisements and story videos, exhibit a rich blend of creativity and multiple modalities. They incorporate elements like text, visuals, audio, and storytelling techniques, employing devices like emotions, symbolism, and slogans to convey meaning. There is a dearth of large annotated training datasets in the multimedia domain hindering the development of supervised learning models with satisfactory performance for real-world applications. On the other hand, the rise of large language models (LLMs) has witnessed remarkable zero-shot performance in various natural language processing (NLP) tasks, such as emotion classification, question answering, and topic classification. To leverage such advanced techniques to bridge this performance gap in multimedia understanding, we propose verbalizing long videos to generate their descriptions in natural language, followed by performing video-understanding tasks on the generated story as opposed to the original video. Through extensive experiments on fifteen video-understanding tasks, we demonstrate that our method, despite being zero-shot, achieves significantly better results than supervised baselines for video understanding. Furthermore, to alleviate a lack of story understanding benchmarks, we publicly release the first dataset on a crucial task in computational social science on persuasion strategy identification."

summary: ""

tags:
- Video Understanding
- Zero-Shot Learning for Long Videos
- Persuasion Strategy
- Behavior-in-the-Wild
- Behavioral Sciences

featured: true



links:
url_pdf: "https://aclanthology.org/2023.emnlp-main.608.pdf"
url_code: "https://github.com/Aanisha/video-persuasion"
url_dataset: "https://drive.google.com/drive/folders/1rATHvwd4sOYB363ijGObAkev_Z3uqFPn?usp=share_link"
url_poster: ""
url_project: "https://behavior-in-the-wild.github.io/memorability"
url_slides: ""
url_source: ""
url_video: "https://aclanthology.org/2023.emnlp-main.608.mp4"

image:
  caption: "Example story and predicted video understanding outputs. Original video: https://youtu.be/_amwPjAcoC8."
  focal_point: "Smart"
  preview_only: false
  alt_text: "An example of a story generated by the proposed pipeline along with the predicted outputs of the video understanding tasks on the generated story. The generated story captures information across scenes, characters, event sequences, dialogues, emotions, and the environment. This helps the downstream models to get adequate information about the video to reason about it correctly. The original video can be watched at https://youtu.be/_amwPjAcoC8."

projects: []
slides: ""
---