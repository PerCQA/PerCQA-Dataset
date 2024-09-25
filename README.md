# PerCQA: Persian Community Question Answering Dataset

**[PerCQA: Persian Community Question Answering Dataset](https://aclanthology.org/2022.lrec-1.654) (Jamali et al., LREC 2022)**

## Authors:
- [Naghme Jamali](https://scholar.google.com/citations?user=uVoJmrUAAAAJ&hl)
- Yadollah Yaghoobzadeh
- Heshaam Faili

## Abstract:
Community Question Answering (CQA) forums provide answers to many real-life questions. These forums are trendy among machine learning researchers due to their large size. Automatic answer selection, answer ranking, question retrieval, expert finding, and fact-checking are example learning tasks performed using CQA data. This paper presents PerCQA, the first Persian dataset for CQA. This dataset contains the questions and answers crawled from the most well-known Persian forum. After data acquisition, we provide rigorous annotation guidelines in an iterative process and then the annotation of question-answer pairs in SemEvalCQA format. PerCQA contains 989 questions and 21,915 annotated answers. We make PerCQA publicly available to encourage more research in Persian CQA. We also build strong benchmarks for the task of answer selection in PerCQA by using mono- and multi-lingual pre-trained language models.

## Use Cases:
- Information retrieval
- Retrieval-Augmented Generation (RAG) system
- Question Answer similarity
- Question Answer system
- Large Language Models (LLMs)

## Dataset:
- Source: Crawled from NiniSite.com, containing Persian language questions and answers.
- Format: SemEvalCQA format with annotated question-answer pairs.
- Size: 989 questions and 21,915 answers.

## Algorithms Used:
- Transformer-based models such as:
  - BERT
  - RoBERTa

## Links:
- 🌍 [URL](https://aclanthology.org/2022.lrec-1.654)
- 📜 [PDF](https://aclanthology.org/2022.lrec-1.654.pdf)

## Contact:
- Email: [naghme.jamali.ai@gmail.com](mailto:naghme.jamali.ai@gmail.com)
- LinkedIn: [linkedin.com/in/naghmeh-jamali-0382a0172](https://linkedin.com/in/naghmeh-jamali-0382a0172)

## Citation:
If you use **PerCQA** in your work, please cite the following paper:

### BibTeX:
```bibtex
@inproceedings{jamali-etal-2022-percqa,
    title = "{P}er{CQA}: {P}ersian Community Question Answering Dataset",
    author = "Jamali, Naghme  and
      Yaghoobzadeh, Yadollah  and
      Faili, Heshaam",
    booktitle = "Proceedings of the Thirteenth Language Resources and Evaluation Conference",
    month = jun,
    year = "2022",
    address = "Marseille, France",
    publisher = "European Language Resources Association",
    url = "https://aclanthology.org/2022.lrec-1.654",
    pages = "6083--6092"
}
