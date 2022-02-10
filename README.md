# html-boilerplate

## Cand se modifica codul, rulati:

` git add .` adaugam toate fisierele in comit

``git commit -m "mesaj comit"` salvam stadiul codului cu mesajul "mesaj comit"

` git push` urcam continutul commitului pe server (origin )

## Daca descarcam prima data codul:

`git clonehttps://...` creaza o copiea repo-ului de pe github

Aceasta copie are tot istoricul de pe github pentru acest repo

o data clonat se poate urca normal ca la procesul de mai sus

## daca lucram pe acelasi proiect,pe mai mult device-uri:

se presupune ca repo-ul a fost clonat pe toate device-urile.

- situatia 1: pe leptop 1 s-au modificat fisiere:

Se urca in mod normal pe github cu comenzile de `add`,`commit`,`push`

Pe laptop 2 trebuie sincronizat codul. Se va rula:

`git pull` va aduce in local toate schimbarile de pe github

-situatia 2: pe laptop 2 s-au modificat si urcat schimbari:

Se urmeaza instrunctiunile de add si commit

inainte de a da `push` se va da un `git pull` pentru a sincroniza ce e local cu ce e pe github

se poate rula `git push` care va contine modificarile locale si cele de pe github

end documentatie
