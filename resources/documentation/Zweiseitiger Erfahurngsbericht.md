# Innovationsprojekt Amrein & Furrer

## Ziel
Ziel ist es mit Machine Learning (ML) und Deep Learning (DL) eine Vorhersage über die zukünftigen Covid Fallzahlen vorherzusagen.

## Arbeitsaufteilung
Marco Daten zusammensammeln in eine CSV Datei
Jonas: Daten Analyse und Bereinigung
? : Preparierne der Daten
Modelle : 


Datenaufbereitung gemeinsam

Gegenseitiges Review und austesten, verbessern

# Methodik
Zuerst mit Google Colab, dann mit Anakonda. Zuletzt gute Erfahrung mit Code Bearbeitung in Visual Studio Code und Remote Anaconda Server.
Für die gemeinsame Datenablage haben wir uns für eine Github Projekt entschieden. 

Problem: Jupyter Notebook Änderungen im Git sind nicht sehr gut nachvollziehbar. Es wird nicht nur der Phyton Code eingecheckt sondern auch die zueletzt ausgeführten Daten.

# Einführung in Machine Learing und Deep Learning
Machine Learning wird bei strucktuierten Daten verwendet.

Deep Learning wird bei unstrucktuierten Daten verwendet.

## Hypothese


## Herausforderung
- Daten in Zeitstrahl
- Visualisierung der Daten 


## Erkenntnisse

## Persönliche Erfahrungen
Roh-Daten Analyse ist sehr wichig, Daten müssen von beiden gleich verstanden werden und beide müssen das gleiche Verständnis dafür haben. Dank genauer Datendefinitionen wie https://www.covid19.admin.ch/api/data/documentation/models/sources-definitions-hospcapacitydailyincomingdata.md ist es gut nachvollziehbar was in den Daten vorhanden ist.

## Empfehlung seitens Bund
Öffentliches ML oder DL Modell für jeden einsehbar und nachvollziehbar für Versierte. Modell kann auch jeder bei sich zu Hause ausführen. 
Das führt zu einer höheren Transparenz gegenüber der Bevölkerung. Durch den Aufbau einer Community könnte das Modell kontinuierlich verbessert werden.
Ausw

## Auswahl der Modelle
Rückmeldung von Ladan Pooyan-Weihs zu den Modellen:
> ML- Linear Regression ist für unabhängige Daten (im Sinne der War’keit). Aber Time series sind abhängig.
> ML-Logistics: Dieses ist für die Klassifizierung. Es scheint nicht geeignet für dieses Projekt zu sein.
> ML-Support Vector Machine: hauptsächlich für die Klassifikation aber Regression ist auch möglich. Falls dieses untersucht werden sollte, könnte man dann sagen, wie gut dieses Model für Regression geeignet ist
> ML- Decision Tree: hauptsächlich für die Klassifikation aber Regression ist auch möglich. Falls dieses untersucht werden sollte, könnte man dann sagen, wie gut dieses Model für Regression geeignet ist
> DL- Multilayer Perceptron (MLP): Klassisch. Sie können dieses Model mit den Daten untersuchen und dann feststellen, wie gut dieses Model ist
> DL- Long short-term memory (LSTM): Es sollte mit Time series Date gehen. Falls dieses untersucht werden sollte, könnte man dann sagen, wie gut dieses Model für Regression geeignet ist
> DL- Convolutional Neural Network (CNN): Eher geeignet für Bilder als andere Dinge.

Wir beschränken uns auf folgende Modelle:
- Polynomiale Regression
- CNN
- LSTM