# mediavuk-test
Ovo je test za prezentaciju.

# Git Komande
Otvoriti komandnu liniju ( command pront, powerShell, GitBash...) i unositi komande koje su navedene u nastavku
cd path/to/folder (putanja ka folderu koji vam treba u tom trenutku) ili desnim klikom na lokalni folder koji zelite da povezete sa repositoriumom i odaberite opciju iz padajuceg menija “Git Bash Here”.
git init (dodavanje git foldera u izabrani folder)
Konfigurisanje podataka o korisniku se radi putem komandi:
git config --global user.email "e-mail@test.com"
git config --global user.name "username"
Da bi ste podesili na nivou celog racunara dodate komandu --global, ako zelite da podesite samo na nivou pojedinacnog foldera izostavite gore navedenu komandu.
Kada je napravljen repositorium, da bi se povezao sa lokalnim folderom, koristi se komanda;
git remote add origin  https://github.com/username/repositories.git
- Ukoliko repositorium na GitHub-u sadrzi bilo kakav fajl moramo da ga prvo kloniramo na svoj racunar komandom; 
git clone https://github.com/username/repositories.git 
komanda kojom sve fajlove iz lokalnog foldera ubacimo na GutHub repositorium 
git push --set-upstream origin master ( skracena verzija je --set-upstream je -u )
git status radi provere statusa fajlova - moze posle svake komande jer nema nikakav uticaj
Dodavanje svih fajlova i foldera komandom git add . ili  dodavanje pojedinacnog fajla komandom git add [name-of-file]
git commit -m “message” komentarisanje promena pre ubacivanja na github
git push komanda kojom pusujemo izabrane fajlove i foldere iz commit-a
Vraćanje prethodnih verzija projekta možete uraditi komandama reset ili checkout.
git checkout 999899Po pa onda git commit - vraća na određenu verziju ali ne briše ostale verzije dok git reset --hard 999899Po briše sve vezije nakon commit-a na koji se vratimo.
