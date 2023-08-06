# Read Me

## References
- [https://pythonhumanities.com/](https://pythonhumanities.com/)
- [Python for Humanities Course Material](http://python-textbook.pythonhumanities.com/01_intro/01_01-04_coding_basics.html)
- [Mathplotlib Graph Reference](https://matplotlib.org/3.4.3/gallery/images_contours_and_fields/image_annotated_heatmap.html#sphx-glr-gallery-images-contours-and-fields-image-annotated-heatmap-py)

## Main Course Links
- [Introduction to Python](https://www.youtube.com/watch?v=KSOX_4tTSQk)



## Useful Libraries

- Pandas - allows manipulation of data in a pythonic way - [Reference](https://pandas.pydata.org/)
- requests - for web scraping - [Reference](https://pypi.org/project/requests/)
- BeautifulSoup - Process data from requests and parse it - [Reference](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- regex - [Cheat sheet reference](https://www.rexegg.com/regex-quickstart.html) [101.com](https://regex101.com/)
- xlrd - for excel data [Reference](https://xlrd.readthedocs.io/en/latest/)
- xlswriter - for excel data [Reference](https://xlsxwriter.readthedocs.io/)
- tkinter - GUI library




![image](https://github.com/johnosbb/PythonForDigitalHumanities/assets/12407183/e6eb28e3-5a56-42c3-b6d2-0caa2955d9de)


# NLP - Natural Language Processing.


# NLU - Natural Language Understanding.

## Named Entity Recognition

Extract entity based meta data from a text. This is a part of information extraction and there are two ways of doing this. A Gazetteer extracts information based on rule-based-methods. This approach has its limits because of Linguistic-Ambiguity. Natural language is ambiguous by its very nature; this is what makes language beautiful. For a computer trying to interpret language, this ambiguity makes reliable entity extraction very difficult. Domain Adaption is the process of taking existing models and adapt them to a particular domain.
We want to produce models that can generalize well. Generalization is the process of being able to process data it has not seen before.

Spacy scales better than NLTK for named entity recognition.
Gensim is a library for topic modelling. It has a system that allows it to train efficiently on word vectors. These word vectors can then be used with Spacy.
