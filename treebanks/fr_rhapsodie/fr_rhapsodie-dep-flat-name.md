---
layout: base
title:  'Statistics of flat:name in UD_French-Rhapsodie'
udver: '2'
---

## Treebank Statistics: UD_French-Rhapsodie: Relations: `flat:name`

This relation is a language-specific subtype of <tt><a href="fr_rhapsodie-dep-flat.html">flat</a></tt>.

161 nodes (0%) are attached to their parents as `flat:name`.

161 instances of `flat:name` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.12422360248447.

The following 2 pairs of parts of speech are connected with `flat:name`: <tt><a href="fr_rhapsodie-pos-PROPN.html">PROPN</a></tt>-<tt><a href="fr_rhapsodie-pos-PROPN.html">PROPN</a></tt> (160; 99% instances), <tt><a href="fr_rhapsodie-pos-NOUN.html">NOUN</a></tt>-<tt><a href="fr_rhapsodie-pos-PROPN.html">PROPN</a></tt> (1; 1% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 6 flat:name	color:blue
1	réponse	réponse	NOUN	_	Gender=Fem|Number=Sing	0	root	_	_
2	à	à	ADP	_	_	3	mark	_	_
3	suivre	suivre	VERB	_	VerbForm=Inf	1	acl	_	Subject=NoRaising
4	avec	avec	ADP	_	_	5	case	_	_
5	Hélène	Hélène	PROPN	_	_	3	obl:mod	_	_
6	Chevalier	Chevalier	PROPN	_	_	5	flat:name	_	_
7	à	à	ADP	_	_	9	case	_	_
8	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	9	det	_	_
9	congrès	congrès	NOUN	_	Gender=Masc|Number=Sing	3	obl:mod	_	_
10	de	de	ADP	_	_	11	case	_	_
11	Barcelone	Barcelone	PROPN	_	_	9	nmod	_	SpaceAfter=No
12	.	.	PUNCT	_	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 8 flat:name	color:blue
1	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	2	det	_	_
2	président	président	NOUN	_	Gender=Masc|Number=Sing	0	root	_	_
3	de	de	ADP	_	_	5	case	_	_
4	l'	le	DET	_	Definite=Def|Number=Sing|PronType=Art	5	det	_	SpaceAfter=No
5	Unef	Unef	PROPN	_	_	2	nmod	_	SpaceAfter=No
6	,	,	PUNCT	_	_	7	punct	_	_
7	Jean-Baptiste	Jean-Baptiste	PROPN	_	_	2	flat	_	_
8	Prévot	Prévot	PROPN	_	_	2	flat:name	_	SpaceAfter=No
9	,	,	PUNCT	_	_	12	punct	_	_
10	à	à	ADP	_	_	12	case	_	_
11	le	le	DET	_	Definite=Def|Gender=Masc|Number=Sing|PronType=Art	12	det	_	_
12	micro	micro	NOUN	_	Gender=Masc|Number=Sing	7	nmod	_	_
13	de	de	ADP	_	_	14	case	_	_
14	Sonia	Sonia	PROPN	_	_	12	nmod	_	_
15	Bourane	Bourane	PROPN	_	_	14	flat:name	_	SpaceAfter=No
16	.	.	PUNCT	_	_	2	punct	_	_

~~~


