# HIKLIMATE

## Tema i motivació
He escollit realitzar la pàgina web sobre el projecte que vam iniciar durant el transcurs de l'assignatura projecte V amb 
el meu company **Lluís Salvat** referent a la creació d'un servei climàtic per a la pràctica del senderisme a Andorra a partir de 
la definició d'unes variables i la automatització i càlcul del índex d'aquestes variables tal com veiem a continuació:

**Variables:**

[Dades](data/base_dades.png)

[Operacionalització de les variables](data/operac_variables.png)

Si ens centrem en el que m'ha motivat per la realització d'aquesta pàgina web, hi han diversos motius. En primer lloc, 
perquè coma a amant de la geografia, el senderisme es realitza en geografies 
diferents de les que ens són habituals com ara qualsevol localització enmig d’una ciutat, on el principal factor que es té en compte
per la seva pràctica és la sensació de llibertat i el clima, sobretot si entre l'inici i el final d'un itinerari hi ha molts quilòmetres de distància.
Cal adonar-se que, fins i tot, al llarg d'un dia en un mateix punt, les condicions meteorològiques poden canviar significativament; 
sobretot si es programa una activitat que suposi un gran desnivell en algun dels sistemes muntanyosos d’Andorra. Així doncs, trobo molt important 
conèixer la previsió del temps i en especial, les alertes meteorològiques de les diferents rutes, ja que si la informació anuncia unes condicions 
adverses, s’han de planificar altres destinacions o activitats.

En segon lloc, un fet que m'ha motivat a fer aquest pàgina web, fa referència a que no disposem d’un sistema climàtic de qualitat que se centri en 
aquesta activitat al territori, ja que em vaig adonar que Andorra disposa de poca informació climàtica, i que la tenim és molt limitada segons la 
parròquia on ens trobem, així que em vaig proposar aconseguir diferents dades meteorològiques especifiques pels diferents itineraris.

En definitiva, com que a Andorra tenim un clima molt variat depenent del territori on ens trobem, la creació d'una pàgina web que
pugui arribar a donar servei a diferents usuaris que vulguin pràcticar aquesta activitat em sembla molt interessant i necessària.

## Continguts
El meu repositori està fragmentat en diferents arxius i carpetes que permetran observar la dinàmica que tinc pensat seguir a l'hora d'elaborar la pàgina web,
com la carpeta *data*, on explico en detall gran part dels continguts que m'agradaria que apareixissin en la pàgina web. Encara així, pel moment m'agradaria que la meva pàgina web disposés d'aquests tres punts a la capçalera d'aquesta:

**Pàgina d'inici**: en aquesta primera secció, introduiriem un breu anàlisi de diferents variables gràcies a l'oportunitat i constant informació climàtica i de predicció que ens pot oferir un servei climàtic de qualitat i la potencialitat que té en un sector turístic com és el senderisme en un país petit com Andorra.

**Itineraris**: en aquest segon apartat, m'agradaria establir les condicions meteorològiques òptimes per a dur a terme l’activitat de senderisme en els diferents itineraris del territori de manera òptima i adaptada als usuaris finals als quals ens dirigim (*anomenats al word de la carpeta data*)

**Condicions climàtiques**: en aquest punt, analitzarem la variabilitat climàtica depenent del punt del territori on ens trobem a partir del tractament de diferents variables com:(longitud, latitud, temps i LCC (Baixa Coberta Nuvosa)) extretes del Centre Europeu de Previsions Meteorològiques a Mitjà Termini.

**Contacte**: finalment, en aquest darrer punt deixarem l'opció d'omplir un formulari de contacte, compòs per un número de telèfon i e-mail, i si es vol el nom d'usuari.

Pel que fa als continguts de les carpetes d'aquest repositori que comentavem anteriorment, tinc una carpeta amb les diferents imatges a utilitzar, una altra de mapes, on hi ha el mapa realitzat amb QGis2web i els fitxers generats, una altra amb la LICENSE que ens va recomanar el professor seguir i un arxiu igual txt. on es fa una sinopsis de 9 punts de la LICENSE GPL3 utilitzada, un arxiu .gitignore on hi han els arxius que no vull que el lector tingui en compte i finalment un index.html on hi ha el codi de la meva pàgina web.
Dins d'aquest mateix punt, també considero molt important destacar les referències bibliogràfiques que he seguit a l'hora d'obtenir els continguts d'aquesta.

**Bibliografia**

Servei Meteorològic Nacional (2021). Estacions meteorològiques. 
https://www.meteo.ad/estacions

Servei Meteorològic Nacional (2021). Climatologia. 
https://www.meteo.ad/climatologia

European Centre for Medium-Range Weather Forecasts. (2017). ECMWF. Free Public 
Datasets
https://www.ecmwf.int/en/forecasts/datasets

Institut d’Estudis Andorrans. (2021). Visor de mapes (IDE)
https://www.ideandorra.ad/geoportal/


## Estructura de la web
Aquest punt l'he realitzat a partir de **Mermaid**, una eina de diagrames i gràfics basada en Javascript que representa definicions de text per crear i modificar diagrames de manera dinàmica. 
```mermaid

graph TD;
%% contenidors;
A[fa:fa-mountain Servei climàtic aplicat al senderisme a Andorra.];
    
A-->B[fa:fa-home HIKLIMATE];

B-->C[fa:fa-star Pàgina d'inici];
B-->D[fa:fa-walking Itineraris];
B-->E[fa:fa-sun fa:fa-cloud Condicions climàtiques];
B-->G[fa:fa-envelope fa:fa-phone Contacte];

C-->H(Analitzar diferents variables <br> dirigides a la pràctica <br> òptima del senderisme.<br> <br> Adaptació del canvi climàtic <br> a tots els nivells. <br> <br.);
D-->I(Factors diferencials: <br/><br> - Variabilitat dels climes. <br><br> - Dificultats. <br><br> - Alternatives segons nivell.);
E-->J(Factors de cancelació de  <br> l'activitat/pràctica òptima: <br> <br>- Longitud i latitud. <br><br> - Temps i coberta nuvosa.);
G-->L(Formulari de contacte. <br><br> - Número de telèfon i <br> direcció e-mail.<br><br> - Nom d'usuari);

%% estils;
classDef p1 fill:#C0E1FF,stroke:#000000,stroke-width:3x;
classDef p2 fill:#E2F0FF,stroke:#000000,stroke-width:1.5px;
classDef p3 fill:#FFFAD5,stroke:#000000,stroke-width:1px;

class A p1;
class B,C,D,E,F,G p2;
class H,I,J,K,L p3;
```
## Cartografia
Per tal de realitzar aquest punt, mostraré el mapa realitzat amb QGIS2web que vaig realitzar com a esquema i que per suposat s'haura de modificar i millorar en tots els aspectes. 
![mapa](Images/mapa_qgis2web.png)

