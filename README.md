
Project Overview

This project demonstrates the analysis of phishing emails and highlights common phishing techniques used by attackers. The objective is to identify phishing indicators, analyze email headers, classify email risks, and provide security awareness guidelines to help users recognize and avoid phishing attacks.

The repository contains sample phishing emails, email header analysis, screenshots, and a detailed phishing detection report.

 Objectives

* Analyze phishing and legitimate email samples.
* Examine email headers and authentication results.
* Identify phishing indicators.
* Classify the risk associated with each email.
* Document findings in a professional report.
* Provide phishing prevention and awareness recommendations.



 Tools Used

The following tools were used during the analysis:

| Tool                                 | Purpose                                                                                                               |
| ------------------------------------ | --------------------------------------------------------------------------------------------------------------------- |
| Gmail                                | Sending and receiving sample emails for analysis.                                                                     |
| Gmail – Show Original                | Viewing complete email headers and authentication results.                                                            |
| Google Admin Toolbox – Messageheader | Analyzing email headers, SPF, DKIM, DMARC, and routing information.                                                   |
| MXToolbox Header Analyzer            | Verifying email authentication results and inspecting header information.                                             |                    
| GitHub                               | Storing project files and documentation.                                                                              |
| Microsoft Word / Canva               | Preparing and designing the final project report.                                                                     |



Analysis Approach

The following methodology was used to analyze each email:

1. Email Collection

Four sample emails were collected, consisting of three phishing emails and one legitimate business email.

 2. Email Header Analysis

The complete email headers were extracted using Gmail's **Show Original** feature. The following fields were examined:

* From
* Return-Path
* Reply-To
* SPF
* DKIM
* DMARC
* Received Chain

3. Sender Domain and Link Inspection

The sender's email domain was compared with the official domain of the organization it claimed to represent. Embedded hyperlinks were also reviewed to identify suspicious or spoofed domains.

4. Phishing Indicator Identification

Each email was examined for common phishing characteristics, including:

* Spoofed sender domains
* Generic greetings
* Urgent or threatening language
* Suspicious hyperlinks
* Unexpected attachments
* Requests for credentials or sensitive information

5. Risk Classification

Each email was classified according to its potential impact:

* Legitimate
* Medium Risk
* High Risk
* Critical Risk

### 6. Documentation

The findings were documented using screenshots, email header analysis, phishing indicators, and risk assessments to create a professional phishing detection report.

### 7. Awareness Recommendations

Best practices and preventive measures were included to educate users on identifying and avoiding phishing attacks.

---

# Repository Structure

```text
Phishing-Detection-Awareness/
│
├── README.md
├── Report/
│   └── Phishing_Detection_Awareness_Report.pdf
│
├── Sample_Emails/
│   ├── Phishing_Email_1.png
│   ├── Phishing_Email_2.png
│   ├── Phishing_Email_3.png
│   ├── Legitimate_Email.png
│   ├── Email_Header_1.txt
│   ├── Email_Header_2.txt
│   ├── Email_Header_3.txt
│   └── Legitimate_Header.txt
│
├── Screenshots/
│   ├── Gmail_Show_Original.png
│   ├── Header_Analysis_1.png
│   ├── Header_Analysis_2.png
│   └── Header_Analysis_3.png
│
└── Evidence/
    ├── Risk_Assessment.md
    └── Phishing_Indicators.md
```

---

# Conclusion

This project demonstrates a structured approach to phishing email analysis by combining email header inspection, sender domain verification, phishing indicator identification, and risk classification. The findings emphasize the importance of user awareness and proper email verification techniques in defending against phishing attacks.
