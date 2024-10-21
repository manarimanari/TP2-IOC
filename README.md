# TP2-IOC
Explication des Concepts
1.	Inversion de Contrôle (IoC) : C'est un principe de conception où le contrôle de l'objet est inversé, signifiant que l'objet ne crée pas ses dépendances lui-même, mais celles-ci lui sont fournies par un conteneur (ici, Spring).
2.	Injection de Dépendances (DI) : Une technique où les dépendances d'un objet sont fournies par le conteneur IoC, permettant une séparation des préoccupations et facilitant les tests unitaires.
3.	Annotations Spring :
o	@Component : Marque une classe comme un bean Spring.
o	@Autowired : Indique que Spring doit injecter une dépendance.
4.	ApplicationContext : C'est le conteneur de Spring qui gère les beans et leurs cycles de vie. Dans cet exercice, AnnotationConfigApplicationContext est utilisé pour charger la configuration à partir des annotations.
Conclusion
Ce TP démontre comment utiliser Spring pour gérer l'inversion de contrôle et l'injection de dépendances, ce qui rend le code plus flexible, testable et maintenable. Les concepts d'IoC et de DI sont fondamentaux dans le développement moderne d'applications Java, permettant de construire des architectures robustes et modulaires.
projet maven
Résumé du TP 2 : Implémentation de l'Inversion de Contrôle et Injection des Dépendances avec Spring
Ce TP a pour but de créer une application Java utilisant le framework Spring pour mettre en œuvre l'inversion de contrôle (IoC) et l'injection de dépendances (DI) à l'aide d'annotations. L'application inclut une interface DAO, une interface métier, et gère l'injection de dépendances entre elles, permettant de démontrer les avantages de Spring dans la gestion des dépendances.
