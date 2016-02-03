---
layout: page
title: Teaser
permalink: /teaser/
---

## Teaser

Dans le but de vous préparer au CTF le 10 mars 2016, la Secu'RT publie [deux challenges de
sécurité](http://188.165.25.112:8000/) :

1. Un challenge web ([source disponible](http://188.165.25.112:8000/main.py))
    + Une faille s'est glissée dans le code python du serveur
    + Saurez-vous la trouver et l'exploiter ?
    + Pouvez-vous accéder au fichier linux *passwd* sur le serveur ?
2. Un challenge de rétro ingénierie ([programme ici](http://188.165.25.112:8000/securt.out))
    + Le programme tourne sous linux 32bit
    + Plusieurs solutions possibles
    + Une est suffisante pour valider l'épreuve
    + Vous gagnez quand le programme affiche *Congratulation!* (sans que vous l'ayez modifié à la main)

L'objectif est le même que pendant un CTF. Il vous faut trouver le *flag* (un mot de passe) qui prouve que
vous avez passé l'épreuve. Les deux challenges ont un *flag* qui suit le format **securt{...}**. Vous avez un doute ?
Envoyez votre solution à securt@univ-fcomte.fr et nous serons ravi de vérifier :)

Ci-dessous différentes ressources qui pourront peut être vous être utiles :

1. Challenge web
    + OWASP Top 10 : <https://www.owasp.org/index.php/Top_10_2013-Top_10>
    + Lycée Français d'Irlande : <https://en.wikipedia.org/wiki/LFI>
    + Burp Suite (proxy HTTP) : <https://portswigger.net/burp/download.html>
    + Documentation python 3 : <https://docs.python.org/3/library/http.server.html>
2. Challenge rétro ingénierie :
    + Instructions x86 : <https://en.wikipedia.org/wiki/X86_instruction_listings>
    + radare2 : <http://www.radare.org/r/>
    + Defeating ioli with radare2 : <https://dustri.org/b/defeating-ioli-with-radare2.html>
    + IDA version d'évaluation : <https://www.hex-rays.com/products/ida/support/download_demo.shtml>

Un doute ? Une question ? [Faites un tour sur IRC](http://webchat.freenode.net/?channels=hackgyver) ou envoyez un mail
à securt@univ-fcomte.fr :)
