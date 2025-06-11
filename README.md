# View non-printable Unicode Characters

This fork has been significantly rewritten. The tool is now entirely implemented in JavaScript and runs as a single HTML file, requiring no server-side code or installation.

In addition to recognizing invisible Unicode characters, this version also detects non-typable ASCII (US-QWERTY) characters, such as homoglyphs that look similar to Latin letters but come from different Unicode blocks, often used in phishing, obfuscation or IDN (internationalized domain name) homograph attacks.

The tool's target group are software developers and others who step over strange issues when handling text/data inputs. These may be inputs from users, server responses or database contents that the own scripts do no handle as expected. If the reason is not obvious when looking at the input, it may be caused by Unicode characters that are typically invisible.

This project was originally based on a small PHP script designed to recognize and display Unicode characters that are otherwise invisible.

The original tool is still available online and can be used without installation at [www.soscisurvey.de/tools/view-chars.php](https://www.soscisurvey.de/tools/view-chars.php).