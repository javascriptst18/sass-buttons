# sass-buttons

## Installation 

1. Klona ner detta repository till vilket ställe som helst på din dator via Git Bash. Se till så att du står på det ställe där du vill lägga mappen, navigera annars till rätt ställe med `cd`.
```bash
git clone https://github.com/jesperorb/sass-buttons
```
2. Navigera in i mappen med `cd`:
```bash
cd sass-buttons
```
3. Starta sass via valfritt program, enklast är att använda [Scout App](http://scout-app.io/). Ladda ner programmet och starta upp det. När det har startat så drar du mappen som du har klonat ner in i Scout och trycker sedan på "Play"-knappen.

## Uppgift

Koden i `style.scss` är vanlig `.css`. Uppgiften är att göra om den css som finns i filen till att använda:
* _Variabler_ där det är upprepning eller vanligt förekommande värden
* _Nesting_ där en selektor refererar till ett barn så som `.card div`
* Det finns även en lösning med [`@extend`](https://sass-lang.com/guide), testa att lösa denna med det om du har tid.
* Testa använda någon funktion som är inbyggd i sass: http://sass-lang.com/documentation/Sass/Script/Functions.html

En översikt av vad som går att göra finns på:
* https://sass-lang.com/guide
