<img src="masterSBD_logo.jpg" width=500/>

# Mobility Data Analysis (MDA)
[Master in Big Data Analytics & Social Mining](https://masterbigdata.it/), University of Pisa.

## Teachers
- Mirco Nanni (ISTI-CNR)
- Luca Pappalardo (ISTI-CNR)

## Abstract
In these hands-on lessons, we present an overview on the fundamental principles underlying the analysis of mobility data, using **[scikit-mobility](https://github.com/scikit-mobility/scikit-mobility)**, a specific Python library designed by the tutorial presenters.

In particular, we see how to visualize trajectories, flows and tessellations, how to clean raw mobility data by using standard techniques proposed in the mobility data mining literature, and how to analyze mobility data by using the main measures characterizing human mobility patterns (e.g., radius of gyration, daily motifs, mobility entropy).

## Outline of hands-on course

**Lessons**
- Lesson 1: [Intro and Data Structures](https://github.com/scikit-mobility/tutorials/blob/master/mda_masterbd2020/intro_and_data_structures.ipynb)
- Lesson 2: [Preprocessing mobility data](https://github.com/scikit-mobility/tutorials/blob/master/mda_masterbd2020/preprocessing.ipynb)
- Lesson 3: [Mobility measures](https://github.com/scikit-mobility/tutorials/blob/master/mda_masterbd2020/measures.ipynb)

**Practice**
- [Practice 1](https://github.com/scikit-mobility/tutorials/blob/master/mda_masterbd2020/practice1.ipynb)
- Practice 2
  - [traccia](https://github.com/scikit-mobility/tutorials/blob/master/mda_masterbd2020/practice2_traccia.ipynb)
  - [solved](https://github.com/scikit-mobility/tutorials/blob/master/mda_masterbd2020/practice2.ipynb)
- Practice 3
  - [traccia](https://github.com/scikit-mobility/tutorials/blob/master/mda_masterbd2020/practice3-traccia.ipynb)
  - [solved](https://github.com/scikit-mobility/tutorials/blob/master/mda_masterbd2020/practice3.ipynb)
- [Read Google Timeline Data](https://github.com/scikit-mobility/tutorials/blob/master/mda_masterbd2020/read_my_tracks.ipynb)

## Get ready: install scikit-mobility and download data

<img src="logo_skmob.png" width="300" />

- Repository: https://github.com/scikit-mobility/scikit-mobility
- Documentation: https://scikit-mobility.github.io/scikit-mobility/
- Paper: https://arxiv.org/abs/1907.07062
- Jupyter Notebook: https://jupyter.org/
- To run notebooks in Jupyter using slideshow, install [RISE](https://rise.readthedocs.io/en/stable/)

- Download [Geolife Dataset](https://www.microsoft.com/en-us/download/details.aspx?id=52367&from=https%3A%2F%2Fresearch.microsoft.com%2Fen-us%2Fdownloads%2Fb16d359d-d164-469e-9fd4-daa38f2b2e13%2F), unzip it, and put it in folder `data`
- Download [San Francisco cabs data](https://bit.ly/sf_cabs_data), and put the file in the folder `data`
- Download your [Google Location data](https://support.google.com/accounts/answer/3024190), and put the `json` file in folder `data`
- Download data of [taxis in Rome](https://drive.google.com/file/d/1wZfW5l2d7MWNHWXQUlpNynJUi8haAuqD/view?usp=sharing)

## Tips and tricks
- How to make folium Custom Icons: https://ocefpaf.github.io/python4oceanographers/blog/2015/11/02/icons/
- Cloropleth maps in folium: https://python-graph-gallery.com/292-choropleth-map-with-folium/
- Adding the geographic scale in a folium map: https://github.com/python-visualization/folium/issues/414
