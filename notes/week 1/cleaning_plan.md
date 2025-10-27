### 🔍 Observations from Raw Data:
1. Multiple header rows (Segment, Ship Mode).  
2. Empty cells scattered across columns.  
3. Duplicated “Total” columns (e.g., Consumer Total, Corporate Total, Home Office Total).  
4. Extra spaces and inconsistent column names.  
5. Data structure is not Easily understable.  

---

### 🧩 Cleaning Plan

| **Issue** | **Planned Fix** | **Excel Tool / Formula** |
|------------|-----------------|---------------------------|
| Multi-level headers | Remove top header rows and rename columns manually | Delete rows + Rename columns |
| Totals included in data | Delete “Total” rows/columns to avoid double-counting | Manual removal |
| Duplicates | Identify and remove duplicates | Data → Remove Duplicates |
| Data structure | Use pivot table to filter each segment |  add this data to data model |
---
