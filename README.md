# Digital Forensics Final Project – BlackEagle Investigation

## **Overview**

This project documents a full digital forensic investigation conducted by the Digital Forensics Unit at Al-Hussein Technical University. The investigation was launched to examine a damaged USB drive and a suspect PC linked to the "BlackEagle" group. The objective was to uncover hidden data and recover evidence that could prevent an anticipated criminal activity.

## **Case Information**

- **Case Name:** BlackEagle Investigation  
- **Case Number:** CH-2024-1212  
- **Investigator:** Farouq Hassan  
- **Location:** Digital Forensics Lab, HTU  
- **Search Warrant ID:** DF-2024-203456  
- **Start Date:** June 7, 2024  

## **Objectives**

- Recover hidden or corrupted data from a USB drive and suspect PC  
- Validate the integrity of all digital evidence  
- Discover time-sensitive intelligence related to a planned incident

## **Tools Used**

| Tool               | Version   | Purpose                                           |
|--------------------|-----------|---------------------------------------------------|
| FTK Imager         | 4.7.1.2   | Imaging and mounting digital storage devices      |
| HxD Hex Editor     | 2.5.0.0   | Low-level data inspection and manual recovery     |
| HashMyFiles        | 2.4.4.0   | Generating and verifying hash values              |
| JumpListExplorer   | 2.0.0.0   | Jump List data analysis on Windows systems        |
| File Signature DB  | -         | File signature validation (Gary Kessler’s list)   |

## **Summary of Findings**

### **USB Drive**
- Initially unreadable using FTK Imager  
- Manual recovery performed with HxD  
- Located and extracted NTFS mirror, repaired file system  
- Successfully recovered documents and images  
- Verified all recovered files with hashes  

### **Suspect PC**
- Forensic image created with write-blocker  
- Key files discovered: `cage.png`, `cage3.png`, `untitled0.docx`  
- `cage3.png` contained embedded DOCX file with hidden white-on-white text  
- Message revealed a planned meeting on **June 11, 2024 at 12 PM, KHBP**

## **Chain of Custody and Evidence Handling**

- USB and PC were bagged, labeled, and logged  
- Hash values generated before and after imaging  
- Forensic images stored securely using Tableau TX1  
- Actions and handlers recorded in chain of custody form  

## **Methodology**

The investigation followed **Rodney McKemmish’s Four-Step Model**:
1. **Identification** – Devices identified and tagged  
2. **Preservation** – Write-blockers used, original data untouched  
3. **Analysis** – Hex analysis, signature checks, data carving  
4. **Presentation** – Report with visual aids and detailed logs

## **Legal and Ethical Compliance**

- Search warrant obtained before evidence seizure  
- CCPA and GDPR data privacy compliance enforced  
- Confidentiality, non-discrimination, and data minimization upheld  
- Chain of custody and admissibility standards followed

## **Tool Comparison: Autopsy vs FTK Imager**

| Feature             | Autopsy                              | FTK Imager                         |
|---------------------|---------------------------------------|-------------------------------------|
| Type                | Full forensic suite                   | Imaging and preview tool            |
| Use Case            | Deep analysis and reporting           | Initial acquisition and validation  |
| Learning Curve      | Moderate                              | Easy                                |
| Strength            | Timeline, email, web artifacts        | Imaging accuracy and hash checking  |
| Limitation          | Resource intensive                    | Limited analysis capability         |

## **Recommendations for Future Investigations**

- Use automated recovery and AI-powered analysis tools  
- Standardize templates for documentation and reporting  
- Implement digital chain-of-custody systems  
- Train investigators continuously on modern threats  
- Maintain a secured forensic lab with proper access control  

## **Conclusion**

This project successfully demonstrated end-to-end digital forensic practice, including data recovery, low-level hex editing, and hidden message extraction. The evidence led to actionable intelligence that could disrupt a planned criminal act. The investigation adhered to industry best practices, legal standards, and ethical responsibilities.

## **Author**

**Farouq Hassan**  
Spring 2024  
HTU – Digital Forensics  
Instructor: Dr. Safaa Hriez
