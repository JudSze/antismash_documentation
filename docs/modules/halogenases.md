# Halogenation
Halogenated biochemicals are often found among medical drugs, pesticides, insecticides and in household items. Besides their significance in our everyday life, they are also often admired because of the chemical diversity that the compounds and the diversity in mechanism that the halogenating enzymes hold.\
Although we can appreciate both halogenated compounds and halogenase enzymes, revealing their biosynthesis should come with exploring their degradation as well considering their role in environmental pollution.

## Electrophilic halogenation
### Vanadium-dependent halogenases

Vanadium-dependent halogenases form a family within the group of enzymes carrying out halogenation through electrophilic substitution.\
Which halide they accept is hinted by the nomenclature. They are named after the most electronegative halide they place on the substrate. Therefore, seeing the label "chloroperoxidase" indicates the acceptance of Cl, Br and I. Bromoperoxidases can utilize Br and I. Iodoperoxidases are only acting with I.\
They are often labelled as promiscuous, althought the group of selective enzymes started being broadened some years ago.\
In antiSMASH, their categorization boils down to their halide-specificity and whether they are selective or non-selective.
While determining the halide-specificity based on pHMM output seems to be reliable, the label of the enzyme being selective is only viable for the chloroperoxidases.\
Regioselective bromination of two VBPOs from marine algae (_Ascophyllum nodosum_ and _Corallina officinalis_) have been reported. However, which catalytic residues account for this selectivity is not well explored, therefore there is no support to determine this within antiSMASH.
https://doi-org.proxy.findit.cvt.dk/10.1021/ja004176c

### Flavin-dependent halogenases

Flavin-dependent halogenases show diversity both through sequence, domain composition and selectivity.
In antiSMASH, they are placed into two categories. One category being the conventional enzymes, which possess the three motifs often used for sequence mining: **GxGxxG**, **WxWxI(P)** and **Fx.Px.Sx.G**. It is worth noting that the **WxWxI** motif can be missing in unique members of this family.Although the conventional enzymes are often acting on aromatic ring structures, such as tryptophan, indole, pyrrole or phenolic compounds, some fungal sequencees (CmlS, AoiQ) are known to decorate aliphatic chemicals. \
The unconventional category includes enzymes lacking all the mentioned motifs. Most members of this group are capable of acting on terminal alkynes, which is an unusual substrate for FDHs. 
https://doi.org/10.1021/jacs.3c05750

## Radical halogenation

## Non-heme iron alphaketoglutarate-dependent enzymes
Non-heme iron alphaketoglutarate-dependent halogenases (NHFeHals) tailor unactivated carbons and are seen in the biosynthesis of indole alkaloids, small amino acid-, and fatty acyl-containinf compounds.

| Halogenase family | Substitution reaction | Halides | Substrate | Supporting residues | Close homologs |Disjunctive residues |
| --- | --- | --- | --- | --- | --- | --- |
| Vanadium-dependent | Electrophilic substitution | Cl, Br, I | Aromatic | | Phosphatases/transcriptional regulators | |
| Flavin-dependent | Electrophilic substitution | | Aromatic, aliphatic | GxGxxG, WxWxI, **Fx.Px.Sx.G** | Monooxygenases | |
| Non-heme iron alphaketoglutarate-dependent | Radical substitution || Aliphatic | HX**G**/**A** | Hydroxylases/dioxygenases |HX**D**/**E**|
| S-Adenosyl-L-methionine (SAM)-dependent| Nucleophilic substitution | Cl/F | Aliphatic | **RNAA**, **YYGG** | Adenosyltransferases/Deaminases | |
