# Hi, I'm Aakash 👋

I use these repositories to practise careful engineering: checking whether results hold up, testing the important behaviour,
and writing down what doesn't work as well as what does.

## Projects

| Project | What it is | What I focused on |
|---|---|---|
| [crypto-price-prediction](https://github.com/Aakashnaidum/crypto-price-prediction) | Next-day closing-price forecasts for five cryptocurrencies, with a Django app (Python, scikit-learn) | Leakage-safe features, a persistence baseline and significance tests. Result: no model reliably beats "tomorrow = today". |
| [news-classification-nlp](https://github.com/Aakashnaidum/news-classification-nlp) | Fake-vs-real and 7-way news-category classification with a Django app (scikit-learn, TensorFlow) | Found that duplicate texts inflated the original scores, and re-evaluated on de-duplicated splits. A TF-IDF baseline beats the RNN/LSTM models. |
| [voting-management-system](https://github.com/Aakashnaidum/voting-management-system) | Educational Java Servlet/JSP election app (MySQL/H2) | Security review and rebuild: hashed passwords, role checks, CSRF, one vote per voter enforced by the database, a tamper-evident ballot log. |

All three began as third-party academic project packages. Each README explains what came from that base and what I changed,
and gives the tests and results that were actually run.
