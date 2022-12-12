# RadQA: A Question Answering Dataset to Improve Comprehension of Radiology Reports

RadQA is a radiology question answering dataset with 3074 questions posed against radiology reports and annotated with their corresponding answer spans (resulting in a total of 6148 question-answer evidence pairs) by physicians. The questions are manually created using the clinical referral section of the reports that take into account the actual information needs of ordering physicians and eliminate bias from seeing the answer context (and, further, organically create unanswerable questions). The answer spans are marked within the Findings and Impressions sections of a report. The dataset aims to satisfy the complex clinical requirements by including complete (yet concise) answer phrases (which are not just entities) that can span multiple lines. The best-performing transformer language model achieved an F1 of 63.55 on the test set. However, the top human-level performance on this dataset is 90.31 (with an average human performance of 84.52), which demonstrates the challenging nature of RadQA that leaves ample scope for future method research.

# Dataset

The corpus is released through PhysioNet at https://doi.org/10.13026/ckkp-6y19.

Detailed information about the dataset files are available at PhysioNet.

# Citation

Additional details about the dataset can be found in our [LREC paper](https://aclanthology.org/2022.lrec-1.672). Please cite using:

```
@inproceedings{soni2022radqa,
  author={Soni, Sarvesh  and  Gudala, Meghana  and  Pajouhi, Atieh  and  Roberts, Kirk},
  title={RadQA: A Question Answering Dataset to Improve Comprehension of Radiology Reports},
  booktitle={Proceedings of the Language Resources and Evaluation Conference},
  month={June},
  year={2022},
  address={Marseille, France},
  pages={6250--6259},
  url={https://aclanthology.org/2022.lrec-1.672}
}
```

# Contact

Please open a GitHub issue with any questions related to the dataset.