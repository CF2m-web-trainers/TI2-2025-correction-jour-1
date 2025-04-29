# TI2-2025

## Correction des TI2 WEBDEV 2025 

## Partie 1 : le 28/04/2025 de 9h à 12h30 et 13h15 à 16h45

### Cloner le projet

Utiliser `git` pour cloner le projet sur votre machine locale, en dehors d'un projet existant !


```bash
git clone git@github.com:CF2m-web-trainers/TI2-2025-correction-jour-1.git
cd TI2-2025-correction-jour-1
```

Pour voir les branches des stagiaires remises à 16h45 le 28/04 :

```bash
git branch -a
```

### Prérequis pour la correction
- Avoir un serveur Web (Apache ou Nginx) installé et configuré pointant vers le répertoire `public` de ce répertoire.
- Avoir PHP 8.0 ou supérieur installé et configuré.
- Installation de la DB en MySQL et en MariaDB (suivant le choix des stagiaires) via PHPMyAdmin en important le fichier `data/ti2web2025.sql` dans chacune des DB.
- Enregistrer le fichier `config.php.ini` sous le nom `config.php` à la racine du projet.

### Correction

La branche `main` contient le code avant la correction. On est dessus par défaut.

Pour créer chacune des branches des stagiaires en local (les données du stagiaire seront automatiquement dessus, ce qui permet d'avoir qu'une URL pour vérifier les tests), il faut faire dans le dossier les commandes suivantes (exactement) :

- Vahag
```bash
git checkout vahag1991-ti2
```
- Reda
```bash
git checkout redasnkrs-reda
```
- Jérémy
```bash
git checkout jeremyvdk91-TI2
```
- Agim
```bash
git checkout agim-coroli-agim
```
- Soulaiman
```bash
git checkout SoulaimanDev-main
```
- Sola
```bash
git checkout SolaKabuta-sola
```
- Omer
```bash
git checkout OkiSenpai-omer
```
- Nordine
```bash
git checkout Nono1050-Ti2025
```
- Mykyta
```bash
git checkout NikGorban-ti2Mykyta
```
- Daniel
```bash
git checkout Misikalenga-main
```
- Massine
```bash
git checkout Massine2k1-bonus
```
- Jean-Michael
```bash
git checkout MRJMV-main
```
- Géraldine
```bash
git checkout GEUNGA-main
```
- Samuel
```bash
git checkout Eultype-DARRYSamuel
```

### Et là vous pouvez tester chaque stagiaire en local sur votre serveur Web.

### Pour les bonus / corrections

Ils peuvent continuer à travailler sur leur branche ou une nouvelle branche sur l'adresse du TI2 :

https://github.com/WebDevCF2m2025/TI2-2025

(Il ne faut pas accepter leurs `pull requests`)

Bon courage !


