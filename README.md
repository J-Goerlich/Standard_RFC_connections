# Standard_RFC_connections
Collection of SAP default connections

RFC Destination | Connection Type | Path | Description | References | Comment
---|---|---|---|---|---
SDCC_\<SID> | G | | HTTP Destination for SDCCN| https://me.sap.com/notes/2641304 | used by SDCCN if FRUN is used to send EWA data
SDCC_OSS | 3 | | | https://me.sap.com/notes/2923799 | Obsolete as of 2020
SAPNET_RTCC | 3 | | | https://me.sap.com/notes/2923799 | Obsolete as of 2020
SAP-OSS | 3 | | | https://me.sap.com/notes/2923799 | Obsolete as of 2020
SAPOSS | 3 | | | https://me.sap.com/notes/2923799 | Obsolete as of 2020
SAP-SUPPORT_PORTAL | H | [\<SAPRouter-string>]apps.support.sap.com:443 | HTTPS Destination for SAP Support Portal | https://me.sap.com/notes/2836302 | used by SDCCN
SAP-SUPPORT_NOTE_DOWNLOAD | G | [\<SAPRouter-string>]notesdownloads.sap.com:443 | HTTPS Destination for SAP Note Download | https://me.sap.com/notes/2836302 | used by SNOTE
SAP-SUPPORT_PARCELBOX | H | [\<SAPRouter-string>]documents.support.sap.com:443/parcel/ | HTTPS Destination for SAP Parcel Download | | used by SDCCN
