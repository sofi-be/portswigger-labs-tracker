# PortSwigger Web Security Academy - Solved Labs

![Total Labs Solved](https://img.shields.io/badge/Total_Labs_Solved-95-blue)
![Last Updated](https://img.shields.io/badge/Last_Updated-2026--09--3-yellow)
![Level](https://img.shields.io/badge/Level-NEWBIE-green)
![Completed](https://img.shields.io/badge/Completed-19%25-magenta)

This file tracks my progress through [PortSwigger Web Security Academy](https://portswigger.net/web-security) labs. I focus on web app pentesting, documenting key labs as full writeups (linked below) and logging all solves here for reference. Full writeups are reserved for first-time techniques, complex exploits, or custom tools.

## Level progress

* **Apprentice:** 35 of 61
* **Practitioner:** 55 of 174
* **Expert:** 5 of 39

## Categories Covered

* **Authentication vulnerabilities:** 11/14 lab
* **SQL injection:** 13/18 lab
* **Access control:** 13/13 lab
* **Path traversal:** 6/6 lab
* **OS command injection:** 4/5 lab
* **File upload vulnerabilities:** 6/7 lab
* **Cross-site scripting:** 20/30 lab
* **Race conditions:** 2/6 lab
* **Server-side request forgery (SSRF):** 2/6 lab
* **API testing:** 2/5 lab
* **Information disclosure:** 3/5 lab
* **Cross-site request forgery :** 3/11 lab
*  **Server-side template injection:** 6/7 lab

## Notes

* **Full Writeups:** Only for significant labs (e.g., chained exploits or scripted solutions). See `platforms/portswigger/` for details.
* **Tools Used:** Burp Suite

## How to Read

### Columns:
* **No :** Sequential lab number.
* **Date :** When I solved it (YYYY-MM-DD).
* **Topic :** Vulnerability category (e.g., API Testing, XSS).
* **Lab Title :** Exact name from PortSwigger.
* **Difficulty :** Apprentice, Practitioner, or Expert.
* **Writeup Link :** Links to full writeup (if exists) or "N/A" for quick solves.

---

## Solved Labs

| No | Date | Topic | Lab Title | Difficulty | Writeup Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 2026-06-16 | SQL Injection| SQL injection vulnerability in WHERE clause allowing retrieval of hidden data|APPRENTICE | N/A |
| 2 | 2026-06-16 | SQL Injection| SQL injection vulnerability allowing login bypass| APPRENTICE| N/A|
| 3 | 2026-06-17 | SQL Injection|SQL injection UNION attack, determining the number of columns returned by the query | PRACTITIONER| N/A |
| 4 | 2026-06-17| SQL Injection| SQL injection UNION attack, finding a column containing text| PRACTITIONER| N/A |
| 5 | 2026-06-17 | SQL Injection|SQL injection UNION attack, retrieving data from other tables| PRACTITIONER| N/A |
| 6 | 2026-06-17 | SQL Injection| SQL injection UNION attack, retrieving multiple values in a single column| PRACTITIONER| N/A |
| 7 | 2026-06-19 |SQL Injection | Blind SQL injection with conditional responses|PRACTITIONER | N/A |
| 8 | 2026-06-19 | SQL Injection| Blind SQL injection with conditional errors| PRACTITIONER| N/A |
|9|2026-06-20|SQL Injection|Blind SQL injection with time delays|PRACTITIONER|N/A|
|10|2026-06-20|SQL Injection|Visible error-based SQL injection|PRACTITIONER|N/A|
|11|2026-06-20|SQL Injection|SQL injection attack, querying the database type and version on Oracle|PRACTITIONER|N/A|
|12|2026-06-20|SQL Injection|SQL injection attack, querying the database type and version on MySQL and Microsoft|PRACTITIONER|N/A|
|13|2026-06-20|SQL Injection|SQL injection attack, listing the database contents on non-Oracle databases|PRACTITIONER|N/A|
|14|2026-06-24|Authentication vulnerabilities|Username enumeration via subtly different responses|PRACTITIONER|N/A|
|15|2026-06-24|Authentication vulnerabilities|Username enumeration via different responses|Apprentice|N/A|
|16|2026-06-25|Authentication vulnerabilities|Broken brute-force protection, IP block|PRACTITIONER|N/A|
|17|2026-06-25|Authentication vulnerabilities|Username enumeration via account lock|PRACTITIONER|N/A|
|18|2026-06-26|Authentication vulnerabilities|2FA simple bypass|Apprentice|N/A|
|19|2026-06-26|Authentication vulnerabilities|Password reset broken logic|Apprentice|N/A|
|20|2026-06-26|Authentication vulnerabilities|Brute-forcing a stay-logged-in cookie|PRACTITIONER|N/A|
|21|2026-06-26|Authentication vulnerabilities|Offline password cracking|PRACTITIONER|N/A|
|22|2026-06-26|Authentication vulnerabilities|Password reset poisoning via middleware|PRACTITIONER|N/A|
|23|2026-06-26|Authentication vulnerabilities|Password brute-force via password change|PRACTITIONER|N/A|
|24|2026-07-01|Path traversal|File path traversal, simple case|Apprentice|N/A|
|25|2026-07-01|Path traversal|File path traversal, traversal sequences blocked with absolute path bypass|PRACTITIONER|N/A|
|26|2026-07-01|Path traversal|File path traversal, traversal sequences blocked with absolute path bypass|PRACTITIONER|N/A|
|27|2026-07-02|Path traversal|File path traversal, traversal sequences stripped with superfluous URL-decode|PRACTITIONER|N/A|
|28|2026-07-02|Path traversal|File path traversal, validation of start of path|PRACTITIONERN/A|
|29|2026-07-02|Path traversal|File path traversal, validation of file extension with null byte bypass|PRACTITIONER|N/A|
|30|2026-07-03|OS command injection|OS command injection, simple case|Apprentice|N/A|
|31|2026-07-03|OS command injection|Blind OS command injection with time delays|PRACTITIONER|N/A|
|32|2026-07-04|OS command injection|Blind OS command injection with output redirection|PRACTITIONER|N/A|
|33|2026-07-04|OS command injection|Blind OS command injection with out-of-band interaction|PRACTITIONER|N/A|
|34|2026-07-04|Access control|Unprotected admin functionality|Apprentice|N/A|
|35|2026-07-04|Access control|Unprotected admin functionality with unpredictable URL|Apprentice|N/A|
|36|2026-07-04|Access control|User role controlled by request parameter|Apprentice|N/A|
|37|2026-07-10|Access control|URL-based access control can be circumvented|PRACTITIONER|N/A|
|38|2026-07-10|Access control|User role can be modified in user profile|Apprentice|N/A|
|39|2026-07-10|Access control|User ID controlled by request parameter |Apprentice|N/A|
|40|2026-07-10|Access control|User ID controlled by request parameter, with unpredictable user IDs|Apprentice|N/A|
|41|2026-07-10|Access control|User ID controlled by request parameter with data leakage in redirect |Apprentice|N/A|
|42|2026-07-10|Access control|User ID controlled by request parameter with password disclosure|Apprentice|N/A|
|43|2026-07-10|Access control|Insecure direct object references|Apprentice|N/A|
|44|2026-07-11|Access control|Method-based access control can be circumvented|PRACTITIONER|N/A|
|45|2026-07-11|Access control|Multi-step process with no access control on one step|PRACTITIONER|N/A|
|46|2026-07-11|Access control|Referer-based access control |PRACTITIONER|N/A|
|47|2026-07-15|File upload vulnerabilities|Remote code execution via web shell upload|Apprentice|N/A|
|48|2026-07-15|File upload vulnerabilities|Web shell upload via Content-Type restriction bypass|Apprentice|N/A|
|49|2026-07-15|File upload vulnerabilities|Web shell upload via path traversal|PRACTITIONER|N/A|
|50|2026-07-17|File upload vulnerabilities|Web shell upload via obfuscated file extension|PRACTITIONER|N/A|
|51|2026-07-17|File upload vulnerabilities|Remote code execution via polyglot web shell upload|PRACTITIONER|N/A|
|52|2026-07-17|File upload vulnerabilities|Web shell upload via race condition|EXPERT|N/A|
|53|2026-07-19|Cross-site scripting|Reflected XSS into HTML context with nothing encoded|Apprentice|N/A|
|54|2026-07-19|Cross-site scripting|Stored XSS into HTML context with nothing encoded|Apprentice|N/A|
|55|2026-07-19|Cross-site scripting|DOM XSS in document.write sink using source location.search|Apprentice|N/A|
|56|2026-07-19|Authentication vulnerabilities|Broken brute-force protection, multiple credentials per request|Expert|N/A|
|57|2026-07-00|Cross-site scripting|DOM XSS in innerHTML sink using source location.search
|Apprentice|N/A|
|58|2026-07-00|Cross-site scripting|DOM XSS in jQuery anchor href attribute sink using location.search source|Apprentice|N/A|
|59|2026-07-00|Race conditions|Limit overrun race conditions|Apprentice|N/A|
|60|2026-07-00|Race conditions|Multi-endpoint race conditions|PRACTITIONER|N/A|
|61|2026-07-25|Cross-site scripting|DOM XSS in jQuery selector sink using a hashchange event|Apprentice|N/A|
|62|2026-07-25|Cross-site scripting|Reflected XSS into attribute with angle brackets HTML-encoded|Apprentice|N/A|
|63|2026-07-25|Cross-site scripting|Stored XSS into anchor href attribute with double quotes HTML-encoded|Apprentice|N/A|
|64|2026-07-25|Cross-site scripting|Reflected XSS into a JavaScript string with angle brackets HTML encoded|Apprentice|N/A|
|65|2026-07-31|Server-side request forgery (SSRF)|Basic SSRF against the local server|Apprentice|N/A|
|66|2026-07-31|Server-side request forgery (SSRF)|Basic SSRF against another back-end system|Apprentice|N/A|
|67|2026-07-31|Cross-site scripting|DOM XSS in document.write sink using source location.search inside a select element|PRACTITIONER|N/A|
|68|2026-07-31|Cross-site scripting|DOM XSS in AngularJS expression with angle brackets and double quotes HTML-encoded|PRACTITIONER|N/A|
|69|2026-08-31|Cross-site scripting|Reflected DOM XSS|PRACTITIONER|N/A|
|70|2026-08-31|Cross-site scripting|Stored DOM XSS|PRACTITIONER|N/A|
|71|2026-08-07|Information disclosure|Information disclosure in error messages|Apprentice|N/A|
|72|2026-08-07|Information disclosure|Information disclosure on debug page|Apprentice|N/A|
|73|2026-08-07|Information disclosure|Source code disclosure via backup files|Apprentice|N/A|
|74|2026-08-07|API testing|Exploiting an API endpoint using documentation|Apprentice|N/A|
|75|2026-08-07|API testing|Finding and exploiting an unused API endpoint|PRACTITIONER|N/A|
|76|2026-08-13|Cross-site scripting|Reflected XSS into HTML context with most tags and attributes blocked|PRACTITIONER|N/A|
|77|2026-08-13|Cross-site scripting|Reflected XSS into HTML context with all tags blocked except custom ones|PRACTITIONER|N/A|
|78|2026-08-13|Cross-site scripting|Reflected XSS with some SVG markup allowed|PRACTITIONER|N/A|
|79|2026-08-27|Cross-site request forgery |CSRF vulnerability with no defenses|Apprentice|N/A|
|80|2026-08-27|Cross-site request forgery |CSRF where token validation depends on request method|PRACTITIONER|N/A|
|81|2026-08-00|Cross-site request forgery |CSRF where token validation depends on token being present|PRACTITIONER|N/A|
|82|2026-08-00|Cross-site scripting |Reflected XSS in canonical link tag|PRACTITIONER|N/A|
|83|2026-08-00|Cross-site scripting|Reflected XSS into a JavaScript string with single quote and backslash escaped|PRACTITIONER|N/A|
|84|2026-08-00|Cross-site scripting|Reflected XSS into a JavaScript string with angle brackets and double quotes HTML-encoded and single quotes escaped|PRACTITIONER|N/A|
|85|2026-08-00|Cross-site scripting|Stored XSS into onclick event with angle brackets and double quotes HTML-encoded and single quotes and backslash escaped|PRACTITIONER|N/A|
|86|2026-08-00|Cross-site scripting|Reflected XSS into a template literal with angle brackets, single, double quotes, backslash and backticks Unicode-escaped|PRACTITIONER|N/A|
|87|2026-08-00|Cross-site scripting|Exploiting XSS to bypass CSRF defenses|PRACTITIONER|N/A|
|88|2026-08-00|Cross-site scripting|Reflected XSS with AngularJS sandbox escape without strings|EXPERT|N/A|
|89|2026-08-00|Cross-site scripting|Reflected XSS with AngularJS sandbox escape and CSP|EXPERT|N/A|
|90|2026-09-00|Server-side template injection|Basic server-side template injection|PRACTITIONER|N/A|
|91|2026-09-00|Server-side template injection|Basic server-side template injection (code context)|PRACTITIONER|N/A|
|92|2026-09-00|Server-side template injection|Server-side template injection using documentation|PRACTITIONER|N/A|
|93|2026-09-00|Server-side template injection|Server-side template injection in an unknown language with a documented exploit|PRACTITIONER|N/A|
|94|2026-09-00|Server-side template injection|Server-side template injection with information disclosure via user-supplied objects|PRACTITIONER|N/A|
|95|2026-09-00|Server-side template injection|Server-side template injection in a sandboxed environment|EXPERT|N/A|
|96|2026-09-00||||N/A|
|97|2026-09-00||||N/A|
|98|2026-09-00||||N/A|
