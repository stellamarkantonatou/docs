---
layout: base
title:  'Statistics of csubj in UD_Sinhala-STB'
udver: '2'
---

## Treebank Statistics: UD_Sinhala-STB: Relations: `csubj`

This relation is universal.

17 nodes (2%) are attached to their parents as `csubj`.

16 instances of `csubj` (94%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.05882352941176.

The following 7 pairs of parts of speech are connected with `csubj`: <tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="si_stb-pos-VERB.html">VERB</a></tt> (8; 47% instances), <tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt>-<tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt> (4; 24% instances), <tt><a href="si_stb-pos-ADJ.html">ADJ</a></tt>-<tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt> (1; 6% instances), <tt><a href="si_stb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="si_stb-pos-PART.html">PART</a></tt> (1; 6% instances), <tt><a href="si_stb-pos-PROPN.html">PROPN</a></tt>-<tt><a href="si_stb-pos-VERB.html">VERB</a></tt> (1; 6% instances), <tt><a href="si_stb-pos-VERB.html">VERB</a></tt>-<tt><a href="si_stb-pos-NOUN.html">NOUN</a></tt> (1; 6% instances), <tt><a href="si_stb-pos-VERB.html">VERB</a></tt>-<tt><a href="si_stb-pos-VERB.html">VERB</a></tt> (1; 6% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 csubj	color:blue
1	ඔහු	ඔහු	PRON	_	Case=Nom|Gender=Masc|Number=Sing|PronType=Prs	6	nsubj	_	_
2	කලකට	කල	NOUN	_	Definite=Ind|Gender=Neut|Number=Ptan	3	nmod:tmod	_	_
3	පෙර	පෙර	ADV	_	AdvType=Tim	6	advmod	_	_
4	තම	තම	PRON	_	Poss=Yes|PronType=Prs	5	nmod	_	_
5	දක්ෂතාව	දක්ෂ	NOUN	_	Case=Acc|Definite=Def|Gender=Neut|Number=Sing	6	obj	_	_
6	පෙන්වූයේ	පෙන්ව	VERB	_	Mood=Ind|Tense=Past|VerbForm=Part	7	csubj	_	_
7	ලේඛනයෙනි	ලේඛන	NOUN	_	Case=Ins|Definite=Def|Gender=Neut|Number=Sing	0	root	_	_
8	.	.	PUNCT	_	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 csubj	color:blue
1	උද්ධමනය	උද්ධමන	NOUN	_	Case=Nom|Definite=Def|Gender=Neut|Number=Sing	5	nsubj	_	_
2	ශීඝ්‍ර	ශීඝ්‍ර	ADV	_	AdvType=Man	5	advmod	_	_
3	ලෙස	ලෙස	PART	_	AdpType=Post	2	case	_	_
4	ඉහළ	ඉහළ	NOUN	_	Case=Acc|Definite=Def|Gender=Neut|Number=Sing	5	compound:lvc	_	_
5	යෑම	ය	NOUN	_	Case=Acc|Definite=Def|Number=Sing|VerbForm=Ger	7	csubj	_	_
6	තවත්	තවත්	DET	_	_	7	dep	_	_
7	කාරණයෙකි	කාරණය	NOUN	_	Case=Acc|Definite=Ind|Gender=Neut|Number=Sing	0	root	_	_
8	.	.	PUNCT	_	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 3 csubj	color:blue
1	ඒ	ඒ	PRON	_	Case=Acc|Gender=Neut|PronType=Dem	3	nsubj	_	_
2	ගැන	ගැන	PART	_	AdpType=Post	1	case	_	_
3	කල්පනා	කල්පනා	NOUN	_	Case=Nom|Gender=Neut	6	csubj	_	_
4	කිරීම	කර	NOUN	_	Case=Acc|Definite=Def|Number=Sing|VerbForm=Ger	3	compound:lvc	_	_
5	පවා	පවා	PART	_	AdpType=Post	3	case	_	_
6	භයානක	භයානක	ADJ	_	Degree=Pos	0	root	_	_
7	ය	ය	PART	_	AdpType=Post	6	dep	_	_
8	.	.	PUNCT	_	_	6	punct	_	_

~~~


