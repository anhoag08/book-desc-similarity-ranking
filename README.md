## Requirements
pip install fasttext

## Installation

1. Chạy file model-install.py để tải model và nén model

2. Chạy file tfidf-ranking

```
  calculate_tfidf(desc_list): Nhận vào desc list với desc của người dùng ở đầu
  text_embedding(tfidf_scores=tfidf_scores): Trả về ranking các score similarity của các desc so với desc người dùng
```

