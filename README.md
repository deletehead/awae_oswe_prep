# Advanced Web Attacks & Exploitation

All efforts for the AWAE course and preparation for the Offensive Security Web Expert (OSWE) exam.

## Study Strategy
 * Several rounds of course content
 * First round:
   * Watch videos
   * Read text and take good notes
   * Complete the main exercises
 * Second round:
   * Watch videos again
   * Read text and take more notes as-needed
   * Craft your own tools and scripts in a language other than python
   * Complete exercises AND all extra mile exercises
 * Further study:
   * Find interesting vulns in open source software, find the vuln from scratch and analyze
     * Analyze APKs for Android apps. Take 8 hours and analyze several each, tryna find vulns as if you're mid-test and have a time limit to find exploit chains
     * Find interesting vulns in OSS. 
       * Use vuln apps first to help develop custom regex tools for SAST: Webgoat (Java), JuiceShop (JavaScript), Mutillidae (PHP), .NETGoat (C#)
       * Check out an app in each relevant language that may not have had any security review done. Try to find some vulns and get some CVEs!! 
         * Check for the main suspects as taught in the course for each app, timebox it, and move on to another one. 
       * Make sure to pay attn to app architecture, request routing, etc in each language:
         * [ ] Java
         * [ ] JavaScript (node.js)
         * [ ] PHP
         * [ ] C#/.NET
   * HackTheBox and CTFs (see wetw0rk's prep guide)
     * SecureCodeWarrior (see bookmark in AWAE)
   * Codecademy courses
     * [x] Java
     * [x] JavaScript
     * [x] PHP
     * [x] C#

## Course Completion
Taken from publicly-available syllabus.
 * [x] 1. Introduction
   * [x] Videos
   * [x] Read/Notes
 * [x] 2. Tools & Methodologies
   * [x] Videos
   * [x] Read/Notes
   * [x] 2.1.5 Exercise - Web Inspection
   * [x] 2.2.1 Exercise - Python Requests
   * [x] 2.3.3 Exercise - Decompilation
 * [ ] 3. Atmail Mail Server Appliance: from XSS to RCE
   * [x] Videos
   * [x] Read/Notes
   * [x] 3.3.1 Exercise - Vuln Discovery
   * [x] 3.4.1 Exercise - Session Hijack
   * [x] 3.5.4 Exercise - Session Riding
   * [x] 3.5.5 Extra Mile - Session Riding
   * [x] 3.6.5 Exercise - globalsaveAction Vuln Analysis
   * [x] 3.6.7 Exercise - Make it fully automagical
   * [x] 3.6.8 Extra Mile
   * [ ] 3.6.8 Extra Mile - Also see if you can background it completely
 * [x] 4. ATutor Auth Bypass and RCE
   * [x] Videos
   * [x] Read/Notes
   * [x] 4.3.1 Exercise - Vuln Discovery
   * [x] 4.6.3 Exercise - Data Exfil
   * [x] 4.6.4 Extra Mile - Data Exfil
   * [x] 4.7.1 Exercise - ATutor Auth
   * [x] 4.7.2 Extra Mile - ATutor Auth
   * [x] 4.8.1 Exercise - ATutor Auth
   * [x] 4.8.2 Extra Mile - ATutor Auth
   * [x] 4.9.1 Exercise - File Upload
   * [x] 4.10.5 Exercise - RCE
   * [x] 4.10.6 Extra Mile - RCE
 * [x] 5. ATutor LMS Type Juggling Vuln
   * [x] Videos
   * [x] Read/Notes
   * [x] 5.4.1 Exercise - String Conversion
   * [x] 5.6.3 Exercise - Loose Comparison
   * [x] 5.6.4 Extra Mile - Loose Comparison
 * [ ] 6. ManageEngine Applications Manager AMUserResourcesSyncServlet SQL Injection RCE
   * [x] Videos
   * [x] Read/Notes
   * [x] 6.3.6 Exercise - Vuln Discovery
   * [x] 6.5.1 Exercise - Blind Bats
   * [x] 6.6.1 Exercise - Access FS
   * [x] 6.6.3 Exercise - VBS file [!! Need to do the batch! Got the reverse shell... !!]
   * [ ] 6.6.4 Extra Mile - Shell via JSP
   * [x] 6.7.4 Exercise - PostgreSQL Extensions
   * [x] 6.8.1 Exercise - UDF Reverse Shell
   * [x] 6.9.3 Exercise - Moar Shells
   * [ ] 6.9.4 Extra Mile - Moar Shells
 * [ ] 7. Bassmaster NodeJS Arbitrary JavaScript Injection Vulnerability
   * [x] Videos
   * [x] Read/Notes
   * [x] 7.6.1 Exercise - RevShell
   * [ ] 7.6.2 Extra Mile - RevShell
 * [ ] 8. DotNetNuke Deserialization RCE
   * [x] Videos
   * [x] Read/Notes
   * [x] 8.4.3 Exercise - Serialization Basics
   * [x] 8.4.5 Exercise - Serialization Basics
   * [x] 8.4.7 Exercise - Serialization Basics
   * [x] 8.5.3 Exercise - DNN Vuln Analysis
   * [x] 8.6.4 Exercise - Payload Options
   * [x] 8.6.7 Exercise - Payload Options
   * [x] 8.7.1 Exercise - Payload Options
   * [ ] 8.8.1 Extra Mile - Y SO SERIAL? .NET
   * [x] 8.8.2 Extra Mile - Y SO SERIAL? Java
 * [ ] 9. ERPNext Authentication Bypass and Server Side Template Injection
   * [x] Videos
   * [ ] Read/Notes
   * [x] 9.1.1.1 Exercise - Configure Kali SMTPd server
   * [x] 9.1.2.1 Exercise - Configure remote debugging
   * [x] 9.1.3.1 Exercise - Configure MariaDB logging
   * [x] 9.2.3.2 Exercise - Find whitelisted functions
   * [x] 9.3.1.2 Exercises - SQLi
   * [x] 9.4.2.1 Exercises - Access the admin acct
   * [x] 9.5.2.1 Exercise - Find the SSTI
   * [ ] 9.5.2.2 Extra Mile - Find another instance of SSTI
   * [x] 9.5.3.1 Exercise - Recreate the `__class__` rendering
   * [ ] 9.5.3.2 Extra Mile - Alternative filter bypass
   * [x] 9.6.1.1 Exercises - Recreate the filter bypass and exploit and find other classes to own
   * [x] 9.6.2.1 Exercises - Recreate RCE and get shell
   * [ ] 9.6.2.2 Extra Mile - Get output to display
 * [ ] 10. openCRX Authentication Bypass and Remote Code Execution
   * [x] Videos
   * [ ] Read/Notes
   * [x] 10.2.1.1 Exercise - Recreate the Rando and SecureRando
   * [x] 10.2.4.1 Exercise - Generate a token list
   * [ ] 10.2.4.2 Extra Mile - Update token program to take start/stop
   * [x] 10.2.5.2 Exercises - Reset password
   * [ ] 10.2.5.3 Extra Mile - Automate the attack chain
   * [x] 10.3.6.2 Exercises - Recreate the XXE attack
   * [ ] 10.3.6.3 Extra Mile - Script to parse XXE results
   * [x] 10.3.8.1 Exercise - Implement the "wrapper" payload
   * [x] 10.3.9.2 Exercise - Connect to HSQLDB
   * [x] 10.4.1.1 Exercises - Write file and confirm
   * [ ] 10.4.2.1 Exercise - Find dir with JSP files
   * [x] 10.4.3.1 Exercises - Get. That. Shell.
 * [ ] 11. openITCOCKPITXSSandOSCommandInjection - Blackbox
   * [x] Videos
   * [ ] Read/Notes
   * [x] 11.5.1 Exercise - Recreate the XSS
   * [x] 11.6.2.1 Exercises - DOM rewrite
   * [ ] 11.6.2.2 Extra Mile - Prevent new page load
   * [x] 11.6.3.1 Exercises - Finish the script and initialize the DB
   * [x] 11.6.4.1 Exercises - Finish the API script and get a fake login page with the XSS
   * [ ] 11.6.4.2 Extra Mile - Add cookie functionality
   * [ ] 11.6.5.1 Exercises - Exploit the XSS
   * [ ] 11.6.5.2 Extra Miles - Beef up dat XSS
   * [ ] 11.6.6.1 Exercise - Dump the SQLite DB
   * [x] 11.7.4.1 Exercise - Fuzz and find cmds
   * [x] 11.7.5.1 Exercise - Test cmd injection
   * [ ] 11.7.6.1 Exercise - Get a meterpreter shell
   * [ ] 10.7.7 Extra Mile - Get RCE via administrator session
