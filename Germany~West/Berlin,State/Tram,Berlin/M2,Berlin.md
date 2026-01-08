---
dv_is_:
  same_as:
    - "[[/_Standards/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin|M2,Berlin]]"
    - "[[/_public/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.public|M2,Berlin.public]]"
    - "[[/_internal/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.internal|M2,Berlin.internal]]"
    - "[[/_protect/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.protect|M2,Berlin.protect]]"
    - "[[/_private/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.private|M2,Berlin.private]]"
    - "[[/_personal/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.personal|M2,Berlin.personal]]"
    - "[[/_secret/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.secret|M2,Berlin.secret]]"
dv_is_same_as:
  - "[[/_Standards/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin|M2,Berlin]]"
  - "[[/_public/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.public|M2,Berlin.public]]"
  - "[[/_internal/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.internal|M2,Berlin.internal]]"
  - "[[/_protect/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.protect|M2,Berlin.protect]]"
  - "[[/_private/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.private|M2,Berlin.private]]"
  - "[[/_personal/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.personal|M2,Berlin.personal]]"
  - "[[/_secret/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.secret|M2,Berlin.secret]]"
---


```mermaid
graph TD

  %% M2 Tram Line with Connections
  subgraph M2 ["M2 Tram Line"]
    M2_Heinersdorf["Heinersdorf"] --> M2_Prenzlauer_Promenade_Am_Steinberg["Prenzlauer Promenade/Am Steinberg"]
    M2_Prenzlauer_Promenade_Am_Steinberg --> M2_Am_Steinberg["Am Steinberg"]
    M2_Am_Steinberg --> M2_Prenzlauer_Allee_Ostseestraße["Prenzlauer Allee/Ostseestraße"]
    M2_Prenzlauer_Allee_Ostseestraße --> M2_Erich_Weinert_Straße["Erich-Weinert-Straße"]
    M2_Erich_Weinert_Straße --> M2_S_Prenzlauer_Allee["S Prenzlauer Allee"]
    M2_S_Prenzlauer_Allee --> M2_Fröbelstraße["Fröbelstraße"]
    M2_Fröbelstraße --> M2_Prenzlauer_Allee_Danziger_Straße["Prenzlauer Allee/Danziger Straße"]
    M2_Prenzlauer_Allee_Danziger_Straße --> M2_Marienburger_Straße["Marienburger Straße"]
    M2_Marienburger_Straße --> M2_Knaackstraße["Knaackstraße"]
    M2_Knaackstraße --> M2_Prenzlauer_Allee_Metzer_Straße["Prenzlauer Allee/Metzer Straße"]
    M2_Prenzlauer_Allee_Metzer_Straße --> M2_Mollstraße_Prenzlauer_Allee["Mollstraße/Prenzlauer Allee"]
    M2_Mollstraße_Prenzlauer_Allee --> M2_Alexanderplatz["Alexanderplatz"]
    M2_Alexanderplatz --> M2_Alexanderplatz_Bhf_Memhardstraße["S+U Alexanderplatz Bhf/Memhardstraße"]
    M2_Alexanderplatz_Bhf_Memhardstraße --> M2_Alexanderplatz_Bhf_Dircksenstraße["S+U Alexanderplatz Bhf/Dircksenstraße"]
  end

  %% Connections to Other Lines
  %% S Prenzlauer Allee
  M2_S_Prenzlauer_Allee --> S_Prenzlauer_Allee

  %% Prenzlauer Allee/Danziger Straße
  M2_Prenzlauer_Allee_Danziger_Straße --> M10_Prenzlauer_Allee_Danziger_Straße

  %% Alexanderplatz
  M2_Alexanderplatz -- "S-Bahn S3, S5, S7, S9" --> S_Alexanderplatz
  M2_Alexanderplatz -- "Trams M4, M5, M6" --> M4_Alexanderplatz
  M2_Alexanderplatz --> U2_Alexanderplatz
  M2_Alexanderplatz --> U5_Alexanderplatz
  M2_Alexanderplatz --> U8_Alexanderplatz
  M2_Alexanderplatz --> S_Alexanderplatz
  M2_Alexanderplatz --> M4_Alexanderplatz -->  M5_Alexanderplatz --> M6_Alexanderplatz
  M2_Alexanderplatz --> M5_Alexanderplatz
  M2_Alexanderplatz --> M6_Alexanderplatz
  M4_Alexanderplatz --> M6_Alexanderplatz


  %% S+U Alexanderplatz Bhf/Memhardstraße
  M2_Alexanderplatz_Bhf_Memhardstraße -- "Tram M4" --> M4_Alexanderplatz_Memhardstraße


```


## Confidential Links & Embeds: 

### #is_/same_as :: [[/_Standards/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin|M2,Berlin]] 

### #is_/same_as :: [[/_public/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.public|M2,Berlin.public]] 

### #is_/same_as :: [[/_internal/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.internal|M2,Berlin.internal]] 

### #is_/same_as :: [[/_protect/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.protect|M2,Berlin.protect]] 

### #is_/same_as :: [[/_private/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.private|M2,Berlin.private]] 

### #is_/same_as :: [[/_personal/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.personal|M2,Berlin.personal]] 

### #is_/same_as :: [[/_secret/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/Berlin,State/Tram,Berlin/M2,Berlin.secret|M2,Berlin.secret]] 

