# Faillissement_2023_analyse
Python-script dat gegevens over faillissementen voor het jaar 2023 analyseert en visualiseert

# Inleiding

De code maakt gebruik van verschillende bibliotheken voor gegevensmanipulatie, reiniging en visualisatie, zoals pandas, matplotlib, seaborn, geopy, geopandas en folium.

# Instructies voor gebruik

    Zorg ervoor dat je de benodigde Python-bibliotheken hebt geïnstalleerd.

    Zorg ervoor dat je 'your_google_api_key' vervangt door je daadwerkelijke Google API-sleutel in de code waar geocoding wordt uitgevoerd.

# Download de vereiste gegevensbestanden:

    'faillissement_database_2023.xlsx': gegevens over faillissementen voor 2023.
    'standaard_bedrijfsindeling_2008_excel1.xlsx': Standaard Bedrijfsindeling (SBI)-codes.

Voer het script uit, en het genereert de volgende visualisaties en gegevensbestanden:

# Visualisaties en Uitvoer

1. Histogram van Faillissementsstatuscategorieën

    Toont een histogram van faillissementsstatuscategorieën in oplopende volgorde.

2. Maandelijkse verdeling van Faillissementen

    Toont een lijnplot van maandelijkse faillissementen en een staafplot van het totale aantal gevallen per maand.

3. Verdeling van SBI-codes bij Faillissementen

    Genereert een taartdiagram dat de verdeling van SBI-codes voor faillissementen illustreert.

4. Geolocatiekaart van Faillissementen

    Creëert een interactieve Folium-kaart met markers die de geolocaties van faillissementen in 2023 vertegenwoordigen.

5. Ruimtelijke Join met Gemeente GeoDataFrame

    Voert een ruimtelijke join uit tussen het faillissementsgegevensframe en een GeoJSON-bestand met gemeentegrenzen.

6. Choroplethkaart van Faillissementen per Gemeente

    Toont een choroplethkaart die de verdeling van faillissementen over gemeenten laat zien.

# Uitvoerbestanden

    'subset_faillissement.xlsx': Excel-bestand met de subset van faillissementsgegevens die voor de analyse zijn gebruikt.
    'Geolocaties_Faillissementen_2023.html': Interactieve HTML-kaart die de geolocaties van faillissementen in 2023 laat zien.

# Belangrijke aantekeningen

    Zorg ervoor dat de juiste paden voor gegevensbestanden zijn gespecificeerd in het script.
    Zorg ervoor dat 'your_google_api_key' is vervangen door een geldige Google API-sleutel voor geocoding.

Voel je vrij om de code te verkennen en aan te passen op basis van je specifieke vereisten!
