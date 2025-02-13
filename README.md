# Handbók húsfélagsins Bríetartúni 9-11

## Setja upp þróunarumhverfið
Síðan er búin til með static site generatornum [MkDocs](https://www.mkdocs.org/). Nánar tiltekið [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/). Byrjaður á að [kynna þér hvernig það kerfi virkar](https://squidfunk.github.io/mkdocs-material/getting-started/).

### Setja upp Python og Git
1. Athugaðu hvort þú sért með Python 3 uppsett á tölvunni og ef ekki byrjaðu á að setja það upp. 
*Það eru nokkrar leiðir til að gera þetta, ein er að sækja installer á [python.org](https://www.python.org/downloads/). og setja upp.*

Sjá leiðbeiningar í [Python Setup and Usage](https://docs.python.org/3/using/index.html) undir viðeigandi kafla fyrir þitt stýrikerfi.

Leiðbeiningarnar gera ráð fyrir að "python" skipunin sé í path og vísi á python 3 uppsetninguna. Ef þú ert ekki með python í path eða ert með aðra útgafu af python í path en útgáfu 3 þá þarftu að aðlaga skipanirnar þinnar að þinni uppsetningu eða breyta stillingunum á tölvunni þinni þannig sú útgáfa sé í path. 

2. Sæktu kóðann á GitHub
*Þú þarft að kunna á git og vera með git client settan upp á tölvunni þinni til að geta sótt og unnið með kóðan á bakvið síðuna. Sjá til dæmis: [Getting started with GitHub](https://help.github.com/en/github/getting-started-with-github)*

### Búa til virtual environment og setja upp python library
Eftir að hafa sótt kóðan í fyrsta skiptið, búðu þá til virtual environment til að keyra kóðan inní 

```bash
python -m venv env
source env/Scripts/activate
pip install -r requirements.txt
```

## Ræsa þróunarvefþjón

```bash
mkdocs serve
```

Núna ættirðu að geta opnað síðuna á http://127.0.0.1:8000/