git init - kijelöltem a mappát amiben dolgozok.

git pull https://github.com/szabopeter92/git-vizsga0104.git - letöltöttem a fájlokat a saját mappámba

git branch console - létrehoztam a console nevű ágat.

git checkout console - átváltottam a console ágra.

git commit -m "app.js módostva, kiírja a konzol, ha betöltődött az oldal."

git add . - hozzá adtam a fájlokat, hogy lássa mit fogok commitolni (nem tudom ez így helyes-e vagy nem, de csak így engedte)

git commit -m "Az oldal háttere módosítva."

git remote add origin https://github.com/Mursa97/mursarichard-gitvizsa-0105.git
git branch -M console
git push -u origin console    - megadtam a github repositoryt és fel pusholtam a console branchet.