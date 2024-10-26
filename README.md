# Compression/Décompression Audio avec DWT et LZW

## Overviwe
Ce projet implémente un outil de compression et de décompression de fichiers audio. La compression est réalisée en utilisant une combinaison des algorithmes **Transformée en Ondelette Discrète (DWT)** et **Lempel-Ziv-Welch (LZW)**. Cet outil permet de réduire la taille des fichiers audio (WAV, MP3, OGG, etc.) tout en préservant autant que possible la qualité audio. Le format de compression utilisé est nommé **IRM** (Informatique, Réseaux et Multimédias), inspiré de notre filière académique.

## Fonctionnalités
- Compression des fichiers audio avec les techniques DWT et LZW.
- Prise en charge de formats audio courants tels que WAV, MP3, OGG.
- Réduction efficace de la taille des fichiers tout en conservant l'essentiel de l'information audio.
- Récupération du fichier audio original lors de la décompression avec une perte minimale.

## Prérequis
- Python 3.x
- Bibliothèques Python requises :
  - numpy
  - pywavelets
  - scipy
  - matplotlib

Vous pouvez installer les dépendances en utilisant la commande suivante :
```bash
pip install numpy pywavelets scipy matplotlib
