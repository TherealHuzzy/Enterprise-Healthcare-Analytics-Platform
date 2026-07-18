# Enterprise Healthcare Data Warehouse

## Fact Tables

FactEncounter
- Grain: One row per patient encounter.

FactProcedure
- Grain: One row per procedure performed.

FactMedication
- Grain: One row per medication prescribed/administered.

FactObservation
- Grain: One row per clinical observation.

FactCondition
- Grain: One row per diagnosis.

## Dimensions

DimPatient
- Grain: One row per patient.

DimProvider
- Grain: One row per provider.

DimOrganization
- Grain: One row per organization.

DimDate
- Grain: One row per calendar day.
