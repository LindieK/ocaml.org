<!-- ((! set title Contributeurs !)) -->

Contributeurs
=============

Les contributeurs à ce site :
<ul>
((! cmd git log --format="%aN" | sort -k 2 | uniq | sed -e "/^[^ ]*$/ d" -e "s|\(.*\)|<li>\1</li>|" !))
</ul>

Cette liste est obtenue depuis le log GIT, pensez à vérifier que votre
nom y est bien configuré.

Anciens contributeurs aux tutoriels
-----------------------------------

Beaucoup des tutoriaux de ce site étaient à l'origine sur `cocan.org`.
Voici la liste de ceux qui y ont contribué :

* Doug Bagley
* Nicolas Cannasse
* Eric C. Cooper
* Richard Donkin
* Jim Farrand
* Fabrice Le Fessant
* Jacques Garrigue
* Stephen Gilmore
* Flavio Grossi
* Damien Guichard
* Brian Hurt
* Neel Krishnaswami
* Michel Levy
* Sven Luther
* John Gerard Malecki
* Luc Maranget
* Jean-Francois Monin
* Markus Mottl
* Thomas Mraz
* Wolfgang Mueller
* Lars Nilsson
* Jose Manuel Nunes
* Frederic van der Plancke
* Paul Steckler
* Fabian Sturm
* Ryan Tarpine
* Remi Vanicat
* Yamagata Yoriyuki
* Stefano Zacchiroli
