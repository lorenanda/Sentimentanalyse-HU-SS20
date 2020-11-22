Humboldt-Universität zu Berlin | Institut für deutsche Sprache und Linguistik | Sommersemester 2020 | LV "Einführung in NLP mit Python" (Thomas Krause)

## Projektgruppe
* Lorena Ciutacu
* Damyan Lissitchkov

## Thema
Sentimentanalyse von Produkt-Bewertungen

## Beschreibung

Sentimentanalyse ist eine Methode des Textmining, die es ermöglicht, die Valenz eines Textes zu erkennen und zu klassifizieren. Ziel unseres Projektes ist es, eine Sentimenanalyse von Produktbewertungen durchzuführen, um die schriftlich ausgedrückten Meinungen der Kunden als positiv/negativ zu klassifizieren. Wir analysieren deutschsprachige Bewertungen von Kleidungen und Kaffees. Die Herausforderung dieser Aufgabe besteht darin, dass die Tools für Sentimentanalyse vorwiegend auf die englische Sprache trainiert sind und nicht einfach auf Deutsch übertragen werden können. Dafür verwenden wir verschieden Libraries und vergleichen ihre Leistung bzw. Genauigkeit für deutsche Texte.

## Daten
In diesem Projekt benutzen wir die folgende Datasets:

* [Kaffee Bewertungen](https://www.kaggle.com/mldado/german-online-reviewsratings-of-organic-coffee)
* [E-Commerce Kleidungsbewertungen](https://www.kaggle.com/timoboz/womens-ecommerce-clothing-reviews)
* [Studenten Bewertungen von deutschen Unis](https://www.kaggle.com/longnguyen2306/germany-universities-reviews-and-recommendation)

## Analyse
Erstens haben wir eine [Text- bzw. Sentimentanalyse von deutschen Kaffeebewertungen](https://github.com/lorenanda/Sentimentanalyse-HU-SS20/blob/master/sentiment_analyse.ipynb) mit VADER und TextBlob durchgeführt.

Zweitens haben wir englische und deutsche Kleidungsbewertungen (übersetzte Bewertungen) mit SpaCy verarbeitet, dann zwei Machine Learning Modelle für die [Klassifizierung von Sentiment-Scores](https://github.com/lorenanda/Sentimentanalyse-HU-SS20/blob/master/spacy_kleidung.ipynb) verwendet und folgende Genauigkeit Werte erreicht:
- Logistic Regression: 95,65% auf English bzw. 86,53% auf Deutsch
- Support Vector Classifier: 86,46% auf English

## Tools
* NLTK ([VADER](https://www.nltk.org/howto/sentiment.html))
* [TextBlob](https://textblob.readthedocs.io/en/dev/quickstart.html#sentiment-analysis)
* [SpaCy](https://spacy.io/usage/models)
* [Sentiment Wortschatz](https://wortschatz.uni-leipzig.de/en/download/)
