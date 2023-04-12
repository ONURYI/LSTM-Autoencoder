# LSTM Autoencoder für EKG-Anomalieerkennung

In diesem Github-Repository finden Sie Code und Daten für die Verwendung eines LSTM-Autoencoders zur Erkennung von Anomalien in Elektrokardiogrammen (EKGs). Der Code wurde in Python mit Keras und Tensorflow implementiert.

## Was ist ein LSTM Autoencoder?

Ein LSTM-Autoencoder ist ein tiefes neuronales Netzwerk, das aus zwei Hauptkomponenten besteht: einem Encoder und einem Decoder. Der Encoder lernt, eine Eingabe (in diesem Fall ein EKG) in eine komprimierte Darstellung umzuwandeln. Der Decoder lernt, die komprimierte Darstellung wieder in die ursprüngliche Eingabe zu dekodieren. Wenn der Autoencoder trainiert wird, um eine Eingabe erfolgreich zu reproduzieren, kann er als normal betrachtet werden. Wenn jedoch eine Eingabe einen signifikanten Fehler in der Reproduktion aufweist, kann sie als anomalous betrachtet werden.

## Wie wird der LSTM-Autoencoder in diesem Projekt verwendet?

In diesem Projekt verwenden wir einen LSTM-Autoencoder, um Anomalien in EKGs zu erkennen. Wir trainieren den Autoencoder mit einer Reihe von normalen EKGs und testen ihn dann auf einer Reihe von anomalen EKGs. Der Autoencoder soll in der Lage sein, die normalen EKGs erfolgreich zu reproduzieren, aber die anomalen EKGs nicht. Wir evaluieren die Leistung des Modells anhand der Precision, Recall und F1-Score.

## Daten

Die EKG-Daten für dieses Projekt stammen aus: https://www.kaggle.com/code/lionsai/p2-autoencoder-for-anomaly-detection-in-ecg/input

## Code

Der Code für das LSTM-Autoencoder-Modell ist in der Datei `lstm_autoencoder.ipynb` enthalten. 


## Verwendete Bibliotheken

* Keras
* Tensorflow
* NumPy
* Matplotlib

## Autoren

Dieses Projekt wurde von Onur Yilmaz erstellt.

