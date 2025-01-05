
## #has_/diagram 


```mermaid
graph TD
  %% M9 Tram Line with Connections
  subgraph M9 ["M9 Tram Line"]
    M9_Pankow["Pankow"] --> M9_Pankow_Kirche["Pankow Kirche"]
    M9_Pankow_Kirche --> M9_Prenzlauer_Promenade["Prenzlauer Promenade"]
    M9_Prenzlauer_Promenade --> M9_Granitzstraße["Granitzstraße"]
    M9_Granitzstraße --> M9_Schönhauser_Allee["Schönhauser Allee"]
    M9_Schönhauser_Allee --> M9_Bornholmer_Straße["Bornholmer Straße"]
    M9_Bornholmer_Straße --> M9_Seestraße["Seestraße"]
    M9_Seestraße --> M9_Wedding["Wedding"]
    M9_Wedding --> M9_Leopoldplatz["Leopoldplatz"]
    M9_Leopoldplatz --> M9_Birkenstraße["Birkenstraße"]
    M9_Birkenstraße --> M9_Westhafen["Westhafen"]
    M9_Westhafen --> M9_Beusselstraße["Beusselstraße"]
    M9_Beusselstraße --> M9_Jungfernheide["Jungfernheide"]
    M9_Jungfernheide --> M9_Mierendorffplatz["Mierendorffplatz"]
    M9_Mierendorffplatz --> M9_Sophie_Charlotten_Straße["Sophie-Charlotten-Straße"]
    M9_Sophie_Charlotten_Straße --> M9_Kaiserdamm["Kaiserdamm"]
    M9_Kaiserdamm --> M9_Bhf_Charlottenburg["S-Bhf Charlottenburg"]
    M9_Bhf_Charlottenburg --> M9_Wilmersdorfer_Straße["Wilmersdorfer Straße"]
    M9_Wilmersdorfer_Straße --> M9_Bismarckstraße["Bismarckstraße"]
    M9_Bismarckstraße --> M9_Deutsche_Oper["Deutsche Oper"]
    M9_Deutsche_Oper --> M9_Zoologischer_Garten["Zoologischer Garten"]
  end

  %% Connections to Other Lines
  %% S Pankow
  M9_Pankow --> S2_Pankow
  M9_Pankow --> S8_Pankow
  M9_Pankow --> S85_Pankow
  M9_Pankow --> U2_Pankow

  %% Schönhauser Allee
  M9_Schönhauser_Allee --> S41_Schönhauser_Allee
  M9_Schönhauser_Allee --> S42_Schönhauser_Allee
  M9_Schönhauser_Allee --> S8_Schönhauser_Allee
  M9_Schönhauser_Allee --> S85_Schönhauser_Allee
  M9_Schönhauser_Allee --> U2_Schönhauser_Allee

  %% Bornholmer Straße
  M9_Bornholmer_Straße --> S1_Bornholmer_Straße
  M9_Bornholmer_Straße --> S2_Bornholmer_Straße
  M9_Bornholmer_Straße --> S25_Bornholmer_Straße
  M9_Bornholmer_Straße --> S26_Bornholmer_Straße

  %% Seestraße
  M9_Seestraße --> U6_Seestraße
  M9_Seestraße --> M13_Seestraße

  M9_Leopoldplatz --> U6_Leopoldplatz
  M9_Leopoldplatz --> U9_Leopoldplatz

  M9_Westhafen --> S41_Westhafen
  M9_Westhafen --> S42_Westhafen
  M9_Westhafen --> U9_Westhafen

  M9_Jungfernheide --> S41_Jungfernheide
  M9_Jungfernheide --> S42_Jungfernheide
  M9_Jungfernheide --> S46_Jungfernheide
  M9_Jungfernheide --> U7_Jungfernheide

  M9_Mierendorffplatz --> U7_Mierendorffplatz

  M9_Kaiserdamm --> S41_Kaiserdamm
  M9_Kaiserdamm --> S42_Kaiserdamm
  M9_Kaiserdamm --> U2_Kaiserdamm

  M9_Bhf_Charlottenburg --> S3_Charlottenburg
  M9_Bhf_Charlottenburg --> S5_Charlottenburg
  M9_Bhf_Charlottenburg --> S7_Charlottenburg
  M9_Bhf_Charlottenburg --> S9_Charlottenburg
  M9_Bhf_Charlottenburg --> U7_Charlottenburg

  M9_Wilmersdorfer_Straße --> U7_Wilmersdorfer_Straße

  M9_Bismarckstraße --> U2_Bismarckstraße
  M9_Bismarckstraße --> U7_Bismarckstraße

  M9_Deutsche_Oper --> U2_Deutsche_Oper

  %% Zoologischer Garten
  M9_Zoologischer_Garten --> S3_Zoologischer_Garten
  M9_Zoologischer_Garten --> S5_Zoologischer_Garten
  M9_Zoologischer_Garten --> S7_Zoologischer_Garten
  M9_Zoologischer_Garten --> S9_Zoologischer_Garten
  M9_Zoologischer_Garten --> U2_Zoologischer_Garten
  M9_Zoologischer_Garten --> U9_Zoologischer_Garten

```
