# Hyperparameter
- externe Konfiguration
- werden vor dem Training manuell oder automatisch festgelegt
- beispiele sind Anzahl der Knoten und Schichten in einem neuronalen Netzwerk oder die Anzahl der Zweige in einem Entscheidungsbaum
- der Prozess der Hyperparameter-Einstellung ist iterativ was bedeutet durch probieren der verschiedenen Kombinationen von Parametern und Werten wird die ideale Hyperparameter-Einstellung herausgefunden
## Techniken zur Hyperparameter-Einstellung
- Bayesian-Optimierung
- Grid-Suche
- Zufällige Suche

Quelle: https://aws.amazon.com/de/what-is/hyperparameter-tuning/

# Feature Skalierung
- ist ein wichtiger Schritt bei der Vorverarbeitung von Daten 
- die gebräuchlichsten Techniken sind Normalisierung und Standardisierung und Min/Max-Skalierung
- bei der Normalisierung werden alle Werte zwischen zwei Zahlen gebunden typischerweise zwischen [0,1] oder [-1,1]
- das Ziel der Feature Skalierung ist das vermeiden von Dominanzen von Features

## Gradientenabstieg basierende Algorithmen
- lineare Regression, logistische Regression, neuronale Netzwerke benutzen den Gradientenabstieg als Optimierungstechnik
- diese Algorithmen benötigen die Skalierung von Daten
## Entferungsbasierte Algorithmen
- KNN, K-Means-Clustering und SVM sind stark von der Bandbreite der Funktionen betroffen
## Baumbasierte Algorithmen
- sind unempfindlich gegenüber dem Maßstab der Merkmale

Quellen: 
https://towardsdatascience.com/all-about-feature-scaling-bcc0ad75cb35
https://www.analyticsvidhya.com/blog/2020/04/feature-scaling-machine-learning-normalization-standardization/
