# Mizan-Corpus-NMT
A Parallel Corpus from the Mizan dataset including over a million sentences in Farsi and English. They are split and shuffled randomly in one file and also split non-randomly and remain in order to preserve integrity in another file. Each of the files contain the .txt files of the data. You can check on the preprocessing steps in the preprocessing file. I tried using training it with OpenNMT in google colab on a GPU, yet still working on achieving a higher accuracy. I believe it may involve cleaning the data more and tokenizing. It may also require alterations to the n-sample size and steps in the config.yaml for the OpenNMT stage.


Link to Original source of Dataset (Github and Paper):
https://github.com/omidkashefi/Mizan

Documentation used to create config.yaml:
https://opennmt.net/OpenNMT-py/quickstart.html

* May need to find alternative method besides OpenNMT that porovides more flexibility in parameter selection
* Can still use corpus with a transformer on hugging face potentially
