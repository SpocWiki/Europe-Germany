---

FoodWasteArray:
- [Source, Tons]
- [Household,6.5]
- [Restaurant,1.9]
- [Processing,1.6]
- [Sales,0.8]
- [Producton,0.2]

---

# Germany~Stats

## 2023
### Food Waste 2023 


```dataviewjs
let pages = dv.current().FoodWasteArray;
dv.table(pages[0],pages.slice(1));
```

