# FileHashCheckerPS1
PowerShell script to calculate the checksum of a file using different algorithms (MD5, SHA1, SHA256, SHA512) 

## Description
This PowerShell script will prompt the user to provide the file path of a file, it will then prompt the user for the algorithm to be used and will provide a checksum/hash value that in turn can be checked against a known checksum/hash value for integrity/security.

## What is a Checksum?

A checksum is a value derived from a set of data that is used to detect errors during data transmission or storage. It is typically a simple mathematical calculation performed on the data, resulting in a fixed-size value. This value is then compared to a previously calculated checksum or transmitted checksum to verify the integrity of the data.

The purpose of a checksum is to ensure that data has not been corrupted or modified during its transmission or storage. When data is transmitted over a network or written to a storage medium, there is always a possibility of errors occurring due to noise, interference, or hardware/software issues. By comparing the calculated checksum with the expected checksum, it is possible to determine if the data has been altered in any way.

Checksums are widely used in various applications, including network protocols, file transfer protocols, error detection and correction algorithms, data integrity checks, and cryptographic algorithms. They provide a quick and efficient method for error detection, enabling the identification of corrupted or tampered data.

Commonly used checksum algorithms include cyclic redundancy check (CRC), message digest algorithms (such as MD5 and SHA-1), and cryptographic hash functions (such as SHA-256). The choice of checksum algorithm depends on the specific requirements of the application, including the desired level of error detection and the computational overhead involved.

## Why Check the Checksum of a File for Security

Checking the checksum of a file can help ensure its security in several ways:

1. **Data Integrity:** Verifying the checksum of a file allows you to confirm that the file has not been altered or corrupted during transmission or storage. If the calculated checksum matches the expected checksum, it provides a strong indication that the file has remained intact and has not been tampered with.

2. **Detection of Malicious Modifications:** By comparing the checksum of a file with the expected checksum, you can detect any unauthorized modifications made to the file. If the checksums do not match, it suggests that the file may have been maliciously altered, potentially indicating the presence of malware, unauthorized changes, or tampering.

3. **File Authenticity:** In some cases, a checksum can be used to verify the authenticity of a file. By comparing the checksum with a trusted source or a known checksum value provided by the file creator, you can confirm that the file has not been tampered with and originates from a trusted or verified source.

4. **Prevention of Data Corruption:** By identifying corrupted files through checksum verification, you can take necessary measures to rectify or replace them before they cause problems or propagate errors in systems or processes that rely on the file's integrity.

It's important to note that while checksum verification is a useful security measure, it is not a comprehensive solution on its own. It primarily helps with error detection and integrity verification. For stronger security, additional measures such as digital signatures, encryption, and secure file transfer protocols may be necessary depending on the specific security requirements of your application or use case.
