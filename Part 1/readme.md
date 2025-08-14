## 📊 Analysis Workflow

The notebook is divided into **5 sections**:

### **1. Getting to Know the Data**
- Listed all tables in the database.
- Previewed each table to understand available fields and data types.

### **2. Diving into Water Sources**
- Identified unique water source types.
- Counted how many of each type exist in the dataset.

### **3. Unpacking Visits to Water Sources**
- Investigated locations where people spend unusually long times fetching water (~8 hours).
- Linked visits to their corresponding water source types.

### **4. Assessing the Quality of Water Sources**
- Found sources with high visit counts and perfect quality scores.

### **5. Investigating Pollution Sources**
- Discovered inconsistencies in pollution records.
- Corrected mislabelled results and standardized descriptions.

---

## 🧠 Key Insights
- **Shared taps** were the only water source type with extremely long wait times (~8 hours).
- Several pollution entries were incorrectly labelled as "Clean" despite biological contamination.
- Standardizing text fields is crucial for reliable reporting and filtering.
