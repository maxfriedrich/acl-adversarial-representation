# Todos 21. 6. 2019

- [x] Am wichtigsten: "Wie sieht der allgemeine Ablauf aus?"
  - Was macht Mensch, was Maschine? -> Diagramm
  - Formulierungen: "Dieses System hat ein Modell", "crucial component"

- [x] "97.4%" muss in Tabelle 2
  - "x + Privacy"
  - @Reviewer 2: Wir vergleichen nur mit unserer Baseline, nicht mit SotA (wir benutzen auch diese Methoden nicht)

- [x] "DANN doesn't work": wir sagen "adversary schafft 80% -> discard"
  - vorher Elazar et al erklären, dass Adversary allein trainieren ein Problem ist -- das steht schon in 2.2
  - "Das System funktioniert nur gut, wenn auch Adversary allein trainieren nicht möglich ist" bei Adversaries 5.3

- [x] S 5: es ist unklar, was unseres ist
  - Formulierung mit Passiv sollte ausreichen

- [ ] "Term de-identification unklar"
  - könnte mit Diagramm gelöst werden
  - [x] "Automatic classifiers…" Satz im Abstract ist verwirrend: Teilprozess kann nicht so heißen wie der ganze Prozess
  - "changing PHI in medical text…"
  - "Automatic classifiers that detect PHI…"
  - de-identification vs sanitization (Max soll Begriffe nachlesen)
    - [Sanitization](https://en.wikipedia.org/wiki/Sanitization_(classified_information)) ist _entfernen_/schwärzen von sensitive information
  - Z 64: "manual sanitization?" sansitive data "has to be performed manually" -- steht da eigentlisch schon (""sanitization cannot be fully automated…")
    - [x] Arne: "cannot be fully automated" ist aber etwas anderes als "has to be performed manually" -- das erste könnte auch einfach heißen,dass es aktuell technisch nicht geht.  Der Punkt ist aber, dass es von Menschen gemacht werden *muss*, da es rechtlich notwendig ist. -- noch mal klargestellt

- [x] Adversary output muss single unit (binary) klarer machen?

- [ ] Footnote 1 ist wichtig, lieber in Klammern?
  - Max: die Footnote ist ja direkt unten und was sollte sonst in [] markiert sein…

- [x] 7.3 "confirms the findings by" -- was sind die Findings? -- sie stehen in 2.2 aber sind bis hier wieder vergessen?

- [x] Bei den Diagrammen: error bars oder sagen, dass es 5 Durchläufe waren
  - erstmal nur gesagt, dass es 5 Durchläufe waren (Results oben)

- [x] Z 641: Wort "augmented" in diesem Zusammenhang?
  - In diesem Abschnitt wollen wir nur sagen:
    1. Es funktioniert besser -> see table X
    2. Hypothese, warum? (was heißt "es ist besser"?)
  - "in constrast to the autom. pseudom. approach, in the adversarial model, …, feature extractor"
  - "augmented"-Satz löschen?

- [x] Z 700: "on the training data" (erstmal nur so klargestellt)
  - Das ist die Definition von "overfit"
  - Hilft die Figure mit den learning curves?
    - Nein, weil sie ja das Training und nicht die frozen evaluation abbildet, wo Adversary Train/val loss konstant schlecht ist -- dafür braucht man auch keine Figure

## Max zusammenfassende Todos

- [x] Die "draft figure" will ich noch mal überdenken und dann vernünftig in Tikz zeichnen
- [ ] Klarer machen, was unsere Contribution genau ist
- [ ] Vielleicht bei der Conclusion alles löschen, was 1:1 Wiederholung von davor ist?
- [x] Noch ein paar Wording-Sachen -- danke Chris!
  - [x] z.B. direkt am Anfang der Einleitung, wo in zwei Sätzen 2x "contain" und "data" steht
- [ ] Author information, will Arne Hamburg oder Saarland sein?
- [ ] Welches Yimam Paper ist genau gemeint:
  - Automatic Annotation Suggestions and Custom Annotation Layers in WebAnno https://aclweb.org/anthology/papers/P/P14/P14-5016/
  - Interactive and Iterative Annotation for Biomedical Entity Recognition https://link.springer.com/chapter/10.1007/978-3-319-23344-4_34
- [x] Strich bei 0.5 adversary accuracy (yticks angepasst, sollte auch reichen)
- [x] Arxiv papers checken -- habe keine akzeptierten Versionen mehr gefunden
