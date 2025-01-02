

```mermaid
graph TD 



subgraph S46 ["S46 Line"]
S_Westend("Westend") --> 
S_Messe_Nord("Messe Nord/ICC") --> 
S_Westkreuz("Westkreuz") --> 
S_Halensee("Halensee") --> 
S_Hohenzollerndamm("Hohenzollerndamm") --> 
S_Heidelberger_Platz("Heidelberger Platz") --> 
S_Bundesplatz("Bundesplatz") --> 
S_Innsbrucker_Platz("Innsbrucker Platz") --> 
S_Schöneberg("Schöneberg") --> 
S_Südkreuz("Südkreuz") --> 
S_Tempelhof("Tempelhof") --> 
S_Hermannstraße("Hermannstraße") --> 
S_Neukölln("Neukölln") --> 
S_Köllnische_Heide("Köllnische Heide") --> 
S_Baumschulenweg("Baumschulenweg") --> 
S_Schöneweide("Schöneweide") --> 
S_Johannisthal("Johannisthal") --> 
S_Adlershof("Adlershof") --> 
S_Grünau("Grünau") --> 
S_Eichwalde("Eichwalde") --> 
S_Zeuthen("Zeuthen") --> 
S_Wildau("Wildau") --> 
S_Königs_Wusterhausen("Königs Wusterhausen")
end


S_Heidelberger_Platz --> U3_Heidelberger_Platz
S_Bundesplatz --> U9_Bundesplatz
S_Innsbrucker_Platz --> U4_Innsbrucker_Platz
S_Tempelhof --> U6_Tempelhof
S_Hermannstraße --> U8_Hermannstraße
S_Neukölln --> U7_Neukölln


class S_Westend,S_Messe_Nord,S_Westkreuz,S_Halensee,S_Hohenzollerndamm,S_Heidelberger_Platz,S_Bundesplatz,S_Innsbrucker_Platz,S_Schöneberg,S_Südkreuz,S_Tempelhof,S_Hermannstraße,S_Neukölln,S_Köllnische_Heide,S_Baumschulenweg,S_Schöneweide,S_Johannisthal,S_Adlershof,S_Grünau,S_Eichwalde,S_Zeuthen,S_Wildau,S_Königs_Wusterhausen blueText;

```