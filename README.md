# geosdi-data
## limits_IT_municipalities.topo.json

I limiti dei comuni italiani, oggetto `comuni`. Il codice ISTAT è in due forme :

- `com_istat_code` / `com_istat_code_num` — la codifica **attuale**, con le province della
  Sardegna riformate nel 2025 (112–119) ;
- `com_istat_code_2024_num` — la codifica **di prima della riforma** (province sarde 90, 91, 92,
  95, 111). Fuori dalla Sardegna vale quanto `com_istat_code_num`. Serve ai dati che usano ancora i
  codici vecchi, come i progetti del PNRR e le tile `istat-2025` di tileserver.geosdi.org. Per i
  377 comuni sardi è stato ricavato abbinando regione e nome del comune.
