# ismir-2019-posters

## How to add your poster
Add it by making a pull request!

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

## Session B

### [B-02] Deep Unsupervised Drum Transcription | [paper](http://archives.ismir.net/ismir2019/paper/000020.pdf) | [code](https://github.com/keunwoochoi/DrummerNet)

[Keunwoo Choi](https://keunwoochoi.wordpress.com); [Kyunghyun Cho](http://www.kyunghyuncho.me)
> "DrummerNet is a drum transcriber trained in an unsupervised fashion. DrummerNet learns to transcribe by learning to reconstruct the audio with the transcription estimate. Unsupervised learning + a large dataset allow DrummerNet to be less-biased."

![B-02 Poster](posters/B-02-Deep-Unsupervised-Drum-Transcription.png)


## Session C

## Session D

## Session E

### [E-06] FMP Notebooks: Educational Material for Teaching and Learning Fundamentals of Music Processing | [paper](http://archives.ismir.net/ismir2019/paper/000069.pdf) | [web](https://www.audiolabs-erlangen.de/FMP)

[Meinard Müller](https://www.audiolabs-erlangen.de/fau/professor/mueller); [Frank Zalkow](https://www.audiolabs-erlangen.de/fau/assistant/zalkow)
> "The FMP notebooks include open-source Python code, Jupyter notebooks, detailed explanations, as well as numerous audio and music examples for teaching and learning MIR and audio signal processing."

![E-06 Poster](posters/B-06-FMP.png)

## Session F

## Session G

### [G-03] Adaptive Time–Frequency Scattering for Periodic Modulation Recognition in Music Signals | [paper](http://archives.ismir.net/ismir2019/paper/000099.pdf) | [dataset](https://zenodo.org/record/3250223)

[Changhong Wang](https://changhongw.github.io/); Emmanouil Benetos; Vincent Lostanlen; Elaine Chew
> "Scattering transform provides a versatile and compact representation for analysing playing techniques."

![G-03 Poster](posters/G-03.png)

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

### [L-49] Linking and Visualising Performance Data and Semantic Music Encodings in Real-Time | [paper](http://archives.ismir.net/ismir2019/latebreaking/000049.pdf) | [code](https://github.com/trompamusic/clara) | [web](https://trompa.mdw.ac.at)

[David M. Weigl](https://iwk.mdw.ac.at/david-weigl); [Carlos Cancino-Chacón](http://carloscancinochacon.com/); [Martin Bonev](); [Werner Goebl](https://www.mdw.ac.at/iwk/werner-goebl/)
> "We present CLARA (Companion for Long-term Analyses of Rehearsal Attempts), a visualisation interface for real-time performance-to-score alignment based on the MELD (Music Encoding and Linked Data) framework for semantic digital notation, employing MAPS (Matcher for Alignment of Performance and Score), an HMM-based polyphonic score-following system for symbolic (MIDI) piano performances."

![L-49 Poster](posters/L-49-Performance-Data-Semantic-Music-Encodings.png)

## MIREX
