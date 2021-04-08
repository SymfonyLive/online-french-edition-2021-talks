# [SymfonyLive Online French Edition 2021](https://live.symfony.com/2021-france/) talks

- All talks are in **french**.
- You can send feedback and love to speakers on their twitter account

## Boring is the new hype

<dl>
  <dt>Description</dt>
  <dd>You are not Google, are you? 99.9% of applications will never have the problems top websites face. So, why are we using the same strategies?

This controversial session will talk about taking informed decisions when starting a project from a technical, economical, and ecological point of views. These decisions will greatly influence the maintenance of an application as well. When the project is finally stable and switch to a more quiet pace of fixes and small features, you will thank me for choosing boring technologies. I will share how I maintain my small and not so small projects. From a good dependency upgrade strategy to cron, backup, and error monitoring, there is a lot to talk about.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## Une sérialisation adaptée avec API Platform et Symfony

<dl>
  <dt>Description</dt>
  <dd>API Platform, le fameux framework REST/GraphQL basé sur Symfony, est construit autour du processus de sérialisation/déserialisation, c'est-à-dire du processus de représentation d'un objet dans un format pouvant être persisté et inversement.

Une très forte dépendance existe ainsi entre API Platform et le composant Serializer de Symfony qui nous proposent à eux deux de multiples solutions techniques concernant la sérialisation d'un objet.

Groups, ContextBuilders, Serializers, DataTransformers, DTOs, Access controls, [...]. Tant d'outils disponibles répondant chacun à des besoins spécifiques. Certains moins complexes, d'autres plus puissants. Mais comment choisir la solution technique adaptée à son besoin ?

Durant ce talk, nous aborderons certaines de ces solutions et nous pencherons sur les besoins auxquels elles tentent de répondre afin d'utiliser ces solutions à bon escient.

Nous pourrons aussi constater qu'API Platform continue à améliorer ce processus de sérialisation avec notamment quelques fonctionnalités très intéressantes sorties dans sa version 2.6</dd>
</dl>

~~Slides~~  
~~Video~~

By [Mathias Arlaud](https://connect.symfony.com/profile/mtarld)  
![github](icon/github.png) [@mtarld](https://github.com/mtarld)  
![twitter](icon/twitter.png) [@matarld](https://twitter.com/matarld)

---

## Bref, j'ai fait du Serverless en PHP

<dl>
  <dt>Description</dt>
  <dd>Il y a 1 an, je découvrais le Serverless, et j'étais vite perdue : s'agit-t-il du paradigme, du framework, ou encore d'un documentaire dernier cri sur Netflix ?

À la fin de la présentation, ce terme n'aura plus de secrets pour vous : vous saurez à quel moment et pourquoi il est pertinent de déployer ses applications en serverless.

Vous découvrirez également comment déployer une application PHP/Symfony de cette manière, en passant par GCP, AWS et la librairie Bref.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Marie Minasyan](https://connect.symfony.com/profile/marie.minassyan)  
![github](icon/github.png) [@MarieMinasyan](https://github.com/MarieMinasyan)  
![twitter](icon/twitter.png) [@MarieMinasyan](https://twitter.com/MarieMinasyan)

---

## Comment éviter les écueils les plus classiques en équipe Agile ?

<dl>
  <dt>Description</dt>
  <dd>Une équipe, Agile ou non, est amenée à rencontrer des difficultés qui peuvent nuire à son harmonie et en conséquence à son efficacité.
Je vous propose donc d'identifier les conflits les plus fréquents, d'en analyser les facteurs humains et techniques puis de vous proposer des solutions concrètes.
À la fin de cette présentation, vous saurez sur quels outils vous reposer, et comment créer et partager une vision commune avec votre équipe.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Marianne Joseph-Gehannin](https://connect.symfony.com/profile/marianne)

---

## Comment nous avons tiré parti de symfony/http-client pour construire un nouveau SDK AWS

<dl>
  <dt>Description</dt>
  <dd>AWS fournit un excellent SDK PHP : stable, complet et bien maintenu. Mais il présente des inconvénients tels que son poids, son nombre important de dépendances et une mauvaise "Developer eXperience" (DX).

Nous avons créé async-aws pour fournir un SDK alternatif qui comble ces lacunes avec le même niveau de qualité.

Lors de ce talk, je vais vous montrer comment nous utilisons le client HTTP de Symfony et comment nous tirons parti de son comportement "asynchrone par défaut" pour améliorer la DX et permettre à l'utilisateur de passer du mode séquentiel au mode asynchrone complet sans effort ni douleur.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Jérémy Derussé](https://connect.symfony.com/profile/jderusse)  
![github](icon/github.png) [@jderusse](https://github.com/jderusse)  
![twitter](icon/twitter.png) [@jderusse](https://twitter.com/jderusse)

---

## Pied au plancher avec Symfony Turbo

<dl>
  <dt>Description</dt>
  <dd>Hotwire Turbo est une petite bibliothèque qu'a récemment publié DHH, le créateur de Ruby On Rails. Turbo permet de créer des sites web dont l'expérience utilisateur est similaire à celle des Single Page Apps, mais sans avoir à écrire de JavaScript !

Dans le cadre de l'initiative Symfony UX, j'ai créé une intégration officielle de Turbo avec Symfony. Grâce à Symfony Turbo, vous allez pouvoir vous débarrasser de JavaScript et profiter à nouveau à 100% de Twig, sans concession au niveau des performances ni de l'expérience utilisateur.

Au cours de cette conférence, nous découvrirons comment la bibliothèque fonctionne, comment l'utiliser pour améliorer vos templates Twig existants, comment "streamer" en temps réel des changements d'états grâce à l'intégration avec Mercure et comment tester tout ça avec Symfony Panther.</dd>
</dl>

~~Slides~~  
~~Video~~  

By [Kévin Dunglas](https://connect.symfony.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)

---

## Deep dive into the form component

<dl>
  <dt>Description</dt>
  <dd>Démystifions le composant Form !

Le composant Form n'est pas forcément le composant le plus simple de Symfony. Notamment à cause de son grand nombre de FormType ayant chacun leur spécificités mais aussi par rapport à la "magie" qui semble à première vue se dérouler en interne. En regardant le composant d'un peu plus près, nous verrons que la magie n'est pas le moteur mais plutôt un fonctionnement cohérent avec des objets qui travaillent parfaitement ensemble.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Laurent Voullemier](https://connect.symfony.com/profile/lvo)  
![github](icon/github.png) [@l-vo](https://github.com/l-vo)  
![twitter](icon/twitter.png) [@lvodev](https://twitter.com/lvodev)

---

## De meilleurs identifiants grâce au composant Symfony UID

<dl>
  <dt>Description</dt>
  <dd>Les identifiants, qu'ils soient techniques ou fonctionnels, sont essentiels car ils permettent d'immatriculer les différentes ressources que nous manipulons au sein de nos projets. Ils peuvent être représentés sous différentes formes : nombres entiers, chaînes de caractères, UUID, etc. Quel est le format le plus compréhensible ? Quel est le plus performant ? Au cours de cette conférence, je vous propose d'échanger sur ce thème passionnant, notamment en (re)découvrant le composant Symfony UID. À travers un retour d'expérience, j'aborderai également le sujet de la rétrocompatibilité dans le cadre de la migration d'identifiants existants.</dd>
</dl>

~~Slides~~   
~~Video~~

By [Thomas Calvet](https://connect.symfony.com/profile/fancyweb)  
![github](icon/github.png) [@fancyweb](https://github.com/fancyweb)  
![twitter](icon/twitter.png) [@fancyweb_](https://twitter.com/fancyweb_)

---

## Des trésors cachés dans Symfony

<dl>
  <dt>Description</dt>
  <dd>Symfony est un ensemble de composants riche en fonctionnalités. Lorsqu'ils sont utilisés ensemble sous forme de framework, leurs capacités ne s'additionnent pas seulement, elles se combinent ! Avec l'autowiring, l'auto-configuration et l'auto-découverte, il n'a jamais été aussi facile de coder avec efficacité, Symfony se chargeant de la plupart des étapes de démarrage et de branchement.

Si vous suivez de près les articles "Living on the Edge" sur symfony.com, ou si vous lisez attentivement la documentation, vous connaissez peut-être déjà certains trésors de Symfony. Mais tous ne font pas l'object d'une publication ni de documentation (pour l'instant).

Dans cette conférence, j'aimerais vous présenter quelques trésors que vous pourrez trouver dans les applications Symfony, n'attendant que vous pour être exploités. Je vous donnerai également un aperçu de ce qui se prépare en Symfony 5.3. La communauté trouve toujours des moyens d'améliorer l'état de l'art !</dd>
</dl>

~~Slides~~  
~~Video~~

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

---

## Cypress, le E2E moderne doit encore apprendre du passé

<dl>
  <dt>Description</dt>
  <dd>Dans ce talk, nous aborderons Cypress, un outil dédié aux tests E2E et qui gagne rapidement en notoriété (de grosses entreprises tel que Paypal, Disney, Github, Slack et bien d'autres l'utilisent au quotidien).  
Le premier objectif sera la comparaison face aux “concurrents” actuels et notamment Behat (avec le couple Mink/Selenium), un outil bien connu des développeurs(euses) PHP.

De par son adoption rapide, Cypress peut être amené à croiser des difficultés et tout n’est pas parfait du premier coup, c’est pourquoi nous verrons les pièges à éviter et ce que nous pouvons apprendre de ces "ancêtres", nous verrons aussi ses points positifs/négatifs et comment l'utiliser au quotidien afin de ne pas reproduire les erreurs du passé.

Nous verrons aussi comment l'intégrer dans une application Symfony et comment le rendre facile à prendre en main, évolutif et facile à maintenir.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Guillaume Loulier](https://connect.symfony.com/profile/guikingone)  
![github](icon/github.png) [@Guikingone](https://github.com/Guikingone)  
![twitter](icon/twitter.png) [@Guikingone](https://twitter.com/Guikingone)

---

## Démarrer avec Symfony UX

<dl>
  <dt>Description</dt>
  <dd>Symfony UX est une initiative et un groupe de librairies ayant pour objectif d'intégrer l'écosystème JavaScript dans vos applications. Des graphiques aux zones de drag and drop, Symfony UX fournit différents outils rapidement réutilisables dans vos projets, avec très peu de code. Découvrons ensemble son fonctionnement et son composant principal : Stimulus.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Titouan Galopin](https://connect.symfony.com/profile/tgalopin)  
![github](icon/github.png) [@tgalopin](https://github.com/tgalopin)  
![twitter](icon/twitter.png) [@titouangalopin](https://twitter.com/titouangalopin)

---

## The New Testing Landscape: Panther, Foundry & More

<dl>
  <dt>Description</dt>
  <dd>Symfony comes with a number of tools for testing, like BrowserKit & DomCrawler as well as test classes for booting the kernel, accessing services, and using a bunch of built-in assertions.

But what do you do if you need to test the JavaScript on your page? And what's the best approach for setting up your database? Should you load fixtures? Clear the data before each test? And how can I run my tests in parallel?

In this talk, we'll explore a set of new tools & clear patterns (Arrange, Act, Assert) for test…</dd>
</dl>

~~Slides~~  
~~Video~~

By [Ryan Weaver](https://connect.symfony.com/profile/weaverryan)  
![github](icon/github.png) [@weaverryan](https://github.com/weaverryan)  
![twitter](icon/twitter.png) [@weaverryan](https://twitter.com/weaverryan)
