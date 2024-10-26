# Calcolatore di Area e Circonferenza di un Cerchio

Questo script `.vbs` è un semplice programma per calcolare l'area e la circonferenza di un cerchio dato il raggio, inserito dall'utente tramite una finestra di input.

## Funzionalità

- **Calcolo Area**: calcola l'area di un cerchio usando la formula: `area = π * r^2`
- **Calcolo Circonferenza**: calcola la circonferenza di un cerchio usando la formula: `circonferenza = 2 * π * r`

> Nota: Questo script utilizza un valore approssimato di π (3.14).

## Requisiti

- Windows con supporto per VBScript

## Utilizzo

1. Esegui il file `.vbs` facendo doppio clic su di esso.
2. Inserisci il raggio del cerchio nella finestra di input che si apre.
3. Appariranno due finestre con i risultati:
   - **Area del Cerchio**
   - **Circonferenza del Cerchio**

## Codice

```vbscript
r = InputBox("Raggio.")
area = (r^2 * 3.14)
lunghezza = (2 * r * 3.14) 'Corretto il calcolo della circonferenza
MsgBox "Area cerchio = " & area
MsgBox "Circonferenza = " & lunghezza
```


## Autore

Realizzato da HighMark
