# CIKM-2024
<h1>BanFakeNews-2.0</h1>
<p> The spread of fake news is a pressing global issue, especially in low-resource languages like Bangla, which lack sufficient datasets and tools for effective detection. Manual fact-checking, though accurate, is time-consuming and allows misleading information to propagate widely. Building on previous efforts, we introduce BanFakeNews-2.0, an enhanced dataset that significantly advances fake news detection capabilities in Bangla. This new version includes 11,700 additional meticulously curated and manually annotated fake news articles, resulting in a more balanced and comprehensive collection of 47,000 authentic news and 13,000 fake news items across 13 categories. In addition, we develop an independent test dataset with 460 fake news and 540 authentic news for rigorous evaluation. To understand the data characteristics, we perform an exploratory analysis of BanFakeNews-2.0 and establish a benchmark system using cutting-edge Natural Language Processing (NLP) techniques. Our benchmark employs transformer-based models, including Bidirectional Encoder Representations from Transformers (BERT) and its Bangla and multilingual variants. Furthermore, we fine-tune the large language models (LLMs) with Quantized Low-Rank Approximation (QLORA), leveraging gradient accumulation and a paged Adam 8-bit optimizer for classification tasks. Our results show that LLMs and transformer-based approaches significantly outperform traditional linguistic feature-based and neural network-based methods in detecting fake news. BanFakeNews-2.0's expanded and balanced dataset offers substantial potential to drive further research and development in fake news detection for low-resource languages. By providing a robust and comprehensive resource, we aim to empower researchers and practitioners to develop more accurate and efficient tools to combat misinformation in Bangla and similar languages. </p>
<h3>The following link is directed to our BanFakeNews-2.0 dataset which is uploaded in Kaggle platform. We have annotated our authentic news as 1 and fake news as 0</h3>
<href>https://www.kaggle.com/datasets/hrithikmajumdar/bangla-fake-news</href>