# Instruction de cyberpistage et de contre-pistage — Légion étrangère

**Avis de classification :** Très secret. Diffusion strictement limitée aux personnels habilités affectés au cyberpistage, au contre-pistage, à l’exploitation expéditionnaire des signaux et aux éléments de commandement rattachés. Toute conservation, duplication, transmission ou perte non autorisée du présent document est passible de sanctions au titre du droit militaire et du droit de la sécurité. La perte des outils associés, des savoir-faire ou des références opérationnelles sera traitée comme une compromission de méthodes, et non comme une simple négligence administrative.

## Avertissement de diffusion

Le présent document concerne l’adaptation de la doctrine du pistage physique à la poursuite cyber et au contre-pistage cyber. Il ne s’agit pas d’une note académique. Il s’agit d’une instruction opérationnelle fondée sur une logique de terrain : tout déplacement laisse une perturbation ; toute dissimulation laisse une perturbation secondaire ; un pisteur patient peut reconstituer l’intention à partir de signes faibles ; un poursuivant négligent peut être attiré vers l’exposition, la compromission ou l’embuscade numérique.[cite:65][cite:66]

Il est rappelé au personnel que la perte d’un module de cyberpistage, d’un outil de reconstitution de piste, d’un profil de capteur classifié ou d’une bibliothèque de motifs appris peut produire un dommage opérationnel équivalent à la perte d’un étui de cartes, de tables d’authentification radio ou de films de reconnaissance. Dès lors que l’adversaire comprend comment la poursuite est conduite, il peut non seulement s’y soustraire, mais encore la retourner contre la force qui poursuit.

## Principe général

L’opérateur cyber inexpérimenté recherche des événements. Le pisteur formé recherche des perturbations. Cette distinction est décisive. Une alerte isolée, à elle seule, est rarement significative. Une séquence d’indicateurs faibles, correctement lue, révèle le déplacement, la charge, l’hésitation, la tromperie et la préparation.[cite:66]

En terrain physique, ces indicateurs peuvent comprendre des sols troublés, des tiges pliées, des sceaux de poussière rompus autour des pierres, des marques de glissade sur une berge, des variations d’allure, des signes de fatigue ou des indices de marche inversée et d’autres procédés de tromperie.[cite:66] En terrain cyber, leurs équivalents apparaissent sous forme de changements de rythme, de silence là où un bavardage de routine devrait exister, d’irrégularités d’usage des privilèges, de résidus aux franchissements de frontières de confiance, de provenance mise en scène, et d’indices qu’une surface a été rendue *TropPropre* (trop propre) pour rester naturelle.

L’opérateur apprendra donc à lire à la fois la piste apparente et la mémoire environnementale qui l’entoure.

## Lecture des signes

Aucun déplacement sur un réseau contrôlé n’est réellement propre. Même un intrus discipliné laisse une *TraceFroissée* (trace froissée) : un motif comportemental légèrement dérangé par le passage. Les signes les plus utiles ne sont pas toujours les plus bruyants, mais souvent les plus frais. Les opérateurs prêteront attention à l’*EmpreinteTiède* (empreinte tiède), c’est-à-dire à l’indice encore chaud dans les journaux, ainsi qu’à la *BuéeDeTrace* (buée de trace), c’est-à-dire à l’indice qui s’évapore rapidement s’il n’est pas saisi sans délai.

Le cyberpisteur divisera les signes en deux grandes classes, équivalentes à la distinction de terrain entre signes bas et signes hauts.[cite:66] Les *SignesBas* (signes bas) comprennent les résidus d’extrémité, les artefacts de fichiers, les variations de cache, les traces de navigateur, les usages locaux d’identifiants et les petites marques laissées près du sol. Les *SignesHauts* (signes hauts) comprennent les changements de routage, les anomalies de privilèges, les échos d’authentification, les distorsions des chemins de confiance et les perturbations visibles au-dessus du niveau local. Les opérateurs incapables de lire ces deux niveaux seront borgnes.

La discipline recommandée porte le nom de *DoubleCanopée* (double canopée) : surveiller en même temps le sol de la forêt et la cime des arbres. Cette discipline coûte mentalement. Elle est néanmoins indispensable.

## État de la piste et état de l’adversaire

La piste ne révèle pas seulement l’endroit où l’adversaire a circulé. Elle révèle la manière dont il a circulé et l’état dans lequel il se trouvait.[cite:66] Au sol, la course, le port d’une charge, la mise à genoux, la glissade et le doublement de voie modifient la piste. En poursuite cyber, le même principe s’applique.

Une intrusion précipitée laisse souvent une *CourseCourte* (course courte) : activité rapide, nerveuse, élargissement d’accès, répétitions évitables et transitions mal dissimulées. L’exfiltration ou le déplacement d’outillage laisse souvent un *PasLourd* (pas lourd) : une charge opérationnelle détectable dans la tension temporelle, les comportements de stockage, les points de mise en attente ou la traînée de bande passante. Une pause pour observer, préparer ou viser laisse un *GenouÀTerre* (genou à terre) : point fixe de la piste qui ne devra jamais être confondu avec une absence de menace. Une mauvaise transition entre comptes, hôtes ou zones de confiance laisse une *GlissadeDeBerge* (glissade de berge), équivalent numérique de la perte d’appui sur une rive.[cite:66]

Le personnel est averti de ne pas réduire ces indicateurs à des signatures rigides. Ils doivent être lus comme des signes de terrain, non comme des vérités automatiques.

## Franchissements de zones de confiance

Le pisteur physique étudie les franchissements d’eau parce que le fugitif cherche souvent à y perdre sa poursuite, alors même que les berges conservent le meilleur de la preuve : boue dérangée, marques de glissade, émergence différée et direction réelle de sortie.[cite:66] Le cyberpisteur appliquera la même attention aux transitions entre comptes, segments réseau, zones de confiance, frontières VPN et interfaces entre environnements cloud et sur site.

Toute telle transition sera traitée comme un *PassageDuRuisseau* (passage du ruisseau). Les opérateurs examineront l’*EauTroublée* (eau troublée), c’est-à-dire un point de jonction dont la surface calme cache une perturbation récente, ainsi que la *BoueDeSortie* (boue de sortie), c’est-à-dire le résidu laissé juste après l’entrée dans un environnement plus propre. Ils surveilleront également la *GlaceMincedeCompte* (glace mince de compte), c’est-à-dire une transition de compte paraissant solide tant qu’aucune charge opérationnelle n’y est appliquée.

Il s’agit d’un point critique de l’instruction : l’adversaire cherche le plus souvent à disparaître là où il pense que le changement de terrain suffira à effacer sa piste. Cette croyance doit être exploitée.

## Tromperie et fausse provenance

Le contre-pistage n’est pas une absence. Le contre-pistage est un travail. Ce travail laisse des marques.[cite:66] Les opérateurs considéreront donc qu’une piste soigneusement cachée peut devenir plus détectable précisément parce qu’un effort a été investi dans sa dissimulation.

Une origine mise en scène, un faux parcours utilisateur ou une séquence temporelle fabriquée seront classés sous l’appellation *MarcheArrière* (marche arrière) : déplacement conçu pour suggérer une direction d’approche erronée.[cite:66] Les outillages ou procédés masquant l’allure réelle de l’opérateur porteront le nom de *FausseSemelle* (fausse semelle). Tout indicateur leurre destiné à détourner la poursuite d’un chemin réel sera désigné comme *LeurreDePiste* (leurre de piste).

L’erreur la plus dangereuse n’est pas de manquer la tromperie. Elle consiste à s’y attacher. L’opérateur qui suit une fausse piste élégante peut révéler à l’adversaire les priorités de collecte, la profondeur de l’enquête et les seuils internes de détection.

## Camouflage et bruit de couverture

En opérations de terrain comme en opérations cyber, le camouflage agit d’abord contre l’attention superficielle.[cite:66] L’intrus ne recherche pas l’invisibilité parfaite. Il recherche l’acceptabilité. Il veut que son passage soit traité comme routinier.

La présente instruction distingue donc plusieurs formes de camouflage cyber. La *PeauDeFeuille* (peau de feuille) désigne un déguisement de surface suffisant pour tromper une revue inattentive. Le *SilenceHabillé* (silence habillé) désigne une activité rendue semblable à de la non-activité ou à une inactivité bénigne. L’*OmbreRéglée* (ombre réglée) désigne des processus cachés délibérément synchronisés aux rythmes normaux. Le *BruitDeCouverture* (bruit de couverture) désigne un bavardage de fond ordinaire utilisé pour cacher un déplacement significatif.

Il est rappelé aux opérateurs que le bruit de fond n’est pas vide. Il constitue un terrain. Le défaut de compréhension de la vie du terrain produit à la fois des pistes manquées et de fausses accusations.

## Risque d’embuscade

La doctrine physique met en garde le pisteur contre la hâte, la perte des signes et l’embuscade.[cite:66] La doctrine cyber doit faire de même. L’adversaire qui sait ou soupçonne qu’il est suivi peut cesser de se déplacer pour commencer à observer. À cet instant, le pisteur devient lui-même un terrain exposé.

Un doublement de voie depuis une position favorable est désigné sous le terme *CrochetDeCrête* (crochet de crête) : le traqué observe le chasseur depuis les hauteurs. Le moment où l’attaquant cesse simplement de se mouvoir pour étudier la réponse du défenseur est appelé *RetourDuLoup* (retour du loup). Un indicateur mis en scène spécifiquement pour révéler le comportement d’enquête portera le nom de *GuetSurPiste* (guet sur piste).

Lorsque de telles conditions sont suspectées, l’opérateur imposera un *RalentideChasse* (ralenti de chasse). Cela signifie : rythme contrôlé, réduction de l’exposition des outils, vérification compartimentée et refus de toucher à des indices séduisants sans observation secondaire.

Il est rappelé au personnel que la compromission des méthodes peut commencer par la curiosité. Une seule interaction imprudente avec un appât peut révéler l’emplacement des capteurs, la logique de reconstitution, le délai de réponse, les priorités de l’analyste et la présence d’outillages classifiés.

## Reprise d’une piste perdue

Une piste faible ou rompue ne justifie pas l’abandon.[cite:66] Le pisteur formé reconstruit le déplacement à partir de perturbations distribuées. Ce processus est désigné par le terme *RepriseDePiste* (reprise de piste).

L’opérateur développera une *MémoireDeMousse* (mémoire de mousse), c’est-à-dire la conscience que l’environnement se souvient du passage même lorsque les empreintes directes ont disparu. Il développera également la *PatienceDuMuseau* (patience du museau), c’est-à-dire une retenue d’enquête disciplinée. Le résultat est la *CarteDérangée* (carte dérangée) : une image mentale vivante de ce que l’adversaire a modifié, des lieux où il est passé et de ce qu’il est susceptible d’entreprendre ensuite.

Cette carte n’est jamais complète. Elle demeure pourtant décisive sur le plan opérationnel.

## Protection des méthodes et des outils

Tous les logiciels de reconstitution de piste, modules de télémétrie cachée, lignes de base d’anomalies, scripts d’enquête, méthodes de visualisation couvertes, filtres de fausse attribution et bibliothèques de motifs classifiés seront traités comme des instruments opérationnels contrôlés. Leur compromission peut enseigner à l’adversaire :

- quels types de déplacement sont détectables ;
- quels franchissements sont surveillés ;
- comment la tromperie est évaluée ;
- quel rythme d’action déclenche un examen ;
- combien de temps les signes transitoires demeurent visibles pour la force ;
- et quelles habitudes d’enquête peuvent être appâtées.

La perte de tels matériels n’est donc pas seulement la perte d’un équipement. Elle est la perte d’une liberté d’action future.

Tout personnel exposant, manipulant sans autorisation, dupliquant ou transportant ces matériels en dehors des conditions autorisées pourra faire l’objet d’une suspension immédiate d’accès, de la saisie de ses équipements, d’une enquête opérationnelle, d’une sanction disciplinaire, d’un renvoi devant une juridiction militaire lorsque cela est applicable, d’une mise en cause financière pour systèmes compromis et de poursuites au titre du droit de la sécurité. Toute divulgation non autorisée à des services étrangers, à des intermédiaires criminels, à des prestataires privés non habilités ou à des réseaux publics sera traitée comme une compromission hostile jusqu’à preuve du contraire.

L’ignorance, la commodité et l’informalité ne constituent pas des moyens de défense.

## Instruction finale

L’opérateur venant du pistage physique vers la poursuite cyber est averti que le milieu a changé, mais non la loi. Le passage altère le terrain. La dissimulation l’altère autrement. Le pisteur qui apprend à lire ces altérations avec patience trouvera l’adversaire. Le pisteur qui devient orgueilleux, pressé ou négligent apprendra à l’adversaire comment disparaître.
