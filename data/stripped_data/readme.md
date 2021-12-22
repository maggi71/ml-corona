# Features

Dokumentation der Rohdaten unter https://www.covid19.admin.ch/api/data/documentation

Download der Rohdaten unter https://www.covid19.admin.ch/de/hosp-capacity/icu, zuunterst bei 'Daten herunterladen'

| Feature Name|Beschreibung|Rohdaten CSV|Feature in Rohdaten CSV|Speziell |
|-------------------|--------------------|:-----------------------------:|:-----------------------:|:-------------:|
|cases|Absolute number of occurrences for this day.|COVID19Cases_geoRegion.csv|        entries | ddd|
|vaccination_atLeastOneDosePersons|Number of persons that have received at least one dose|COVID19VaccPersons_v2.csv|type |age_group=total_population - records containing data for the total population|
|vaccination_firstBoosterPersons|Number of persons that have received at least one booster vaccine dose. Subset of the 'COVID19FullyVaccPersons'|COVID19VaccPersons_v2.csv|type |age_group=total_population - records containing data for the total population|
|vaccination_fullyVaccPersons|Number of fully vaccinated persons|COVID19VaccPersons_v2.csv| type |age_group=total_population - records containing data for the total population|
|vaccination_partiallyVaccPersons|Number of persons that are partially vaccinated (difference between COVID19AtLeastOneDosePersons and COVID19FullyVaccPersons)|COVID19VaccPersons_v2.csv| type |age_group=total_population - records containing data for the total population|
|certificate_all|Sum of all COVID certificates issued.|COVID19Certificates.csv|        type_variant ||
|certificate_recovered| Issued COVID certificates for persons that have recovered from COVID-19.|COVID19Certificates.csv|        type_variant ||
|certificate_tested|Issued COVID certificates for persons with a negative test result.|COVID19Certificates.csv|        type_variant ||
|certificate_vacinated| Issued COVID certificates for vaccinated persons.|COVID19Certificates.csv|        type_variant ||
|hosp_total_icu_covid|Absolute number of ICU beds in use by COVID-19 patients.|COVID19HospCapacity_geoRegion|        ICU_Covid19Patients |type_variant=nfp Reported date is only valid for the current day, no forward propagation is done. Each record reflects the data reported for that specific day.|
|hosp_total_covid |Absolute number of beds in use by COVID-19 patients.|COVID19HospCapacity_geoRegion|        Total_Covid19Patients |type_variant=nfp Reported date is only valid for the current day, no forward propagation is done. Each record reflects the data reported for that specific day.|
|death|Absolute number of occurrences for this iso-week.|COVID19Death_geoRegion.|        entries ||


## Datensicherung
Test: Pos und Neg müssen in der Summe gleich Total sein

