# Release Information 

- **Version**: 1.0.0 
- **Certified**: No 
- **Publisher**: Fortinet 
- **Compatible Version**: FortiSOAR 7.4.0 and later 
 

# Overview 
FortiGuards labs observed critical level of exploitation attempts relating to security bypass vulnerabilities in Adobe ColdFusion. Successful exploitation could result in access of the ColdFusion Administrator endpoints.

The **Outbreak Response - Adobe ColdFusion Access Control Bypass Attack** solution pack works with the Threat Hunt rules in [Outbreak Response Framework](https://github.com/fortinet-fortisoar/solution-pack-outbreak-response-framework/blob/release/1.0.0/README.md#threat-hunt-rules) solution pack to conduct hunts that identify and help investigate potential Indicators of Compromise (IOCs) associated with this vulnerability within operational environments of *FortiSIEM*, *FortiAnalyzer*, *QRadar*, *Splunk*, and *Azure Log Analytics*.

The [FortiGuard Outbreak Page](https://www.fortiguard.com/outbreak-alert/adobe-coldfusion-access-bypass) contains information about the outbreak alert **Outbreak Response - Adobe ColdFusion Access Control Bypass Attack**.

## Background
Adobe ColdFusion is a commercial rapid web-application development computing platform to rapidly build, test and deploy web applications. Previously, in Aug 2023, we saw it being actively targeted by the attackers to exploit CVE-2023-26359, CVE-2023-26360 which lead to the release of an Outbreak Alert at that time, to read the full Outbreak visit: https://www.fortiguard.com/outbreak-alert/adobe-coldfusion-code-execution

## Announced:
Jul 19, 2023: Adobe released security updates for ColdFusion versionsâ€¯2023, 2021 andâ€¯2018 to fix (CVE-2023-38205).
https://helpx.adobe.com/security/products/coldfusion/apsb23-47.html
At the time of the release, Adobe mentioned that CVE-2023-38205 has been exploited in the wild and has been seen in limited attacks. Please note, CVE-2023-38205 was released as a fix for incomplete patch for CVE-2023-29398.

July 20, 2023: Adobe ColdFusion vulnerabilities (CVE-2023-38205, CVE-2023-29298) were added to CISA's KEV catalog.

Nov 28, 2023: CVE-2023-26347- Another Access Control Bypass vulnerability was announced and Adobe released patches for it.
https://helpx.adobe.com/ca/security/products/coldfusion/apsb23-52.html


## Latest Developments:
Jan 8, 2024: CVE-2023-38203- Adobe ColdFusion Deserialization of Untrusted Data Vulnerability, was added to CISA KEV list and has been seen to be actively exploited.

Jan 2024: FortiGuard Labs observed critical level of continued attacks on Adobe Coldfusion with IPS detections reaching upto 50,000+ unique detections. Users of Adobe ColdFusion are advised to apply patches as per vendor guidelines as soon as possible to mitigate any risk completely, if not already done.

# Next Steps

| [Installation](./docs/setup.md#installation) | [Configuration](./docs/setup.md#configuration) | [Usage](./docs/usage.md) | [Contents](./docs/contents.md) |
|----------------------------------------------|------------------------------------------------|--------------------------|--------------------------------|