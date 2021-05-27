# tessdata_best – Best (most accurate) trained models

This repository contains the best trained models for the
[Tesseract Open Source OCR Engine](https://github.com/tesseract-ocr/tesseract).

These models only work with the LSTM OCR engine of Tesseract 4.

### Data files for a particular script

Initial capitals in the filename indicate the one model for all languages in that script. These are now available under script subdirectory.

- **GT4HistOCR** finetuning of the **Fraktur** model based on the GT4Hist dataset with about 5000000 training iterations. These model is called Fraktur_50000000.402_257887, if you want to use another model from the training output see [Fraktur_5000000](https://ub-backup.bib.uni-mannheim.de/~stweil/ocrd-train/data/Fraktur_5000000/).
- **frak2021** a model trained from scratch based on GT4Hist, ÖNB and Fibel dataset. These model is called frak2021_1.028_762537_3731130, if you want to use another model from the training output see [frak2021](https://ub-backup.bib.uni-mannheim.de/~stweil/tesstrain/frak2021/).

--------------------------------

All data in the repository are licensed under the
Apache-2.0 License, see file [LICENSE](LICENSE).
