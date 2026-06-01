# Summary

This treebank is based on data from the It-tok corpus (TikTok videos in Italian).
See also: https://github.com/cabinsix/It-Tok

# Introduction

The It-tok corpus is made up of two sections, distinguishable based on the ID of each file.

The files starting with a _G_ (ex. G0125) are part of the generalist section of the corpus; the ones without letters (ex. 0125) are part of the PolSo section (videos of socio-political theme).

Each file is a section of different videos.

# Composition

The treebank now consists of 10186 tokens in 20 sample videos.

Maximal units segmentation and annotation protocols are based on the ones introduced for other spoken Italian treebanks (see KIParla FOREST, Pannitto & Mauri 2024). This holds also for the annotation of time alignment, and interrupted and prolonged tokens.

Pauses are marked alternatively as {sp}, short, or {lp}, long, and have PAUSE as lemma.

A .json file containing metadata for each video of It-tok is to be found in not-to-release as metadati_ittok.json, containing mese (month), subcorpus, create_time, speech-to-text voice_to_text, general_data , video_duration, id_corpus, tokens(NoPunct) (number of tokens excluding punctuation), text, hashtags, treebank (is in TrIttok), tipologia_Gen (class in Gen, generalist section), commento_risposto (answered comment), trascr_stitchato (transcription of stitched segment), macrotema_PolSo (PolSo macrotheme), and the individual hashtag fields hashtags1–hashtags37.


# Acknowledgments

This work was supported by COST Action CA21167 —Universality, diversity and idiosyncrasy in language technology (UniDive).

I would like to thank Ludovica Pannitto and Flavio Pisciotta for the support throughout the building of the treebank.

## References

For referring to the treebank (as for the Ittok corpus):
...
@inproceedings{troncone-2025-building,
    title = "Building It-tok: an Italian TikTok Corpus",
    author = "Troncone, Luisa",
    booktitle = "Proceedings of CLiC-it 2025: Eleventh Italian Conference on Computational Linguistics",
    year = "2025",
    note = "Pre-print available on ResearchGate",
    url = "https://www.researchgate.net/publication/396559002_Building_It-tok_an_Italian_TikTok_corpus"
}
...

# Changelog

* 2026-11-15 v2.19
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.19
License: CC BY-SA 4.0
Includes text: yes
Parallel: no
Genre: tiktok videos
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Troncone, Luisa
Contributing: here
Contact: ltroncone@unisa.it
===============================================================================
</pre>
