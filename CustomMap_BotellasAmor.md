# Custom Google Map for a non-profit: Botellas de Amor Colombia

## Botellas de Amor Color Palette

The color palette used was obtained from the Home page of botellas de amor [https://botellasdeamor.org/](url)

![FinalPalette_Botellas de amor](https://user-images.githubusercontent.com/98049283/159191811-beca38bc-9c4e-48cd-b2ac-d083136ad9f4.jpg)

## Outline of the process for creating a custom map

Once the color palette was defined for the styled map Google Styling Wizard ([https://mapstyle.withgoogle.com/](url)) was used for creating a custom map. The base map used was Aubergine. After setting this theme various features were modified to match the colors in the palette or similar ones. In detail the changes made using the advanced options were:

- Overall text fill and outlines modification to match the HEX codes b5bab9 and 081e2b , respectively.
- Country geometry stroke modified to match the HEX code 86959c.
- Province geometry stroke modified to match the HEX code a6c3d3.
- Human made landscape geometry modified to match the HEX code 85b5cb for fill and b48d91 for stroke.
- Nature landscape geometry modified to match the HEX code 023e58 for fill and stroke.
- Overall points of interests geometry was modified to match the HEX code b73b47. The associated text fill for this category was modified to match the HEX code e9e2e3; text outline was changed to the HEX code 1d2c4d.
- The particular category of Parks geometry fill was altered to match the HEX code a4c35e and text codes changed for fill and outline using the HEX codes 3c7680 and eef1f1, respectively,
- Roads geometry updated to use the HEX code e3e4ea and its respective text was changed to HEX code 1b5899 for the fill and dcdee0 for the outline.
- Transit features text was changed to match the HEX codes 1d2c4dd for outline and 98a5be for the fill.
 
## Screenshot of the stylized map
![BotellasAmorCustomMap](https://user-images.githubusercontent.com/98049283/159191660-b237e3d1-f25e-4ce3-9e86-0884c0ed9c47.jpg)

## JSON Code

[ { "elementType": "geometry", "stylers": [ { "color": "#1d2c4d" } ] }, { "elementType": "labels.text.fill", "stylers": [ { "color": "#b5bab9" } ] }, { "elementType": "labels.text.stroke", "stylers": [ { "color": "#081e2b" } ] }, { "featureType": "administrative.country", "elementType": "geometry.stroke", "stylers": [ { "color": "#86959c" } ] }, { "featureType": "administrative.land_parcel", "elementType": "labels.text.fill", "stylers": [ { "color": "#d0d9eb" } ] }, { "featureType": "administrative.province", "elementType": "geometry.stroke", "stylers": [ { "color": "#a6c3d3" } ] }, { "featureType": "landscape.man_made", "elementType": "geometry.fill", "stylers": [ { "color": "#85b5cb" } ] }, { "featureType": "landscape.man_made", "elementType": "geometry.stroke", "stylers": [ { "color": "#b48d91" } ] }, { "featureType": "landscape.natural", "elementType": "geometry", "stylers": [ { "color": "#023e58" } ] }, { "featureType": "poi", "elementType": "geometry", "stylers": [ { "color": "#b73b47" } ] }, { "featureType": "poi", "elementType": "labels.text.fill", "stylers": [ { "color": "#e9e2e3" } ] }, { "featureType": "poi", "elementType": "labels.text.stroke", "stylers": [ { "color": "#1d2c4d" } ] }, { "featureType": "poi.park", "elementType": "geometry.fill", "stylers": [ { "color": "#a4c35e" } ] }, { "featureType": "poi.park", "elementType": "labels.text.fill", "stylers": [ { "color": "#3C7680" } ] }, { "featureType": "poi.park", "elementType": "labels.text.stroke", "stylers": [ { "color": "#eef1f1" } ] }, { "featureType": "road", "elementType": "geometry", "stylers": [ { "color": "#e3e4ea" }, { "visibility": "simplified" }, { "weight": 1 } ] }, { "featureType": "road", "elementType": "labels.text.fill", "stylers": [ { "color": "#1b5899" } ] }, { "featureType": "road", "elementType": "labels.text.stroke", "stylers": [ { "color": "#dcdde0" } ] }, { "featureType": "road.highway", "elementType": "geometry", "stylers": [ { "color": "#2c6675" } ] }, { "featureType": "road.highway", "elementType": "geometry.stroke", "stylers": [ { "color": "#255763" } ] }, { "featureType": "road.highway", "elementType": "labels.text.fill", "stylers": [ { "color": "#b0d5ce" } ] }, { "featureType": "road.highway", "elementType": "labels.text.stroke", "stylers": [ { "color": "#023e58" } ] }, { "featureType": "transit", "elementType": "labels.text.fill", "stylers": [ { "color": "#98a5be" } ] }, { "featureType": "transit", "elementType": "labels.text.stroke", "stylers": [ { "color": "#1d2c4d" } ] }, { "featureType": "transit.line", "elementType": "geometry.fill", "stylers": [ { "color": "#346fac" } ] }, { "featureType": "transit.line", "elementType": "labels.text.fill", "stylers": [ { "color": "#748eaa" } ] }, { "featureType": "transit.station", "elementType": "geometry", "stylers": [ { "color": "#3a4762" } ] }, { "featureType": "water", "elementType": "geometry", "stylers": [ { "color": "#0e1626" } ] }, { "featureType": "water", "elementType": "labels.text.fill", "stylers": [ { "color": "#4e6d70" } ] } ]
