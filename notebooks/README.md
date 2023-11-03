# Notebooks

Contains the code used to filter and clean the original dataset (not the cleaned splits in ```data/``` . Currently not usable, however will be kept here as reference. 

To use:
1. Parse the raw dataset using ```parse_raw_dataset.ipynb``` which will do some light filtering, remove urls and extract PubMed Ids.
2. Create the QA pairs using ```produce_qa_pairs.ipynb``` which will produce the original QA pairs. This will remove bot posts, image posts, and filter by comment score.

