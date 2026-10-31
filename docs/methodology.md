# Technical Methodology

## 1. Android Device Management — Headwind MDM

### Objective
Explore centralized Android device management and understand how organizations manage enrolled devices and apply security policies.

### Activities Performed
- Accessed and explored the Headwind MDM management dashboard.
- Created and configured a device group.
- Enrolled an Android test device into the MDM environment.
- Reviewed device inventory and installed application information.
- Explored available remote device management options, including remote lock and wipe.
- Reviewed device configuration and security policy options.

### Learning Outcomes
- Understanding of Mobile Device Management (MDM).
- Familiarity with Android device enrollment workflows.
- Awareness of centralized device inventory and policy management.
- Understanding of remote device management capabilities.

## 2. Android Application Static Analysis — MobSF

### Objective
Explore static security analysis of an Android application package (APK) using MobSF.

### Tool
Mobile Security Framework (MobSF).

### Activities Performed
- Analyzed the AndroGoat Android application package.
- Reviewed application information and scan results.
- Examined exported activities, services, receivers, and providers.
- Explored the security analysis interface and available report sections.

### Observed Result
The documented MobSF dashboard displayed an application security score of 45/100.

This score is recorded as the tool's displayed result and should not be interpreted as a complete measure of application security.

### Learning Outcomes
- Introduction to Android APK static analysis.
- Familiarity with application components and security assessment reports.
- Awareness of potential mobile application security weaknesses.

## 3. Android Application Traffic Inspection — Burp Suite

### Objective
Understand how an intercepting proxy can be used to inspect HTTP requests during application security testing.

### Tool
Burp Suite Community Edition.

### Activities Performed
- Explored the Proxy and Intercept interface.
- Reviewed HTTP request history.
- Inspected request methods, URLs, and HTTP headers.
- Examined request information using the Inspector panel.

### Learning Outcomes
- Understanding of proxy-based HTTP traffic inspection.
- Familiarity with HTTP request structure and headers.
- Awareness of how application traffic can be examined during authorized security testing.

**Evidence limitation:** The included screenshot demonstrates a GET request to example.com. It is evidence of Burp Suite traffic inspection, not proof that this specific request originated from AndroGoat.

## 4. Overall Learning Outcomes

Through these internship activities, I gained practical exposure to:

- Android Mobile Device Management.
- Device enrollment and inventory management.
- Mobile application static analysis.
- HTTP request inspection using an intercepting proxy.
- Common mobile application security concepts.
- Security assessment tools and documentation practices.

## 5. Scope and Limitations

This repository documents the activities and observations recorded during the internship.

- The original testing environment is no longer available.
- The repository does not contain a reproducible MDM or Android testing lab.
- No custom application or security automation code was developed as part of the documented work.
- The documented screenshots represent selected evidence from the internship report.
- No vulnerability exploitation or remediation is claimed unless supported by documented evidence.

## 6. Security Disclaimer

All activities described in this project were conducted as part of a controlled cybersecurity learning environment.

Security testing tools must only be used on systems and applications for which appropriate authorization has been granted.
