ZAP by Checkmarx Scanning Report
Generated with The ZAP logoZAP on Tue 10 Nov 2026, at 18:48:17

ZAP Version: 2.17.0

ZAP by Checkmarx

Contents
About This Report
Report Parameters
Summaries
Alert Counts by Risk and Confidence
Alert Counts by Site and Risk
Alert Counts by Alert Type
Insights
Alerts
Risk=Medium, Confidence=High (2)
Risk=Medium, Confidence=Medium (1)
Risk=Low, Confidence=Medium (1)
Risk=Informational, Confidence=High (1)
Risk=Informational, Confidence=Medium (4)
Risk=Informational, Confidence=Low (2)
Appendix
Alert Types
About This Report
Report Parameters
Contexts
No contexts were selected, so all contexts were included by default.

Sites
The following sites were included:

https://tirfe-shop.vercel.app
(If no sites were selected, all sites were included by default.)

An included site must also be within one of the included contexts for its data to be included in the report.

Risk levels
Included: High, Medium, Low, Informational

Excluded: None

Confidence levels
Included: User Confirmed, High, Medium, Low

Excluded: User Confirmed, High, Medium, Low, False Positive

Summaries
Alert Counts by Risk and Confidence
This table shows the number of alerts for each level of risk and confidence included in the report.

(The percentages in brackets represent the count as a percentage of the total number of alerts included in the report, rounded to one decimal place.)

Confidence
User Confirmed	High	Medium	Low	Total
Risk	High	0
(0.0%)	0
(0.0%)	0
(0.0%)	0
(0.0%)	0
(0.0%)
Medium	0
(0.0%)	2
(18.2%)	1
(9.1%)	0
(0.0%)	3
(27.3%)
Low	0
(0.0%)	0
(0.0%)	1
(9.1%)	0
(0.0%)	1
(9.1%)
Informational	0
(0.0%)	1
(9.1%)	4
(36.4%)	2
(18.2%)	7
(63.6%)
Total	0
(0.0%)	3
(27.3%)	6
(54.5%)	2
(18.2%)	11
(100%)
Alert Counts by Site and Risk
This table shows, for each site for which one or more alerts were raised, the number of alerts raised at each risk level.

Alerts with a confidence level of "False Positive" have been excluded from these counts.

(The numbers in brackets are the number of alerts raised for the site at or above that risk level.)

Risk
High
(= High)	Medium
(>= Medium)	Low
(>= Low)	Informational
(>= Informational)
Site	https://tirfe-shop.vercel.app	0
(0)	3
(3)	1
(4)	7
(11)
Alert Counts by Alert Type
This table shows the number of alerts of each alert type, together with the alert type's risk level.

(The percentages in brackets represent each count as a percentage, rounded to one decimal place, of the total number of alerts included in this report.)

Alert type	Risk	Count
Content Security Policy (CSP) Header Not Set	Medium	2
(18.2%)
Cross-Domain Misconfiguration	Medium	5
(45.5%)
Sub Resource Integrity Attribute Missing	Medium	5
(45.5%)
Cross-Domain JavaScript Source File Inclusion	Low	5
(45.5%)
Authentication Request Identified	Informational	1
(9.1%)
Content Security Policy (CSP) Report-Only Header Found	Informational	2
(18.2%)
Information Disclosure - Sensitive Information in URL	Informational	2
(18.2%)
Information Disclosure - Suspicious Comments	Informational	16
(145.5%)
Modern Web Application	Informational	2
(18.2%)
Re-examine Cache-control Directives	Informational	3
(27.3%)
Retrieved from Cache	Informational	5
(45.5%)
Total		11
Insights
This table shows information that is likely to be very relevant to you, but which is not related to vulnerabilities, or potentially even related to the application in question.

Level	Reason	Site	Description	Statistic
Low
Warning
ZAP errors logged - see the zap.log file for details
1
Info
Informational
https://tirfe-shop.vercel.app
Percentage of responses with status code 2xx
54 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of responses with status code 4xx
45 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with content type application/javascript
63 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with content type application/json
5 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with content type image/png
10 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with content type text/html
10 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with content type text/plain
10 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with method GET
100 %
Info
Informational
https://tirfe-shop.vercel.app
Count of total endpoints
19
Info
Informational
https://tirfe-shop.vercel.app
Percentage of slow responses
70 %
Alerts
Risk=Medium, Confidence=High (2)
https://tirfe-shop.vercel.app (2)
Content Security Policy (CSP) Header Not Set (1)
GET https://tirfe-shop.vercel.app/
Sub Resource Integrity Attribute Missing (1)
GET https://tirfe-shop.vercel.app/
Risk=Medium, Confidence=Medium (1)
https://tirfe-shop.vercel.app (1)
Cross-Domain Misconfiguration (1)
GET https://tirfe-shop.vercel.app/
Risk=Low, Confidence=Medium (1)
https://tirfe-shop.vercel.app (1)
Cross-Domain JavaScript Source File Inclusion (1)
GET https://tirfe-shop.vercel.app/
Risk=Informational, Confidence=High (1)
https://tirfe-shop.vercel.app (1)
Content Security Policy (CSP) Report-Only Header Found (1)
GET https://tirfe-shop.vercel.app/
Risk=Informational, Confidence=Medium (4)
https://tirfe-shop.vercel.app (4)
Information Disclosure - Sensitive Information in URL (1)
GET https://tirfe-shop.vercel.app/?email=zaproxy%40example.com&password=ZAP
Information Disclosure - Suspicious Comments (1)
GET https://tirfe-shop.vercel.app/js/common/register_chooser.js
Modern Web Application (1)
GET https://tirfe-shop.vercel.app/
Retrieved from Cache (1)
GET https://tirfe-shop.vercel.app/
Risk=Informational, Confidence=Low (2)
https://tirfe-shop.vercel.app (2)
Authentication Request Identified (1)
GET https://tirfe-shop.vercel.app/?email=zaproxy%40example.com&password=ZAP
Re-examine Cache-control Directives (1)
GET https://tirfe-shop.vercel.app/
Appendix
Alert Types
This section contains additional information on the types of alerts in the report.

Content Security Policy (CSP) Header Not Set
Source	raised by a passive scanner (Content Security Policy (CSP) Header Not Set)
CWE ID	693
WASC ID	15
Reference	
https://developer.mozilla.org/en-US/docs/Web/HTTP/Guides/CSP
https://cheatsheetseries.owasp.org/cheatsheets/Content_Security_Policy_Cheat_Sheet.html
https://www.w3.org/TR/CSP/
https://w3c.github.io/webappsec-csp/
https://web.dev/articles/csp
https://caniuse.com/#feat=contentsecuritypolicy
https://content-security-policy.com/
Cross-Domain Misconfiguration
Source	raised by a passive scanner (Cross-Domain Misconfiguration)
CWE ID	264
WASC ID	14
Reference	
https://vulncat.fortify.com/en/detail?category=HTML5&subcategory=Overly%20Permissive%20CORS%20Policy
Sub Resource Integrity Attribute Missing
Source	raised by a passive scanner (Sub Resource Integrity Attribute Missing)
CWE ID	345
WASC ID	15
Reference	
https://developer.mozilla.org/en-US/docs/Web/Security/Defenses/Subresource_Integrity
Cross-Domain JavaScript Source File Inclusion
Source	raised by a passive scanner (Cross-Domain JavaScript Source File Inclusion)
CWE ID	829
WASC ID	15
Authentication Request Identified
Source	raised by a passive scanner (Authentication Request Identified)
Reference	
https://www.zaproxy.org/docs/desktop/addons/authentication-helper/auth-req-id/
Content Security Policy (CSP) Report-Only Header Found
Source	raised by a passive scanner (Content Security Policy (CSP) Header Not Set)
CWE ID	693
WASC ID	15
Reference	
https://www.w3.org/TR/CSP2/
https://w3c.github.io/webappsec-csp/
https://caniuse.com/#feat=contentsecuritypolicy
https://content-security-policy.com/
Information Disclosure - Sensitive Information in URL
Source	raised by a passive scanner (Information Disclosure - Sensitive Information in URL)
CWE ID	598
WASC ID	13
Information Disclosure - Suspicious Comments
Source	raised by a passive scanner (Information Disclosure - Suspicious Comments)
CWE ID	615
WASC ID	13
Modern Web Application
Source	raised by a passive scanner (Modern Web Application)
Re-examine Cache-control Directives
Source	raised by a passive scanner (Re-examine Cache-control Directives)
CWE ID	525
WASC ID	13
Reference	
https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html#web-content-caching
https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/Cache-Control
https://grayduck.mn/2021/09/13/cache-control-recommendations/
Retrieved from Cache
Source	raised by a passive scanner (Retrieved from Cache)
CWE ID	525
Reference	
https://datatracker.ietf.org/doc/html/rfc7234
https://datatracker.ietf.org/doc/html/rfc7231
https://www.rfc-editor.org/rfc/rfc9110.html
