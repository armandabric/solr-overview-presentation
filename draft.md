# Solr Overview Presentation

## Sommaire

## Moi

## Présentation générale

### Survol rapide

Serveur de recherche utilisant l'algorithme Lucene (= Basse de données
non relationnelle spécialisé dans la recherche de donnée textuelle, mais
pas que)

Développé par la fondation Apache

Ecrit en Java

Actuellement en version 4.6

### Lucene

Lucene est une librairie proposant les fonctionnalités d'un moteur de
recherche (indexation, stockage des données, analyse, recherche...).

Ecrit en Java

### Solr une surcouche de Lucene

### Solr (vs) SGBD traditionnels

### Présentation de l'interface d'admistration

Interface d'administration claire et moderne

Communication

API (presque) REST simple qui permet de (presque) tout faire.

Il existe des librairies (officielle ou non) dans de nombreux langages
pour prendre charge la communication avec Solr : PHP, Java, C, Ruby,
Python...

En particulier en PHP on a une extension PECL, des implémentations faire
par la communauté[^1], et même des bumdles[^2] Symphony 2

## Un SI avec Solr

Un moteur de recherche viens généralement en supplément de BDD
existantes (relationnelle, NoSQL, fichier...).

[schéma de présentation]

## Indexation

### Processus d'indexation

Soir on

Soit on la réalise manuellement (extraction des données d'une BDD,
transformation puis transmission à Solr)

Soit de manirère

 (en live ou en différé, manuellement ou aut).

-   Full indexation

-   indexation live

-   Indexation automatique

### Configuration du schéma.xml à l'indexation

## Introduction à la recherche

### Présentation de la synthaxe

### Survol des nombreux pramètres

### Survol des types de retours

### Debugging

## Recherche avancées

### Grouping

### Faceting

### Search revelancy

## Modules complémentaires

### Highlight

### SpellCheck

### Autocomplete / suggester

### Stats

## Allez plus loins

Liens

## Fin

C'est pas tout mais moi j'ai soif.

[^1]: Solarium - <http://www.solarium-project.org/>

[^2]: SolrBundle - <http://floriansemm.github.io/SolrBundle/>\
     NelmioSolariumBundle -
    <https://github.com/nelmio/NelmioSolariumBundle>
