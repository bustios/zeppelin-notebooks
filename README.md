[![Apache License 2.0](http://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

# Zeppelin notebooks

This repository contains a set of notebooks I developed using [Apache Zeppelin](http://zeppelin.apache.org), as part of my participation in [Google Summer of Code 2016](https://summerofcode.withgoogle.com/projects/#5094334298849280). If you've noticed any errors or would like to contribute to this repository, please don't hesitate to contact me submitting an issue on GitHub or forking the repository and making a pull request.

If you just want to take a look at the notebooks, you can view them on ZeppelinHub [viewer](https://www.zeppelinhub.com/viewer).

## License

All the source code in the notebooks is licensed under [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).

## Notebooks

### 1. Classification of motor imagery EEG signals

- The objective of this notebook is to present a simple approach to classify left and right hand motor imagery EEG signals.
- [Source code](https://raw.githubusercontent.com/bustios/zeppelin-notebooks/master/notebook-01/note.json) on Github.
- [View](https://www.zeppelinhub.com/viewer/notebooks/bm90ZTovL2J1c3Rpb3MvbG9jYWwvOThlYTU4OTczMTc5NGYyNThmNjQ2YmVlM2Q3ODI3ZTYvbm90ZS5qc29u) on ZeppelinHub.

![image.jpg](/images/note01.jpg?raw=true)

<br>

### 2. World Development Indicators

- This notebook shows some indicators of the World Development Indicators dataset in an easy way through maps and interactive graphics using R.
- [Source code](https://raw.githubusercontent.com/bustios/zeppelin-notebooks/master/notebook-02/note.json) on Github.
- [View](https://www.zeppelinhub.com/viewer/notebooks/bm90ZTovL2J1c3Rpb3MvbG9jYWwvZjhlZTE1Zjk1MGQ1NDQ4MDg2OTUwMWYyOTkwZWNlYzMvbm90ZS5qc29u) on ZeppelinHub.

![image.gif](/images/note02.gif?raw=true)

<br>

### 3. Machine learning on Titanic disaster

- This notebook is intended to show the common steps present in a machine learning problem.
- [Source code](https://raw.githubusercontent.com/bustios/zeppelin-notebooks/master/notebook-03/note.json) on Github.
- [View](https://www.zeppelinhub.com/viewer/notebooks/bm90ZTovL2J1c3Rpb3MvbG9jYWwvYmI0Y2EwNjVkMTI1NDY2Y2EzNTIzNThiZjViYzIxOWQvbm90ZS5qc29u) on ZeppelinHub.

![image.jpg](/images/note03.jpg?raw=true)

<br>

Additionally to these notebboks, I reported the following issues on Apache JIRA:

- [ZEPPELIN-1244](https://issues.apache.org/jira/browse/ZEPPELIN-1244): %python.sql is not initialized properly by default
- [ZEPPELIN-1255](https://issues.apache.org/jira/browse/ZEPPELIN-1255): z.show() does not display Pandas DataFrame with non-string values
- [ZEPPELIN-1261](https://issues.apache.org/jira/browse/ZEPPELIN-1261): z.show() height parameter doesn't take effect
- [ZEPPELIN-1327](https://issues.apache.org/jira/browse/ZEPPELIN-1327): Height parameter in z.show python interpreter does not take effect for PNG images
- [ZEPPELIN-1328](https://issues.apache.org/jira/browse/ZEPPELIN-1328): z.show in python interpreter does not display PNG images in python 3
- [ZEPPELIN-1358](https://issues.apache.org/jira/browse/ZEPPELIN-1358): Displaying Pandas DataFrame index in table using z.show()

and made these [commits](https://github.com/apache/zeppelin/commits/master?author=bustios) on Zeppelin repository.
