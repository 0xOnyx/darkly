# Darkly - Security Write-up

This project contains a detailed analysis of vulnerabilities found in the Darly web application, a web security exercise.

## 🎯 Objective

The objective of this project is to identify and exploit various security vulnerabilities in a web application while proposing solutions to fix them.

## 📋 List of Exploits

1. [Hidden Email Exploit](#1-hidden-email-exploit)
2. [XSS via Feedback Form](#2-xss-via-feedback-form)
3. [File Upload Bypass](#3-file-upload-bypass)
4. [HTTP Header Manipulation](#4-http-header-manipulation)
5. [SQL Injection](#5-sql-injection)
6. [Image Metadata Extraction](#6-image-metadata-extraction)
7. [Cookie Manipulation](#7-cookie-manipulation)
8. [Directory Traversal](#8-directory-traversal)
9. [Open Redirect](#9-open-redirect)
10. [Robots.txt Information Disclosure](#10-robotstxt-information-disclosure)
11. [Media Source XSS](#11-media-source-xss)
12. [Survey Form Manipulation](#12-survey-form-manipulation)
13. [Email Recovery Exploit](#13-email-recovery-exploit)
14. [Hidden Directory Crawling](#14-hidden-directory-crawling)
15. [Login Brute Force](#15-login-brute-force)

## 🛠️ Prerequisites

- Python 3.x
- PHP 7.4 or higher
- MySQL 5.7 or higher
- Apache/Nginx web server
- Modern web browser with developer tools
- cURL

## 🔍 Usage

Each exploit is documented in the `exploits.md` file. To run the Python scripts:

```bash
python scripts/crawler.py  # For directory crawling exploit
python scripts/bruteforce.py  # For login brute force exploit
```

## 🔒 Security Measures Implemented

1. Input Validation
   - Server-side validation for all user inputs
   - SQL injection prevention using prepared statements
   - XSS prevention through proper escaping

2. Authentication & Authorization
   - Secure session management
   - Role-based access control
   - Multi-factor authentication support

3. File Security
   - Secure file upload handling
   - MIME type validation
   - Malware scanning

4. Data Protection
   - Secure password hashing
   - Encrypted sensitive data
   - Secure cookie handling

5. Infrastructure Security
   - HTTPS enforcement
   - Directory traversal prevention
   - Secure redirect handling

## ⚠️ Warning

This project is for educational purposes only. Do not use these exploits on systems without authorization.

## 📝 License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## 📚 Resources

- [OWASP Top 10](https://owasp.org/www-project-top-ten/)
- [Web Security Academy](https://portswigger.net/web-security)
- [HackTheBox](https://www.hackthebox.com/)
- [PHP Security Guide](https://phpsecurity.readthedocs.io/en/latest/)
- [MySQL Security Best Practices](https://dev.mysql.com/doc/refman/8.0/en/security.html)

## 🙏 Acknowledgments

- Security testing team
- Contributors
- Open source community
- OWASP community
- All security researchers who contributed to this project
