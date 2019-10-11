# Dataset collection
A list of publicly available datasets (or available upon request) grouped not just by data type but also according to information related to the domain a trained model would be applicable.

## Speech

### Reading:
* **LibriSpeech**: 1000 hours of read books (audiobooks) in English. [[Link]](http://www.openslr.org/12)
* **VCC Challenge 2016 dataset**: A cleaner version of the DAPS dataset. The data contains 20 speakers (10 male and 10 female), reading five excerpts each, about 13 minutes per speaker. The excerpts are read in 4 different recording settings (Raw, Clean Raw, Produced and Device). [[Link]](https://datashare.is.ed.ac.uk/handle/10283/2211)
* **ZeroSpeech2019**: The training data was recorded from 1 male and 1 female for 2 hours per talker and read text from 100 speakers with 10 minutes per speaker. There is also data contains also parallel utterances from a target voice and other voices. Lastly, the test set contains 15 speakers with about 2 minutes of speech per speaker. [[Link]](https://zerospeech.com/2019/index.html)

### Pre-recorded speech replayed
* **The VOiCES Corpus**: Pre-recorded clean speech (from LibriSpeech) played and recorded again under realistic conditions from 12 different microphones. 120 hours of speech were recorded per mic (1440 hours in total). Audio was recorded with only the ambient room noise but also with a distractor adding noise on the foreground speech. The distractor was either TV noise, music being played or babble noise. [[Link]](https://voices18.github.io/downloads/ )

### Spoofed speech

#### Spoofed speech from TTS and VC
* **ASVspoof2015**: Genuine speech collected from 106 speakers (45 male and 61 female) and spoofed speech generated from the genuine data using different spoofing algorithms. The dataset was created for a challenge where the task was to discriminate genuine human speech from speech produced from text-to-speech (TTS) and voice conversion (VC). [[Link]](https://datashare.is.ed.ac.uk/handle/10283/853) 
#### Spoofed speech from recording genuine speech
* **ASVspoof2017v2:** A set of genuine speech recordings and spoofed ones. The genuine ones are a subset of the RedDots database which was collected by volunteers using Android Smartphones. Utterances correspond to 10 fixed phrases. The spoofed recordings were generated by recording genuine ones in a variety of environments and using different devices. [[Link]](https://datashare.is.ed.ac.uk/handle/10283/3055=) 

### Emotional Speech

#### Non-scripted
* **FAU Aibo Emotion Corpus**: 9 hours of 51 young (10-13 y/o) children interacting in German with a pet robot. 11 Emotion categories. 
 [[Link]](https://www5.cs.fau.de/de/mitarbeiter/steidl-stefan/fau-aibo-emotion-corpus/) 

#### Scripted
* **Interface ("Multimodal Analysis/Synthesis System for Human Interaction to Virtual and Augmented environments"):** Acted speech in Slovenian, English, Spanish and French. One male and one female actors per language except for two males and one female in English. About 4 hours per speaker. Currently (10/10/2019) only the Spanish recordings are available but the rest are to be published too.  [[Link]](http://universal.elra.info/product_info.php?cPath=37_39&products_id=62) 
* **The Sincere Apology Corpus (SinA-C):** English speech recorded from 15 male and 17 female, 20 to 60 year old people, 27 of them being native American and 5 from other nationalities but fluent in English. 24 of the people were actors while 12 were artists. The speakers were instructed to speak in four prosodic styles: i)monotonic, ii) pitch prominence, iii) fast speaking rate, iv) slow speaking rate.The dataset is annotated in terms of the sincerity perceived by listeners. [[Link]](https://zenodo.org/record/3241253#.XaA6CEYzZPY)

### Medical
* **VanDam Validation HomeBank Corpus:** About 7.5 hours of data selected from single-day recordings from the home-environment of 15 families with children that either develop or already have hearing problems. The children were 7-33 months old and the data was recording through a LENA system worn by the child. [[Link]](https://homebank.talkbank.org/access/Public/VanDam-Validation.html)
* **Parkinson Speech Dataset with Multiple Types of Sound Recordings Data Set**: Contains sound recordings from 20 people with Parkinson (14 males and 6 females) and 20 without (10 males and 10 females). [[Link]](https://archive.ics.uci.edu/ml/datasets/Parkinson+Speech+Dataset+with++Multiple+Types+of+Sound+Recordings#)
 
### Events in speech
* **SSPNet Vocalization Corpus**: Audio from 63 females and 57 males, unacquainted with each other, trying to solve the Winter Survival Task over phone. [[Link]](http://www.dcs.gla.ac.uk/vincia/?p=378)
* **SSPNet Conflict Corpus**: 1430 audioclips, 30 seconds each from 45 political debates televised in Switzerland. Data dedicated to detecting conflicts in speech, which are common in debates. [[Link]](http://www.dcs.gla.ac.uk/vincia/?p=270)
* **IBM Debate Speech Analysis Corpus:** Dataset made up from 3 separate datasets with good quality sound debates. The dataset is originally purposed for Automatic Speech Recognition. [[Link]](https://www.research.ibm.com/haifa/dept/vst/debating_data.shtml#Project)


## Multimodal

### Interviews
* **VoxCeleb**: Large scale dataset consisting of 2000 hours of audiovisual data from interviews uploaded to YouTube with 7000+ speakers of which 1251 are celebrities. [[Link]](http://www.robots.ox.ac.uk/~vgg/data/voxceleb/)

### Emotional speech
#### Scripted
* **Multimodal EmotionLines Dataset (MELD):** Dialogue data from the Friends TV series labelled with emotions such as Anger, Disgust, Sadness, etc. or a sentiment label (positive, negative or neutral).[[Link]](https://github.com/SenticNet/MELD)
#### Mixed scripted and non scripted
* **IEMOCAP**: Data from 10 actors, male and female having affective dyadic interactions in both improvised and scripted sessions. Comprises of 12 hours of audiovisual data with text along with the scripted data.  [[Link]](https://sail.usc.edu/iemocap/iemocap_release.htm)

### Medical
* **Dem@Care**: Audio-visual and physiological sensor data collected from lab and home experiments from Greek dementia patients. The dataset includes samples recorded during sleep and motion.  [[Link]](http://www.demcare.eu/results/datasets)
* **DAIC-WOZ**: About 50 hours of transcribed audio-visual data recorded from clinical interviews designed to support the diagnosis of anxiety, depression and PTSD. Part of the data was interviews conducted by a human controlled virtual interviewer.  [[Link]](
http://dcapswoz.ict.usc.edu/)

### Indoor noisy environment

#### Non-scripted
* **CHiME-5**: Audio data along with the transcriptions from 20 dinner parties (minimum 2 hours each) with two hosts and two guests each. The party members were all close friends and were instructed to act naturally. The transcriptions include annotations such as noise (when non-language noise is made), inaudible, laughter or reducted (removed for privacy reasons). [[Link]](http://spandh.dcs.shef.ac.uk/chime_challenge/CHiME5/data.html)



