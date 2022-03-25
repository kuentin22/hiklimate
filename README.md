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
parròquia on ens trobem, així que em vaig proposar aconseguir diferents dades meteorològiques.

En definitiva, com que a Andorra tenim un clima molt variat depenent del territori on ens trobem, la creació d'una pàgina web que
pugui arribar a donar servei a diferents usuaris que vulguin pràcticar aquesta activitat em sembla molt interessant i necessària.

## Continguts





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


