# From Tables to Tabs: Plant, Sales, Purchasing in One RAP App (Simplest Example)

A minimal **ABAP RAP + Fiori Elements (List Report/Object Page)** app that turns classic SAP tables into a clean Object Page with **4 tabs**:
**Overview**, **Plant & Stock**, **Sales Org Data**, **Purchasing/Sourcing**.  
Includes a classic-style **Material Value Help** (MAKT/MARA) with **Language** and **Material Type** filters.

---

## ✨ Features
- Root entity: `ZI_MATERIAL` (MARA + MAKT)
- Tabs via 1:N associations:
  - `ZI_MAT_PLANT_STOCK` (MARC/MARD)
  - `ZI_MAT_SALES_ORG`   (MVKE)
  - `ZI_MAT_PURCH`       (EINA/EINE)
- **Value Help**: `ZVH_MaterialF4` (MAKT+MARA), optional `ZVH_MaterialType` (T134/T134T)
- Proper **unit/currency semantics** and clean **Metadata Extensions (DDLX)**
- Single **OData V2** service: `ZUI_MAT_SRV`

