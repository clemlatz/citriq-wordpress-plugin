=== Citriq.net ===
Contributors: clementbourgoin
Tags: books, reviews, links
Donate link: http://nokto.net/
Requires at least: 3.8
Tested up to: 3.8.1
Stable tag: 1.0.1
License: GPL v2 or later
License URI: http://www.gnu.org/licenses/old-licenses/gpl-2.0.html

Référencez automatiquement vos critiques littéraires sur Citriq.net

== Description ==
Qu'est-ce que Citriq.net ?

Citriq.net est un moteur de recherche et d'échange de critiques littéraires. Grace à un petit code JavaScript à ajouter à votre site, Citriq va automatiquement afficher des liens depuis chacune de vos critiques vers les critiques du mêmes livres sur tous les autres sites participants. Si une nouvelle critique d'un livre que vous avez déjà critiqué est posté ailleurs sur le web, inutile de mettre votre article à jour, les liens seront automatiquement ajoutés à votre article, et le nouvel article proposera automatiquement un lien vers le votre.

Pour utiliser Citriq, il faut normalement entrer chaque critique manuellement sur Citriq.net puis ajouter à votre article le petit code JavaScript qui vous est retourné. Grace à cette extension Wordpress, ce n'est plus nécessaire : le code JavaScript sera généré automatiquement à partir de l'ISBN du livre critiqué.

Pourquoi utiliser Citriq ?

Les lecteurs se content rarement d'un seul avis et cherchent souvent à lire plusieurs critiques d'un livre dont ils envisagent l'achat. Certains sites proposent ainsi des revues de presse qui nécessite un suivi au fil du temps. Citriq vous permet de générer automatiquement une liste de liens vers des critiques d'un même livre, qui se met à jour des qu'une nouvelle critique est proposée sur un autre site.

À quoi sert le code JavaScript ?

Une fois activée, l'extension va générer pour chacune de vos critiques un code JavaScript. Ce code va envoyer à Citriq.net les informations suivantes :
 - L'adresse de la page d'où est appelée le code JavaScript (c'est à dire l'adresse de votre critique)
 - L'ISBN du livre critiqué

Grace à ces informations, Citriq.net pourra générer des liens vers votre critique sur son site et sur tous les autres sites proposant une critique du même livre (correspondant au même ISBN).
En retour, Citriq retournera une liste de liens vers des critiques du même livre sur d'autres sites que le code JavaScript affichera sur votre site, à la fin de votre article. 

== Installation ==
Une fois l'extension installée, utilisez les champs personnalisés suivant pour faire référencer vos articles dans Citriq :
- isbn (obligatoire) : le code IBSN du livre critiqué ;
- excerpt : un extrait de la critique (jusqu’à 500 caractères) ;
- reviewer : l’auteur de la critique (sinon, l'auteur de l'article Wordpress sera utilisé) ;
- source : support dont est issue la critique (si différent du site) ;
- rating : permet d’indiquer une note (un entier, sur 100).

== Frequently Asked Questions ==
Pour toute question, contactez Clément Bourgoin : http://nokto.net/contact

== Changelog ==
1.0.1 (10/02/2014)
 - Suppression de la mise à jour automatique
 - Mise à jour de readme.txt
1.0 (08/02/2014)
 - Première version de l'extension