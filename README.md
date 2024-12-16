# SAM-Finetuning

### Contributions of the SAM (Segment Anything) Paper
1. **Promptable Segmentation**: The paper introduces a novel task called "promptable segmentation," where the model is trained to segment any object in an image using various types of prompts, such as points, boxes, masks, and free-form text. This approach is more versatile than previous methods, offering enhanced flexibility and enabling zero-shot transfer to new tasks.
   
2. **Segment Anything Model (SAM)**: The paper presents SAM, a model designed specifically for promptable segmentation. SAM's architecture is simple yet effective, consisting of an image encoder, a prompt encoder, and a mask decoder. This design allows the model to process diverse prompts and generate accurate segmentation masks efficiently.

3. **SA-1B Dataset**: To improve the model's generalization capabilities, the authors created the largest segmentation dataset to date, called SA-1B. This dataset includes over 1 billion masks across 11 million images, collected using a data engine that continuously refines the model and data generation process.

### References
**SAM**
- [Segment Anything (SAM1) – Arxiv Paper](https://arxiv.org/pdf/2304.02643)
- [Dataset for Segment Anything – MetaAI](https://arxiv.org/pdf/2304.02643)
- [Segment Anything Official Repo – Github](https://github.com/facebookresearch/segment-anything)
- [SAM – Hugging Face Docs](https://huggingface.co/docs/transformers/en/model_doc/sam)

**SAM2**
- [SAM 2: Segment Anything in Images and Videos – Arxiv Paper](https://arxiv.org/abs/2408.00714)
- [SAM2 Official Repo – Github](https://github.com/facebookresearch/sam2)
- [Segment Anything 2 Blog – AI Meta](https://ai.meta.com/blog/segment-anything-2/)

Special thanks to the Facebook Research team for releasing this model as open-source.