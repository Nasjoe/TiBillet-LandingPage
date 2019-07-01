# Landing Page pour le projet TiBillet.

### Hébergé sur www.tibillet.re

Un dépot faisant parti du projet TiBillet :
Application 360° de billetterie et de système cashless pour cafés, associations, salles de concerts, festivals et tout évènements culturels.
Créée sur l'île de la Réunion et portée par l'association des 3Peaks de Manapany ( www.3peaks.fr ) et l'entreprise GDNA ( www.gdna.re )

## Autre dépots du projet :
- https://github.com/Nasjoe/TiBillet-Cashless
- https://github.com/Nasjoe/TiBillet-LandingPage

## Landing Page.

Une simple page statique propulsée par nginx et docker.
Le docker compose comporte des informations supplémentaires nécéssaires au fonctionnement avec le service Traefik.

La ligne importante : 
     ´´´- ./Template:/usr/share/nginx/html´´´
Nginx s'occupe du reste. Rien d'autre à faire ! 

## Licence :

	Copyright 2017 2019+* - Jonas TURBEAUX - GDNA - 3Peaks.
	La distribution et l'utilisation de ce programme sont régies par la GPL version 3 ou ultérieure.
	Les auteurs demandent juste à être invités à chaque évènement où ce système est mis en place ! :) 
	Et puis si vous en faites une utilisation commerciale et que vous gagnez du fric avec, 
	soyez sympa, faites un don ! https://www.3peaks.fr/

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.