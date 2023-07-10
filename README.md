RFC Destination | Connection Type | Path | Description | User | References | Comment
---|---|---|---|---|---|---
\<hostname>>_\<SID>_\<Inst.No.> | I | | | | | 
BACK | I | | | | | 
C_TP_\<Inst.No.>_\<hostname>  | T | | | | | used by TMS to call tp on OS-level
CSI_AWS_EC2 | G | ec2.amazonaws.com:80 | | | |
CSI_AWS_S3 | G | s3.amazonaws.com:80 | | | |
DOCUMENTATION_HELP | T | | | | | on the client side (SAPGui)
EU_SCRP_WN32 | T | | | | | used by the graphical screenpainter on the client side (SAPGui)
F1_HELP_SERVER_40 | T | | | | | on the client side (SAPGui)
GFW_ITS_RFC_DEST | T | | | | | 
IGS_RFC_DEST | T | | | | | used to call the integrated IGS
LOCAL_EXEC | T | | | | | N=rfcexec,
LOCAL_PRINT | T | | | | | on the client side (SAPGui)
MDX PARSER | T | | | | |            
NONE | I | | | | |
NONE_NU | I | | | | |
OPTSERVER_MIP01 | T | | | | | 
R3_WINDOWS_SERVER | T | | | | | on the client side (SAPGui)
RCC_GRID_ENGINE | G | | | | | 
RECORDER | X | | | | |
RECORDER_NU | X | | | | |
SAP_KEN_IOE | T | | | | | on the client side (SAPGui)
SAP_KW_HTMLEDITOR     | T | | | | | used to call the editor on the client side (SAPGui)
SAP_SCHEDULE_16 | T | | | | | on the client side (SAPGui)
SAP_SCHEDULE_32 | T | | | | | on the client side (SAPGui)
SAP_SSFATAS | T | | | | |
SAP_SSFATGUI | T | | | | | on the client side (SAPGui)
SAP-OSS | 3 | |  | | https://me.sap.com/notes/2923799 | Obsolete as of 2020
SAP-SUPPORT_NOTE_DOWNLOAD | G | [\<SAPRouter-string>]notesdownloads.sap.com:443 | HTTPS Destination for SAP Note Download | technical S-User with authX for the cust.no. | https://me.sap.com/notes/2836302 | used by SNOTE
SAP-SUPPORT_PARCELBOX | H | [\<SAPRouter-string>]documents.support.sap.com:443/parcel/ | HTTPS Destination for SAP Parcel Download | technical S-User with authX for the cust.no. | https://me.sap.com/notes/2836302 | used by SDCCN
SAP-SUPPORT_PORTAL | H | [\<SAPRouter-string>]apps.support.sap.com:443 | HTTPS Destination for SAP Support Portal | technical S-User with authX for the cust.no. | https://me.sap.com/notes/2836302 | used by SDCCN
SAPFORMS | T | | | | | on the client side (SAPGui)
SAPGUI | T | | | | |
SAPGUI_QUEUE | X | | | | |
SAPIRCONTROLLER | T | | | | |  on the client side (SAPGui)
SAPIRPCFILETRANSFER | T | | | | |  on the client side (SAPGui)
SAPJ2EE | T | | | | |
SAPKPROTP             | T | | | | | 
SAPNET_RTCC | 3 | |  | | https://me.sap.com/notes/2923799 | Obsolete as of 2020    
SAPOSS | 3 | | | | https://me.sap.com/notes/2923799 | Obsolete as of 2020
SDCC_\<SID>| G | HTTP Destination for SDCCN | | User in FRUN | https://me.sap.com/notes/2641304  | used by SDCCN if FRUN is used to send EWA data
SDCC_OSS | 3 | | | | https://me.sap.com/notes/2923799 | Obsolete as of 2020
SELF | I | | | | | same as NONE but with fast serialization (not shown in SM59)
SERVER_EXEC | T | | | | |
SLD_NUC | T | | | | |
SLD_UC | T | | | | |
VFOLDER               | T | | | | | on the client side (SAPGui)
WSSELF | W | | | | | same as none but with WebSocket RFC
