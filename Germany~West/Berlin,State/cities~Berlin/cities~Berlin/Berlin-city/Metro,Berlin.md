---
aliases:
- Berlin_Metro
---

## #has_/text_of_/abstract 

> The Berlin U-Bahn (German: [ˈuː baːn]; short for Untergrundbahn, "underground railway") 
> is a rapid transit system in Berlin, the capital and largest city of Germany, 
> and a major part of the city's public transport system. 
> 
> Together with the S-Bahn, a network of suburban train lines, 
> and a tram network that operates mostly in the eastern parts of the city, 
> it serves as the main means of transport in the capital.
>
> Opened in 1902, the U-Bahn serves 175 stations spread across nine lines, 
> with a total track length of 155.64 kilometres (96 miles 57 chains), about 80% of which is underground. 
> 
> Trains run every two to five minutes during peak hours, 
> every five minutes for the rest of the day and every ten minutes in the evening. 
> 
> Over the course of a year, U-Bahn trains travel 132 million kilometres (82 million miles), 
> and carry over 400 million passengers. In 2017, 553.1 million passengers rode the U-Bahn. 
> The entire system is maintained and operated by the Berliner Verkehrsbetriebe, 
> commonly known as the BVG.
>
> Designed to alleviate traffic flowing into and out of central Berlin, the U-Bahn was rapidly expanded 
> until the city was divided into East and West Berlin at the end of World War II. 
> 
> Although the system remained open to residents of both sides at first, 
> the construction of the Berlin Wall and the subsequent restrictions 
> imposed by East Germany limited travel across the border. 
> 
> The East Berlin U-Bahn lines from West Berlin were severed, 
> except for two West Berlin lines that ran through East Berlin (U6 and U8). 
> These were allowed to pass through East Berlin without stopping at any of the closed stations. 
> 
> [[Stations,Berlin/Friedrichstraße_Station,Berlin]] was the exception because it was used as a 
> transfer point between U6 and the West Berlin S-Bahn system, and a __border crossing__ into East Berlin. 
> The system was reopened completely following the fall of the Berlin Wall and German reunification.
>
> The Berlin U-Bahn is the most extensive underground network in Germany.
>
> In 2006, travel on the Berlin U-Bahn was equivalent to 122.2 million km (76 million mi) of car journeys.
>
> [Wikipedia](https://en.wikipedia.org/wiki/Berlin%20U-Bahn)

## #has_/parts 

### [[U1,Berlin]] 

### [[U2,Berlin]] 

### [[U3,Berlin]] 

### [[U4,Berlin]] 

### [[U5,Berlin]] 

### [[U6,Berlin]]

### [[U7,Berlin]]

### [[U8,Berlin]] 

### [[U9,Berlin]] 


## #has_/diagram 

```mermaid
graph TD

    %% Class Definitions %%
    classDef greenText fill:#6ECF68,stroke:#2E7D32,stroke-width:2px,color:#FFF;
    classDef redText fill:#E57373,stroke:#C62828,stroke-width:2px,color:#FFF;
    classDef blueText fill:#64B5F6,stroke:#1565C0,stroke-width:2px,color:#FFF;
    classDef cyanText fill:#6CC,stroke:#2E7D32,stroke-width:2px,color:#FFF;
    classDef magentaText fill:#C6C,stroke:#C62828,stroke-width:2px,color:#FFF;
    classDef orangeText fill:#FA0,stroke:#1565C0,stroke-width:2px,color:#FFF;
    classDef brownText fill:#A33,stroke:#1565C0,stroke-width:2px,color:#FFF;
    classDef oliveText fill:#880,stroke:#1565C0,stroke-width:2px,color:#FFF;
    classDef yellowText fill:#FF0,stroke:#1565C0,stroke-width:2px,color:#000;

  subgraph U1 ["U1 Line"]
    U1_Krumme_Lanke("Krumme Lanke") --> U1_Onkel_Toms_Huette("Onkel Toms Hütte")
    U1_Onkel_Toms_Huette --> U1_Oskar_Helene_Heim("Oskar-Helene-Heim")
    U1_Oskar_Helene_Heim --> U1_Thielplatz("Thielplatz")
    U1_Thielplatz --> U1_Dahlem_Dorf("Dahlem-Dorf")
    U1_Dahlem_Dorf --> U1_Freie_Universitaet("Freie Universität (Thielplatz)")
    U1_Freie_Universitaet --> U1_Breitenbachplatz("Breitenbachplatz")
    U1_Breitenbachplatz --> U1_Suedwestkorso("Südwestkorso")
    U1_Suedwestkorso --> U1_Hohenzollernplatz("Hohenzollernplatz")
    U1_Hohenzollernplatz --> U1_Wittenbergplatz("Wittenbergplatz")
    U1_Wittenbergplatz --> U1_Nollendorfplatz("Nollendorfplatz")
    U1_Nollendorfplatz --> U1_Kurfürstendamm("Kurfürstendamm")
    U1_Kurfürstendamm --> U1_Gleisdreieck("Gleisdreieck")
    U1_Gleisdreieck --> U1_Möckernbrücke("Möckernbrücke")
    U1_Möckernbrücke --> U1_Hallesches_Tor("Hallesches Tor")
    U1_Hallesches_Tor --> U1_Kottbusser_Tor("Kottbusser Tor")
    U1_Kottbusser_Tor --> U1_Goerlitzer_Bahnhof("Görlitzer Bahnhof")
    U1_Goerlitzer_Bahnhof --> U1_Schlesisches_Tor("Schlesisches Tor")
    U1_Schlesisches_Tor --> U1_Warschauer_Strasse("Warschauer Straße")
  end

    class U1_Krumme_Lanke,U1_Onkel_Toms_Huette,U1_Oskar_Helene_Heim,U1_Thielplatz,U1_Dahlem_Dorf,U1_Freie_Universitaet,U1_Breitenbachplatz,U1_Sedwestkorso,U1_Hohenzollernplatz,U1_Wittenbergplatz,U1_Nollendorfplatz,U1_Kurfürstendamm,U1_Gleisdreieck,U1_Möckernbrücke,U1_Hallesches_Tor,U1_Kottbussr_Tor,U1_Goerlitzer_Bahnhof,U1_Schlesisches_Tor,U1_Suedwestkorso,U1_Kottbusser_Tor,U1_Warschauer_Strasse greenText;



  subgraph U2 ["U2 Line"]
    U2_Pankow("Pankow") --> U2_Vinetastraße("Vinetastraße")
    U2_Vinetastraße --> U2_Schönhauser_Allee("Schönhauser Allee")
    U2_Schönhauser_Allee --> U2_Eberswalder_Straße("Eberswalder Straße")
    U2_Eberswalder_Straße --> U2_Senefelderplatz("Senefelderplatz")
    U2_Senefelderplatz --> U2_Rosa_Luxemburg_Platz("Rosa-Luxemburg-Platz")
    U2_Rosa_Luxemburg_Platz --> U2_Alexanderplatz("Alexanderplatz")
    U2_Alexanderplatz --> U2_Klostertor("Klosterstraße")
    U2_Klostertor --> U2_Markisches_Museum("Märkisches Museum")
    U2_Markisches_Museum --> U2_Spittelmarkt("Spittelmarkt")
    U2_Spittelmarkt --> U2_Hausvogteiplatz("Hausvogteiplatz")
    U2_Hausvogteiplatz --> U2_Stadtmitte("Stadtmitte")
    U2_Stadtmitte --> U2_Mohrenstraße("Mohrenstraße")
    U2_Mohrenstraße --> U2_Potsdamer_Platz("Potsdamer Platz")
    U2_Potsdamer_Platz --> U2_Mendelssohn_Bartholdy_Park("Mendelssohn-Bartholdy-Park")
    U2_Mendelssohn_Bartholdy_Park --> U2_Gleisdreieck("Gleisdreieck")
    U2_Gleisdreieck --> U2_Bülowstraße("Bülowstraße")
    U2_Bülowstraße --> U2_Nollendorfplatz("Nollendorfplatz")
    U2_Nollendorfplatz --> U2_Wittenbergplatz("Wittenbergplatz")
    U2_Wittenbergplatz --> U2_Zoologischer_Garten("Zoologischer Garten")
    U2_Zoologischer_Garten --> U2_Ernst_Reuter_Platz("Ernst-Reuter-Platz")
    U2_Ernst_Reuter_Platz --> U2_Deutsche_Oper("Deutsche Oper")
    U2_Deutsche_Oper --> U2_Bismarckstraße("Bismarckstraße")
    U2_Bismarckstraße --> U2_Sophie_Charlotte_Platz("Sophie-Charlotte-Platz")
    U2_Sophie_Charlotte_Platz --> U2_Kaiserdamm("Kaiserdamm")
    U2_Kaiserdamm --> U2_Theodor_Heuss_Platz("Theodor Heuss Platz")
    U2_Theodor_Heuss_Platz --> U2_Westend("Westend")
    U2_Westend --> U2_Olympiastadion("Olympiastadion")
    U2_Olympiastadion --> U2_Ruhleben("Ruhleben")
  end

U1_Nollendorfplatz --> U2_Nollendorfplatz --> U3_Nollendorfplatz --> U4_Nollendorfplatz --> U1_Nollendorfplatz
U2_Nollendorfplatz --> U4_Nollendorfplatz
U2_Gleisdreieck --> U3_Gleisdreieck --> U1_Gleisdreieck --> U2_Gleisdreieck


    class U2_Pankow,U2_Vinetastraße,U2_Schönhauser_Allee,U2_Eberswalder_Straße,U2_Senefelderplatz,U2_Rosa_Luxemburg_Platz,U2_Alexanderplatz,U2_Klostertor,U2_Markisches_Museum,U2_Spittelmarkt,U2_Hausvogteiplatz,U2_Stadtmitte,U2_Potsdamer_Platz,U2_Mendelssohn_Bartholdy_Park,U2_Gleisdreieck,U2_Bülowstraße,U2_Nollendorfplatz,U2_Wittenbergplatz,U2_Zoologischer_Garten,U2_Ernst_Reuter_Platz,U2_Sophie_Charlotte_Platz,U2_Bismarckstraße,U2_Deutsche_Oper,U2_Richard_Wagner_Platz,U2_Westend,U2_Kaiserdamm,U2_Theodor_Heuss_Platz,U2_Olympiastadion,U2_Ruhleben blueText;


  %% Subgraph for U3
  subgraph U3 ["U3 Line"]
    U3_Krumme_Lanke("Krumme Lanke") --> U3_Onkel_Toms_Huette("Onkel Toms Hütte")
    U3_Onkel_Toms_Huette --> U3_Oskar_Helene_Heim("Oskar-Helene-Heim")
    U3_Oskar_Helene_Heim --> U3_Thielplatz("Thielplatz(Freie Universität)")
    U3_Thielplatz --> U3_Dahlem_Dorf("Dahlem-Dorf")
    U3_Dahlem_Dorf --> U3_Podbielskiallee("Podbielskiallee")
    U3_Podbielskiallee --> U3_Breitenbachplatz("Breitenbachplatz")
    U3_Breitenbachplatz --> U3_Rüdesheimer_Platz("Rüdesheimer Platz")
    U3_Rüdesheimer_Platz --> U3_Heidelbergerplatz("Heidelberger Platz")
    U3_Heidelbergerplatz --> U3_Fehrbelliner_Platz("Fehrbelliner Platz")
    U3_Fehrbelliner_Platz --> U3_Hohenzollernplatz("Hohenzollernplatz")
    U3_Hohenzollernplatz --> U3_Spichernstraße("Spichernstraße")
    U3_Spichernstraße --> U3_Nürnberger_Platz("Nürnberger Platz") --> U3_Augsburger_Straße("Augsburger Straße") 
--> U3_Wittenbergplatz("Wittenbergplatz")
--> U3_Nollendorfplatz("Nollendorfplatz")
--> U3_Kurfürstenstraße("Kurfürstenstraße")
--> U3_Gleisdreieck("Gleisdreieck")
--> U3_Möckernbrücke("Möckernbrücke")
--> U3_Hallesches_Tor("Hallesches Tor")
--> U3_Prinzenstraße("Prinzenstraße")
--> U3_Kottbusser_Tor("Kottbusser Tor")
--> U3_Görlitzer_Bahnhof("Görlitzer Bahnhof")
--> U3_Schlesisches_Tor("Schlesisches Tor")
--> U3_Warschauer_Straße("Warschauer Straße")
  end

U1_Möckernbrücke --> U3_Möckernbrücke --> U7_Möckernbrücke --> U1_Möckernbrücke

class U3_Krumme_Lanke,U3_Onkel_Toms_Huette,U3_Oskar_Helene_Heim,U3_Thielplatz,U3_Dahlem_Dorf,U3_Freie_Universitaet,U3_Breitenbachplatz,U3_Rüdesheimer_Platz,U3_Hohenzollernplatz,U3_Spichernstraße,U3_Nürnberger_Platz,U3_Augsburger_Straße,U3_Wittenbergplatz,U3_Nollendorfplatz,U3_Kurfürstenstraße,U3_Gleisdreieck,U3_Möckernbrücke,U3_Hallesches_Tor,U3_Prinzenstraße,U3_Kottbusser_Tor,U3_Görlitzer_Bahnhof,U3_Schlesisches_Tor,U3_Warschauer_Straße redText; 


  %% Subgraph for U4
  subgraph U4 ["U4 Line"]
    U4_Nollendorfplatz("Nollendorfplatz") --> U4_Viktoria_Luise_Platz("Viktoria-Luise-Platz")
    U4_Viktoria_Luise_Platz --> U4_Bayerischer_Platz("Bayerischer Platz")
    U4_Bayerischer_Platz --> U4_Rathaus_Schöneberg("Rathaus Schöneberg")
    U4_Rathaus_Schöneberg --> U4_Innsbrucker_Platz("Innsbrucker Platz")
  end

class U4_Nollendorfplatz,U4_Viktoria_Luise_Platz,U4_Bayerischer_Platz,U4_Rathaus_Schöneberg,U4_Innsbrucker_Platz cyanText; 



  %% Subgraph for U5
  subgraph U5 ["U5 Line"]
    U5_Hönow("Hönow") --> U5_Louis_Lewin_Straße("Louis-Lewin-Straße")
    U5_Louis_Lewin_Straße --> U5_Kaulsdorf_Nord("Kaulsdorf-Nord")
    U5_Kaulsdorf_Nord --> U5_Kienberg_Gärten_der_Welt("Kienberg (Gärten der Welt)")
    U5_Kienberg_Gärten_der_Welt --> U5_Cottbusser_Platz("Cottbusser Platz")
    U5_Cottbusser_Platz --> U5_Hellersdorf("Hellersdorf")
    U5_Hellersdorf --> U5_Carola_Neher_Straße("Carola-Neher-Straße")
    U5_Carola_Neher_Straße --> U5_Biesdorf_Süd("Biesdorf-Süd")
    U5_Biesdorf_Süd --> U5_Elsterwerdaer_Platz("Elsterwerdaer Platz")
    U5_Elsterwerdaer_Platz --> U5_Wuhletal("Wuhletal")
    U5_Wuhletal --> U5_Kaulsdorf("Kaulsdorf")
    U5_Kaulsdorf --> U5_Magdeburger_Platz("Magdeburger Platz")
    U5_Magdeburger_Platz --> U5_Friedrichsfelde("Friedrichsfelde")
    U5_Friedrichsfelde --> U5_Lichtenberg("Lichtenberg")
    U5_Lichtenberg --> U5_Strausberger_Platz("Strausberger Platz")
    U5_Strausberger_Platz --> U5_Alexanderplatz("Alexanderplatz")
    U5_Alexanderplatz --> U5_Museum_Ins("Museumsinsel")
    U5_Museum_Ins --> U5_Brandenburger_Tor("Brandenburger Tor")
    U5_Brandenburger_Tor --> U5_Hauptbahnhof("Hauptbahnhof")
  end


class U5_Hönow,U5_Louis_Lewin_Straße,U5_Kaulsdorf_Nord,U5_Kienberg_Gärten_der_Welt,U5_Cottbusser_Platz,U5_Hellersdorf,U5_Carola_Neher_Straße,U5_Biesdorf_Süd,U5_Elsterwerdaer_Platz,U5_Wuhletal,U5_Kaulsdorf,U5_Magdeburger_Platz,U5_Friedrichsfelde,U5_Lichtenberg,U5_Strausberger_Platz,U5_Alexanderplatz,U5_Museum_Ins,U5_Brandenburger_Tor,U5_Hauptbahnhof orangeText;



  %% Subgraph for U6
  subgraph U6 ["U6 Line"]
    U6_Alt_Tegel("Alt-Tegel") --> U6_Borsigwerke("Borsigwerke")
    U6_Borsigwerke --> U6_Holzhauser_Straße("Holzhauser Straße")
    U6_Holzhauser_Straße --> U6_Otisstraße("Otisstraße")
    U6_Otisstraße --> U6_Kurt_Schumacher_Platz("Kurt-Schumacher-Platz")
    U6_Kurt_Schumacher_Platz --> U6_Afrikanische_Straße("Afrikanische Straße")
    U6_Afrikanische_Straße --> U6_Rehberge("Rehberge")
    U6_Rehberge --> U6_Seestraße("Seestraße")
    U6_Seestraße --> U6_Leopoldplatz("Leopoldplatz")  
    U6_Leopoldplatz --> U6_Wedding("Wedding")
    U6_Wedding --> U6_Reinickendorfer_Straße("Reinickendorfer Straße")
    U6_Reinickendorfer_Straße --> U6_Naturkundemuseum("Naturkundemuseum")
    U6_Naturkundemuseum --> U6_Oranienburger_Tor("Oranienburger Tor")
    U6_Oranienburger_Tor --> U6_Friedrichstraße("Friedrichstraße")
    U6_Friedrichstraße --> U6_Stadtmitte("Stadtmitte")
    U6_Stadtmitte --> U6_Kochstraße("Kochstraße (Checkpoint Charlie)")
    U6_Kochstraße --> U6_Hallesches_Tor("Hallesches Tor")
    U6_Hallesches_Tor --> U6_Mehringdamm("Mehringdamm")
    U6_Mehringdamm --> U6_Platz_der_Luftbrücke("Platz der Luftbrücke")
    U6_Platz_der_Luftbrücke --> U6_Tempelhof("Tempelhof")
    U6_Tempelhof --> U6_Alt_Mariendorf("Alt-Mariendorf")
  end


U6_Mehringdamm --> U7_Mehringdamm
U1_Hallesches_Tor --> U3_Hallesches_Tor --> U6_Hallesches_Tor --> U1_Hallesches_Tor


class U6_Alt_Tegel,U6_Borsigwerke,U6_Holzhauser_Straße,U6_Otisstraße,U6_Kurt_Schumacher_Platz,U6_Afrikanische_Straße,U6_Rehberge,U6_Seestraße,U6_Wedding,U6_Reinickendorfer_Straße,U6_Naturkundemuseum,U6_Oranienburger_Tor,U6_Friedrichstraße,U6_Stadtmitte,U6_Kochstraße,U6_Hallesches_Tor,U6_Mehringdamm,U6_Platz_der_Luftbrücke,U6_Tempelhof,U6_Alt_Mariendorf,U6_Leopoldplatz magentaText; 



  %% Subgraph for U7
  subgraph U7 ["U7 Line"]
    U7_Rathaus_Spandau("Rathaus Spandau") --> U7_Altstadt_Spandau("Altstadt Spandau")
    U7_Altstadt_Spandau --> U7_Zitadelle("Zitadelle")
    U7_Zitadelle --> U7_Haselhorst("Haselhorst")
    U7_Haselhorst --> U7_Paulsternstraße("Paulsternstraße")
    U7_Paulsternstraße --> U7_Rohrdamm("Rohrdamm")
    U7_Rohrdamm --> U7_Siemensdamm("Siemensdamm")
    U7_Siemensdamm --> U7_Halemweg("Halemweg")
    U7_Halemweg --> U7_Jakob_Kaiser_Platz("Jakob-Kaiser-Platz")
    U7_Jakob_Kaiser_Platz --> U7_Jungfernheide("Jungfernheide")
    U7_Jungfernheide --> U7_Mierendorffplatz("Mierendorffplatz")
    U7_Mierendorffplatz --> U7_Richard_Wagner_Platz("Richard-Wagner-Platz")
    U7_Richard_Wagner_Platz --> U7_Bismarckstraße("Bismarckstraße")
    U7_Bismarckstraße --> U7_Wilmersdorfer_Straße("Wilmersdorfer Straße")
    U7_Wilmersdorfer_Straße --> U7_Adenauerplatz("Adenauerplatz")
    U7_Adenauerplatz --> U7_Konstanzer_Straße("Konstanzer Straße")
    U7_Konstanzer_Straße --> U7_Fehrbelliner_Platz("Fehrbelliner Platz")
    U7_Fehrbelliner_Platz --> U7_Bliesestraße("Blissestraße")
    U7_Bliesestraße --> U7_Berliner_Straße("Berliner Straße")
    U7_Berliner_Straße --> U7_Bayerischer_Platz("Bayerischer Platz")
    U7_Bayerischer_Platz --> U7_Eisenacher_Straße("Eisenacher Straße")
    U7_Eisenacher_Straße --> U7_Kleistpark("Kleistpark")
    U7_Kleistpark --> U7_Yorckstraße("Yorckstraße")
    U7_Yorckstraße --> U7_Möckernbrücke("Möckernbrücke")
    U7_Möckernbrücke --> U7_Mehringdamm("Mehringdamm")
    U7_Mehringdamm --> U7_Gneisenaustraße("Gneisenaustraße")
    U7_Gneisenaustraße --> U7_Südstern("Südstern") --> U7_Hermannplatz("Hermannplatz")
    U7_Hermannplatz --> U7_Rathaus_Neukölln("Rathaus Neukölln") 
--> U7_Karl_Marx_Straße("Karl-Marx-Straße") --> U7_Neukölln("Neukölln") --> U7_Grenzallee("Grenzallee")
--> U7_Blaschkoallee("Blaschkoallee") --> U7_Parchimer_Allee("Parchimer Allee") 
--> U7_Britz_Süd("Britz-Süd") --> U7_Johannisthaler_Chaussee("Johannisthaler Chaussee") 
--> U7_Lipschitzallee("Lipschitzallee")
--> U7_Wutzkyallee("Wutzkyallee") --> U7_Zwickauer_Damm("Zwickauer Damm") --> U7_Rudow("Rudow")
  end

U1_Möckernbrücke --> U7_Möckernbrücke 
U3_Fehrbelliner_Platz --> U7_Fehrbelliner_Platz
U2_Bismarckstraße --> U7_Bismarckstraße

class U7_Rathaus_Spandau,U7_Altstadt_Spandau,U7_Zitadelle,U7_Haselhorst,U7_Paulsternstraße,U7_Rohrdamm,U7_Siemensdamm,U7_Halemweg,U7_Jungfernheide,U7_Mierendorffplatz,U7_Richard_Wagner_Platz,U7_Bismarckstraße,U7_Wilmersdorfer_Straße,U7_Adenauerplatz,U7_Konstanzer_Straße,U7_Fehrbelliner_Platz,U7_Bliesestraße,U7_Berliner_Straße,U7_Bayerischer_Platz,U7_Eisenacher_Straße,U7_Kleistpark,U7_Yorckstraße,U7_Mehringdamm,U7_Gneisenaustraße,U7_Hermannplatz,U7_Rathaus_Neukölln,U7_Karl_Marx_Straße,U7_Neukölln,U7_Grenzallee,U7_Blaschkoallee,U7_Parchimer_Allee,U7_Britz_Süd,U7_Johannisthaler_Chaussee,U7_Lipschitzallee,U7_Jakob_Kaiser_Platz,U7_Wutzkyallee,U7_Zwickauer_Damm,U7_Südstern,U7_Möckernbrücke,U7_Paradestraße,U7_Britz_Süd,U7_Parchimer_Allee,U7_Blaschkoallee,U7_Rudow brownText;



  %% Subgraph for U8
  subgraph U8 ["U8 Line"]
    U8_Wittenau("Wittenau") --> U8_Rathaus_Reinickendorf("Rathaus Reinickendorf")
    U8_Rathaus_Reinickendorf --> U8_Lindauer_Allee("Lindauer Allee")
    U8_Lindauer_Allee --> U8_Paracelsus_Bad("Paracelsus-Bad")
    U8_Paracelsus_Bad --> U8_Franz_Neumann_Platz("Franz-Neumann-Platz (Am Schäfersee)")
    U8_Franz_Neumann_Platz --> U8_Pankstraße("Pankstraße")
    U8_Pankstraße --> U8_Gesundbrunnen("Gesundbrunnen")
    U8_Gesundbrunnen --> U8_Voltastraße("Voltastraße")
    U8_Voltastraße --> U8_Bernauer_Straße("Bernauer Straße")
    U8_Bernauer_Straße --> U8_Rosenthaler_Platz("Rosenthaler Platz")
    U8_Rosenthaler_Platz --> U8_Alexanderplatz("Alexanderplatz")
    U8_Alexanderplatz --> U8_Heinrich_Heine_Straße("Heinrich-Heine-Straße")
    U8_Heinrich_Heine_Straße --> U8_Moritzplatz("Moritzplatz")
    U8_Moritzplatz --> U8_Kottbusser_Tor("Kottbusser Tor")
    U8_Kottbusser_Tor --> U8_Schönleinstraße("Schönleinstraße")
    U8_Schönleinstraße --> U8_Hermannplatz("Hermannplatz")
    U8_Hermannplatz --> U8_Boddinstraße("Boddinstraße")
    U8_Boddinstraße --> U8_Leinestraße("Leinestraße")
    U8_Leinestraße --> U8_Hermannstraße("Hermannstraße")
  end

U7_Hermannplatz --> U8_Hermannplatz



class U8_Wittenau,U8_Rathaus_Reinickendorf,U8_Lindauer_Allee,U8_Paracelsus_Bad,U8_Franz_Neumann_Platz,U8_Pankstraße,U8_Gesundbrunnen,U8_Voltastraße,U8_Bernauer_Straße,U8_Rosenthaler_Platz,U8_Alexanderplatz,U8_Heinrich_Heine_Straße,U8_Moritzplatz,U8_Kottbusser_Tor,U8_Schönleinstraße,U8_Hermannplatz,U8_Boddinstraße,U8_Leinestraße,U8_Hermannstraße oliveText;


  %% Subgraph for U9
  subgraph U9 ["U9 Line"]
    U9_Osloer_Straße("Osloer Straße") --> U9_Leopoldplatz("Leopoldplatz")
    U9_Leopoldplatz --> U9_Amrumer_Straße("Amrumer Straße")
    U9_Amrumer_Straße --> U9_Westhafen("Westhafen")
    U9_Westhafen --> U9_Birkenstraße("Birkenstraße")
    U9_Birkenstraße --> U9_Turmstraße("Turmstraße")
    U9_Turmstraße --> U9_Hansaplatz("Hansaplatz")
    U9_Hansaplatz --> U9_Zoologischer_Garten("Zoologischer Garten")
    U9_Zoologischer_Garten --> U9_Kurfürstendamm("Kurfürstendamm")
    U9_Kurfürstendamm --> U9_Spichernstraße("Spichernstraße")
    U9_Spichernstraße --> U9_Hohenzollernplatz("Hohenzollernplatz")
    U9_Hohenzollernplatz --> U9_Bundesplatz("Bundesplatz")
    U9_Bundesplatz --> U9_Friedrich_Wilhelm_Platz("Friedrich-Wilhelm-Platz")
    U9_Friedrich_Wilhelm_Platz --> U9_Walther_Schreiber_Platz("Walther-Schreiber-Platz")
    U9_Walther_Schreiber_Platz --> U9_Schloßstraße("Schloßstraße")
    U9_Schloßstraße --> U9_Rathaus_Steglitz("Rathaus Steglitz")
  end

U6_Leopoldplatz --> U9_Leopoldplatz 
U1_Kurfürstendamm --> U9_Kurfürstendamm
U1_Wittenbergplatz --> U2_Wittenbergplatz
U2_Alexanderplatz --> U5_Alexanderplatz --> U8_Alexanderplatz --> U2_Alexanderplatz

class U9_Osloer_Straße,U9_Leopoldplatz,U9_Amrumer_Straße,U9_Westhafen,U9_Birkenstraße,U9_Turmstraße,U9_Hansaplatz,U9_Zoologischer_Garten,U9_Kurfürstendamm,U9_Spichernstraße,U9_Hohenzollernplatz,U9_Bundesplatz,U9_Friedrich_Wilhelm_Platz,U9_Walther_Schreiber_Platz,U9_Schloßstraße,U9_Rathaus_Steglitz yellowText;








```


## Confidential Links & Embeds: 

### #is_/same_as :: [Metro,Berlin](Metro,Berlin.md) 

### #is_/same_as :: [Metro,Berlin.public](/_public/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Metro,Berlin.public.md) 

### #is_/same_as :: [Metro,Berlin.internal](/_internal/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Metro,Berlin.internal.md) 

### #is_/same_as :: [Metro,Berlin.protect](/_protect/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Metro,Berlin.protect.md) 

### #is_/same_as :: [Metro,Berlin.private](/_private/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Metro,Berlin.private.md) 

### #is_/same_as :: [Metro,Berlin.personal](/_personal/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Metro,Berlin.personal.md) 

### #is_/same_as :: [Metro,Berlin.secret](/_secret/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Metro,Berlin.secret.md)

