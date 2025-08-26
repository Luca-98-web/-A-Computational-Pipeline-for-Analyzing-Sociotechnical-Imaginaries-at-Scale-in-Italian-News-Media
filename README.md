This repository presents a computational pipeline for large-scale analysis of AI sociotechnical imaginaries in news media, developed as part of my Master's thesis. The pipeline is based on the SIPCs framework developed in the paper "Sociotechnical imaginaries and public communication: Analytical framework and empirical illustration using the case of artificial intelligence" (Brause et al., 2025). The pipeline is grounded in the principle of multi-resolution design, allowing for both a "zoom out" perspective for large-scale analysis and a "zoom in" approach for nuanced examination of imaginaries (Gillespie et al., 2024). Given the increasing production of articles, especially in web-based news media, and AI's central role in public debate, the use of computational methods enables researchers to conduct large-scale systematic analyses.

Technology use in this project
1. Natural Language Inference
Zero-shot classifiers developed by Laurer et al. (2023), available on Laurer's Hugging Face Hub (https://huggingface.co/collections/MoritzLaurer/zeroshot-classifiers-6548b4ff407bb19ff5c3ad6f) Specifically, the multilingual model MoritzLaurer/bge-m3-zeroshot-v2.0 was used for article classification across SIPC framework dimensions.
2. Topic Modeling
BERTopic (https://maartengr.github.io/BERTopic/index.html) was employed for topic modeling and semantic clustering. The Qwen/Qwen3-Embedding-0.6B model was used as the embedding model due to its larger token window, enabling better processing of longer news articles.

References
Brause, S.R., Schäfer, M.S., Katzenbach, C., Mao, Y., Richter, V. and Zeng, J. (2025). Sociotechnical imaginaries and public communication: Analytical framework and empirical illustration using the case of artificial intelligence. Convergence The International Journal of Research into New Media Technologies. doi:https://doi.org/10.1177/13548565251338192.
Gillespie, A., Glăveanu, V., de Saint-Laurent, C., Zittoun, T. and Bernal Marcos, M.J. (2024). Multi-Resolution Design: Using Qualitative and Quantitative Analyses to Recursively Zoom in and out of the Same Dataset. Journal of Mixed Methods Research. doi:https://doi.org/10.1177/15586898241284696.
Laurer, M., Atteveldt, van, Casas, A. and Welbers, K. (2023). Building Efficient Universal Classifiers with Natural Language Inference. arXiv (Cornell University). doi:https://doi.org/10.48550/arxiv.2312.17543.

