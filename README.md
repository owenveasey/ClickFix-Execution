# ClickFix-Execution
Detects ClickFix execution patterns where users are tricked into running malicious commands in the Run dialog through fake CAPTCHA challenges on infected websites. These commands often include comments like "I'm human" or "Recaptcha verification," and use mshta.exe, powershell.exe, to download and execute a malicious payload from a URL.
