# Summary

UD Turkish-German SAGT is a Turkish-German code-switching treebank that is developed as part of the [SAGT](https://www.ims.uni-stuttgart.de/en/research/projects/sagt/) project. 

# Introduction

The treebank consists of bilingual conversation transcriptions annotated with several
layers: language IDs, lemmas, POS tags, morphological features, and dependency
relations. Language IDs employ the tag set of Çetinoğlu (2017).
The rest of the annotations follow Universal Dependencies annotation scheme, and
the conventions used in monolingual Turkish and German treebanks. 

There are 48 distinct conversations from 17 participants.
The majority of the speakers are university students, hence the most
frequent age range is 18–25. Common conversation themes include studies, work,
travel, free time activities such as sports, books, TV, and future plans.

The accompanying audio recordings of transcriptions are also available as a speech corpus, with
a separate licence. Please contact ozlem@ims.uni-stuttgart.de for further information.

# Data Split

In total, there are 2184 sentences in the treebank. All sentences contain at least one intrasentential switch.
The data is split into train, development, and test sets, paying attention to conversation boundaries as well as a balanced theme and participant distribution.

<table>
<tr style="background-color: #eee"><th>Split</th><th># Conversations</th><th># Sentences</th><th># Tokens</th>
</tr>
<tr><td>train      </td><td>15</td><td>578</td><td>10084</td></tr>
<tr><td>development</td><td>17</td><td>801</td><td>13057</td></tr>
<tr><td>test       </td><td>16</td><td>805</td><td>14092</td></tr>
</table>

# Contributors

* Özlem Çetinoğlu -- IMS, University of Stuttgart
* Çağrı Çöltekin -- Department of Linguistics, University of Tübingen

# Acknowledgments

The treebank development is funded by DFG via project CE 326/1-1 “Computational Structural Analysis of German-Turkish  Code-Switching”. We thank Cansu Turgut, Reha Sakızlı, Semanur Ceylan, and Sevde Ceylan for data collection and annotation.

## References
For the treebank:
* Özlem Çetinoğlu and Çağrı Çöltekin (2019). "Challenges of Annotating a Code-Switching Treebank". In _Proceedings of the 18th International Workshop on Treebanks and Linguistic Theories (TLT, SyntaxFest 2019)_
<https://www.aclweb.org/anthology/W19-7809.pdf>

For the speech collection (Note that the paper describes a separate speech corpus but the methodology is parallel.)
* Özlem Çetinoğlu (2017). "A Code-Switching Corpus of Turkish-German Conversations". In _Proceedings of the 11th Linguistic Annotation Workshop_
<https://www.aclweb.org/anthology/W17-0804.pdf>


# Changelog

* 2020-11-15 v2.7
  * Initial release in Universal Dependencies.


<pre>
=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v2.7
License: CC BY-NC-SA 4.0
Includes text: yes
Genre: spoken
Lemmas: manual native
UPOS: manual native
XPOS: not available
Features: manual native
Relations: manual native
Contributors: Çetinoğlu, Özlem; Çöltekin, Çağrı
Contributing: elsewhere
Contact: ozlem@ims.uni-stuttgart.de
===============================================================================
</pre>
