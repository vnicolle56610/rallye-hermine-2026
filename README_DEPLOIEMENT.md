# Rallye de l'Hermine — version interactive

Le grand visuel validé est utilisé comme interface.

Zones cliquables :
- bouton rouge "Ajouter à l'agenda" -> `rallye-hermine.ics`
- bouton "Itinéraire Google Maps" -> Google Maps
- bouton "Plans Apple" -> Apple Plans
- bandeau "Réservation obligatoire" -> copie l'adresse de réponse

Les hotspots utilisent des coordonnées en pourcentage et restent alignés lorsque
l'image se redimensionne sur mobile ou ordinateur.

Test local :
    python3 -m http.server 8000

Puis ouvrir :
    http://127.0.0.1:8000
