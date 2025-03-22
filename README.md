# Java App X
This Java app is designed to test a lot of stuffs like
- **Git** (committing, rebasing, reverting history, bisect etc.)  
- **Property file parsing** for configs & stuff
- **Ignoring files in Git**  
- **CSV file parsing** parsing data  
- **Manual testing** just saw raw test code with ansii colors  
- **Writing scalable and maintainable Java code**  
- **And much more...**  

---

## **Requirements**  

### **Config File (app.property)**  
The application depends on a **property file** for configuration.  

- You must create an `app.property` file in the **root directory** of the project.  
- It should contain the following key-value pairs:  

```properties
# Test Settings
test.isTestEnabled=true
test.isAdvancedTestEnabled=true
test.canPrintTestLogs=true

# CSV Configuration
csv.path=users.csv
csv.filename=users.csv
```

---

### **CSV File (users.csv) - User Data**  
The application processes a **CSV file** containing user data.  

#### **CSV Requirements**  
- The CSV file must be named **`users.csv`** and placed in the **root directory**.  
- It must contain **three fields** in the following order:  
  1. `name` (Full name)  
  2. `age` (Age in years)  
  3. `gender` (Male/Female)  
- The values **must not be empty**.  
- The file follows a simple format, parsed using a **custom-built fast CSV parser** (it's just does the job). Future updates may integrate a dedicated parsing library.  

#### **📌 Sample CSV File**
```csv
name,age,gender
John Doe,2,Male
Jane Smith,19,Female
Alex Meyer,22,Male
Emily Davis,28,Female
Michael Brown,35,Male
```

---

### **Todo**  
**Planned Enhancements:**  
- Use a **standard CSV parsing library** (e.g., OpenCSV) instead of a custom parser.  
- Improve **error handling** for missing or incorrect values.  

