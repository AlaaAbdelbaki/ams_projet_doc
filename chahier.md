<div class="titlepage">

</div>
<h1 id="introduction">Introduction</h1>
<h2 id="contexte">Contexte</h2>
<p>Le projet <strong>"Factory de mots de passes"</strong> s’inscrit dans
le contexte de l’apprentissage automatique pour la génération des mots
de passes. Il consiste à développer une application qui implémente un
réseau de neurones avec des options permettant d’entraîner le modèle
sur des données d’entrée et l’évaluer en générant des nouvelles
séquences à partir de quelques caractères de départ entrés par
l’utilisateur.<br />
Cette solution permet ainsi de générer automatiquement des mots de
passes qui respectent les conventions d’une entreprise ou d’un domaine
spécifique.</p>
<h2 id="objectifs-du-projet">Objectifs du projet</h2>
<p>Ce projet a les objectifs suivants à atteindre:</p>
<ul>
<li><p>Développer un modèle intelligent en utilisant la bibliothèque
PyTorch <span class="citation" data-cites="pytorch"></span> de Python
<span class="citation" data-cites="python"></span>.</p></li>
<li><p>Développer des fonctions d’entrainement et d’évaluation pour le
modèle.</p></li>
<li><p>Préparer un corpus d’entrainement contenant des mots de passes
respectant une convention.</p></li>
<li><p>Développer une solution logicielle pour mieux utiliser la
solution intelligente.</p></li>
</ul>
<h2 id="portée">Portée</h2>
<p>Cette application sera destinée pour un grand public qui veut générer
des mots de passes facile à mémoriser en entrant un mot clé.</p>
<h1 id="périmètre-du-projet">Périmètre du projet</h1>
<h2 id="fonctionnalités-attendues">Fonctionnalités attendues</h2>
<p>La solution proposée doit être capable de fournir plusieurs
fonctionnalités aux utilisateurs tels que:</p>
<ul>
<li><p>Temps d’entrainement minimal.</p></li>
<li><p>Générer des mots de passes selon des critères bien
déterminés.</p></li>
<li><p>Modifier les données d’apprentissage pour mettre à jour les
politiques de génération des mots de passes si nécessaire.</p></li>
<li><p>Utilisation simple et non complexe à l’aide d’une interface
graphique facile à utiliser.</p></li>
</ul>
<h2 id="technologies-utilisées">Technologies utilisées</h2>
<p>Afin de pouvoir élaborer ce projet, on a eu recours aux différents
languages de programmation, frameworks et outils techniques tels
que:</p>
<ul>
<li><p><strong>Python:</strong> Pour le développement du réseau de
neurones et d’un serveur qui permettra la communication entre une
application et/ou un site web avec le modèle entrainé.</p></li>
<li><p><strong>Flutter:</strong> Pour le développement d’une application
mobile/web qui sera utilisée par l’utilisateur pour utiliser le modèle
de génération de mots de passes.</p></li>
</ul>
<h1 id="public-cible">Public cible</h1>
<h2 id="profil-des-utilisateurs">Profil des utilisateurs</h2>
<p>La solution est destinée à:</p>
<ul>
<li><p>Administrateurs système au sein d’une entreprise.</p></li>
<li><p>Utilisateurs d’applications nécessitant une création de
compte.</p></li>
<li><p>Personnes ayant des compétences faibres à moyennes en
informatique.</p></li>
</ul>
<h2 id="nombre-de-personnes-pour-les-tests">Nombre de personnes pour les
tests</h2>
<ul>
<li><p><strong>Phase 1:</strong> 10 utilisateurs (Phase
exploratoire)</p></li>
<li><p><strong>Phase 2:</strong> 50 utilisateurs (Test grandeur
nature)</p></li>
</ul>
<h1 id="scénario-des-tests-utilisateurs">Scénario des tests
utilisateurs</h1>
<h2 id="objectifs-des-tests-utilisateurs">Objectifs des tests
utilisateurs</h2>
<ul>
<li><p>Identifier les défaillances du système.</p></li>
<li><p>Tester le temps d’apprentissage et d’exécution.</p></li>
<li><p>Tester la robustesse des mots de passes générés.</p></li>
<li><p>Corriger le problèmes identifiés.</p></li>
<li><p>Améliorer le paramètres d’apprentissage pour améliorer le temps
d’entrainement.</p></li>
</ul>
<h2 id="méthodologie-des-tests">Méthodologie des tests</h2>
<ul>
<li><p>Test avec un corpus de mots de passes différent du corpus
d’entrainement.</p></li>
<li><p>Tester avec une partie du corpus d’entrainement qui est dédiée au
test.</p></li>
</ul>
<h2 id="scénarios-de-tests">Scénarios de tests</h2>
<ul>
<li><p>Entrainer le modèle avec un corpus de mots de passes de taille
importante dont chaque mot de passe valide des conditions
prédéfinies.</p></li>
<li><p>Modification des hyper paramètres du réseau de neuronne
d’entrainement et comparer le résultat les autres qui utilisent des
paramètres différents.</p></li>
</ul>
<h1 id="critères-dévaluation-et-de-réussite">Critères d’évaluation et de
réussite</h1>
<h2 id="indicateurs-de-performance---kpi">Indicateurs de performance -
KPI</h2>
<p>Identifier les KPIs à suivre pour mesurer la réussite des
tests.<br />
<strong>Exemple:</strong></p>
<ul>
<li><p>Taux de confiance important lors de l’entrainement (&gt;
90%)</p></li>
<li><p>Test avec un corpus de test similaire au corpus d’entrainement et
calculer le tax de réussite de prédiction des mots de passes.</p></li>
<li><p>Temps nécessaire pour prédire un mot de passe.</p></li>
</ul>
<h1 id="contraintes-et-risques">Contraintes et risques</h1>
<h2 id="contraintes-techniques">Contraintes techniques</h2>
<ul>
<li><p>Temps d’entrainement important lié à la taille de corpus
d’entrainement.</p></li>
<li><p>Trouver un corpus d’entrainement qui couvre plusieurs exigences
des mots de passes.</p></li>
</ul>
