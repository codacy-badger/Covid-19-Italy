# Covid-19-Italy

A python Class that provide you all the latest informations about COVID-19 from "protezione civile" (https://github.com/pcm-dpc/COVID-19)
## Dependencies

```
requests
json
```

## How to use 

### Import the Class:
```
from covid import Covid

c = Covid()
```
### Here the list of class arguments:
```
c.stato
c.ricoverati_con_sintomi
c.terapia_intensiva
c.totale_ospedalizzati 
c.isolamento_domiciliare 
c.totale_positivi 
c.variazione_totale_positivi 
c.nuovi_positivi 
c.dimessi_guariti 
c.deceduti 
c.nuovi_deceduti
c.casi_da_sospetto_diagnostico 
c.casi_da_screening 
c.totale_casi
c.tamponi 
c.casi_testati 
c.note
```

### Here the list of class functions:
```
c.getSmallReport()
c.getFullReport()
```
**getSmallReport()** will provide you some minimal but important information about latest Covid19 news (from Italy)

**getFullReport()** will provide you all the latest available information about Covid19 (from Italy)

## Example code

**Source**
```
from covid import Covid
c = Covid()

print(c.getSmallReport())

```

**Output**

```
Totale positivi: 21932
Nuovi positivi: 1411
Guariti: 206554
Deceduti: 35463
Nuovi Deceduti: 5
Tamponi: 8313445
```

