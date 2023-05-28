# Getting Started in 'ML-Audio'
Suggestions for students.

## About
Audio and acoustics students sometimes ask "How do I get started learning  machine learning?"  Not everyone gets their start in a major research environment, so this page is intended to serve as a series of suggestions for those who may find themselves "on their own" in their interest in this area.  It was started by @drscotthawley and [Ryan Miller](https://www.linkedin.com/in/ryan-miller-1aa8355a/), but is intended to serve and evolve with the community. 

- ***This is a collaborative page. Please suggest additions, re-organizations, edits, updates, etc., either via Issues or Pull Requests.***  *(In addition, @drscotthawley may gladly cede control of this content to whichever student or group wants to Wiki-fy it!)*

## Active Practictioners to Follow
Many of us learn about and contribue to news of new developments, papers, conferences, grants, and networking opportunities via [Twitter](http://www.twitter.com).

* [Audio ML Twitter list](https://twitter.com/i/lists/1260142677884121088) by Fabian-Robert Stöter (@faroit).  **<-- Follow these people!**

## Quick Quotes
* [Justin Salomon](https://twitter.com/justin_salamon/status/1202016519720300545): "Anyone working in ML, *anyone*, should be *obliged* to curate a dataset before they're allowed to train a single model. The lessons learnt in the process are invaluable, and the dangers of skipping said lessons are manifold (see what I did there?)"

## Best Practices
["Tips for Publishing Research Code"](https://github.com/paperswithcode/releasing-research-code) courtesy of  [Papers with Code](https://paperswithcode.com/)

## General Reference Information
* [Machine Learning Glossary](https://ml-cheatsheet.readthedocs.io/en/latest/index.html) - A reference resource for common ML math topics, definitions, concepts, etc.
* [Notes on Music Information Retreival](https://musicinformationretrieval.com/)

## Online Training (ML+audio Specific)
* [Valerio Velardo's "Deep Learning for Audio"](https://www.youtube.com/watch?v=fMqL5vckiU0&list=PL-wATfeyAMNrtbkCNsLcpoAyBBRJZVlnf)  
* [Jordi Pons' "Deep neural networks for music"](http://www.jordipons.me/apps/teaching-materials/) teaching materials

## Online Training (More General, Courses)
* Rebecca Fiebrink's [Machine Learning for Musicians and Artists](https://www.kadenze.com/courses/machine-learning-for-musicians-and-artists/info) on Kadenze -- No actual audio DSP, but great for concepts, interactive and fun (no math!)
* [Advanced Digital Signal Processing](https://github.com/GuitarsAI/ADSP_Tutorials) series taught by Dr.-Ing Gerald Schuller of Fraunhofer IDMT, with [videos](https://www.youtube.com/playlist?list=PL6QnpHKwdPYjbDezYkAE-sAQ5MOpYeqM6) and acommpanying Jupyter notebooks by [Renato Profeta](https://twitter.com/guitars_ai) 
* [Andrew Ng's ML Course](https://www.coursera.org/learn/machine-learning) on Coursera (Good all-around ML course)
* [Fast.ai](https://www.fast.ai) (Can get you up and running fast)
* [Neural Network Programming - Deep Learning with PyTorch](https://deeplizard.com/learn/video/v5cngxo4mIg). Learn how to code an image predictor neural network in Pytorch. Provides practical NN fundamentals
* [Foundations of Machine Learning](https://bloomberg.github.io/foml/#home) taught by [David Rosenberg](https://bloomberg.github.io/foml/#people)

## Tutorials
* Andrew Trask's ["Anyone Can Learn To Code an LSTM-RNN in Python"](https://iamtrask.github.io/2015/11/15/anyone-can-code-lstm/) 
* [Machine Learning & Deep Learning Fundamentals](https://deeplizard.com/learn/video/gZmobeGL0Yg) (Good high level intro to ML concepts and how neural networks operate)

## Talks (at conferences)
Talks we found helpful/inspiring (and are hopefully still relevant). TODO: add more recent talks! 
* Paris Smaragdis at SANE 2015: ["NMF? Neural Nets? It’s all the same..."](https://www.youtube.com/watch?v=wfmpViJIjWw)
* Ron Weiss at SANE 2015: ["Training neural network acoustic models on waveforms"](https://www.youtube.com/watch?v=sI_8EA0_ha8)
* Jordi Pons at DLBCN 2018: ["Training neural audio classifiers with few data"](https://www.youtube.com/watch?v=AJ-XM07wSjg)
* Sander Dieleman at ISMIR 2019: ["Generating Music in the Waveform Domain"](https://benanne.github.io/2020/03/24/audio-generation.html?fbclid=IwAR3nw8WLrT3ZVFrz4AsxNeoufUllqHQO4wFvH3bafqfjJDJArnm5s2VOxLM)

## Key Papers / Codes
(Let's try to list "representative" or "landmark" papers, not just our latest tweak, unless it includes a really good intro/review section. ;-) )
* Keunwoo Choi et al, ["Automatic tagging using deep convolutional neural networks"](https://arxiv.org/abs/1606.00298) (ISMIR 2016 Best Paper)
* [SampleRNN](https://arxiv.org/abs/1612.07837)
* [WaveNet](https://arxiv.org/pdf/1609.03499.pdf)
* [WaveRNN, i.e. "Efficient Neural Audio Synthesis"](https://arxiv.org/abs/1802.08435)
* [GANSynth](https://magenta.tensorflow.org/gansynth)
* [Wave-U-Net](https://arxiv.org/pdf/1806.03185.pdf)

## Demos
(Not sure if this only means "deployed models you can play with in your browser," or if other things should count as demos)
* Chris Donahue's [WaveGAN Demo](https://chrisdonahue.com/wavegan/)
* Scott Hawley's [SignalTrain Demo](http://signaltrain.herokuapp.com/)
* Neil Zeghidour and David Grangier's [Wavesplit](https://soundcloud.com/wavesplitdemo)
* David Samuel, Aditya Ganeshan, and Jason Naradowsky's [Meta-TasNet](https://paperswithcode.com/paper/meta-learning-extractors-for-music-source)


## Packages & Libraries
* [awesome-python-scientific-audio](https://github.com/faroit/awesome-python-scientific-audio) Curated list of python software and packages related to scientific research in audio
* [Librosa](https://librosa.github.io/librosa/) Great package for various kinds of audio analysis and manipulation
* [Audiomentations, data augmentation for audio](https://github.com/iver56/audiomentations)
* [tf.signal: signal processing for TensorFlow](https://www.tensorflow.org/api_docs/python/tf/signal)
* [fastai_audio](https://github.com/mogwai/fastai_audio) (and [fastai2_audio](https://github.com/rbracco/fastai2_audio)), audio libraries for [Fast.ai](https://www.fast.ai) library/[MOOC](https://course.fast.ai). Primarily for image, text & tabular data processing, there are efforts to add audio. (Work in progress.)

## Tools / GUIs / Gists
* Jesse Engel's [gist to plot "rainbowgrams"](https://gist.github.com/jesseengel/e223622e255bd5b8c9130407397a0494)

## Books

* [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) online book.  How drscotthawley first started reading.
* [Open-Source Tools & Data for Music Source Separation](https://source-separation.github.io/tutorial/landing.html) by By Ethan Manilow, Prem Seetharaman, and Justin Salamon (2020). An online, interactive book with Python examples! 
* [List of Books Recommended by ML expert Juergen Schmidthuber](https://www.reddit.com/r/MachineLearning/comments/2xcyrl/i_am_jürgen_schmidhuber_ama/cp5c0py/) for students entering his lab. (Probably pretty demanding material.)


## Computer-Related Topics
Python: 
* [learnpython.org](https://www.learnpython.org/)
* Python notebooks for [fundamentals of music processing](https://www.audiolabs-erlangen.de/resources/MIR/FMP/C0/C0.html)


## Signal Processing Topics
* [Advanced Digital Signal Processing](https://github.com/GuitarsAI/ADSP_Tutorials) series taught by Dr.-Ing Gerald Schuller of Fraunhofer IDMT, with [videos](https://www.youtube.com/playlist?list=PL6QnpHKwdPYjbDezYkAE-sAQ5MOpYeqM6) and acommpanying Jupyter notebooks by [Renato Profeta](https://twitter.com/guitars_ai) 
* [An Interactive Introduction to Fourier Transforms](http://www.jezzamon.com/fourier/) by Jez Swanson. (so good!)
* Yuge Shi's ["Gaussian Processes, Not Quite for Dummies"](https://thegradient.pub/gaussian-process-not-quite-for-dummies/) (GPs get used for *much* more than signal processing, but are also promising there; feel free to suggest a different category for this content)


## Statistics / Math Topics
* Gradient Descent 
  * https://ml-cheatsheet.readthedocs.io/en/latest/gradient_descent.html ,
  * https://en.wikipedia.org/wiki/Gradient_descent ,
  * https://www.kdnuggets.com/2017/04/simple-understand-gradient-descent-algorithm.html,
  * ["Following Gravity"](https://drscotthawley.github.io/Following-Gravity/) by @drscotthawley
* Principal Component Analysis:  ["PCA From Scratch"](https://drscotthawley.github.io/PCA-From-Scratch/) by @drscotthawley


## Datasets (raw audio)
One finds that many supposed "audio datasets" are really only features or even just metadata!  Here are some "raw audio" datasets:
* [NSynth](https://magenta.tensorflow.org/datasets/nsynth) Musical Instruments
* [GTZAN Genre Collection](http://marsyas.info/downloads/datasets.html)  (Note [critique by Bob Sturm](https://arxiv.org/abs/1306.1461))
* [Fraunhofer IDMT Guitar/Bass Effects](https://www.idmt.fraunhofer.de/en/business_units/m2d/smt/audio_effects.html)
* [Urban Sound Dataset](serv.cusp.nyu.edu/projects/urbansounddataset)
* [FreeSound Annotator](https://annotator.freesound.org/) (formerly FreeSound Datasets)
* [FSD50K dataset (from FreeSound)](https://annotator.freesound.org/fsd/release/FSD50K/)
* [AudioSet](https://research.google.com/audioset)
* [Birdvox-Full-Night](https://wp.nyu.edu/birdvox/birdvox-full-night/)
* [SignalTrain LA2A](https://zenodo.org/record/3348083)
* [Kaggle Heartbeat Sounds](https://www.kaggle.com/kinguistics/heartbeat-sounds)
* [Electric Guitars](http://www.rptecnologias.com/research/guitar-dataset) by Renato Profeta ("Guitars AI") of Fraunhofer IDMT
* Search for other [audio datasets at Kaggle](https://www.kaggle.com/datasets?tags=16072-audio+data) (list)
* [A collated list of MIR datasets can be found here](https://github.com/ismir/mir-datasets), which is the source for [audiocontentanalysis.org](https://www.audiocontentanalysis.org/data-sets/),but only some are raw audio
* Another [list of "audio datasets" by Christopher Dossman](https://towardsdatascience.com/a-data-lakes-worth-of-audio-datasets-b45b88cd4ad)
* [A list of ai audio datasets by Yuan Man](https://github.com/Yuan-ManX/ai-audio-datasets-list)
* ...your dataset here...

## DIY Audio Dataset-Making:

(Inspired by [Nathan Sepulveda](https://twitter.com/nateysepy))

### Searchable resources:
* FreeSound: https://freesound.org/

* Internet Archive audio: https://archive.org/details/audio

* https://search.audioburst.com/ - speech only. you're searching transcripts.

* https://www.mp3juices.cc/ - searches YouTube, lets you download MP3 by pressing a button for each one.

* https://sounds.com/ from National Instruments, but it won't be free!

* https://www.findsounds.com/ meh.

### Scrapers

* https://github.com/carlthome/audio-scraper: "Scrape audio from YouTube and SoundCloud with a simple command-line interface", e.g. `audio-scraper "acoustic guitar"`. It's 5 years old, but it still works in 2021!

### Other DIY Audio Dataset Tricks

* Depending on your application, you might be able to get away with using *samples* produced by virtual instruments (i.e. MIDI). 
* If you don't have a lot of labels or targets, you can still pretrain your represenations & weights using autoregressive predictions (even for different audio domains) -- this amounts to doing your own Transfer Learning even without a pretrained model. (This strategy was used by FastAI's text language model system "ULMFit")

### Cleaning Audio Datasets?
With images, you can quickly look at many of them almost at once. 
With audio, you have to listen to *each one*.  But take a cue from fast.ai's Jeremy Howard: 

> "It's easier to clean a dataset once you've trained a model."  

So we can train the model, and then look for high-loss / low-confidence ratings for certain samples: those should be the ones we should check *first*. 

Could even start with someone else's pretrained model and look for anomalies when running inference on your data, i.e. similar inputs *should* yield similar outputs, so if they don't...?

#### Length of audio?
You might be able to find short samples of exactly what you need, but it's also common to have the desired audio be just a part of a much longer clip.  How to segment it and keep just what you want? You could use other people's models, e.g. for detecting speech or guitars:
* Delete what you don't want: Audio you might get off YouTube needs to be segmented in order to make it useful -- the stuff you don't want needs to be cut out.  If you're looking for musical audio, you could use a *speech detector* (there are lots of them available) and then *delete or ignore all the speech*. 
* What if all you want is the guitar solo, not the whole song?  Someone else's pretrained model for detecting guitars could help you.

#### Are we classifying or regressing?

Standards are a lot higher for regression systems, e.g. phase errors / time alignment issues probably won't matter to a classifier, but might for a regression model, depending on the goal. What about clipping, distortion,...?  This will depend on what you're trying to do. 


## "Major" ML-Audio Research/Development Groups
#### Universities:
(or, "Where should I apply for grad school?")
* QMUL (London)
* UPF (Barcelona)
* CRRMA (Stanford, San Francisco)
* IRCAM (Paris)
* NYU (New York)

#### Industry:
("Where can I get an internship/job"?)
* [Google Magenta](https://magenta.tensorflow.org)
* [Google Perception](https://research.google/teams/perception/) ([speech publications](https://research.google/pubs/?team=perception&area=speech-processing))
* Adobe
* Spotify
* Increasingly, everywhere. ;-)

## Conferences
("Which conference(s) should I go to?" -- asked by student on the day this doc began)
#### Audio-Specific
**Long list of Music Technology specific conferences [https://conferences.smcnetwork.org/](https://conferences.smcnetwork.org/) - which is references from here [https://github.com/MTG/conferences](https://github.com/MTG/conferences)
* Audio Engineering Society (AES)
* ASA
* Digital Audio Effects (DAFx)
* ICASSP
* ISMIR
* SANE
* Web Audio Conference (WAC)
* SMC
* LVA/ICA
* Audio Mostly
* WIMP
* DCASE
* CSMC
* MuMe
* ICMC
* CMMR
* IBAC
* MLSP
* Interspeech
* FMA

#### General ML
* ICLR
* ICML
* NeurIPS
* IJCNN
* 

## Journals
("Where can I get published?")

* [IEEE TASLP](https://signalprocessingsociety.org/publications-resources/ieeeacm-transactions-audio-speech-and-language-processing)
* [JAES](http://www.aes.org/journal/)
* [CMJ](http://computermusicjournal.org/)
* [JNMR](https://www.tandfonline.com/toc/nnmr20/current)
* [TISMIR](https://transactions.ismir.net/)
* [JASA](https://asa.scitation.org/journal/jas)
* EURASIP Journal on Audio Speech and Music Processing 

In addition, in machine learning specifically, the tendency is for conference papers to be peer-reviewed and to "count" as journal publications.

## Competitions / Benchmarks
Some are yearly, some may be defunct but still interesting.
* [MIREX](https://www.music-ir.org/mirex/wiki/MIREX_HOME)
* [SiSEC](https://sisec18.unmix.app/#/) (Signal Separation Evaluation Campaign)
* [Kaggle Heartbeat Sounds](https://www.kaggle.com/kinguistics/heartbeat-sounds)


## Contributors
[Ryan Miller](https://www.linkedin.com/in/ryan-miller-1aa8355a/), RJ Skerry-Ryan, Dave Moffat, Jesse Engel, Iver Jordal

*If you want your name listed here, you may. ;-)* 
