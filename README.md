# IOT

                                                        Présentation du projet 


Avant d’introduire le sujet, nous allons tout d’abord présenter l’équipe.
Notre chef de projet : Benjamin Doucet également en charge du travail sur Arduino ; Guillaume Hecht en charge de Arduino et GitHub ; Romain Girard en charge du travail sur Orange Pi et du rapport ; et enfin Damien Girard était helper et nous aidais lorsque qu’une personne du groupe lorsque cette dernière était en difficulté, il a également travaillé sur l’Orange Pi.
Maintenant que nous nous sommes présentés, nous allons pouvoir vous exposer notre projet.
Le but final de ce projet est de relier un capteur de température à un Arduino, elle-même reliée à une Orange PI avec un Debian installé dessus. Le capteur doit capter la chaleur et renvoyer les données à l’Orange Pi, car, contrairement à l’Arduino, cette dernière à internet (l’Orange Pi nous sert de routeur internet)

                                                        Matériel et déroulement 
                                                        
                                                        
Nous disposons d’une Orange Pi, d’un Arduino et leurs câbles respectifs. Nous disposons également d’un capteur de température. 
Tout d’abord, nous avons installé Debian sur la carte micro SD qu’on a mis dans l’orange PI. Pendant ce temps, Guillaume et Benjamin s’occupaient de faire le programme pour que le capteur de chaleur renvoie les données à l’Arduino qui s’affiche sur le terminal de l’ordinateur.
Après ça, Damien et Romain cherchais à faire fonctionner l’orange PI et ainsi lancer le Debian jessy. Pendant ce temps, Guillaume et Benjamin créaient un code en Java pour récupérer les données de l’Arduino, au cas où la connexion à l’orange PI ne fonctionnait pas.

                                                Problèmes rencontrés et solutions apportées
                                                
                                                
Le problème majeur que nous avons rencontré sont les drivers pour connecter l’Orange PI à nos pc, ce qui a fait que nous n’avons pas pu accéder à l’orange PI (code erreur 10). Pour pallier ce problème, nous avons tout d’abord penser à installer un dual boot linux sur l’un de nos pc en pensant que le problème venait de Windows. Sauf que le problème du dual boot a été le temps d’installation trop long pour pouvoir optimiser notre temps de travail.

                                                              Conclusion 


Pour terminer, nous avons décider de remplacer l’orange PI par un programme JAVA sur l’ordinateur étant donné les difficultés rencontrés. 

                                                                Annexe
                                                                
                                                                
Nous avons pris en photo notre Arduino, et nous avons mis quelques explications pour les câbles. 
![alt text](https://github.com/Atrany/IOT/blob/master/schema_explicatif.jpg)
