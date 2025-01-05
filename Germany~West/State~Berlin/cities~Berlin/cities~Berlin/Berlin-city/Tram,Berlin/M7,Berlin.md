
## #has_/diagram 


```mermaid
graph TD
  %% M7 Tram Line with Connections
  subgraph M7 ["M7 Tram Line"]
    M7_Bhf_Friedrichsfelde_Ost["S+U Friedrichsfelde Ost"] --> M7_Rhinstraße_Weißenseer_Weg["Rhinstraße/Weißenseer Weg"]
    M7_Rhinstraße_Weißenseer_Weg --> M7_Landsberger_Allee_Rhinstraße["Landsberger Allee/Rhinstraße"]
    M7_Landsberger_Allee_Rhinstraße --> M7_Landsberger_Allee_Petersburger_Straße["Landsberger Allee/Petersburger Straße"]
    M7_Landsberger_Allee_Petersburger_Straße --> M7_Warschauer_Straße["Warschauer Straße"]
    M7_Warschauer_Straße --> M7_Strausberger_Platz["Strausberger Platz"]
    M7_Strausberger_Platz --> M7_Alexanderplatz["Alexanderplatz"]
    M7_Alexanderplatz --> M7_Hackescher_Markt["Hackescher Markt"]
    M7_Hackescher_Markt --> M7_Oranienburger_Tor["Oranienburger Tor"]
    M7_Oranienburger_Tor --> M7_Naturkundemuseum["Naturkundemuseum"]
    M7_Naturkundemuseum --> M7_Hauptbahnhof["Hauptbahnhof"]
    M7_Hauptbahnhof --> M7_S_Bhf_Jungfernheide["S+U Jungfernheide"]
    M7_S_Bhf_Jungfernheide --> M7_S_Bhf_Spandau["S+U Spandau"]
  end

  %% Connections to Other Lines
  M7_Bhf_Friedrichsfelde_Ost --> S5_Friedrichsfelde_Ost
  M7_Bhf_Friedrichsfelde_Ost --> S7_Friedrichsfelde_Ost
  M7_Bhf_Friedrichsfelde_Ost --> S75_Friedrichsfelde_Ost
  M7_Bhf_Friedrichsfelde_Ost --> U5_Friedrichsfelde_Ost

  M7_Landsberger_Allee_Petersburger_Straße --> M10_Landsberger_Allee_Petersburger_Straße

  M7_Warschauer_Straße --> S3_Warschauer_Straße
  M7_Warschauer_Straße --> S5_Warschauer_Straße
  M7_Warschauer_Straße --> 7S_Warschauer_Straße
  M7_Warschauer_Straße --> S9_Warschauer_Straße
  M7_Warschauer_Straße --> U1_Warschauer_Straße
  M7_Warschauer_Straße --> U_Warschauer_Straße

  M7_Strausberger_Platz --> U5_Strausberger_Platz

  M7_Alexanderplatz --> S3_Alexanderplatz
  M7_Alexanderplatz --> S5_Alexanderplatz
  M7_Alexanderplatz --> S7_Alexanderplatz
  M7_Alexanderplatz --> S_Alexanderplatz
  M7_Alexanderplatz --> U2_Alexanderplatz
  M7_Alexanderplatz --> U5_Alexanderplatz
  M7_Alexanderplatz --> U8_Alexanderplatz
  M7_Hackescher_Markt --> S3_Hackescher_Markt
  M7_Hackescher_Markt --> S5_Hackescher_Markt
  M7_Hackescher_Markt --> S7_Hackescher_Markt
  M7_Hackescher_Markt --> S9_Hackescher_Markt

  M7_Oranienburger_Tor --> U6_Oranienburger_Tor
  M7_Naturkundemuseum --> U6_Naturkundemuseum

  %% Hauptbahnhof
  M7_Hauptbahnhof --> S3_Hauptbahnhof
  M7_Hauptbahnhof --> S5_Hauptbahnhof
  M7_Hauptbahnhof --> S7_Hauptbahnhof
  M7_Hauptbahnhof --> S9_Hauptbahnhof
  M7_Hauptbahnhof --> U5_Hauptbahnhof

  %% S+U Jungfernheide
  M7_S_Bhf_Jungfernheide --> S41_Jungfernheide
  M7_S_Bhf_Jungfernheide --> S42_Jungfernheide
  M7_S_Bhf_Jungfernheide --> S46_Jungfernheide
  M7_S_Bhf_Jungfernheide --> U7_Jungfernheid

  %% S+U Spandau
  M7_S_Bhf_Spandau --> S3_Spandau
  M7_S_Bhf_Spandau --> S9_Spandau
  M7_S_Bhf_Spandau --> U7_Spandau

```





