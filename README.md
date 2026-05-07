# New_Repo_IT_360_Project

## Team Members
- Luke Gibson
- Christian Scott
- Badur Ibrahim

## Project Idea
Disk Image Metadata & Hashing Analyzer

Our Disk Image Metadata & Hashing Analyzer will be a Python-based digital forensics tool to help investigators verify the integrity and authenticity of digital evidence. It automates extraction of file metadata and the generation of cryptographic hashes (MD5, SHA-1, and SHA-256) from forensic disk images or directories of extracted evidence.

This tool reduces time and human error involved in manual evidence verification by collecting key forensic details such as file names, paths, sizes, and timestamps (creation, modification, accessed). It also generates hash values acting as digital fingerprints, allowing investigators to confirm that files haven't been altered during analysis.

Results are exported in formats such as CSV or JSON, making them suitable for forensic documentation, reporting, and chain-of-custody verification. The program operates in read-only mode to preserve forensic soundness and is built using libraries including os, pathlib, and hashlib.

This project demonstrates core digital forensics principles including evidence integrity, repeatability, and documentation, while also providing functions similar to professional forensic tools in a transparent and educational format.

To enhance the system, we will be adding an AI-based anomaly detection module using scikit-learn. This module will analyze extracted file metadata (like file size, timestamps, and file types) to identify unusual patterns that might indicate suspicious or tampered files. By applying a learning algorithm such as Isolation Forest, the system will automatically find anomalies without training data. This adds a layer of analysis to assist investigators in more effectively identifying evidence beyond standard metadata inspection.
