# [Adaptive-RAG: Learning to Adapt Retrieval-Augmented Large Language Models through Question Complexity](https://arxiv.org/abs/2403.14403)
> This paper card is generated with Claude 3 Opus

## Contributions
- Proposes Adaptive-RAG, a framework that dynamically adjusts retrieval-augmented LLM strategies based on query complexity, spanning from non-retrieval for straightforward queries to multi-step approaches for complex queries.
- Introduces a classifier to determine query complexity, which is trained on automatically collected data from model prediction outcomes and dataset biases.

## Results
- Adaptive-RAG significantly improves overall accuracy and efficiency compared to existing one-size-fits-all approaches on a collection of open-domain QA datasets covering diverse query complexities.
- The classifier effectively categorizes queries into different complexity levels, contributing to the selection of the most suitable retrieval-augmented LLM strategy.

## Insights
- Real-world queries have varying complexities, and existing retrieval-augmented generation approaches tend to be overly simple or complex.
- Adapting retrieval-augmented LLMs to the assessed query complexity enables the utilization of the most suitable approach tailored to each query.
- The query complexity classifier plays a crucial role in the adaptive framework, and there is still room for improvement in its architecture and training data.

## Resources
- [LlamaIndex <> Mistral cookbook on Adaptive-RAG](https://github.com/mistralai/cookbook/blob/7bf0aae46ab8c763efb7800f352bcbfd8aceb8fb/third_party/LlamaIndex/Adaptive_RAG.ipynb)
- Official Code: https://github.com/starsuzi/Adaptive-RAG