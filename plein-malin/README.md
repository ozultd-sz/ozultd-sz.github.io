# Plein Malin

**[Ouvrir l'appli / Open the app → ozultd-sz.github.io/plein-malin](https://ozultd-sz.github.io/plein-malin/)**

*English version below.*

## À quoi ça sert

Plein Malin vous dit **où faire le plein sur votre trajet** en France et en Suisse. Vous indiquez un départ, une arrivée et votre carburant ; l'appli cherche les stations le long de la route et vous montre où le plein vous coûtera le moins cher, en comptant le prix à la pompe **et** le carburant consommé pour faire le détour.

Une station un peu moins chère mais à 5 km de la route n'est pas forcément une bonne affaire : Plein Malin fait le calcul pour vous.

## Ce que vous obtenez

- **Les 3 stations recommandées**, avec le prix au litre, le détour (km et minutes), le coût du plein et l'économie par rapport aux autres stations du trajet.
- **La liste des stations du trajet**, dans l'ordre où vous passez devant, du départ vers l'arrivée. Le nombre de stations dépend de la distance :

  | Trajet | Stations listées |
  |---|---|
  | jusqu'à 50 km | 10 |
  | jusqu'à 100 km | 15 |
  | jusqu'à 400 km | 20 |
  | plus de 400 km | de 30 à 50 |

- **Un bouton « Y aller avec Google Maps »** qui ouvre le trajet complet avec un arrêt à la station, et un lien sur chaque adresse pour voir la station sur la carte.
- **Français ou anglais** : bouton EN / FR en haut à droite.

## Comment l'utiliser

1. Ouvrez [ozultd-sz.github.io/plein-malin](https://ozultd-sz.github.io/plein-malin/) sur votre téléphone ou ordinateur.
2. Saisissez le départ et l'arrivée (ville ou adresse en France ou en Suisse).
3. Choisissez votre carburant et l'écart maximum accepté par rapport à la route (3 km par défaut).
4. Appuyez sur « Trouver les meilleures stations ».

Rien à installer, pas de compte, gratuit.

## D'où viennent les données

- **France** : prix officiels du gouvernement (Prix des carburants), mis à jour environ toutes les 10 minutes. Les prix de plus de 7 jours sont ignorés.
- **Suisse** : il n'existe pas de données de prix publiques officielles. Les stations viennent d'OpenStreetMap et les prix affichés « ~ » sont des **estimations** (moyennes nationales), convertis de CHF en EUR au taux BCE.
- **Itinéraire** : OSRM (OpenStreetMap). **Adresses** : Nominatim. **Marques** : OpenStreetMap.

## Limites à connaître

- Le calcul suppose un plein de 50 L et une consommation de 6,5 L/100 km.
- L'itinéraire est celui d'OpenStreetMap (avec ses variantes) : il peut différer légèrement de celui que Google Maps ou Waze vous proposera.
- Les prix suisses sont indicatifs. Vérifiez à la pompe.
- Quand la marque d'une station française est inconnue, elle s'affiche « Station » + ville.

---

## English

### What it's for

Plein Malin tells you **where to fill up along your route** in France and Switzerland. Enter a start, a destination and your fuel; the app finds the stations along the road and shows where a full tank will cost you least, counting both the pump price **and** the fuel burned on the detour.

A slightly cheaper station 5 km off the road isn't always a good deal. Plein Malin does the maths for you.

### What you get

- **The 3 recommended stations**, with price per litre, detour (km and minutes), cost of a full tank and the saving compared with other stations on the route.
- **The list of stations on the route**, in the order you pass them, from departure to arrival: 10 stations up to 50 km, 15 up to 100 km, 20 up to 400 km, and 30 to 50 beyond that.
- **A "Go with Google Maps" button** that opens the full trip with a stop at the station, plus a link on each address to see the station on the map.
- **French or English**: EN / FR button at the top right.

### How to use it

1. Open [ozultd-sz.github.io/plein-malin](https://ozultd-sz.github.io/plein-malin/) on your phone or computer.
2. Enter the start and destination (a town or address in France or Switzerland).
3. Pick your fuel and how far from the route you're willing to go (3 km by default).
4. Tap "Find the best stations".

Nothing to install, no account, free.

### Where the data comes from

- **France**: official government prices (Prix des carburants), updated about every 10 minutes. Prices older than 7 days are ignored.
- **Switzerland**: there is no official public price data. Stations come from OpenStreetMap and prices shown with "~" are **estimates** (national averages), converted from CHF to EUR at the ECB rate.
- **Routing**: OSRM (OpenStreetMap). **Addresses**: Nominatim. **Brands**: OpenStreetMap.

### Good to know

- Calculations assume a 50 L fill-up and 6.5 L/100 km.
- The route comes from OpenStreetMap (with its alternatives), so it may differ slightly from the one Google Maps or Waze gives you.
- Swiss prices are indicative. Check at the pump.
- When a French station's brand is unknown, it shows as "Station" + town.
