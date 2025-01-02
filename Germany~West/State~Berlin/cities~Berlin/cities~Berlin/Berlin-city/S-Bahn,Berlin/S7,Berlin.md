


```mermaid
graph TD 

subgraph S75 ["S75 Line"]
S_Warschauer_Straße("Warschauer Straße") --> 
S_Ostkreuz("Ostkreuz") --> 
S_Nöldnerplatz("Nöldnerplatz") --> 
S_Lichtenberg("Lichtenberg") --> 
S_Friedrichsfelde_Ost("Friedrichsfelde Ost") --> 
S_Springpfuhl("Springpfuhl") --> 
S_Gehrenseestraße("Gehrenseestraße") --> 
S_Hohenschönhausen("Hohenschönhausen") --> 
S_Wartenberg("Wartenberg") 
end


class S_Warschauer_Straße,S_Ostkreuz,S_Nöldnerplatz,S_Lichtenberg,S_Friedrichsfelde_Ost,S_Springpfuhl,S_Gehrenseestraße,S_Hohenschönhausen,S_Wartenberg violetText;



subgraph S7 ["S7 Line"]
S_Potsdam_Hbf("Potsdam Hauptbahnhof") --> 
S_Babelsberg("Babelsberg") --> 
S_Griebnitzsee("Griebnitzsee") --> 
S_Wannsee("Wannsee") --> 
S_Nikolassee("Nikolassee") --> 
S_Grunewald("Grunewald") --> 
S_Westkreuz("Westkreuz") --> 
S_Charlottenburg("Charlottenburg") --> 
S_Savignyplatz("Savignyplatz") --> 
S_Zoologischer_Garten("Zoologischer Garten") --> 
S_Tiergarten("Tiergarten") --> 
S_Bellevue("Bellevue") --> 
S_Hauptbahnhof("Hauptbahnhof") --> 
S_Friedrichstraße("Friedrichstraße") --> 
S_Hackescher_Markt("Hackescher Markt") --> 
S_Alexanderplatz("Alexanderplatz") --> 
S_Jannowitzbrücke("Jannowitzbrücke") --> 
S_Ostbahnhof("Ostbahnhof") --> 
S_Warschauer_Straße("Warschauer Straße") --> 
S_Ostkreuz("Ostkreuz") --> 
S_Nöldnerplatz("Nöldnerplatz") --> 
S_Lichtenberg("Lichtenberg") --> 
S_Friedrichsfelde_Ost("Friedrichsfelde Ost") --> 
S_Springpfuhl("Springpfuhl") --> 
S_Poelchaustraße("Poelchaustraße") --> 
S_Marzahn("Marzahn") --> 
S_Raoul_Wallenberg_Straße("Raoul-Wallenberg-Straße") --> 
S_Mehrower_Allee("Mehrower Allee") --> 
S_Ahrensfelde("Ahrensfelde")
end

S_Charlottenburg --> U7_Charlottenburg
S_Zoologischer_Garten --> U2_Zoologischer_Garten
S_Zoologischer_Garten --> U9_Zoologischer_Garten
S_Hauptbahnhof --> U5_Hauptbahnhof
S_Friedrichstraße --> U6_Friedrichstraße
S_Alexanderplatz --> U2_Alexanderplatz
S_Alexanderplatz --> U5_Alexanderplatz
S_Alexanderplatz --> U8_Alexanderplatz
S_Jannowitzbrücke --> U8_Jannowitzbrücke
S_Warschauer_Straße --> U1_Warschauer_Straße
S_Warschauer_Straße --> U3_Warschauer_Straße
S_Lichtenberg --> U5_Lichtenberg


class S_Potsdam_Hbf,S_Babelsberg,S_Griebnitzsee,S_Wannsee,S_Nikolassee,S_Grunewald,S_Westkreuz,S_Charlottenburg,S_Savignyplatz,S_Zoologischer_Garten,S_Tiergarten,S_Bellevue,S_Hauptbahnhof,S_Friedrichstraße,S_Hackescher_Markt,S_Alexanderplatz,S_Jannowitzbrücke,S_Ostbahnhof,S_Warschauer_Straße,S_Ostkreuz,S_Nöldnerplatz,S_Lichtenberg,S_Friedrichsfelde_Ost,S_Springpfuhl,S_Poelchaustraße,S_Marzahn,S_Raoul_Wallenberg_Straße,S_Mehrower_Allee,S_Ahrensfelde blueText;


```