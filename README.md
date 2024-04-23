# SIEM_HoneyPot
### **Overview**

This project aims to demonstrate the integration of a honey pot with Microsoft Sentinel, a cloud-native security information and event management (SIEM) solution. The integration includes utilizing PowerShell scripts for data collection and analysis, with the visualization of attack locations on a heatmap using data from https://ipgeolocation.io/.

### **Features**

**Honey Pot Setup**: Guide on setting up a honey pot environment to attract and monitor malicious activities.
**Azure Sentinel Integration**: Instructions for integrating the honey pot data with Microsoft Sentinel for centralized monitoring and analysis.
**PowerShell Scripts**: Custom scripts for collecting honey pot data, formatting it for Microsoft Sentinel, and automating data ingestion.
**Attack Location Visualization**: Utilizing IP geolocation data from https://ipgeolocation.io/ to display attack locations on a heatmap for easy visualization. Created through Microsoft Sentinel's Workbook utilities.

### Query used to visualise the failed RDP logs.
![image](https://github.com/BaileyMele/SIEM_HoneyPot/assets/100643495/65b8f9ad-1c49-4d49-b313-5a8e642aff64)


### Map preview with location data.
![image](https://github.com/BaileyMele/SIEM_HoneyPot/assets/100643495/387197be-8028-4650-8f17-c715133725f2)

### Acknowledgments The IP geolocation data is obtained from https://ipgeolocation.io/.
![image](https://github.com/BaileyMele/SIEM_HoneyPot/assets/100643495/9a43e33f-8d8c-4da1-85b9-6a738c132538)

### Powershell script -> Pulls failed logs and uses IP to grab geolocation data from the api. Stores the logs locally in .txt file
![image](https://github.com/BaileyMele/SIEM_HoneyPot/assets/100643495/baea62c2-8d00-4b0d-ad48-e965ccf2e392)

Powershell Script Courtesy of [Josh](https://github.com/joshmadakor1).
