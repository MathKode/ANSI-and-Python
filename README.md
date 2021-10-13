# ANSI-and-Python
>Intro

Les séquences d'échappements sont des "indications" qui permettent de dire à notre code comment écrire un texte (en gras, surlignés, couleur et même ou écrire le texte).
Elle sont répertorier dans la table ANSI et peuvent être appeller en python avec un ``\x1b[`` dans un print.
A la fin de ce document, qui agit comme cours/mémo, vous serrez capable de comprendre cette fonction :
```
print("\x1b[2;11f\x1b[33;40mok\x1b[0J")
```

>Sommaire:

|Partie|Description|
|---|---|
|[Couleur](/c1.md)|Une partie qui vous apprend à changer les couleurs de votre terminal|
|[Style](/c2.md)|Une partie dédiée aux styles (gras, sousligné...)|
|[Curseur](/c3.md)|Un cours sur le déplacement du curseur|
|[Effacement](/c4.md)|Une partie sur la suppression de texte...|
|[Test](/c5.md)|Des testes pour mieux comprendre|

Bonne lecture !

Si vous avez la moindre question merci de [me contacter](mathiskremer.mk@gmail.com)
