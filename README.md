### **Advanced NLP Project, Fall '22: Multi-document summarization**
-----

Contributors:

- [Vanshpreet Singh Kohli](https://github.com/VKohli17)
- [Likhith Asapu]()
- [Rahothvarman Prithviraj](https://github.com/Rutts07)

\* *Created by the aforementioned authors for a course project for Advanced NLP, IIITH, Fall 2022* \*

The final project report is attached as `Project Report.pdf` in the repository.

-----
#### Introduction:

We work on the task of multi-document summarization using the [Answersumm](https://arxiv.org/abs/2111.06474) dataset. The dataset consists of around 8000 q/a threads from stackexchange fora with gold-standard summaries attached, and we create a novel pipeline, exploiting pre-trained encoders and decoders wherever possible for the best performance, to emulate the (manual) creation of the dataset to ultimately automate generation of summaries for new threads. We compare our model to a couple of baselines, and to the SOTA (RL-based summarization technique laid out in the original paper).

For a more thorough understanding of the project, please refer to the [project report](Report.pdf).

-----

#### Directory Structure:

1. Readme
2. Final Report
3. **Models directory:** Contains the implemented model and a baseline in `.ipynb` format (with outputs stored).

-----