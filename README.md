# CIS-Benchmark-Implementation-on-Windows-Server-2022


## Objective
The objective of this project was to manually implement CIS Benchmark recommendations to improve the security of a Windows Server 2022 system.

In this project, I reviewed the default security settings, identified weak configurations, applied recommended security policies, and confirmed that the system continued to function normally after the changes.This project helped me to understand how security baselines are applied in real environments and how small configuration changes can significantly improve system security. 

### Skills Learned

- Learned how to use CIS Benchmarks to secure a Windows Server system
- Understood how weak default settings can create security risks
- Gained experience in documenting security changes and findings clearly
- Learned how to manually apply security settings using Local Security Policy

### Tools Used


- **Windows Server 2022** (Virtual Machine) for testing and applying security settings
- **CIS Benchmark** for Windows Server 2022 for security guidelines and recommendations
- **Local Security Policy** for configuring password and account lockout settings
- **Microsoft Word** for documenting findings and changes

## Steps



### 1. Setting up the Server
First, I created a Windows Server 2022 virtual machine.
I used this server as a standalone system to test and apply security settings safely.

### 2. Checking Default Security Settings
Before making any changes, I checked the default password and account lockout policies.
I noticed that many security settings were weak or not properly configured, such as low password requirements and high lockout limits.

### 3.Reviewing CIS Benchmark Recommendations
Next, I went through the CIS Benchmark for Windows Server 2022.
I focused mainly on account policies, especially password policies and account lockout rules, and compared them with the current system settings.

### 4. Applying Security Changes
After identifying the gaps, I manually applied the recommended settings using Local Security Policy.
This included increasing password length, enabling password complexity, and tightening account lockout rules.

### 5. Before and After Comparison
I took screenshots before and after applying the CIS recommendations to clearly show the changes made to the system.

#### Before applying CIS Benchmark settings:
##### Weak password policy:
![Weak password policy](https://github.com/rayifck/CIS-Benchmark-Implementation-on-Windows-Server-2022/blob/main/before-password-policy.png)

##### High account lockout threshold:
![High account lockout threshold](https://github.com/rayifck/CIS-Benchmark-Implementation-on-Windows-Server-2022/blob/main/before-account-lockout.png)




#### After applying CIS settings:

##### Strong password policy:
![Strong password policy](https://github.com/rayifck/CIS-Benchmark-Implementation-on-Windows-Server-2022/blob/main/after-password-policy.png)


##### Account lockout threshold reduced:
![Account lockout threshold reduced](https://github.com/rayifck/CIS-Benchmark-Implementation-on-Windows-Server-2022/blob/main/after-account-lockout.png)

### 6. Verifying the Changes
After applying the changes, I verified that the settings were updated correctly.
I also tested user login to make sure the system continued to work without issues.

### 7. Documentation
Finally, I documented all changes, including before and after values, screenshots, and challenges faced.
The report was prepared using Microsoft Word.

## Project Report
The detailed project report is available below. It includes policy comparisons, screenshots, and challenges faced during the implementation.


📄 **CIS Benchmark Implementation Report (PDF)**  
![View Report](https://github.com/rayifck/CIS-Benchmark-Implementation-on-Windows-Server-2022/blob/main/report/CIS%20Benchmark%20Implementation%20Report.pdf)






