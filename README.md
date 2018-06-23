# train-ASR

Repository to train voice models with new speech recognition models using KALDI. 

## how to download data

We have a custom phoneme dataset that can be accessed here. 

## goals / what to beat 

The ASR project is basically to help build an ASR model from a database of phonemes that we have assembled. I have created a training dataset of about 40 phonemes to help recognize my own voice; so that could be a starting point. But there are other programs like KALDI (https://github.com/pykaldi/pykaldi) where you can build custom ASR models based on pre-trained models using things like GMMs and other acoustic and language models (these correct for things such as speaker frequencies and format lengths - the length of the intratrachael tube so that model is not overfitted to one speaker). The goal here is to sort of look deeper into these technologies and build a minimum viable ASR that could have a tailored vocabulary (this may be important for some of the surveys we're working on, especially for medical words in transcription).

## references 
* [TED-LIUM_an_Automatic_Speech_Recognition_dedicated_corpus](https://www.researchgate.net/publication/260986481_TED-LIUM_an_Automatic_Speech_Recognition_dedicated_corpus?enrichId=rgreq-6b2e69cb437031330e5f3798c20b8d25-XXX&enrichSource=Y292ZXJQYWdlOzI2MDk4NjQ4MTtBUzoyMTIyOTM2NTc4NjIxNDhAMTQyNzYyNjE2MDMzOA%3D%3D&el=1_x_3&_esc=publicationCoverPdf)
* [librosa](https://github.com/librosa/librosa)
* [spacy](https://spacy.io/)
* [pykaldi](https://github.com/pykaldi/pykaldi)
* [SpeechRecognition / pocketsphinx](https://pypi.org/project/SpeechRecognition/)
* [google speech API](https://cloud.google.com/speech-to-text/pricing)
