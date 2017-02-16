---
title       : Einführung in DataCamp
description : Dieses Kapitel soll dazu dienen sich in DataCamp zurechtzufinden.
attachments :
  slides_link : 

--- type:NormalExercise lang:r xp:100 skills:1 key:07024a9b16
## Vektoren

*** =instructions

An dieser Stelle finden Sie immer die Aufgabenstellung. Starten Sie zunächst mit einer einfachen Übung: Definieren Sie einen Vektor, der aus den Elementen 1 bis 5 besteht.


*** =hint
c(1:5)

*** =pre_exercise_code
```{r}

```

*** =sample_code
```{r}
# Dieses Fenster stellt den Editor dar, den Sie bereits aus RStudio kennnen und erlaubt es Skripte zu schreiben.
# Für Lösungen der Aufgaben muss immer in dieses Fenster genutzt werden. Für Zwischenschritte können Sie aber auch direkt in der Konsole arbeiten.

# Wichtig: In dem auskommentierten Teil am Anfang dieses Skriptes finden Sie weitere Hinweise, wie die Aufgabe zu lösen ist.
# Im vorliegenden Beispiel lautet die Anweisung, die Lösung unter dem Objekt *testvektor* zu speichern.
```

*** =solution
```{r}
testvektor <- c(1:5)
```

*** =sct
```{r}
test_error()
test_object("testvektor",
            undefined_msg = "Hier hat etwas nicht geklappt. Versuchen Sie es erneut!",
            incorrect_msg = "Es wurden falsche Werte zugewiesen.")
success_msg("Richtig!")
```
