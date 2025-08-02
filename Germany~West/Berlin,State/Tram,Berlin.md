
## #has_/text_of_/abstract 

>  The Berlin tramway (German: Straßenbahn Berlin) is the main tram system in Berlin, Germany.  
>  It is one of the oldest tram networks in the world having its origins in 1865 
>  and is operated by Berliner Verkehrsbetriebe (BVG), which was founded in 1929. 
>  
>  It is notable for being the third-largest tram system in the world, after Melbourne and St. Petersburg. 
>  
>  Berlin's tram system is made up of 22 lines that operate across a standard gauge network, 
>  with almost 800 stops and measuring almost 190 kilometres (120 mi) in route length 
>  and 430 kilometres (270 mi) in line length. 
>  
>  Nine of the lines, M1 - M9 called Metrotram, operate 24 hours a day 
>  and are identified with the letter "M" before their number; 
>  the other thirteen lines are regular city tram lines and are identified by just a line number.
>
> Most of the current network is within the confines of the former East Berlin, 
> as tram lines within West Berlin were replaced by buses during the division of Berlin. 
> 
> However, the first extension into West Berlin opened in 1994 on today's M13. 
> In the eastern vicinity of the city there are also three private tram lines 
> that are not part of the main system; 
> the Potsdam tram system, with its own network of lines, is just to the south-west of Berlin.
>
> [Wikipedia](https://en.wikipedia.org/wiki/Trams%20in%20Berlin)



## #has_/parts 


### [[Tram,Berlin/M1,Berlin]] 


### [[Tram,Berlin/M2,Berlin]] 


### [[Tram,Berlin/M3,Berlin]] 


### [[Tram,Berlin/M4,Berlin]] 


### [[Tram,Berlin/M5,Berlin]] 


### [[Tram,Berlin/M6,Berlin]] 


### [[Tram,Berlin/M7,Berlin]] 


### [[Tram,Berlin/M8,Berlin]] 


### [[Tram,Berlin/M9,Berlin]] 


### [[Tram12,Berlin]] 


### [[Tram16,Berlin]] 


### [[Tram18,Berlin]] 


### [[Tram21,Berlin]] 


### [[Tram27,Berlin]] 


### [[Tram37,Berlin]] 


### [[Tram50,Berlin]] 


### [[Tram60,Berlin]] 


### [[Tram61,Berlin]] 


### [[Tram62,Berlin]] 


### [[Tram63,Berlin]] 


### [[Tram67,Berlin]] 


### [[Tram68,Berlin]] 




## #has_/diagram 


```mermaid
graph TD
  %% M1 Tram Line
  subgraph M1 ["M1 Tram Line"]
    %% Northern Branch: Rosenthal Nord to Am Kupfergraben
    M1_Rosenthal_Nord["Rosenthal Nord"] --> M1_Wilhelmsruher_Damm["Wilhelmsruher Damm"]
    M1_Wilhelmsruher_Damm --> M1_Schillerstraße["Schillerstraße"]
    M1_Schillerstraße --> M1_Pastor_Niemöller_Platz["Pastor-Niemöller-Platz"]
    M1_Pastor_Niemöller_Platz --> M1_Waldstraße["Waldstraße"]
    M1_Waldstraße --> M1_Hauptstraße["Hauptstraße"]
    M1_Hauptstraße --> M1_Grabbeallee["Grabbeallee"]
    M1_Grabbeallee --> M1_Schönholz_Schillerstraße["Schönholz/Schillerstraße"]
    M1_Schönholz_Schillerstraße --> M1_Breite_Straße["Breite Straße"]
    M1_Breite_Straße --> M1_Pankow_Kirche["Pankow Kirche"]
    M1_Pankow_Kirche --> M1_Pankow["Pankow"]
    M1_Pankow --> M1_Vinetastraße["Vinetastraße"]
    M1_Vinetastraße --> M1_Prenzlauer_Allee_Ostseestraße["Prenzlauer Allee/Ostseestraße"]
    M1_Prenzlauer_Allee_Ostseestraße --> M1_Schönhauser_Allee_Bornholmer_Straße["Schönhauser Allee/Bornholmer Straße"]
    M1_Schönhauser_Allee_Bornholmer_Straße --> M1_Eberswalder_Straße["Eberswalder Straße"]
    M1_Eberswalder_Straße --> M1_Senefelderplatz["Senefelderplatz"]
    M1_Senefelderplatz --> M1_Rosa_Luxemburg_Platz["Rosa-Luxemburg-Platz"]
    M1_Rosa_Luxemburg_Platz --> M1_Alexanderplatz["Alexanderplatz"]
    M1_Alexanderplatz --> M1_Hackescher_Markt["S Hackescher Markt"]
    M1_Hackescher_Markt --> M1_Am_Kupfergraben["Am Kupfergraben"]
  end



  %% Connections to Other Lines
  %% Pankow
  M1_Pankow --> U2_Pankow
  M1_Pankow --> S_Pankow

  %% Vinetastraße
  M1_Vinetastraße --> U2_Vinetastraße

  %% Schönhauser Allee/Bornholmer Straße
  M1_Schönhauser_Allee_Bornholmer_Straße --> S_Schönhauser_Allee
  M1_Schönhauser_Allee_Bornholmer_Straße --> M13_Schönhauser_Allee

  %% Eberswalder Straße
  M1_Eberswalder_Straße --> U2_Eberswalder_Straße

  M1_Hackescher_Markt --> S_Hackescher_Markt




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


## Confidential Links & Embeds: 

### #is_/same_as :: [Tram,Berlin](Tram,Berlin.md) 

### #is_/same_as :: [Tram,Berlin.public](/_public/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Tram,Berlin.public.md) 

### #is_/same_as :: [Tram,Berlin.internal](/_internal/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Tram,Berlin.internal.md) 

### #is_/same_as :: [Tram,Berlin.protect](/_protect/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Tram,Berlin.protect.md) 

### #is_/same_as :: [Tram,Berlin.private](/_private/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Tram,Berlin.private.md) 

### #is_/same_as :: [Tram,Berlin.personal](/_personal/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Tram,Berlin.personal.md) 

### #is_/same_as :: [Tram,Berlin.secret](/_secret/Earth/Continent/Europe/Europe~Central/Germany/Germany~West/State~Berlin/cities~Berlin/cities~Berlin/Berlin-city/Tram,Berlin.secret.md)

