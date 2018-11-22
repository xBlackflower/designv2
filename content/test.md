---
title: "Testsida"
views:
    kursrepo:
        region: sidebar-left
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-kursrepo

    redovisa:
        region: sidebar-right
        template: anax/v2/block/default
        data:
            meta:
                type: single
                route: block/om-redovisa
    byline:
        region: main
        template: anax/v2/block/default
        sort: 2
        data:
            meta:
                type: single
                route: block/byline
---
Testsida för att prova olika konstruktioner
=========================

Här ska jag testa att skriva lite.

_kursiv text skrivs med understreck eller asterisk runt_

__Vill man ha ett stycke eller ord med fet stil skriver man två understreck eller asterisker på båda sidor__

#rubrik 1
##rubrik 2
####rubrik 4
######rubrik 6

Rubrikerna skrivs med brädgård framför, lika många som typen av rubrik. Alltså en brädgård för nivå ett rubrik och två för nivå två osv.

Blockquote skapas med ett större än tecken framför raderna

>Här skriver jag något
>som är en blockquote

För att skapa numrerade listor

1. skriv en siffra med en punkt efter
2. så får du en numrerad lista

ska den vara onumrerad

* skriv med en asterisk framför
* eller plus eller minustecken

För att göra listor i listan drar man in andra listan med en tab eller fyra mellanslag

* ingredienser
    - mjölk
    - ägg
* recept
    1. pannkakor
    2. våfflor

Skriv med en tab

    Använder man tab eller fyra mellanslag så blir texten man skriver exakt som man skriver.
    Skriver man <em>HTML</em> eller *Markdown* så blir det det man skriver.

Man kan använda HTML taggar i markdowntext om man vill. Det finns tex vissa konstruktioner som man inte kan skriva i Markdown som superscript. Då kan man använda HTML taggar istället.

Be cautious about what you read on April 1<sup>st</sup>!
