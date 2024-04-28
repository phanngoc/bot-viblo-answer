# Bot-viblo-answer

Repo dùng để crawl dữ liệu của viblo website chuyên mục hỏi đáp. Mục đích để thực tập question answer trong gpt2, mang tính chất research và học tập, everyone có thể tham khảo vui vẻ là chính ạ =)) 


## List feature of each notebook:

### Crawl data and setup table in mysql.
- viblo_interview-crawl: Use for crawl data from viblo.io

### Auto classify for interview question (Mutilabel classify).

- classify-deep-word2vec.ipynb: use keras + word2vec embedding.
- classify-use-svc.ipynb: use ittdf + SVC
- viblo-classify/tagging-sent-embed.ipynb: use sentence embedding + RandomForestClassifier
  
So i can see use ittdf + SVC is best model for classify interview question.

> Tf–idf is built directly on this data, so it is much more accurate than pre-trained model.


