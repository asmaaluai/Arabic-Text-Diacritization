# Arabic-Text-Diacritization

## Abstract
Nowadays most Arabic native
speakers tend to neglect the importance of
Arabic diacritics. Users in social media for
example rarely use any diacritics when
typing. This is adequate for Native
speakers however a big problem arises
from this habit. It creates a huge gap
between the Native speakers and the nonnative speakers this is because Arabic
diacritics add the true meaning of the
word. Arabic is a sea rich with words, but
some words are written the same but are
different because of the diacritics.
Diacritics help learners and non-native
speakers to differentiate between the
words. Arabic speakers can differentiate
between the words because of the context
but for a new learner, this is a struggle.
For this project, several machine-learning
models are utilized and trained on the data
that was obtained from the Tashkela
corpus. Before modeling, preprocessing
steps were necessary to ensure that we had
clean data, followed by an exploratory
data analysis step to know more about the
data and how to deal with it. For this
matter RNN was evaluated and used,
FFNN, FFNN with embedding, and
finally transformer using sequence to
sequence was also tested. The models were
only trained on a small subset due to the
lack of efficient resources. The RNN with
embedding ended up giving us the best
results with a substantial accuracy of 97%.

## About the Dataset
For this project, the models were
trained in a subset of a larger
dataset. The original dataset was
obtained from the Tashkela corpus.
The dataset was developed by
extracting Arabic text from 97
religious books, and famous Arabic
works like poems and hymns. It has
over 75.6 million words and 67.2
million are discretized. The Arabic
text was written in distinctive styles
and the structure was inconsistent.

