
## #has_/diagram 


```mermaid
graph TD
  subgraph Tram18 ["Tram 18 Line"]
    T18_Riesaer_Str["Riesaer Str."] --> T18_Riesaer_Str_Louis_Lewin_Str["Riesaer Str./Louis-Lewin-Str."]
    T18_Riesaer_Str_Louis_Lewin_Str --> T18_Jenaer_Str["Jenaer Str."]
    T18_Jenaer_Str --> T18_Nossener_Str["Nossener Str."]
    T18_Nossener_Str --> T18_U_Hellersdorf["U Hellersdorf"]
    T18_U_Hellersdorf --> T18_Stendaler_Str_Quedlinburger_Str["Stendaler Str./Quedlinburger Str."]
    T18_Stendaler_Str_Quedlinburger_Str --> T18_Stendaler_Str_Zossener_Str["Stendaler Str./Zossener Str."]
    T18_Stendaler_Str_Zossener_Str --> T18_Zossener_Str_Kastanienallee["Zossener Str./Kastanienallee"]
    T18_Zossener_Str_Kastanienallee --> T18_Alte_Hellersdorfer_Zossener_Str["Alte Hellersdorfer/Zossener Str."]
    T18_Alte_Hellersdorfer_Zossener_Str --> T18_Michendorfer_Str["Michendorfer Str."]
    T18_Michendorfer_Str --> T18_Landsberger_Chaussee_Zossener_Str["Landsberger Chaussee/Zossener Str."]
    T18_Landsberger_Chaussee_Zossener_Str --> T18_Betriebshof_Marzahn["Betriebshof Marzahn"]
  end

  T18_U_Hellersdorf --> U5_Hellersdorf
  T18_U_Hellersdorf --> M6_Hellersdorf
  T18_U_Hellersdorf --> M8_Hellersdorf

  %% Betriebshof Marzahn
  T18_Betriebshof_Marzahn --> M6_Betriebshof_Marzahn
  T18_Betriebshof_Marzahn --> M_Betriebshof_Marzahn

```



