This is an analysis of [early House and Techno Music from Germany and the united states of AMErica (HOTGAME)](https://doi.org/10.5281/zenodo.14958955). Based on recording studio features, a Self-Organizing Map (SOM) is trained to explore similarities and differences between US-American and German house and techno music and their evolution. Some results are available on the [techno analysis project site](https://timziemer.github.io/technoanalysis.html), particularly some interactive SOMs.

The project contains the [SOM algorithm](https://github.com/ifsm/Techno-Analysis/blob/main/som.ipynb), the [trained SOM](https://github.com/ifsm/Techno-Analysis/blob/main/2025-02-24-med-bpm-phsp-chacorr-crest.sav), and the [data normalization](https://github.com/ifsm/Techno-Analysis/blob/main/2025-02-24-med-bpm-phsp-chacorr-crest.pkl). To use it, simply download the HOTGAME corpus (zippped to about 10 GB), adjust the file paths in the jupyter notebook, and run it.

Feel free to rearrange the songs using a different folder structure. This way, you can explore, e.g., the sound of particular artists, regions, (sub-)genres, record labels, or alike. You can even include your own music in the SOM. Simply use the recording studio feature extractor from the [HOTGAME feature extraction project](https://github.com/ifsm/HOTGAME-feature-extraction), and analyze your own audio files (wav, mp3, m4a, opus). 

Detail on the recording studio features can be found in:

* Tim Ziemer, Nikita Kudakov and Christoph Reuter, "Producer vs. Rapper: Who Dominates the Hip Hop Sound?", Journal of the Audio Engineering Society 73(1/2), 2025, pp. 54-62, [https://doi.org/10.17743/jaes.2022.0183](https://doi.org/10.17743/jaes.2022.0183).

* Tim Ziemer, "Goniometers are a Powerful Acoustic Feature for Music Information Retrieval Tasks", DAGA 2023 - 49. Jahrestagung für Akustik, Hamburg, Germany, pp. 934-937, [https://pub.dega-akustik.de/DAGA_2023/data/articles/000600.pdf](https://pub.dega-akustik.de/DAGA_2023/data/articles/000600.pdf).

* Tim Ziemer, Pattararat Kiattipadungkul and Tanyarin Karuchit, "Acoustic features from the recording studio for Music Information Retrieval Tasks", Proceedings of Meetings on Acoustics 42(1), 2020, paper number 035004, [https://doi.org/10.1121/2.0001363](https://doi.org/10.1121/2.0001363).
