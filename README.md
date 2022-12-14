## Evaluating text summarization methods using transfer learning
For CS 230: Deep Learning (Fall 2022) at Stanford University

In this project, I framed model combinations as transfer learning to explore how extractive and abstractive text summarizers may be used to address long, single documents. The document was abstractly summmarized by PEGASUSForConditionalGeneration to identify key information from its semantically different sections. Then, I compared how TextRank and BARTForConditionalGeneration re-summarized the document using ROUGE-L and BERT F-1 scores to meassure the model's ability to maintain or increase comprehensiveness and fluency (semantic and syntactic correctness), respectively. This study demonstrates that abstractive text summarization models may perform better when learning from other such models.

In this repo, you'll find copies of the project code, data, results, final report, and presentations.
