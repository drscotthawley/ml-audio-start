# Getting Started in 'ML-Audio'
Suggestions for students.
## About
Audio and acoustics students sometimes ask "How do I get started learning  machine learning?"  Not everyone gets their start in a major research environment.   

This page began after @drscotthawley felt sufficiently embarassed about not having a coherent answer. Until someone creates a "ML for Audio" online course -- **update 1/7/20:** See Valerio Velardo's ["Deep Learning for Audio"](https://www.youtube.com/watch?v=fMqL5vckiU0&list=PL-wATfeyAMNrtbkCNsLcpoAyBBRJZVlnf)! -- this page may prove helpful.


Notes:
- ***This is a collaborative page. Please suggest additions, re-organizations, edits, updates, etc., either via Issues or Pull Requests.***  *(In addition, @drscotthawley may gladly cede control of this content to whichever student or group wants to Wiki-fy it!)*
- This page is bound to be **biased** toward musical audio and deep neural network methods. Inclusion of other domains and methods -- e.g., Gaussian Processes, NMF, RBMs,... -- will depend on your submissions!
- The field advances rapidly. Some topics listed here will be timeless, others will go obsolete.  Such is the nature of the field. Let's try to keep this relevant, at least for "getting started." 


## Introductory Remarks
"Read all the tutorials and papers you can, watch videos of all the talks you can, try out and modify whatever code you can get your hands on, take whatever courses you can find, go to whatever conferences you can.  Try to build your own system, and spend all your nights and weekends improving it."  

This was the best advice some of us could give, because it was the path we took. Some such stories are shared below.  This page is an attempt to offer something more "direct" for newcomers. 

Nevertheless, a few reflective narratives may provide helpful perspectives...


## Essays / Reflections / Autobiographical Sketches
Many practicioners took very different *interdisciplinary* paths, learning from a hodgepodge of information, in order to complement their existing strengths and fill in gaps in their knowledge.  Here are some stories.

*(For submissions: Either link to elsewhere on the web, or add a file to the repo via PR. Try to make submissions conclude with a section on what you would say to new students.)*

* How `__[someone]__` got started 
* `__[a young person]'s__` story 
* The *N*-step Process that `__[this person]__` thinks all students should follow
* `__[a long-time veteran]'s__` view of the field 
* Where `__[a hot-shot postdoc]__` thinks the field is heading 
* Things `__[so-and-so]__` wishes someone had told him/her
* ...your name(s) here!...**Chris Donahue, Christian Steinmetz, Jordi Pons, Keunwoo Choi, Faro, Justin Salomon,...?**


## Quick Quotes
* [Justin Salomon](https://twitter.com/justin_salamon/status/1202016519720300545): "Anyone working in ML, *anyone*, should be *obliged* to curate a dataset before they're allowed to train a single model. The lessons learnt in the process are invaluable, and the dangers of skipping said lessons are manifold (see what I did there?)"
* `__[so-and-so]'s__` suggestion
* A nugget of wisdom from `__[noted practicioner]__`

## Online Courses

* [Valerio Velardo's "Deep Learning for Audio"](https://www.youtube.com/watch?v=fMqL5vckiU0&list=PL-wATfeyAMNrtbkCNsLcpoAyBBRJZVlnf)
* [Andrew Ng's ML Course](https://www.coursera.org/learn/machine-learning) on Coursera (Good all-around ML course)
* [Fast.ai](https://www.fast.ai) (Can get you up and running fast)
* Rebecca Fiebrink's [Machine Learning for Musicians and Artists](https://www.kadenze.com/courses/machine-learning-for-musicians-and-artists/info) on Kadenze  (No math!)
* [Neural Network Programming - Deep Learning with PyTorch](https://deeplizard.com/learn/video/v5cngxo4mIg)
* [Advanced Digital Signal Processing](https://github.com/GuitarsAI/ADSP_Tutorials) series taught by Dr.-Ing Gerald Schuller of Fraunhofer IDMT, with [videos](https://www.youtube.com/playlist?list=PL6QnpHKwdPYjbDezYkAE-sAQ5MOpYeqM6) and acommpanying Jupyter notebooks by [Renato Profeta](https://twitter.com/guitars_ai) 
* [Notes on Music Information Retreival](https://musicinformationretrieval.com/)
* [Foundations of Machine Learning](https://bloomberg.github.io/foml/#home) taught by [David Rosenberg](https://bloomberg.github.io/foml/#people)

## Tutorials

(I'm often underwhelmed with audio-specific tutorials, actually.  No offense! Feel free to suggest some.  Here are a couple on related topics that I've found inspiring)
* Andrew Trask's ["Anyone Can Learn To Code an LSTM-RNN in Python"](https://iamtrask.github.io/2015/11/15/anyone-can-code-lstm/)
* [Neural Network Programming, Deep Learning with PyTorch](https://deeplizard.com/learn/video/v5cngxo4mIg) (Learn how to program neural networks using PyTorch) 
* [Machine Learning & Deep Learning Fundamentals](https://deeplizard.com/learn/video/gZmobeGL0Yg) (Good high level intro to ML concepts and how neural networks operate)

## Talks (at conferences)
that we found helpful/inspiring (and are hopefully still relevant)
* Paris Smaragdis at SANE 2015: ["NMF? Neural Nets? It’s all the same..."](https://www.youtube.com/watch?v=wfmpViJIjWw)
* Ron Weiss at SANE 2015: ["Training neural network acoustic models on waveforms"](https://www.youtube.com/watch?v=sI_8EA0_ha8)
* Jordi Pons at DLBCN 2018: ["Training neural audio classifiers with few data"](https://www.youtube.com/watch?v=AJ-XM07wSjg)

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
* Scott Hawley's [SignalTrain Demo](http://www.signaltrain.ml/)


## Packages & Libraries
* [Librosa](https://librosa.github.io/librosa/)
* [Audiomentations, data augmentation for audio](https://github.com/iver56/audiomentations)
* [tf.signal: signal processing for TensorFlow](https://www.tensorflow.org/api_docs/python/tf/signal)


## Tools / GUIs / Gists
* Jesse Engel's [gist to plot "rainbowgrams"](https://gist.github.com/jesseengel/e223622e255bd5b8c9130407397a0494)

## Books

* [Neural Networks and Deep Learning](http://neuralnetworksanddeeplearning.com/) online book.  How drscotthawley first started reading.


## Computer-Related Topics
Python: 
* [learnpython.org](https://www.learnpython.org/)
* Python notebooks for [fundamentals of music processing](https://www.audiolabs-erlangen.de/resources/MIR/FMP/C0/C0.html)


## Signal Processing Topics
* [Advanced Digital Signal Processing](https://github.com/GuitarsAI/ADSP_Tutorials) series taught by Dr.-Ing Gerald Schuller of Fraunhofer IDMT, with [videos](https://www.youtube.com/playlist?list=PL6QnpHKwdPYjbDezYkAE-sAQ5MOpYeqM6) and acommpanying Jupyter notebooks by [Renato Profeta](https://twitter.com/guitars_ai) 
* Yuge Shi's ["Gaussian Processes, Not Quite for Dummies"](https://thegradient.pub/gaussian-process-not-quite-for-dummies/)

## Statistics / Math Topics
* Gradient Descent 
  * https://ml-cheatsheet.readthedocs.io/en/latest/gradient_descent.html ,
  *  https://en.wikipedia.org/wiki/Gradient_descent ,
  *  https://www.kdnuggets.com/2017/04/simple-understand-gradient-descent-algorithm.html,
  *   ["Following Gravity"](https://drscotthawley.github.io/Following-Gravity/) by @drscotthawley
* Principal Component Analysis:  ["PCA From Scratch"](https://drscotthawley.github.io/PCA-From-Scratch/) by @drscotthawley

## News / Social Media to Follow
Twitter:  (this could get really long!)


## Datasets (raw audio)
One finds that many supposed "audio datasets" are really only features or even just metadata!  Here are some "raw audio" datasets:
* [NSynth](https://magenta.tensorflow.org/datasets/nsynth) Musical Instruments
* [GTZAN Genre Collection](http://marsyas.info/downloads/datasets.html)  (Note [critique by Bob Sturm](https://arxiv.org/abs/1306.1461))
* [Fraunhofer IDMT Guitar/Bass Effects](https://www.idmt.fraunhofer.de/en/business_units/m2d/smt/audio_effects.html)
* [Urban Sound Dataset](serv.cusp.nyu.edu/projects/urbansounddataset)
* [FreeSound Annotator](https://annotator.freesound.org/) (formerly FreeSound Datasets)
* [Birdvox-Full-Night](https://wp.nyu.edu/birdvox/birdvox-full-night/)
* [SignalTrain LA2A](https://zenodo.org/record/3348083)
* [Kaggle Heartbeat Sounds](https://www.kaggle.com/kinguistics/heartbeat-sounds)
* Search for other [audio datasets at Kaggle](https://www.kaggle.com/datasets?tags=16072-audio+data) (list)
* See this [Long list at audiocontentanalysis.org](https://www.audiocontentanalysis.org/data-sets/), but only some are raw audio
* Another [list of "audio datasets" by Christopher Dossman](https://towardsdatascience.com/a-data-lakes-worth-of-audio-datasets-b45b88cd4ad)
* ...your dataset here...


## "Major" ML-Audio Research/Development Groups
#### Universities:
(or, "Where should I apply for grad school?")
* QMU (London)
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
* AES
* ASA
* DAFx
* ICASSP
* ISMIR
* SANE

#### General ML
* ICLR
* ICML
* NeurIPS

## Journals
("Where can I get published?")





## Competitions / Benchmarks
Some are yearly, some may be defunct but still interesting.
* [MIREX](https://www.music-ir.org/mirex/wiki/MIREX_HOME)
* [SiSEC](https://sisec18.unmix.app/#/) (Signal Separation Evaluation Campaign)
* [Kaggle Heartbeat Sounds](https://www.kaggle.com/kinguistics/heartbeat-sounds)


## Contributors
[Ryan Miller](https://www.linkedin.com/in/ryan-miller-1aa8355a/)

*If you want your name listed here, you may. ;-)* 
