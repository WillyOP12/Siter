# Siter

**Siter** és una petita eina web que genera i obre enllaços de Google Sites a partir del nom, el primer cognom i l'any de naixement d'una persona.

## Característiques

* Formulari senzill i ràpid.
* Generació automàtica de la URL.
* Normalització de caràcters especials:

  * `ç` → `c`
  * `ñ` → `n`
  * elimina accents i espais
* Obre el resultat en una pestanya nova.
* Mostra un enllaç alternatiu per provar sense l'any.
* Disseny fosc amb estil terminal i icona favicon.

## Funcionament

La URL es construeix amb aquesta estructura:

```text
https://sites.google.com/inslasagrera.cat/[primera lletra del nom][primer cognom][dos últims dígits de l'any]
```

Si no funciona, el sistema mostra també l'opció de provar la versió sense l'any:

```text
https://sites.google.com/inslasagrera.cat/[primera lletra del nom][primer cognom]
```

## Ús

1. Obre el fitxer `index.html` al navegador.
2. Introdueix el nom, el primer cognom i l'any de naixement.
3. Fes clic a **Enviar**.
4. S'obrirà el site generat en una pestanya nova.

## Estructura del projecte

```text
Siter/
├── index.html
├── favicon.svg (o favicon inclòs com a data URI dins l'HTML)
└── README.md
```

## Personalització

Pots modificar fàcilment:

* el color verd principal,
* el text del peu de pàgina,
* el domini base de Google Sites,
* el disseny visual,
* el favicon.

## Llicència

Aquest projecte està publicat sota la llicència **Apache 2.0**.

## Crèdits

Creat per al context de l'Institut La Sagrera — Sant Andreu per Guillem Ortiz
