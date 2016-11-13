
Gold Standard
-------------

The gold standard contains a score between 0 and 5 for each pair of sentences, with the following interpretation:

(5) The two sentences are completely equivalent, as they mean the same thing.  
  The bird is bathing in the sink.  
  Birdie is washing itself in the water basin.
(4) The two sentences are mostly equivalent, but some unimportant details differ.
  In May 2010, the troops attempted to invade Kabul.
  The US army invaded Kabul on May 7th last year, 2010.
(3) The two sentences are roughly equivalent, but some important information differs/missing.
  John said he is considered a witness but not a suspect.
  "He is not a suspect anymore." John said.
(2) The two sentences are not equivalent, but share some details.
  They flew out of the nest in groups.
  They flew into the nest together.
(1) The two sentences are not equivalent, but are on the same topic.
  The woman is playing the violin.
  The young lady enjoys listening to the guitar.
(0) The two sentences are on different topics.
  John went horse back riding at dawn with a whole group of friends.
  Sunrise at dawn is a magnificent view to take in if you wake up
  early enough for it.
--------------------------------------------------------------------------------------------------------------------
2012
The dataset comprises pairs of sentences drawn from publicly available datasets:
train+test
- MSR-Paraphrase, Microsoft Research Paraphrase Corpus
  http://research.microsoft.com/en-us/downloads/607d14d9-20cd-47e3-85bc-a2f65cd28042/
  750 + 750 pairs of sentences.

- MSR-Video, Microsoft Research Video Description Corpus
  http://research.microsoft.com/en-us/downloads/38cf15fd-b8df-477e-a4e4-a4680caa75af/
  750 + 750 pairs of sentences.

- SMTeuroparl: WMT2008 develoment dataset (Europarl section)
  http://www.statmt.org/wmt08/shared-evaluation-task.html
  734 + 459 pairs of sentences.

In addition, it contains two surprise datasets comprising the
following collections:

- SMTnews: news conversation sentence pairs from WMT
  399(test) pairs of sentences.

- OnWN: pairs of sentences where the first comes from Ontonotes and
  the second from a WordNet definition.
  750(test) pairs of sentences.
--------------------------------------------------------------------------------------------------------------------
2013

- STS.input.headlines.txt: we used headlines mined from several news  sources by European Media Monitor using the RSS feed. 
  http://emm.newsexplorer.eu/NewsExplorer/home/en/latest.html
    750 lines

- STS.input.OnWN.txt: The sentences are sense definitions from WordNet  and OntoNotes. 
    561 lines

- STS.input.FNWN.txt: The sentences are sense definitions from WordNet and FrameNet. Note that some FrameNet definitions involve more than one sentence.
    189 lines   

--------------------------------------------------------------------------------------------------------------------
2014

- STS.input.OnWN.txt: The sentences are sense definitions from WordNet and OntoNotes. 5 pairs of sentences.
    750 lines

- STS.input.tweet-news.txt: The tweet-news data set is a subset of the Linking-Tweets-to-News data set (Guo et al., 2013), which consists of 34,888 tweets and 12,704 news articles.  The tweets are the comments on the news articles.  The news sentences are the titles of news articles.
    750 lines    

- STS.input.deft-news.txt: A subset of news article data in the DEFT project. 
    300 lines

- STS.input.deft-forum.txt: A subset of discussion forum data in the DEFT project.
    450 lines

- STS.input.headlines.txt: we used headlines mined from several news sources by European Media Monitor using the RSS feed.
  http://emm.newsexplorer.eu/NewsExplorer/home/en/latest.html 
    750 lines

--------------------------------------------------------------------------------------------------------------------
2015

- STS.input.image.txt: The Image Descriptions data set is a subset of the Flickr dataset presented in (Rashtchian et al., 2010), which consisted on 8108 hand-selected images from Flickr, depicting actions and events of people or animals, with five captions per image. The image captions of the data set are released under a CreativeCommons Attribution-ShareAlike license.
        1500 lines

- STS.input.headlines.txt: We used headlines mined from several news sources by European Media Monitor using their RSS feed from April 2, 2013 to July 28, 2014. This period was selected to avoid overlap with STS 2014 data.
  http://emm.newsexplorer.eu/NewsExplorer/home/en/latest.html
        1500 lines

- STS.input.answers-students.txt: The source of these pairs is the BEETLE corpus (Dzikovska et al., 2010), is a question-answer data set collected and annotated during the evaluation of the BEETLE II  tutorial dialogue system. The BEETLE II system is an intelligent tutoring engine that teaches students in basic electricity and  electronics. The corpus was used in the student response analysis  task of semeval-2013. Given a question, a known correct "reference  answer" and the "student answer", the goal of the task was to assess  student answers as correct, contradictory or incorrect (partially  correct, irrelevant or not in the domain). For STS,we selected pairs of answers made up by single sentences.
        1500 lines

- STS.input.answers-forum.txt: This data set consists of paired  answers collected from the Stack Exchange question and answer  websites (http://stackexchange.com/). Some of the paired answers are in response to the same question, while others are in response to different questions. Each answer in the pair consists of a statement composed of a single sentence or sentence fragment. For multi-sentence answers, we extract the single sentence from the larger answer that appears to best summarize the answer. The Stack  Exchange data license requires that we provide additional metadata  that allows participants to recover the source of each paired  answer. Systems submitted to the shared task must not make use of  this meta-data in anyway to assign STS scores or to otherwise inform the operation of the system.
        2000 lines

- STS.input.belief: The data is collected from DEFT Committed Belief  Annotation dataset (LDC2014E55).  All source documents are English
  Discussion Forum data.
        2000 lines

--------------------------------------------------------------------------------------------------------------------
2016

around 250 of each type. problem is with the blank entries



