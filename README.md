INT408 – USB Disk Image Forensic Analysis

A digital forensics investigation completed for the INT408: Digital Evidence Handling and Chain of Custody course using Kali Linux and industry-standard forensic tools.

Overview

This repository documents my analysis of a forensic USB disk image provided for the INT408 laboratory assignment.

The investigation focused on preserving evidence integrity, examining the NTFS file system, recovering deleted artifacts, identifying hidden or encoded data, performing data carving, and documenting the findings using accepted digital forensic procedures.

All analysis was conducted on a forensic image to ensure that the original evidence remained unchanged throughout the investigation.

Case Scenario

The laboratory exercise is based on a fictional investigation involving the Grand Monarch Hotel. Investigators recovered a USB flash drive believed to contain digital evidence related to the incident. The supplied forensic image served as the primary source of evidence for this analysis.

Objectives

The investigation included the following tasks:

Verify the integrity of the forensic image.
Analyze the partition table and file system.
Enumerate allocated and deleted files.
Recover deleted evidence.
Examine hidden and encoded content.
Perform file carving and metadata analysis.
Generate a forensic timeline.
Maintain proper evidence handling and chain of custody.
Produce a professional forensic report.
Tools Used
Kali Linux
The Sleuth Kit (mmls, fsstat, fls, icat, istat, mactime)
Foremost
Binwalk
Steghide
ExifTool
7-Zip
MD5 & SHA-1 Hash Utilities
Base64
Strings
Investigation Highlights

During this investigation, I successfully:

Verified the integrity of the forensic image using MD5 and SHA-1 hashes.
Identified the partition layout and NTFS file system.
Enumerated allocated and deleted files.
Recovered deleted Microsoft Word documents, text files, and images.
Decoded a Base64-encoded message recovered from a deleted text file.
Identified embedded data within a recovered JPEG image.
Performed data carving to recover additional artifacts.
Examined file metadata.
Generated a forensic timeline to support the investigation.
Documented all findings in a formal forensic report.
Repository Structure
INT408-USB-Forensic-Analysis/

 README.md
report/
 INT408_Forensic_Report.pdf

 screenshots/
 hash_verification.png
 partition_analysis.png
filesystem_analysis.png
 deleted_files.png
 file_recovery.png
 base64_decoding.png
binwalk_analysis.png
foremost_results.png
    timeline.png

 logs/
 hashes.txt
 bodyfile.txt
 timeline.csv

 recovered/
R5VUNDH.docx
R8BDGE1.jpg
RVMQAU9.txt
RYT9YUG.txt
Screenshots

The repository includes screenshots demonstrating each stage of the investigation.

Hash Verification
Partition Analysis
Deleted File Recovery




Report

The complete forensic report is available in the report directory.

INT408_Forensic_Report.pdf

Skills Demonstrated
Digital Forensics
Evidence Acquisition and Verification
Chain of Custody
NTFS File System Analysis
Deleted File Recovery
Data Carving
Metadata Analysis
Hidden Data Investigation
Timeline Analysis
Linux Command Line
Key Findings

The investigation resulted in the successful recovery and analysis of multiple deleted artifacts, including Microsoft Word documents, text files, and image files. A Base64-encoded message was decoded, embedded data was identified within a recovered JPEG image, and additional files were recovered through data carving. The investigation also included metadata examination and forensic timeline generation to support the analysis.


Name: ADEBAYO SURAJUDEEN OPEYEMI

Course: INT408 – Digital Evidence Handling and Chain of Custody

Institution: ICDFA

