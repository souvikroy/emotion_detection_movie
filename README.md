# Emotion detection from the screens of a movie and use emotions to personalise the mood based recommended contents in OTT

* Problem : stagnant watchtime/user for OTT whereas video start/session & completion rate of video is concerning. so, 1-1 mood based personalisation capability is required to make the next big viewership growth

* In this notebook, I will show how to detect human face, nodes-objects of faces & classify the emotion based on pre-trained transformer(Google Brain's ViT ** ). The model can be tested based on tuning criteria for further optimisation.
Further, tested emotions is used to feed into existing recommendation engine to make mood based personalised contents.

* Training Data : https://drive.google.com/file/d/1iyh_kLU5GdXKys_TAgIYpo59Vt7PC3r-/view
  
* Architecture : https://github.com/souvikroy/emotion_detection_movie/blob/main/ViT_emotion_arch.png

** Google Brain's ViT is a transformer encoder (like BERT)
