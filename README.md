# Big Data Api
== Contexte
- API Rest pour exposer aux clients les données big data et faire du reporting ou calcul sur les données
- Cette API est codée en Java 8 pour exploiter un maximum les Stream java
- Cette API est branchée à une base de donnée distribuée Apache Hadoop
- Cette API sera utilisée par différentes applications clientes interne à l'entreprise
- Cette API est basée sur une architecture REST

== Transformer l'architecture actuelle de l'Api en micro services
- Analyser les fonctionnalités de l'API et définir les micro services
- Developper et tester les micro services


== Intégration continue
- Créer des jobs jenkins pour builder automatiquement les micro services
- Builder les TU
- Builder les TI régulièrement( daily/nightly build)

== Docker & Ansible
- Definir les différents containers
- Mettre en place un playbook ansible pour deployer l'API sur ces containers
- gerer la montée de version des micro services
- permettre d'avoir 2 versions en parallele d'un meme micro service !!!

 
== Monitoring
- Utiliser Kibana pour:
 1. Identifier les micro services qui sont down et générer des alertes
 2. Remonter sous forme de graphique les "access log" pour identifier les services les plus utilisés


