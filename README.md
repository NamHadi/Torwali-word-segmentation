# Torwali-word-segmentation
Tokenization of input words is a required task in
all language processing applications. Torwali and
all other endangered languages of Northern Paki-
stan are written in a cursive Perso-Arabic script
with a set of joiners and non-joiners thus acquiring
different shapes depending upon the context. For
example, Arabic letter Farsi ‘Yeh’ /ی/ is a joiner
and has four shapes, as in /بہی / , / بیا / , / یا / and /ی/
.Arabic letter Dal د is a non-joiner and has two
forms only as in / در/ and /جدا/. Unlike English,
there is no such concept in Torwali as upper and
lowercase, which help identify word boundaries.
Also, white spaces after word ending in English is
used as a boundary marker but Torwali words do
not contain any spaces after word termination,
languages like Urdu and other Perso-Arabic lan-
guages use zero width non joiners (ZWNJ) instead
of white spaces but Torwali keyboards are still im-
mature to support ZWNJ. We applied a standard
technique called maximum matching to tokenize
input the text which generates all possible seg-
mentations based on given input sequence.
