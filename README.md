# Gitlab RCE - Remote Code Execution
RCE for old gitlab version &lt;= 11.4.7 & 12.4.0-12.8.1
LFI for old gitlab versions 10.4 - 12.8.1

This is an exploit for old Gitlab versions. The vulnerability is from 2018 so this shouldnt work in the wild but it still seems to be popular in CTFs. 
Educational use only. Illegal things are illegal.

CVEs: CVE-2018-19571 (SSRF) + CVE-2018-19585 (CRLF)
CVE-2020-10977

credits: 

  https://www.youtube.com/watch?v=LrLJuyAdoAg - LiveOverflow  
  https://github.com/jas502n/gitlab-SSRF-redis-RCE - jas502n
  https://hackerone.com/reports/827052 - vakzz
  
usage:

  `python gitlab_rce.py <http://gitlab:port> <local-ip>`
  
  You might or might not have to tweak this a bit.

THERE ARE ABSOLUTELY !!NO!! CHECKS OR ERROR HANDLING! 
