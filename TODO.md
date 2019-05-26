# Todos 21. 6. 2019

[ ] "Wie sieht der allgemeine Ablauf aus?"
  - Was macht Mensch, was Maschine? -> Diagramm
  - Formulierungen: "Dieses System hat ein Modell", "crucial component"
  
[ ] "97.4%" muss in Tabelle 2
  - "x + Privacy"
  - @Reviewer 2: Wir vergleichen nur mit unserer Baseline, nicht mit SotA (wir benutzen auch diese Methoden nicht)

[ ] "DANN doesn't work": wir sagen "adversary schafft 80% -> discard"
  - vorher Elizar et al erklären, dass Adversary allein trainieren ein Problem ist
  - "Das System funktioniert nur gut, wenn auch Adversary allein trainieren nicht möglich ist" bei Adversaries 5.3

[ ] S 5: es ist unklar, was unseres ist
  - Formulierung mit Passiv sollte ausreichen

[ ] "Term de-identification unklar"
  - könnte mit Diagramm gelöst werden
  - "Automatic classifiers…" Satz im Abstract ist verwirrend: Teilprozess kann nicht so heißen wie der ganze Prozess
  - "changing PHI in medical text…"
  - "Automatic classifiers that detect PHI…"
  - de-identification vs sanitization (Max soll Begriffe nachlesen)
  - Z 64: "manual sanitization?" sansitive data "has to be performed manually"

[ ] Adversary output muss single unit (binary) klarer machen?

[ ] Footnote 1 ist wichtig, lieber in Klammern?

[ ] 7.3 "confirms the findings by" -- was sind die Findings?

[ ] Bei den Diagrammen: error bars oder sagen, dass es 5 Durchläufe waren

[ ] Z 641: Wort "augmented" in diesem Zusammenhang?
  - In diesem Abschnitt wollen wir nur sagen:
    1. Es funktioniert besser -> see table X
    2. Hypothese, warum? (was heißt "es ist besser"?)
  - "in constrast to the autom. pseudom. approach, in the adversarial model, …, feature extractor"
  - "augmented"-Satz löschen?

[ ] Z 700: "on the training data"
  - Das ist die Definition von "overfit"
  - Hilft die Figure mit den learning curves? 
    - Nein, weil sie ja das Training und nicht die frozen evaluation abbildet, wo Adversary Train/val loss konstant schlecht ist -- dafür braucht man auch keine Figure
