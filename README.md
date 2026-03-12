# Transformer course on LLMs and multimodal models
This is the repository of the course on LLMs based on the Transformer architecture targeted at people with experience in Python, Machine Learning, and Deep Learning but little or no experience with Transformers and LLMS. 

The course focuses on modern LLMs and multimodal models built on the Transformer architecture.  A separate module covers the use of Transformers for non-text modalities (time series, tabular data, and others) and modern multimodal architectures. The course also introduces the fundamentals of building AI agents based on LLMs. As a result, you will gain comprehensive knowledge of how modern LLMs, multimodal models, RAG systems, and basic LLM agents operate both in theory and in practice.

The course emphasizes not only theoretical understanding but also practical skills for applying these models and building systems around them. Special attention is given to modern LLM architectures, relevant frameworks such as Transformers, LLM, Ollama, LangChain, and others, as well as to the efficiency of LLM-based system design.

By the end of the course, you will have a coherent understanding of the principles and practical use of LLMs, multimodal models, RAG systems, and basic LLM agents — with a strong emphasis on practical application, proper evaluation, and computational efficiency.

The course features $14$ sessions: one lecture per session, one practical session per session.

## The course Syllabus

1. [Transformer model](https://github.com/s-nlp/transformers-course/tree/main/course_materials/01.%20Transformer%20model)
2. [Transformer-based Encoders](https://github.com/s-nlp/transformers-course/tree/main/course_materials/02.%20Transformer-based%20Encoders)
3. [Classification with Transformers](https://github.com/s-nlp/transformers-course/tree/main/course_materials/03.%20Classification%20and%20sequence%20tagging%20with%20Transformers)
4. [Transformer-based decoders](https://github.com/s-nlp/transformers-course/tree/main/course_materials/04.%20Transformer-based%20decoders)
5. [Towards ChatGPT](https://github.com/s-nlp/transformers-course/tree/main/course_materials/05.%20Towards%20ChatGPT)
6. [Efficient Transformers](https://github.com/s-nlp/transformers-course/tree/main/course_materials/06.%20Efficient%20Transformers)
7. [RAG with Transformers](https://github.com/s-nlp/transformers-course/tree/main/course_materials/07.%20RAG%20with%20Transformers)
8. [Introduction to AI Agents](https://github.com/s-nlp/transformers-course/tree/main/course_materials/08.%20Introduction%20to%20AI%20Agents)
9. [Uncertainty estimation for Transformers](https://github.com/s-nlp/transformers-course/tree/main/course_materials/09.%20Uncertainty%20estimation%20for%20Transformers)
10. [Uncertainty quantification generation tasks](https://github.com/s-nlp/transformers-course/tree/main/course_materials/10.%20Uncertainty%20quantification%20for%20text%20generation%20tasks)
11. [Multilingual language models](https://github.com/s-nlp/transformers-course/tree/main/course_materials/11.%20Multilingual%20language%20models)
12. [Multimodal dialogue models](https://github.com/s-nlp/transformers-course/tree/main/course_materials/12.%20Multimodal%20dialogue%20models)
13. [Transformers for tabular data](https://github.com/s-nlp/transformers-course/tree/main/course_materials/13.%20Transformers%20for%20tabular%20data)
14. [Transformers for event sequences](https://github.com/s-nlp/transformers-course/tree/main/course_materials/14.%20Transformers%20for%20event%20sequences)

## Editable materials

Raw versions of the editable course materials (e.g., pptx presentations) can be found [here](https://drive.google.com/drive/folders/1rJU9uAyoEcXhutNGeHc8pUIw9gyPzzn7?usp=sharing).

## Citation

If you use materials of this course please refer to the following paper [Industry vs Academia: Running a Course on Transformers in Two Setups](https://aclanthology.org/2024.teachingnlp-1.3/) published at the the 6th Workshop on Teaching NLP co-located with ACL-2024 in Bangkok (materials of this repository are being gradually updated since the initial release):

```
@inproceedings{nikishina-etal-2024-industry-vs,
    title = "Industry vs Academia: Running a Course on Transformers in Two Setups",
    author = "Nikishina, Irina  and Tikhonova, Maria  and Chekalina, Viktoriia  and Zaytsev, Alexey  and Vazhentsev, Artem  and Panchenko, Alexander",
    editor = {Al-azzawi, Sana  and Biester, Laura  and Kov{\'a}cs, Gy{\"o}rgy  and Marasovi{\'c}, Ana  and Mathur, Leena  and Mieskes, Margot  and Weissweiler, Leonie},
    booktitle = "Proceedings of the Sixth Workshop on Teaching NLP",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.teachingnlp-1.3/",
    pages = "7--22",
    abstract = "This paper presents a course on neural networks based on the Transformer architecture targeted at diverse groups of people from academia and industry with experience in Python, Machine Learning, and Deep Learning but little or no experience with Transformers. The course covers a comprehensive overview of the Transformers NLP applications and their use for other data types. The course features 15 sessions, each consisting of a lecture and a practical part, and two homework assignments organized as CodaLab competitions. The first six sessions of the course are devoted to the Transformer and the variations of this architecture (e.g., encoders, decoders, encoder-decoders) as well as different techniques of model tuning. Subsequent sessions are devoted to multilingualism, multimodality (e.g., texts and images), efficiency, event sequences, and tabular data.We ran the course for different audiences: academic students and people from industry. The first run was held in 2022. During the subsequent iterations until 2024, it was constantly updated and extended with recently emerged findings on GPT-4, LLMs, RLHF, etc. Overall, it has been ran six times (four times in industry and twice in academia) and received positive feedback from academic and industry students."
}
```
