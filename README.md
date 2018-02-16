# PowerShell-IPrange-Regex
A PowerShell script that will provide you the Regex syntax for matching an IP range

To use this script:

To get regex syntax for a Single IP:<br>
&nbsp;&nbsp;&nbsp;.\IPrangeRegex.ps1 -IPRange 192.168.10.1
<br><br>
To get regex syntax for a range in format startrange-endrange<br>
&nbsp;&nbsp;&nbsp;.\IPrangeRegex.ps1 -IPRange 192.168.10.0-192.168.10.255
<br><br>
To get Regex syntax for a range in CIDR Format<br>
&nbsp;&nbsp;&nbsp;.\IPrangeRegex.ps1 -IPRange 192.168.10.0/21
<br><br>
Note: Subnet masks < 19 may take some time to calculate. 






