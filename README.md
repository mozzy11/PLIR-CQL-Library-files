# PLIR_CQL_files

Tgis repository contains the sample PLIR cql librarry and measure for PLIR

NOTE : before you run the query below ,  **PUT** the Resources under the `files directory` to the `HAPI FHIR server` with their respective Resource id ie 

    PUT : FHIR-BASE_URL/Library/TX-PVLS 

see files/tx_pvls.cql for the cql Logic used encoded in the TX-PVLS LIbrary

sample query

    http://localhost:8080/fhir/Measure/TX-PVLS/$evaluate-measure?periodStart=2019-01-01&periodEnd=2019-12-31
