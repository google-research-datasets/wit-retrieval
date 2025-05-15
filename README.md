# WIT Retrieval : Wikipedia-based Image-Text Cross Modality Retrieval Dataset

**WIT Retrieval Dataset** is a large scale Cross Modality Retrieval dataset for (image+text -> image) retrieval task.
Specifically, the task is defined as: Given the canonical image representation of an entity and a contextual
description about the entity’s action, retrieve the image where the entity is doing what is described.

We specifically release two datasets:

-   entity-image dataset: This is a collection of canonical entity images from Wikipedia. The dataset consists of
    1.8M images and only contains the image URL and metadata obtained from Wikipedia.
-   cross-modality image retrieval dataset: This is a collection of  images and captions from the publicly released WIT dataset
    along with the canonical entities (from the canonical entities dataset) attached to each WIT image/caption. The dataset
    consists of 9.16M examples with captions from 108 languages. Note that WIT is a publicly available dataset released by Google.

## License

This data is available under the [Creative Commons Attribution-ShareAlike 3.0 Unported](LICENSE) license.

## Contact

For any questions, please contact wit-retrieval-dataset@google.com.
