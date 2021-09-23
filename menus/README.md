# Here you can get a reference about the Utmstack menu structure update file

## Properties with '*' means that

### **Name** *
#### Name of the menu.

### **Url** 
#### Url of the menu. This property takes value only for menus with static urls. With static we refer to those urls that have no dependency with any other component.

### **Type** 
#### This property is required when the menu URL has dependencies on any other update component. Lets you know which component the menu url is related to. Only the following values are allowed:
- COMPLIANCE
- DASHBOARD
- PATTERN

### **Reference** 
####

### **Position** * 
####

### **IsActive** *
####

### **IsAction** *
####

### **Icon** 
####

### **Module** 
#### Name of the module to which this menu belongs. Only the next values are permmited:
- FILE_INTEGRITY
- VULNERABILITIES
- ASSET_MANAGEMENT
- AD_AUDIT
- O365
- AZURE
- AWS

### **Submenus** 
####

