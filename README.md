# iris-task

A Story of the arXiv Dataset Through Recent Research


The earliest of the works in this trajectory is that of [Ginev et al. (2019)](https://arxiv.org/pdf/1908.10993) , who framed arXiv papers not merely as documents but as rich sources of scientific statements. Instead of focusing on whole-paper classification, they introduced the task of scientific statement classification, breaking articles into semantically meaningful units and showing that arXiv provides sufficient linguistic diversity for learning fine-grained distinctions across scientific discourse. Their work demonstrated that the dataset supports granular semantic tasks beyond simple category prediction.

[Kandimalla et al. (2020)](https://arxiv.org/pdf/2007.13826)  shifted attention to subject-area classification at scale. Using deep attentive neural networks on millions of abstracts, they demonstrated how arXiv’s breadth across physics, mathematics, computer science, and more enables robust modeling of disciplinary boundaries. Their results showed that deep architectures can capture domain-specific writing styles, and that the dataset is sufficiently large to support high-capacity models. This work helped cement arXiv as a benchmark for multi-class document classification.

[Scharpf et al. (2021)](https://arxiv.org/pdf/2109.00954) explored classification in STEM fields using both textual content and mathematical formulas, arguing that arXiv is uniquely suited for multimodal scientific NLP. In their work, formulas were treated as first-class linguistic objects, and the study demonstrated how pairing text with symbolic structure can improve classification while providing explanations tied to mathematical entities. This reframed arXiv as a multimodal resource rather than a purely textual one.


[Schopf et al. (2024)](https://arxiv.org/pdf/2410.05770) investigate few-shot multi-label classification, addressing a challenge often overlooked: many scientific papers straddle multiple research areas. Their work demonstrates that arXiv’s hierarchical, overlapping subject categories make it ideal for multi-label learning. By using few-shot methods, they showed how models can generalize across hundreds of categories with minimal supervision, emphasizing arXiv’s value for low-resource and transfer-learning scenarios.

Most recently, [Rahman et al. (2025)](https://arxiv.org/pdf/2510.05495) revisite large-scale multi-class classification, but with an emphasis on practical recommendation and automated sorting systems. Their work highlighted the continuing relevance—and difficulty—of cleanly assigning papers to single subject areas. Even with traditional machine-learning pipelines, arXiv still poses challenges due to overlapping domains, evolving research trends, and diverse writing styles. Their results underscore that even as modeling techniques evolve, arXiv remains a demanding benchmark.

Summary

Together, these studies trace a coherent narrative of progress:

2019 — fine-grained semantic classification within papers (Ginev et al.).

2020 — deep learning for large-scale subject classification (Kandimalla et al.).

2021 — explainability and multimodal STEM understanding (Scharpf et al.).

2023 — transformer fine-tuning and modern baselines (RoBERTa fine-tuning).

2024 — few-shot and multi-label learning for complex taxonomies (Schopf et al.).

2025 — renewed emphasis on scalable multi-class classification and recommendation (Rahman et al.).

This progression reflects the increasing sophistication of the tasks researchers pursue using arXiv, and highlights how the dataset continues to shape advancements in scientific NLP, classification, and explainability.