# Uppgifter i Ruby

# Lätta uppgifter

1. Deklarera en variabel 'x'
2. Deklarera och initialisera en variabel 'name' till 'RubyMine'.
3. Vad får man om man multiplicera en sträng med ett decimal tal?
     t.ex 'Ruby'*3.14.
4. Vad är resultat av 1/3 i Ruby.
5. Skriv en loop som skriver ut de 10 första tal.
6. Omvandla strängen '123' till ett tal.
7. Omvandla strängen '3.14' till ett decimal tal.
8. Med en loop skriver ut alla bokstäver i en sträng med en bokstav per rad.
9. Invertera en sträng med en loop dvs 'RubyMine' bli 'eniMybuR'.
10. Skapa en lista av 20 slumpmässiga valde tal mellan 0 och 10.
11. Skriv en funktion som räknar upp den största värden ('max') av alla tal i en listan.
12. Skriv en funktion som räknar upp den minsta värden ('min') av alla tal i en listan.
13. Skriv en funktion som summerar alla tal i en lista.
14. Skriv en funktion som multiplicerar alla tal i en lista.
15. Skriv en funktion som räknar upp strängen '(10*3.14 + 2.3)/5'.
16. Skriv en funktion som returnera slumpmässig ett tal mellan 1 och 6.
17. Skriv en funktion som simulera AND or (&&) operatör med bara if-statser. 
       Dvs: true AND true  = true
            true AND false = false
18. Skriv en funktion som räknar upp den största värden ('max') av alla tal i en listan.
19. Skriv en funktion som räknar upp den minsta värden ('min') av alla tal i en listan.


# Svårare uppgifter

1. Skapa en variabel som innehåller alla små bokstäver i alfabet genom att använda en 'range' dvs (1..10).
2. Della upp en sträng som t.ex 'RubyMine' i en lista av enskilda bokstäver.
3. Omvandla en lista av bokstäver i en sträng.
4. Skriv en funktion 'histogram' som tar en lista som argument och skriver ut en antal stjärnor (*) för varje tal i listan. T.ex histogram([4,9,7]) ger:
****
*********
******* 
5. Använd Caesar cipher och följande nyckel (ROT-13)
```Ruby
key = {'a':'n', 'b':'o', 'c':'p', 'd':'q', 'e':'r', 'f':'s', 'g':'t', 'h':'u', 'i':'v', 'j':'w', 'k':'x', 'l':'y', 'm':'z', 'n':'a', 'o':'b', 'p':'c', 'q':'d', 'r':'e', 's':'f', 't':'g', 'u':'h', 'v':'i', 'w':'j', 'x':'k','y':'l', 'z':'m', 'A':'N', 'B':'O', 'C':'P', 'D':'Q', 'E':'R', 'F':'S', 'G':'T', 'H':'U', 'I':'V', 'J':'W', 'K':'X', 'L':'Y', 'M':'Z', 'N':'A', 'O':'B', 'P':'C', 'Q':'D', 'R':'E', 'S':'F', 'T':'G', 'U':'H', 'V':'I', 'W':'J', 'X':'K', 'Y':'L', 'Z':'M'}
```
för att dekryptera följande meddelande:
```Ruby
Pnrfne pvcure? V zhpu cersre Pnrfne fnynq!
```
6. International Civil Aviation Organization (ICAO) ersätter varje bostav med en akrofon dvs. namnet börjar med det ljud som orden betecknar.

```Ruby
d = {'a':'alfa', 'b':'bravo', 'c':'charlie', 'd':'delta', 'e':'echo', 'f':'foxtrot','g':'golf', 'h':'hotel', 'i':'india', 'j':'juliett', 'k':'kilo', 'l':'lima','m':'mike', 'n':'november', 'o':'oscar', 'p':'papa', 'q':'quebec', 'r':'romeo','s':'sierra', 't':'tango', 'u':'uniform', 'v':'victor', 'w':'whiskey', 'x':'x-ray', 'y':'yankee', 'z':'zulu'}
```


4. Använd den följande morsekod för att skriva en enkel översättare för att kodera och dekodera en meddelande på engelska.
```Ruby
CODE = {'A': '.-',     'B': '-...',   'C': '-.-.', 
        'D': '-..',    'E': '.',      'F': '..-.',
        'G': '--.',    'H': '....',   'I': '..',
        'J': '.---',   'K': '-.-',    'L': '.-..',
        'M': '--',     'N': '-.',     'O': '---',
        'P': '.--.',   'Q': '--.-',   'R': '.-.',
     	'S': '...',    'T': '-',      'U': '..-',
        'V': '...-',   'W': '.--',    'X': '-..-',
        'Y': '-.--',   'Z': '--..',
        '0': '-----',  '1': '.----',  '2': '..---',
        '3': '...--',  '4': '....-',  '5': '.....',
        '6': '-....',  '7': '--...',  '8': '---..',
        '9': '----.' 
        }
```


