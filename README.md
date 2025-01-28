

# Keygen_manual_TestAssignment

1. Have Attached UI and API Test cases Excel sheet.
2. Have attached API basic collection for license management flow

# **Keygen: Basic Usage and Terminology**  

This document provides an overview of the basic functionality, key features, and terminology used in Keygen. It serves as a guide for developers and teams who wish to leverage Keygen for license management, machine tracking, and more.


## **What is Keygen?**  
Keygen is a software licensing and distribution platform designed to help developers manage software activations, entitlements, and machine tracking. It provides APIs to securely issue, validate, and manage licenses while tracking usage across devices.


### **Licenses**  
- **Definition:** Licenses represent entitlements for users or customers to access a product or service.  
- **Key Properties:**  
  - **Key:** A unique identifier for the license.  
  - **Policy:** The rules governing the license (e.g., expiration date, max activations).  
  - **Product:** The product associated with the license.  
  - **Expiration Date:** Specifies the license's validity period.  

### **Machines**  
- **Definition:** Machines represent the devices or systems where licenses are activated or used.  
- **Key Properties:**  
  - **Fingerprint:** A unique identifier for a device.  
  - **License:** Links the machine to a license.  
  - **Metadata:** Custom attributes for the machine (e.g., OS, platform type).  

### **Policies**  
- **Definition:** Policies define rules and constraints applied to licenses, such as activation limits, expiration dates, or usage restrictions.  
- **Examples:**  
  - **Maximum Activations:** Limits the number of devices per license.  
  - **Trial Periods:** Specifies the length of free usage.  

### **Users**  
- **Definition:** Users represent individuals or entities associated with licenses and machines.  
- **Key Properties:**  
  - **Email:** Identifies the user.  
  - **Role:** Specifies access privileges (e.g., admin, end-user).  

---

## **Keygen Features**  

- **License Management:** Create, update, validate, and revoke licenses.  
- **Machine Tracking:** Monitor devices associated with licenses.  
- **Policy Enforcement:** Automatically enforce activation limits, expiration dates, and trial rules.  
- **User Management:** Associate licenses and machines with specific users.  
- **APIs for Automation:** Comprehensive REST APIs to integrate licensing workflows into your application.  

---

## **Basic Operations**  

### **Managing Licenses**  
1. **Create a License:** Generate a license key, assign it to a product, and link it to a policy.  
2. **View License Details:** Access details such as expiration, policy, and activations.  
3. **Edit License:** Update properties like expiration date or associated product.  
4. **Delete License:** Remove a license from the system permanently.  

### **Managing Machines**  
1. **Create a Machine:** Register a device with a unique fingerprint and associate it with a license.  
2. **View Machine Details:** View metadata and license information for a specific machine.  
3. **Edit Machine:** Update metadata or reassociate it with a new license.  
4. **Delete Machine:** Remove a machine from the system.  

### **Managing Users**  
1. **Create a User:** Add a new user with a unique email address and role.  
2. **View User Details:** Review associated licenses, machines, and metadata.  
3. **Edit User:** Update user information such as email or role.  
4. **Delete User:** Remove a user and their associations.  
