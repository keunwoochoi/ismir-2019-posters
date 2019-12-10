# ismir-2019-posters

## How to add your poster
tl;dr - Make a PR with `poster.png` < 1.5MB.

Details:
- fork this repo and clone it to your local computer
- update the repo with your poster and its description
  - git add your poster image to `posters/` folder
    - or just directly upload to the folder on your webbrowser
  - update your repo's `readme.md` with the right format (you can also directly edit it on webbrowser)
    ```
    ### [poster session code] TITLE | LINK_TO_PAPER | LINK_TO_CODE | LINK_TO_WHATEVER

    AUTHOR NAMES

    > "SHORT DESCRIPTION THAT YOU USED IN THE CONFERENCE WEBSITE"

    POSTER IMAGE HERE WITH A RELATIVE LINK, i.e.,
    ![POSTER SESSION CODE](posters/POSTER_SESSION_CODE-YOUR_POSTER_FILE_NAME.png)
    ```
- commit, push
- make sure it looks good on `readme.md` of your forked repo
- make a pull request
- DO NOT CHANGE OTHERS' POSTERS - WE DON'T NEED A MERGE CONFLICT HERE!

## Sessions
[Session A](https://github.com/keunwoochoi/ismir-2019-posters#session-a),
[Session B](https://github.com/keunwoochoi/ismir-2019-posters#session-b),
[Session C](https://github.com/keunwoochoi/ismir-2019-posters#session-c),
[Session D](https://github.com/keunwoochoi/ismir-2019-posters#session-d),
[Session E](https://github.com/keunwoochoi/ismir-2019-posters#session-e),
[Session F](https://github.com/keunwoochoi/ismir-2019-posters#session-f),
[Session G](https://github.com/keunwoochoi/ismir-2019-posters#session-g),
[Late-Breaking/Demo](https://github.com/keunwoochoi/ismir-2019-posters#late-breakingdemo)
[MIREX](https://github.com/keunwoochoi/ismir-2019-posters#mirex)

## Session A

### [A-01] Zero-shot Learning for Audio-based Music Classification and Tagging | [paper](http://archives.ismir.net/ismir2019/paper/000005.pdf) | [code](https://github.com/kunimi00/ZSL_music_tagging)
[Jeong Choi](https://jeongchoi.home.blog/); [Jongpil Lee](https://jongpillee.github.io/); Jiyoung Park; [Juhan Nam](http://mac.kaist.ac.kr/~juhan/)
> "Investigated the paradigm of zero-shot learning applied to music domain. Organized 2 side information setups for music calssification task. Proposed a data split scheme and associated evaluation settings for the multi-label zero-shot learning."

![A-01 Poster](posters/A-01-Zero-shot-Learning.png)

### [A-09] 20 Years of Playlists: A Statistical Analysis on Popularity and Diversity | [paper](http://archives.ismir.net/ismir2019/paper/000013.pdf) | [code](https://github.com/MTG/playlists-stat-analysis)

[Lorenzo Porcaro](https://lorenzoporcaro.wordpress.com/); [Emilia Gómez](https://emiliagomez.com/)
> "We find extremely valuable to compare playlist datasets generated in different contexts, as it allows to understand how changes in the listening experience are affecting playlist creation strategies."

![A-09 Poster](posters/A-09-20-Years-of-Playlists.png)


### [A-13] Conditioned-U-Net: Introducing a Control Mechanism in the U-Net for Multiple Source Separations | [paper](http://archives.ismir.net/ismir2019/paper/000017.pdf) | [code](https://github.com/gabolsgabs/cunet)

[Gabriel Meseguer-Brocal](https://github.com/gabolsgabs/); [Geoffroy Peeters](https://perso.telecom-paristech.fr/gpeeters/)
> "In this paper, we apply conditioning learning to source separation and introduce a control mechanism to the standard U-Net architecture. The control mechanism allows multiple instrument separations with just one model without losing performance."

![A-09 Poster](posters/A-13-Conditioned-U-Net;-Introducing-a-Control-Mechanism-in-the-U-Net-for-Multiple-Source-Separations.png)

## Session B

### [B-02] Deep Unsupervised Drum Transcription | [paper](http://archives.ismir.net/ismir2019/paper/000020.pdf) | [code](https://github.com/keunwoochoi/DrummerNet)

[Keunwoo Choi](https://keunwoochoi.wordpress.com); [Kyunghyun Cho](http://www.kyunghyuncho.me)
> "DrummerNet is a drum transcriber trained in an unsupervised fashion. DrummerNet learns to transcribe by learning to reconstruct the audio with the transcription estimate. Unsupervised learning + a large dataset allow DrummerNet to be less-biased."

![B-02 Poster](posters/B-02-Deep-Unsupervised-Drum-Transcription.png)

### [B-09] Towards Explainable Emotion Recognition in Music: The Route via Mid-level Features | [paper](http://archives.ismir.net/ismir2019/paper/000027.pdf) |  [demo](https://shreyanc.github.io/ismir_example.html)

[Shreyan Chowdhury](https://shreyanc.github.io), Andreu Vall Portabella, [Verena Haunschmid](https://twitter.com/ExpectAPatronum), Gerhard Widmer

> "Explainable predictions of emotion from music can be obtained by introducing an intermediate representation of mid-level perceptual features in the predictor deep neural network."

![B-09 Poster](posters/B-09-Towards-Explainable-Emotion-Recognition-in-Music.png)


## Session C

### [C-01] Learning a Joint Embedding Space of Monophonic and Mixed Music Signals for Singing Voice | [paper](http://archives.ismir.net/ismir2019/paper/000034.pdf) | [code](http://github.com/kyungyunlee/mono2mixed-singer) | [mashup example](http://kyungyunlee.github.io/archives/ISMIR2019-Mono2Mixed) 
    
[Kyungyun Lee](http://kyungyunlee.github.io); [Juhan Nam](http://mac.kaist.ac.kr/~juhan/)   

> "The paper introduces a new method of obtaining a consistent singing voice representation from both monophonic and mixed music signals. Also, it presents a simple music mashup pipeline to create a large synthetic singer dataset"
    
![C-01 Poster](posters/C-01-Learning-a-Joint-Embedding-Space.png)

### [C-07] Learning to Traverse Latent Spaces for Musical Score Inpainting | [paper](http://archives.ismir.net/ismir2019/paper/000040.pdf) | [code](https://github.com/ashispati/InpaintNet)  | [audio-examples](https://ashispati.github.io/inpaintnet/)

[Ashis Pati](https://ashispati.github.io), [Alexander Lerch](http://www.alexanderlerch.com), [Gaëtan Hadjeres](https://csl.sony.fr/team/gaetan-hadjeres/)

> "Recurrent Neural Networks can be trained using latent embeddings of a Variational Auto-Encoder-based model to to perform interactive music generation tasks such as inpainting."

![C-07 Poster](posters/C-07-Latent-Space-Traversal.png)
## Session D


### [D-02] A Cross-Scape Plot Representation for Visualizing Symbolic Melodic Similarity | [paper](http://archives.ismir.net/ismir2019/paper/000050.pdf) | [code](https://github.com/saebyulpark/cross_scapeplot_visualization)
Saebyul Park; Taegyun Kwon; Jongpil Lee; Jeounghoon Kim; Juhan Nam
> "We propose a cross-scape plot representation to visualize multi-scaled melody similarity between two symbolic music. We evaluate its effectiveness on examples from folk music collections with similarity-based categories and plagiarism cases."
![D-02 Poster](posters/D-02_Cross_scape_plot.png)


### [D-04] A Dataset of Rhytmic Pattern Reproductions and Baseline Automatic Assessment System | [paper](http://archives.ismir.net/ismir2019/paper/000052.pdf) | [code](https://github.com/MTG/mast-rhythm-analysis) | [MAST rhythm dataset](https://zenodo.org/record/2620357) | [re-annotated dataset](https://zenodo.org/record/2619499)

[Felipe Falcão](https://www.linkedin.com/in/felipe29vieira), Baris Bozkurt, Xavier Serra, Nazareno Andrade, Ozan Baysal
> "This present work is an effort to address the shortage of music datasets designed for rhythmic assessment. A new dataset and baseline rhythmic assessment system are provided in order to support comparative studies about rhythmic assessment."

![D-04 Poster](posters/D-04-A-Dataset-of-Rhytmic-Pattern-Reproductions-and-Baseline-Automatic-Assessment-System.png)

### [D-06] Blending Acoustic and Language Model Predictions for Automatic Music Transcription | [paper](http://archives.ismir.net/ismir2019/paper/000054.pdf) | [code](https://github.com/adrienycart/MLM_decoding/tree/ismir2019) | [supplementary-material](http://c4dm.eecs.qmul.ac.uk/ycart/ismir19.html) 

Adrien Ycart, Andrew McLeod, Emmanouil Benetos, Kazuyoshi Yoshii

> "Dynamically integrating predictions from an acoustic and a language model with a blending model improves automatic music transcription performance on the MAPS dataset. Results are further improved by operating on 16th-note timesteps rather than 40ms."

![D-06 Poster](posters/D-06-Blending_Acoustic_and_Language_Model_Predictions_for_Automatic_Music_Transcription.png)

### [D-08] A Comparative Study of Neural Models for Polyphonic Music Sequence Transduction | [paper](http://archives.ismir.net/ismir2019/paper/000056.pdf)

Adrien Ycart, Daniel Stoller, Emmanouil Benetos

> "A systematic study using various neural models and automatic music transcription systems shows that a cross-entropy-loss CNN improves transduction performance, while an LSTM does not. Using an adversarial set-up also does not yield improvement."

![D-08 Poster](posters/D-08-A_Comparative_Study_of_Neural_Models_For_Polyphonic_Music_Transduction.png)

## Session E

### [E-04] A Diplomatic Edition of Il Lauro Secco: Ground Truth for OMR of White Mensural Notation | [paper](http://archives.ismir.net/ismir2019/paper/000067.pdf) | [dataset](https://github.com/SEILSdataset/SEILSdataset)

Emilia Parada-Cabaleiro, Anton Batliner, Björn Schuller
> "We present a symbolic representation in mensural notation of the anthology Il Lauro Secco. For musicological analysis we encoded the repertoire in **mens and MEI; to support OMR research we present ground truth in agnostic and semantic formats."

![E-04 Poster](posters/E-04-SEILS.png)

### [E-05] The Harmonix Set: Beats, Downbeats, and Functional Segment Annotations of Western Popular Music, Nieto, O., McCallum, M., Davies., M., Robertson, A., Stark, A., Egozy, E. | [poster](posters/E-05-TheHarmonixSet.pdf) | [paper](http://archives.ismir.net/ismir2019/paper/000068.pdf) | [code](https://github.com/urinieto/harmonixset)
> "Human annotated dataset containing beats, downbeats, and structural segmentation for over 900 pop tracks."

![E-05 Poster](posters/E-05-TheHarmonixSet.png)

### [E-06] FMP Notebooks: Educational Material for Teaching and Learning Fundamentals of Music Processing | [paper](http://archives.ismir.net/ismir2019/paper/000069.pdf) | [web](https://www.audiolabs-erlangen.de/FMP)

[Meinard Müller](https://www.audiolabs-erlangen.de/fau/professor/mueller); [Frank Zalkow](https://www.audiolabs-erlangen.de/fau/assistant/zalkow)
> "The FMP notebooks include open-source Python code, Jupyter notebooks, detailed explanations, as well as numerous audio and music examples for teaching and learning MIR and audio signal processing."

![E-06 Poster](posters/B-06-FMP.png)

## Session F

### [F-13] Learning Disentangled Representations of Timbre and Pitch for Musical Instrument Sounds Using Gaussian Mixture Variational Autoencoders | [paper](http://archives.ismir.net/ismir2019/paper/000091.pdf) | [demo](https://ismir19-217.github.io/sup-material/ismir19-217-sup-material.html)

[Yin-Jyun Luo](https://yjlolo.github.io/al-folio/); Kat Agres; Dorien Herremans

> "We disentangle pitch and timbre of musical instrument sounds by learning separate interpretable latent spaces using Gaussian mixture variational autoencoders. The model is verified by controllable sound synthesis and many-to-many timbre transfer."

![F-13](posters/F-13-instrument_GMVAE.png)

## Session G

### [G-03] Adaptive Time–Frequency Scattering for Periodic Modulation Recognition in Music Signals | [paper](http://archives.ismir.net/ismir2019/paper/000099.pdf) | [dataset](https://zenodo.org/record/3250223)

[Changhong Wang](https://changhongw.github.io/); Emmanouil Benetos; Vincent Lostanlen; Elaine Chew
> "Scattering transform provides a versatile and compact representation for analysing playing techniques."

![G-03 Poster](posters/G-03.png)

### [G-05] Unmixer: An Interface for Extracting and Remixing Loops | [paper](http://archives.ismir.net/ismir2019/paper/000101.pdf) | [website](https://unmixer.ongaaccel.jp/) | [poster](http://jblsmith.github.io/documents/smith2019-ismir-unmixer_interface-poster.pdf)

[Jordan B. L. Smith](http://jblsmith.github.io/); Yuta Kawasaki; Masataka Goto
> "Unmixer is a web interface where users can upload music, extract loops, remix them, and mash-up loops from different songs. To extract loops with source separation, we use a nonnegative tensor factorization method improved with a sparsity constraint."

![G-05 Poster](posters/G-05-Unmixer-an-interface-for-extracting-and-remixing-loops.png)

### [G-08] GENERATING STRUCTURED DRUM PATTERN USING VARIATIONAL AUTOENCODER AND SELF-SIMILARITY MATRIX | [paper](http://archives.ismir.net/ismir2019/paper/000104.pdf) | [code](https://github.com/Sma1033/drum_generation_with_ssm)

> "We proposed a model that incorporates long term structure into the music generation process using VAE amd SSM. Subjective evaluation results suggest its effectiveness in generating transitions at structural boundaries."

![G-08 Poster](posters/G-08-Generating-Sturctured-Drum-Pattern.png)

### [G-12] Audio-query Based Music Source Separation | [paper](http://archives.ismir.net/ismir2019/paper/000108.pdf)

Jie Hwan Lee(*); Hyeong-Seok Choi(*); Kyogu Lee (*: Equal contribution)
> “We propose a network for audio query-based music source separation that can explicitly encode the source information from a query signal regardless of the number and/or kind of target signals. The proposed method consists of a Query-net and a Separator: given a query and a mixture, the Query-net encodes the query into the latent space, and the Separator estimates masks conditioned by the latent vector, which is then applied to the mixture for separation.”

![G-12 Poster](posters/G-12-AudioQueryBasedMusicSourceSeparation-min.jpg)

### [G-13] Adaptive Time–Frequency Scattering for Periodic Modulation Recognition in Music Signals | [paper](http://archives.ismir.net/ismir2019/paper/000109.pdf) | [code/examples](https://livingthing.danmackinlay.name/mosaicing_omp_ismir_2019/)

[Dan MacKinlay](https://danmackinlay.name/); Zdravko Botev
> “We apply sparse dictionary decomposition twice to autocorrelograms of signals, to get a novel analysis of and method for mosaicing music style transfer, which has the novel feature of handling time-scaling of the source audio naturally.”

![G-13 Poster](posters/G-13-Autocorrelogram_mosaicing_via_OMP.png)

### [G-16] VirtuosoNet: A Hierarchical RNN-based System for Modeling Expressive Piano Performance  | [paper](http://archives.ismir.net/ismir2019/paper/000112.pdf) | [code](https://github.com/jdasam/virtuosoNet)
Dasaem Jeong; Taegyun Kwon; Yoojin Kim; Kyogu Lee; Juhan Nam

> "We present an RNN-based model that reads MusicXML and generates human-like performance MIDI. The model employs a hierarchical approach by using attention network and an independent measure-level estimation module. We share our code and dataset."

![G-16 Poster](posters/G-16-VirtuosoNet.png)



## Late-Breaking/Demo

### [L-06] Tools for Semi-Automatic Bounding Box Annotation of Musical Measures in Sheet Music | [paper](http://archives.ismir.net/ismir2019/latebreaking/000006.pdf) | [web](https://www.audiolabs-erlangen.de/resources/MIR/2019-ISMIR-LBD-Measures)

[Frank Zalkow](https://www.audiolabs-erlangen.de/fau/assistant/zalkow); [Angel Villar Corrales](); [TJ Tsai](http://pages.hmc.edu/ttsai/); [Vlora Arifi-Müller](https://www.audiolabs-erlangen.de/fau/assistant/arifi-mueller); [Meinard Müller](https://www.audiolabs-erlangen.de/fau/professor/mueller);
> "In score following, one main goal is to highlight measure positions in sheet music synchronously to audio playback. Such applications require alignments between sheet music and audio representations. Often, such alignments can be computed automatically in the case that the sheet music representations are given in some symbolically encoded music format. However, sheet music is often available only in the form of digitized scans. In this case, the automated computation of accurate alignments poses still many challenges [1]. In this contribution, we present various semi-automatic tools for solving the subtask of determining bounding boxes (given in pixels) of measure positions in digital scans of sheet music—a task that is extremely tedious when being done manually."

![L-10 Poster](posters/L-06-Measure-Boundaries.png)

### [L-07] Improving Music Tagging from Audio with User-Track Interactions | [paper](http://archives.ismir.net/ismir2019/latebreaking/000007.pdf)

[Andres Ferraro](https://github.com/andrebola); [Jae Ho Jeon](https://www.linkedin.com/in/jae-ho-jeon-036927126); [Jisang Yoon](https://github.com/js1010); [Xavier Serra](https://www.upf.edu/web/xavier-serra); [Dmitry Bogdanov](https://dbogdanov.github.io/about/)
> "We propose to improve the tagging of music by using audio and collaborative filtering information (user-track interactions). We use Matrix Factorization (MF) to obtain a representation of the tracks from the user-track interactions and map those representations to the tags predicted from audio. The preliminary results show that following this approach we can increase the tagging performance."

![L-07 Poster](posters/L-07-improve-tagging.png)

### [L-10] Creating a Tool for Faciltiating and Researching Human Annotation of Musical Patterns | [paper](http://archives.ismir.net/ismir2019/latebreaking/000010.pdf) | [code](https://github.com/StephanWells/ANOMIC)

[Stephan Wells](); [Iris Yuping Ren](http://irisryp.me/); [Anja Volk](http://www.staff.science.uu.nl/~fleis102/)
> "Musical patterns (repeated segments of music) are highly widespread in all varieties of music, and annotations of such patterns are valuable in many areas of music information retrieval. Unfortunately, there is a lack of expert annotations of musical patterns, and most annotation is done by hand. In this project, we introduce a novel software, ANOMIC, designed for users to intuitively annotate repeated musical segments, and we perform a user study which yields a large database of annotations done using the tool. We find that the tool’s reception was strongly positive and show that the annotations done with it reach high levels of inter-annotator agreement compared to traditional approaches."

![L-10 Poster](posters/L-10-ANOMIC.png)


### [L-11] nnAudio: A Pytorch Audio Processing Tool Using 1dconvolution Neural Networks | [paper]() | [code](https://github.com/KinWaiCheuk/nnAudio)

[Kin Wai Cheuk](https://github.com/KinWaiCheuk); [Kat Agres](http://katagres.com/biography); [Dorien Herremans](http://dorienherremans.com/biography)
> "With the advent of Graphics Processing Units (GPUs),  many computational methods, such as Tensorflow and PyTorch, are now taking advantage of these technologies to dramatically speed up calculations. The number of GPU based processing libraries for signal processing is limited to tools such as tf.signal, torchaudio (PyTorch based), and Kapre (Tensorflow based).
We propose a PyTorch based neural network audio processing tool called nnAudio. Our library offer GPU-leveraged calculation of linear spectrograms, log spectrograms, Mel Spectrograms (MelSpec), and constant-Q transform (CQT). nnAudio is the only GPU-based library that offers CQT calculation. We record a speed increase of over 100 times when using nnAudio versus traditional signal processing tools"

![L-11 Poster](posters/L-11-nnAudio.png)

### [L-35] Automated Time-Frequency Domain Audio Crossfades Using Graph Cuts | [paper](http://archives.ismir.net/ismir2019/latebreaking/000035.pdf) | [code](https://github.com/Stack-Attack/time-freq-cut) | ['DJ' Example](https://soundcloud.com/kyle-robinson-13/augmented-recon-dj-4), ['Standard' Example](https://soundcloud.com/kyle-robinson-13/augmented-recon-acoustic)

Kyle Robinson; [Dan Brown](https://cs.uwaterloo.ca/~browndg/)

> "We present the first implementation of a new method to automatically transition between songs by finding an optimal seam in the time-frequency spectrum."

![L-35 Poster](posters/L-35-Time-Frequency-Crossfades.PNG)

### [L-45] An Opensource Web-based Pattern Annotation Framework - PAF | [paper](http://archives.ismir.net/ismir2019/latebreaking/000045.pdf) | [code](https://bitbucket.org/ul-fri-lgm/patternannotationframework/src)

[Matevž Pesek](); [Darian Tomašević](); [Iris Yuping Ren](http://irisryp.me/); [Matija Marolt]()
> "The Pattern Annotation Framework (PAF) tool collects the data about the annotator and the annotation process, to enable an analysis of relations between the user's experience/background and the annotations. The tool tracks the user's actions, such as the start and end time of an individual annotation and its changes, midi player actions and other. By open-sourcing the tool, we hope to aid other researchers in the MIR field dealing with pattern-related data gathering."

![L-45 Poster](posters/L-45-PAF.png)

### [L-49] Linking and Visualising Performance Data and Semantic Music Encodings in Real-Time | [paper](http://archives.ismir.net/ismir2019/latebreaking/000049.pdf) | [code](https://github.com/trompamusic/clara) | [web](https://trompa.mdw.ac.at)

[David M. Weigl](https://iwk.mdw.ac.at/david-weigl); [Carlos Cancino-Chacón](http://carloscancinochacon.com/); [Martin Bonev](); [Werner Goebl](https://www.mdw.ac.at/iwk/werner-goebl/)
> "We present CLARA (Companion for Long-term Analyses of Rehearsal Attempts), a visualisation interface for real-time performance-to-score alignment based on the MELD (Music Encoding and Linked Data) framework for semantic digital notation, employing MAPS (Matcher for Alignment of Performance and Score), an HMM-based polyphonic score-following system for symbolic (MIDI) piano performances."

![L-49 Poster](posters/L-49-Performance-Data-Semantic-Music-Encodings.png)


## MIREX
