# imagessan
Images and Ground Truth files in Sanskrit along with OCR results 
for OCR evaluation

#### OCR Evaluation Tools for Character & Word Accuracy
Using https://github.com/Shreeshrii/ocr-evaluation-tools

* Changed tessaccsummary to use -psm 6

#### Using Traineddaata from the Tesseract project 
from https://github.com/tesseract-ocr/tessdata

* Hindi traineddata with CUBE
* Sanskrit Traineddata without CUBE

#### Using experimental Traineddata built with tesstrain.sh

Mutiple versions using different fonts, training texts, unicharambigs,exposure levels etc.

* Remove fonts with incorrect rendering for Sanskrit eg. Samanata, Sarai, Eczar, Kalimati, Rhodium Libre
* Removed fancy and old style fonts eg. Aparajita, Santipur OT etc.
* Remove Italic versions of fonts (Utsaah and Kokila)
* Used -1, 0, 1 exposure levels - gives thick, normal and thin variants of font
* Degradation is on by default - lines slope up and down on diff pages
* Removed orthographic syllables frequency list (sanskritweb) from training text
* Added more samples of characters ending in viraam 
* Added list of sanskrit ligatures (TITUS) to training text
* Add optional unicharambigs substitutions (one way only) - ma for bha, gha for dha etc


