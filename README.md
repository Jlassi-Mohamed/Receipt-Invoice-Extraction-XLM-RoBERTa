### Project Overview

This repository presents the first approach in our End-of-Year Project, which aims to automate the extraction of entities (such as numbers, dates, products, etc.) from invoices and receipts.

In this approach, we use a traditional NLP method by fine-tuning the **XML-RoBERTa** model on [this dataset](https://github.com/mouadhamri/invoice_dataset). While this method offers high speed and efficiency, it falls short in terms of performance and accuracy due to its lack of awareness of layout and bounding box information—critical aspects in document understanding.

For comparison, our project also explores two additional approaches:
- Using layout-aware models like **LiLT** and **LayoutLMv3**
- Using **prompt engineering** with generative models such as **Qwen2** and **Qwen2.5-VL**
