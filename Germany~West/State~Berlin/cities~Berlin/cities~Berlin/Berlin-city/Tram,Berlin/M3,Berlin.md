

## #has_/diagram  

```mermaid
graph TD


  %% M3 Tram Line with Connections
  subgraph M3 ["M3 Tram Line"]
    M3_Rummelsburg["S Rummelsburg"] --> M3_Rummelsburg_Karlshorster_Straße["Rummelsburg/Karlshorster Straße"]
    M3_Rummelsburg_Karlshorster_Straße --> M3_Hauptstraße["Hauptstraße"]
    M3_Hauptstraße --> M3_Köpenicker_Allee["Köpenicker Allee"]
    M3_Köpenicker_Allee --> M3_Bhf_Rummelsburg["S-Bhf Rummelsburg"]
    M3_Bhf_Rummelsburg --> M3_Nöldnerplatz["Nöldnerplatz"]
    M3_Nöldnerplatz --> M3_Weitlingstraße["Weitlingstraße"]
    M3_Weitlingstraße --> M3_Lichtenberg["Lichtenberg"]
    M3_Lichtenberg --> M3_Friedrichsfelde["Friedrichsfelde"]
    M3_Friedrichsfelde --> M3_Pfarrstraße["Pfarrstraße"]
    M3_Pfarrstraße --> M3_Samariterstraße["Samariterstraße"]
    M3_Samariterstraße --> M3_Warschauer_Straße["Warschauer Straße"]
    M3_Warschauer_Straße --> M3_Ostkreuz["Ostkreuz"]
  end

  M3_Rummelsburg --> S_Rummelsburg
  M3_Nöldnerplatz --> S_Nöldnerplatz

  %% Lichtenberg
  M3_Lichtenberg --> U5_Lichtenberg
  M3_Lichtenberg--> S_Lichtenberg

  M3_Friedrichsfelde  --> U5_Friedrichsfelde

  M3_Warschauer_Straße --> U1_Warschauer_Straße
  M3_Warschauer_Straße --> S_Warschauer_Straße

  %% Ostkreuz
  M3_Ostkreuz --> S_Ostkreuz


```

