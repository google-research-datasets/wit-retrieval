# Entity Image and Mixed-Modal Image Retrieval Datasets

![WIT Retrieval Dataset Image](images/wit_retrieval_dataset_example.png)

**The Entity Image (EI) dataset** comprises a curated collection of canonical images representing entities, sourced from Wikimedia Commons.
For each of these entities, we identified and extracted a single, representative canonical image from its corresponding Wikipedia page.
This image serves as a visual identifier for the entity.

EI dataset comprises $1.80$M entities, each associated with a canonical image.

**Mixed-Modal Image Retrieval (MMIR) dataset** is constructed by leveraging the comprehensive [Wikipedia Image Text (WIT) dataset](https://github.com/google-research-datasets/wit),
which is a carefully curated dataset of 37 million image-text pairings, featuring 11 million distinct images and spanning more than 100 languages.

MMIR dataset encompasses over 9M examples spanning more than 100 languages, partitioned into train, validation, and test splits. To ensure consistency,
we maintained the original data splits from the WIT dataset; specifically, each of the MMIR splits was derived from the corresponding WIT split through
the entity annotation process.

## Download

We believe that such a powerful diverse dataset will aid researchers in building
better multimodal retrieval models and in identifying better learning and
representation techniques leading to improvement of Machine Learning models in
real-world tasks over visio-linguistic data.

The datasets are now available for download. Please check the [data](DATA.md) page.

## License

This data is available under the [Creative Commons Attribution-ShareAlike 3.0 Unported](LICENSE) license.

## Contact

For any questions, please contact wit-retrieval-dataset@google.com.
