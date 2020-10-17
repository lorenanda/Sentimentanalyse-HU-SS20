Humboldt-Universität zu Berlin, Institut für deutsche Sprache und Linguistik, SS 2020

**Lehrveranstaltung**: "Einführung in NLP mit Python" (Thomas Krause)

**Projektgruppe**:
* Lorena Ciutacu
* Damyan Lissitchkov


**Thema**: Sentimentanalyse

**Beschreibung**:

Sentimentanalyse ist eine Methode des Textmining, die es ermöglicht, die Valenz eines Textes zu erkennen und zu klassifizieren. Ziel unseres Projektes ist es, eine Sentimenanalyse von Produktbewertungen durchzuführen, um die schriftlich ausgedrückten Meinungen der Kunden als positiv/negativ zu klassifizieren. Wir analysieren deutschsprachige Bewertungen von Kleidungen und Kaffees. Die Herausforderung dieser Aufgabe besteht darin, dass die Tools für Sentimentanalyse vorwiegend auf die englische Sprache trainiert sind und nicht einfach auf Deutsch übertragen werden können. Dafür verwenden wir verschieden Libraries und vergleichen ihre Leistung bzw. Genauigkeit für deutsche Texte.

In einer ersten Phase, analysieren wir deutsche Kaffeebewertungen mit VADER und TextBlob, zwei Libraries, die auch Deutsch unterstützen.

In der zweiten Phase, analysieren wir englische und deutsche Kleidungsbewertungen (übersetzte Bewertungen) mit SpaCy und vergleichen die Ergebnisse zwischen den zwei Sprachen.

**Datasets**:
In diesem Projekt benutzen wir die folgende Datasets:

* [Kaffee Bewertungen](https://www.kaggle.com/mldado/german-online-reviewsratings-of-organic-coffee)
* [E-Commerce Kleidungsbewertungen](https://www.kaggle.com/timoboz/womens-ecommerce-clothing-reviews)
* [Studenten Bewertungen von deutschen Unis](https://www.kaggle.com/longnguyen2306/germany-universities-reviews-and-recommendation)

**Ergebnisse**
Wir haben zwei Machine Learning Modelle für die Klassifizierung von Sentiment-Scores verwendet und folgende Genauigkeit Werte erreicht:
- Logistic Regression: 95.65% auf English, 86.53% auf Deutsch
- Support Vector Classifier: 86.46% auf English

**Tools**:
* NLTK ([VADER](https://www.nltk.org/howto/sentiment.html))
* [TextBlob](https://textblob.readthedocs.io/en/dev/quickstart.html#sentiment-analysis)
* [SpaCy](https://spacy.io/usage/models)
* [Sentiment Wortschatz](https://wortschatz.uni-leipzig.de/en/download/)

**Quellen / Tutorials**:
* [VADER](https://github.com/cjhutto/vaderSentiment#demo-including-example-of-non-english-text-translations)
* [SpaCy](https://medium.com/analytics-vidhya/training-your-own-sentiment-analyzer-with-spacy-9b924df1514c)
* [Common pitfalls with the preprocessing of German text for NLP](https://medium.com/idealo-tech-blog/common-pitfalls-with-the-preprocessing-of-german-text-for-nlp-3cfb8dc19ebe)