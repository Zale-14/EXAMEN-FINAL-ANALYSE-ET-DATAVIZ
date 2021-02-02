## Bienvenue dans ma page de visualisations de données liées au covid-19 en France
Nous avons téléchargé notre jeu de données sur data.gouv.fr dont le thème principal repose sur la pandémie covid-19 en France. Notre jeu de données comporte des données hospitalières liées à la pandémie covid-19 dans la région d’Auvergne-Rhône-Alpes précisément dans le département d’Isère. Nous avons ouvert le document mais nous avons constaté que sur les données sexe, il y a une erreur ou incohérence car ils ont listé des données par genre c’est-à-dire pour les hommes et pour les femmes mais ils ont listé aussi une donnée appelée Tous dans la colonne Sexe. Dans la donnée Tous on ne peut pas savoir si ce sont des données qui réunies les hommes et les femmes, ou qui les réunit par tranche d’âge. Du coup nous avons importé notre jeu de données sur OpenRefine afin de faire des modifications (filtrer, supprimer, déplacer etc.) qui nous permettraient d’avoir des visualisations qui correspondent à nos attentes. 
### Visualisation de données n° 1 avec datawrapper
cette visualisation ci-dessous est une représentation des données hospitalières liées à la pandémie Covid-19 dans la région Auvergne-Rhône-Alpes. Pour les besoins de cette visualisation nous avons filtré les données sur openRefine afin d'avoir le nombre toatl d'hommes et de femmes décés du covid-19, admis en France 
L'analyse qu'on peut faire à partir de cette visualisation est que la région Auvergne-Rhône-Alpes fait partie des régions les plus touchées par la pandémie covid-19 en France. Cette progression fulgurante dans cette région peut être dûe au non respect des distanciations physiques et à la réglementation en vigeur.
<iframe title="[ Diagramme à plusieurs tartes ]" aria-label="chart" id="datawrapper-chart-Mhp7j" src="https://datawrapper.dwcdn.net/Mhp7j/1/" scrolling="no" frameborder="0" style="width: 0; min-width: 100% !important; border: none;" height="479"></iframe><script type="text/javascript">!function(){"use strict";window.addEventListener("message",(function(a){if(void 0!==a.data["datawrapper-height"])for(var e in a.data["datawrapper-height"]){var t=document.getElementById("datawrapper-chart-"+e)||document.querySelector("iframe[src*='"+e+"']");t&&(t.style.height=a.data["datawrapper-height"][e]+"px")}}))}();
</script>
#### Visualisation de données n°2 avec datawrapper
Pour les besoins de cette représentation, nous avons filtré notre jeu de données sur openRefine afin d’avoir des données sur les hommes uniquements par rapports aux nombres d’hospitalisations par jour, de sortie, de décés et d’admis en soins intensifs. Ainsi l’analyse qu’on peut faire de cette visualisation de données est la suivante: On voit au mois d’avril jusqu’au mois de mai que les courbes du nombre de décés, de soins intensifs et jour_hospitalisation sont en nette progression que même que la courbe sortie. Cette ascenssion des courbes s’explique pr le fait que ça coîncidait à la première vague de l’épidémie (ou pic épidémique) coronavirus en France. Ensuite on voit qu’à partir du mois de juin jusqu’au mois de septembre que les courbes(décés, jour_hospitalisation, soins intensifs) sont en regression. Cela s’explique par l’effet du confinement qui a permis de réduire considérablement l’avancée de l’épidémie et de ses inconvénients. De même la courbe sortie s’est stabilisée car le confinement a réduit les admissions dans les hôpitaux. A partir du mois d’octobre et novembre, toutes les courbes connaissent une ascenssion fulgurante et cela s’explique par une deuxiéme vague de contamination liée à la pandémie covid-19. Elles regressent après petit à petit sous l’effet du couvre-feu et du second confinement. Enfin, au mois de décembre et janvier 2021 on note une stabilisation des courbes du nombre d’admis en soins intensifs et d’hospitalisation par jour contraitement aux courbes du nombre de décés et de sortie qui connaissent une montée.
<iframe title="[ courbes sur les données hommes ]" aria-label="Interactive line chart" id="datawrapper-chart-LoKZM" src="https://datawrapper.dwcdn.net/LoKZM/1/" scrolling="no" frameborder="0" style="border: none;" width="600" height="400"></iframe>
##### Visualisation de données avec n°3 avec datawrapper
Pour les besoins de cette représentation, nous avons filtré notre jeu de données sur openRefine afin d’avoir des données sur les femmes uniquements par rapports aux nombres d’hospitalisations par jour, de sortie, de décés et d’admis en soins intensifs. Ainsi l’analyse qu’on peut faire de cette visualisation de données est une analyse comparative entre les données des hommes et des femmes par rapport au covid-19. Ainsi d'aprés ce graphique ci-dessous on note que le coranivrus a fait plus de victimes chez les hommes que chez les femmes. Cela peut être dû à plusieurs facteurs dont le surpoids chez les hommes, la cigarette et d'autres pathologies mais scientifiquement il n'y a pas encore de réponses pertinentes sur la question. 
<iframe title="[ Graphique de zone  ]" aria-label="Interactive area chart" id="datawrapper-chart-fgWtY" src="https://datawrapper.dwcdn.net/fgWtY/1/" scrolling="no" frameborder="0" style="border: none;" width="320" height="433"></iframe>



Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Zale-14/essai/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
