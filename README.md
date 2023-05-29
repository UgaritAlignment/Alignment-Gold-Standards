# Alignment Gold Standards for Ancient Greek

This repository contains guidelines and gold standard datasets for the alignment of Ancient Greek texts and translations in various languages. The guidelines are currently developed for Ancient Greek-English, Ancient Greek-Brazilian Portuguese, and Ancient Greek-Latin, and more will be added in the course of future work. Each of these guides and related gold standard was created by:  

* Chiara Palladino at Furman University (USA) and Farnoosh Shamsian at the University of Leipzig (Germany): Ancient Greek-English.
* Chiara Palladino and David J. Wright at Furman University (USA): Ancient Greek-Latin.
* Anise d'Orange Ferreira and Michel Ferreira dos Reis at UNESP Araraquara (Brazil): Ancient Greek-Portuguese. 

The guidelines were used to annotate a diverse dataset including Homeric epic, Attic prose, Platonic dialogue and the Fragmenta Historicorum Graecorum, and were tested by measuring inter-annotator agreement of 80% or higher. The Ancient Greek texts used are almost entirely available through the Scaife viewer (https://scaife.perseus.org/), while the fragments are from the DFHG Project (https://www.dfhg-project.org/).  

The datasets used to develop the gold standard were aligned using the Ugarit Translation Alignment Editor for Historical languages (http://ugarit.ialigner.com/), and they are available in this repository.  

The materials available here can be used to perform and evaluate alignments of various texts in Ancient Greek, to create new gold standard corpora, and to train automated translation models.  

The guidelines can also be further adapted to address similar language pairs including an inflected and a synthetic language, such as Latin and English, or can provide a structure for the alignment of other historical texts against modern translations. However, the guidelines are not project-specific: they were specifically intended for the creation of a Gold Standard in the scenario of machine translation. Different scenarios, such as language research or pedagogy, may need further tweaking to these guidelines to make them more compatible with different underlying principles.

For further information on Ugarit and translation alignment of historical languages, see http://ugarit.ialigner.com/bib.php and follow us on Twitter (@ugarit_ty). 

# Using this repository and the Guidelines

The data in this repository is provided with a CC-BY-SA license. If you use any of the materials in this repository, please cite our work as follows.

## Citing the Guidelines and the Gold Standard

To cite the Guidelines, please use the following format:  
- Grc-Eng: Chiara Palladino, & Farnoosh Shamsian. (2022). Translation Alignment: Ancient Greek to English. Annotation Style Guide and Gold Standard. (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.7362097  
- Grc-Lat: Chiara Palladino, & David J. Wright. (2022). Translation Alignment: Ancient Greek to Latin. Annotation Style Guide and Gold Standard (1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.7981085
- Grc-Por: A. d'Orange Ferreira, M. dos Reis. 2022. Critérios ou Convenções de Alinhamento do Grego às Traduções em Português. Version number, date.  

## Citing our papers 

<pre>
@InProceedings{yousef-EtAl:2022:LREC,
  author    = {Yousef, Tariq  and  Palladino, Chiara  and  Shamsian, Farnoosh  and  dâ€™Orange Ferreira, Anise  and  Ferreira dos Reis, Michel},
  title     = {An automatic model and Gold Standard for translation alignment of Ancient Greek},
  booktitle      = {Proceedings of the Language Resources and Evaluation Conference},
  month          = {June},
  year           = {2022},
  address        = {Marseille, France},
  publisher      = {European Language Resources Association},
  pages     = {5894--5905},
  url       = {https://aclanthology.org/2022.lrec-1.634}
}

@InProceedings{yousef-EtAl:2022:LT4HALA2022,
  author    = {Yousef, Tariq  and  Palladino, Chiara  and  Wright, David J.  and  Berti, Monica},
  title     = {Automatic Translation Alignment for Ancient Greek and Latin},
  booktitle      = {Proceedings of the Second Workshop on Language Technologies for Historical and Ancient Languages},
  month          = {June},
  year           = {2022},
  address        = {Marseille, France},
  publisher      = {European Language Resources Association},
  pages     = {101--107},
  url       = {https://aclanthology.org/2022.lt4hala2022-1.14}
}

</pre>
