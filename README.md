# Healthcare Information Retrieval System

Python coursework prototype searching structured healthcare records and research articles using CSV data, text preprocessing, inverted indexing and TF-IDF concepts.

**Project type:** Command-line information-retrieval prototype and report.

## What the work covers

- Separates structured record lookup from free-text research-article search.
- Uses pandas to load EHR, clinical-note, image-reference and research-article CSVs.
- Uses NLTK tokenisation, stopword handling and stemming as part of text preprocessing.
- Documents retrieval design, inverted-index/TF-IDF reasoning, output examples and an evaluation plan.

## Explore the repository

- [Completed system report](COMP1859-2023-24%20Information%20Retrieval.pdf)
- [Python entry point](final.py)
- [EHR sample](ehr.csv)
- [Clinical-note sample](clinical_notes.csv)
- [Image-reference sample](images.csv)
- [Research-article sample](research_articles.csv)
- [Assignment brief](CW%20Assessment%20Brief%20COMP1859-2023-24_v3.pdf)

## Run or read the work

Use Python with pandas and NLTK. From the repository root:

```text
python -m pip install -r requirements.txt
python final.py
```

Keep all four CSVs alongside `final.py`, because the code uses relative paths. Choose the structured-record or article-search option in the menu. The original code downloads NLTK `punkt` and `stopwords` resources, so initial setup requires network access. Depending on the NLTK version, its tokeniser resources may need additional setup; the original dependency versions are not locked.

## Scope and limitations

This is a coursework search prototype, not a clinical decision-support or medical-records product. A described evaluation plan does not establish a measured retrieval benchmark. Fresh execution, ranking quality and deployment readiness have not been verified.

## Academic context

University of Greenwich coursework, COMP1859. The linked specification, where present, is assessment context rather than a completed project deliverable. Reports and source are preserved in their original form.
