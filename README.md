# Introduction

# Corpus Flows Associated with the DHN Workshop

stylistic-profile.json

# Corpora Flows Associated with the DHN Workshop

Each corpora-flow consists of dedicated sections for each plain text corpus it processes. It invokes tasks from the corpus-flow necessary for each task and tweaks any relevant parameters, such as how a particular document should be parsed and split into words and sentences.

## nabokov-english
Novels written in English:

Novels Nabokov
English: corpus-en, sinister-en, lolita-en, pnin-en, harlequins-en, invite-en, gift-en, defense-en, knave-en, speak-en

## nabokov-russian

Russian: corpus-ru, mary-ru, knave-ru, defense-ru, invite-ru, gift-ru, speak-ru, lolita-ru

## Other books to be added in future experiments

### Nabokov’s Novels in English
1. **(1941) The Real Life of Sebastian Knight**
1. **(1947) Bend Sinister**
1. **(1955) Lolita, self-translated into Russian (1965)**
1. **(1957) Pnin**
1. (1962) Pale Fire
1. (1969) Ada or Ardor: A Family Chronicle
1. (1972) Transparent Things
1. **(1974) Look at the Harlequins!**
1. Plus **Speak, Memory (1951/1967)**

### Nabokov’s Novels in Russian
1. **(1926) Mashen'ka** (Машенька); English translation: Mary (1970)
1. **(1928) Korol' Dama Valet (Король, дама, валет)**; English translation: **King, Queen, Knave (1968)**
1. **(1930) Zashchita Luzhina (Защита Лужина)**; English translation: The Luzhin Defense or **The Defense** (1964) (also adapted to film, The Luzhin Defence, in 2000)
1. (1930) Sogliadatai (Соглядатай (The Voyeur)), novella; first publication as a book 1938; English translation: The Eye (1965)
1. (1932) Podvig (Подвиг (Deed)); English translation: Glory (1971)
1. (1933) Kamera Obskura (Камера Обскура); English translations: Camera Obscura (1936), Laughter in the Dark (1938)
1. (1934) Otchayanie (Отчаяние); English translation: Despair (1937, 1965)
1. **(1936) Priglasheniye na kazn'** (Приглашение на казнь (Invitation to an execution)); English translation: **Invitation to a Beheading** (1959)
1. **(1938) Dar** (Дар); English translation: **The Gift** (1963)
Plus **Lolita** and **Drugie berega**.

# Example Flow
## import documents (corpora)
## English
## Russian
## import documents (balanced corpora)
- Brown Fiction
- Russian National Corpus (fiction)
## parse documents
## POS, both unigrams and bigrams combinations of two (we can mention we support trigrams but not necessary to use them)
## do POS-mapping
## visualizing of distributions
## Calling up examples of text with the POS bigrams and unigrams (more than X)
## Sentence length
## Richness (mention exoticism, but unnecessary to run)
## Etymology
- As a special bonus, would be great to run etymology in Russian too - was it possible?
## SoW?

# Tentative Schedule

## First hour:
1. 15 min intro in methods in stylometry, existing tools, their pros and cons
1. 15 min intro into Bukvik and existing results
1. 15 min – Accessing Bukvik on the participants’ computers

## Second hour:
1. Make experiments. We will pre-run each task beforehand to make sure everything is smooth.
1. Simulate research process through experiments. Give quote from Grayson/Nabokov on differences for researchers. How do we test that?

##### POS: First, run Nabokov in Russian and English on POS, focus on nouns and adj.

1. Aha, more nouns, interesting.
1. Find examples of sentences with lots of nouns.

##### Sentence length. Hypothesis – longer sentences? Run.
1. Nope, but look at the translation effect, make a note.
1. So, original texts in English have more nouns but not longer sentences.

##### POS combinations. For example, can it be lists?
1. See NN NN NN. **not done for dissertation**
1. Demonstrate POS combinations. **not done for dissertation**
1. Ask if we should check other combinations, do a couple they suggest.

##### Richness. Another hypothesis – richer vocabulary?
1. Run, yep.
1. Why richer? More foreign words, for sure. Knowing Nabokov, seems like we’re on the right path. Here, cite Chepiga, give an example from Ada.

##### Etymology. Hm, but what about choices in non-foreign words? Run etymology, indeed.

1. Show different languages.
1. Create a diagram with average distribution by origin. **not done for dissertation**
1. If possible, double the experiment for Russian. **not done for dissertation**

## Third hour:

1. Sum up (give reference for forthcoming publication).
1. Is etymology then the reason for richer vocab? For more nouns? Well, it can contribute to varied.
1. Nabokov has more nouns and richer vocab in his L2, and one factor that may help account for it is his preference for a distribution of words with particular kinds of origins, different from the normal distribution. This is one feature of deviation from the norm within standard language = style.
1. Stylistic profile.
1. Get samples of text, read in the light of what we learned – paying attention to nouns. Find a good passage for that.
1. What could we look at next? Brainstorm. Potential projects. Potential development.
1. Intro of other capacities of Bukvik, existing and in progress.
**Society of Words, semantic…**
1. Brainstorm on the future of such tools, and where Bukvik can/will develop (modular etc).
1. Collaborations?
