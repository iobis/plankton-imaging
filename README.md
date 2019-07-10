# plankton-imaging

This repo is to document the mapping of EcoTaxa data fields with Darwin Core terms and how they can be organized into the OBIS-ENV-DATA format. At the WWW.PIC technical kick-off meeting, 9-10 July 2019 (Paris) we agreed on the following minimal terms.

ECOTAXA | Darwin Core | Comments
--- | --- | :---
object_id  | dwc:occurrenceID |
object_lat | dwc:decimalLatitude  |
object_lon | decimalLongitude |
object_date | dwc:eventDate | ISO8601 format: yyyy-mm-dd
object_time | dwc:eventTime | ISO8601 format: hh:mm:ss
