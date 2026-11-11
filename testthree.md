ZAP by Checkmarx Scanning Report
Generated with The ZAP logoZAP on Wed 11 Nov 2026, at 20:20:40

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
Risk=High, Confidence=Medium (1)
Risk=Medium, Confidence=High (6)
Risk=Medium, Confidence=Medium (3)
Risk=Low, Confidence=High (2)
Risk=Low, Confidence=Medium (5)
Risk=Low, Confidence=Low (1)
Risk=Informational, Confidence=High (3)
Risk=Informational, Confidence=Medium (5)
Risk=Informational, Confidence=Low (1)
Appendix
Alert Types
About This Report
Report Parameters
Contexts
No contexts were selected, so all contexts were included by default.

Sites
The following sites were included:

https://cdn.tailwindcss.com
https://developer.chapa.co
https://d1a85gsjeabvpg.cloudfront.net
https://checkout.chapa.co
https://beacons.gvt2.com
https://e2c16.gcp.gvt2.com
https://firebaselogging-pa.googleapis.com
https://firebaseremoteconfig.googleapis.com
https://firebaseinstallations.googleapis.com
https://s-gke-usc1-nssi3-44.firebaseio.com
https://cdn.jsdelivr.net
https://unpkg.com
https://securetoken.googleapis.com
https://identitytoolkit.googleapis.com
https://e2c65.gcp.gvt2.com
https://accounts.google.com
https://beacons.gcp.gvt2.com
https://clientservices.googleapis.com
https://tirfe-app-default-rtdb.firebaseio.com
https://content-autofill.googleapis.com
https://fonts.gstatic.com
https://www.google-analytics.com
https://www.gstatic.com
https://fonts.googleapis.com
https://www.googletagmanager.com
https://cdnjs.cloudflare.com
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
(0.0%)	1
(3.7%)	0
(0.0%)	1
(3.7%)
Medium	0
(0.0%)	6
(22.2%)	3
(11.1%)	0
(0.0%)	9
(33.3%)
Low	0
(0.0%)	2
(7.4%)	5
(18.5%)	1
(3.7%)	8
(29.6%)
Informational	0
(0.0%)	3
(11.1%)	5
(18.5%)	1
(3.7%)	9
(33.3%)
Total	0
(0.0%)	11
(40.7%)	14
(51.9%)	2
(7.4%)	27
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
Site	https://developer.chapa.co	0
(0)	0
(0)	1
(1)	1
(2)
https://checkout.chapa.co	0
(0)	1
(1)	2
(3)	0
(3)
https://identitytoolkit.googleapis.com	0
(0)	1
(1)	0
(1)	0
(1)
https://www.google-analytics.com	0
(0)	1
(1)	1
(2)	0
(2)
https://www.gstatic.com	0
(0)	0
(0)	2
(2)	0
(2)
https://www.googletagmanager.com	0
(0)	0
(0)	1
(1)	0
(1)
https://cdnjs.cloudflare.com	1
(1)	0
(1)	0
(1)	0
(1)
https://tirfe-shop.vercel.app	0
(0)	6
(6)	1
(7)	8
(15)
Alert Counts by Alert Type
This table shows the number of alerts of each alert type, together with the alert type's risk level.

(The percentages in brackets represent each count as a percentage, rounded to one decimal place, of the total number of alerts included in this report.)

Alert type	Risk	Count
Vulnerable JS Library	High	3
(11.1%)
Application Error Disclosure	Medium	1
(3.7%)
CSP: Wildcard Directive	Medium	3
(11.1%)
CSP: script-src unsafe-inline	Medium	3
(11.1%)
CSP: style-src unsafe-inline	Medium	3
(11.1%)
Content Security Policy (CSP) Header Not Set	Medium	8
(29.6%)
Cross-Domain Misconfiguration	Medium	28
(103.7%)
Missing Anti-clickjacking Header	Medium	3
(11.1%)
Session ID in URL Rewrite	Medium	5
(18.5%)
Sub Resource Integrity Attribute Missing	Medium	10
(37.0%)
Big Redirect Detected (Potential Sensitive Information Leak)	Low	1
(3.7%)
Cookie No HttpOnly Flag	Low	3
(11.1%)
Cross-Domain JavaScript Source File Inclusion	Low	10
(37.0%)
Server Leaks Information via "X-Powered-By" HTTP Response Header Field(s)	Low	1
(3.7%)
Server Leaks Version Information via "Server" HTTP Response Header Field	Low	12
(44.4%)
Strict-Transport-Security Header Not Set	Low	57
(211.1%)
Timestamp Disclosure - Unix	Low	15
(55.6%)
X-Content-Type-Options Header Missing	Low	16
(59.3%)
Authentication Request Identified	Informational	2
(7.4%)
Content-Type Header Missing	Informational	5
(18.5%)
Information Disclosure - Information in Browser localStorage	Informational	9
(33.3%)
Information Disclosure - Information in Browser sessionStorage	Informational	6
(22.2%)
Information Disclosure - Suspicious Comments	Informational	30
(111.1%)
Modern Web Application	Informational	5
(18.5%)
Re-examine Cache-control Directives	Informational	13
(48.1%)
Retrieved from Cache	Informational	30
(111.1%)
Session Management Response Identified	Informational	5
(18.5%)
Total		27
Insights
This table shows information that is likely to be very relevant to you, but which is not related to vulnerabilities, or potentially even related to the application in question.

Level	Reason	Site	Description	Statistic
Low
Warning
ZAP warnings logged - see the zap.log file for details
41
Info
Informational
https://accounts.google.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://accounts.google.com
Percentage of endpoints with content type application/javascript
100 %
Info
Informational
https://accounts.google.com
Percentage of endpoints with method POST
100 %
Info
Informational
https://accounts.google.com
Count of total endpoints
2
Info
Informational
https://accounts.google.com
Percentage of slow responses
50 %
Info
Informational
https://beacons.gcp.gvt2.com
Percentage of responses with status code 2xx
81 %
Info
Informational
https://beacons.gcp.gvt2.com
Percentage of responses with status code 3xx
18 %
Info
Informational
https://beacons.gcp.gvt2.com
Percentage of endpoints with content type application/javascript
100 %
Info
Informational
https://beacons.gcp.gvt2.com
Percentage of endpoints with method POST
100 %
Info
Informational
https://beacons.gcp.gvt2.com
Count of total endpoints
5
Info
Informational
https://beacons.gcp.gvt2.com
Percentage of slow responses
36 %
Info
Informational
https://beacons.gvt2.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://beacons.gvt2.com
Percentage of endpoints with content type application/javascript
100 %
Info
Informational
https://beacons.gvt2.com
Percentage of endpoints with method POST
100 %
Info
Informational
https://beacons.gvt2.com
Count of total endpoints
1
Info
Informational
https://beacons.gvt2.com
Percentage of slow responses
100 %
Info
Informational
https://cdn.jsdelivr.net
Percentage of responses with status code 2xx
100 %
Info
Informational
https://cdn.jsdelivr.net
Percentage of endpoints with content type application/javascript
100 %
Info
Informational
https://cdn.jsdelivr.net
Percentage of endpoints with method GET
100 %
Info
Informational
https://cdn.jsdelivr.net
Count of total endpoints
1
Info
Informational
https://cdn.jsdelivr.net
Percentage of slow responses
50 %
Info
Informational
https://cdn.tailwindcss.com
Percentage of responses with status code 2xx
50 %
Info
Informational
https://cdn.tailwindcss.com
Percentage of responses with status code 3xx
50 %
Info
Informational
https://cdn.tailwindcss.com
Percentage of endpoints with content type text/javascript
50 %
Info
Informational
https://cdn.tailwindcss.com
Percentage of endpoints with method GET
100 %
Info
Informational
https://cdn.tailwindcss.com
Count of total endpoints
2
Info
Informational
https://cdn.tailwindcss.com
Percentage of slow responses
100 %
Info
Informational
https://cdnjs.cloudflare.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://cdnjs.cloudflare.com
Percentage of endpoints with content type application/javascript
57 %
Info
Informational
https://cdnjs.cloudflare.com
Percentage of endpoints with content type application/octet-stream
14 %
Info
Informational
https://cdnjs.cloudflare.com
Percentage of endpoints with content type text/css
28 %
Info
Informational
https://cdnjs.cloudflare.com
Percentage of endpoints with method GET
100 %
Info
Informational
https://cdnjs.cloudflare.com
Count of total endpoints
7
Info
Informational
https://cdnjs.cloudflare.com
Percentage of slow responses
57 %
Info
Informational
https://checkout.chapa.co
Percentage of responses with status code 2xx
66 %
Info
Informational
https://checkout.chapa.co
Percentage of responses with status code 3xx
33 %
Info
Informational
https://checkout.chapa.co
Percentage of endpoints with content type text/html
100 %
Info
Informational
https://checkout.chapa.co
Percentage of endpoints with method GET
66 %
Info
Informational
https://checkout.chapa.co
Percentage of endpoints with method POST
33 %
Info
Informational
https://checkout.chapa.co
Count of total endpoints
3
Info
Informational
https://checkout.chapa.co
Percentage of slow responses
100 %
Info
Informational
https://clientservices.googleapis.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://clientservices.googleapis.com
Percentage of endpoints with content type text/plain
100 %
Info
Informational
https://clientservices.googleapis.com
Percentage of endpoints with method POST
100 %
Info
Informational
https://clientservices.googleapis.com
Count of total endpoints
2
Info
Informational
https://clientservices.googleapis.com
Percentage of slow responses
100 %
Info
Informational
https://content-autofill.googleapis.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://content-autofill.googleapis.com
Percentage of endpoints with content type application/x-protobuf
41 %
Info
Informational
https://content-autofill.googleapis.com
Percentage of endpoints with content type text/plain
58 %
Info
Informational
https://content-autofill.googleapis.com
Percentage of endpoints with method GET
58 %
Info
Informational
https://content-autofill.googleapis.com
Percentage of endpoints with method POST
41 %
Info
Informational
https://content-autofill.googleapis.com
Count of total endpoints
17
Info
Informational
https://content-autofill.googleapis.com
Percentage of slow responses
84 %
Info
Informational
https://d1a85gsjeabvpg.cloudfront.net
Percentage of responses with status code 2xx
100 %
Info
Informational
https://d1a85gsjeabvpg.cloudfront.net
Percentage of endpoints with content type font/ttf
16 %
Info
Informational
https://d1a85gsjeabvpg.cloudfront.net
Percentage of endpoints with content type image/png
5 %
Info
Informational
https://d1a85gsjeabvpg.cloudfront.net
Percentage of endpoints with content type image/svg+xml
33 %
Info
Informational
https://d1a85gsjeabvpg.cloudfront.net
Percentage of endpoints with content type text/css
22 %
Info
Informational
https://d1a85gsjeabvpg.cloudfront.net
Percentage of endpoints with content type text/javascript
22 %
Info
Informational
https://d1a85gsjeabvpg.cloudfront.net
Percentage of endpoints with method GET
100 %
Info
Informational
https://d1a85gsjeabvpg.cloudfront.net
Count of total endpoints
18
Info
Informational
https://d1a85gsjeabvpg.cloudfront.net
Percentage of slow responses
94 %
Info
Informational
https://developer.chapa.co
Percentage of responses with status code 2xx
96 %
Info
Informational
https://developer.chapa.co
Percentage of responses with status code 3xx
3 %
Info
Informational
https://developer.chapa.co
Percentage of endpoints with content type image/gif
5 %
Info
Informational
https://developer.chapa.co
Percentage of endpoints with content type image/png
2 %
Info
Informational
https://developer.chapa.co
Percentage of endpoints with content type text/css
2 %
Info
Informational
https://developer.chapa.co
Percentage of endpoints with content type text/html
2 %
Info
Informational
https://developer.chapa.co
Percentage of endpoints with content type text/javascript
56 %
Info
Informational
https://developer.chapa.co
Percentage of endpoints with method GET
100 %
Info
Informational
https://developer.chapa.co
Count of total endpoints
39
Info
Informational
https://developer.chapa.co
Percentage of slow responses
67 %
Info
Informational
https://e2c16.gcp.gvt2.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://e2c16.gcp.gvt2.com
Percentage of endpoints with method POST
100 %
Info
Informational
https://e2c16.gcp.gvt2.com
Count of total endpoints
1
Info
Informational
https://e2c16.gcp.gvt2.com
Percentage of slow responses
100 %
Info
Informational
https://e2c65.gcp.gvt2.com
Percentage of endpoints with content type text/plain
100 %
Info
Informational
https://e2c65.gcp.gvt2.com
Percentage of endpoints with method POST
100 %
Info
Informational
https://e2c65.gcp.gvt2.com
Count of total endpoints
1
Info
Informational
https://firebaseinstallations.googleapis.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://firebaseinstallations.googleapis.com
Percentage of endpoints with content type application/json
50 %
Info
Informational
https://firebaseinstallations.googleapis.com
Percentage of endpoints with content type text/html
50 %
Info
Informational
https://firebaseinstallations.googleapis.com
Percentage of endpoints with method OPTIONS
50 %
Info
Informational
https://firebaseinstallations.googleapis.com
Percentage of endpoints with method POST
50 %
Info
Informational
https://firebaseinstallations.googleapis.com
Count of total endpoints
2
Info
Informational
https://firebaseinstallations.googleapis.com
Percentage of slow responses
100 %
Info
Informational
https://firebaselogging-pa.googleapis.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://firebaselogging-pa.googleapis.com
Percentage of endpoints with content type application/json
100 %
Info
Informational
https://firebaselogging-pa.googleapis.com
Percentage of endpoints with method POST
100 %
Info
Informational
https://firebaselogging-pa.googleapis.com
Count of total endpoints
18
Info
Informational
https://firebaselogging-pa.googleapis.com
Percentage of slow responses
100 %
Info
Informational
https://firebaseremoteconfig.googleapis.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://firebaseremoteconfig.googleapis.com
Percentage of endpoints with content type application/json
50 %
Info
Informational
https://firebaseremoteconfig.googleapis.com
Percentage of endpoints with content type text/html
50 %
Info
Informational
https://firebaseremoteconfig.googleapis.com
Percentage of endpoints with method OPTIONS
50 %
Info
Informational
https://firebaseremoteconfig.googleapis.com
Percentage of endpoints with method POST
50 %
Info
Informational
https://firebaseremoteconfig.googleapis.com
Count of total endpoints
2
Info
Informational
https://firebaseremoteconfig.googleapis.com
Percentage of slow responses
100 %
Info
Informational
https://fonts.googleapis.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://fonts.googleapis.com
Percentage of endpoints with content type text/css
100 %
Info
Informational
https://fonts.googleapis.com
Percentage of endpoints with method GET
100 %
Info
Informational
https://fonts.googleapis.com
Count of total endpoints
2
Info
Informational
https://fonts.googleapis.com
Percentage of slow responses
100 %
Info
Informational
https://fonts.gstatic.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://fonts.gstatic.com
Percentage of endpoints with content type font/woff2
100 %
Info
Informational
https://fonts.gstatic.com
Percentage of endpoints with method GET
100 %
Info
Informational
https://fonts.gstatic.com
Count of total endpoints
4
Info
Informational
https://fonts.gstatic.com
Percentage of slow responses
90 %
Info
Informational
https://identitytoolkit.googleapis.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://identitytoolkit.googleapis.com
Percentage of endpoints with content type application/json
50 %
Info
Informational
https://identitytoolkit.googleapis.com
Percentage of endpoints with content type text/html
50 %
Info
Informational
https://identitytoolkit.googleapis.com
Percentage of endpoints with method OPTIONS
50 %
Info
Informational
https://identitytoolkit.googleapis.com
Percentage of endpoints with method POST
50 %
Info
Informational
https://identitytoolkit.googleapis.com
Count of total endpoints
4
Info
Informational
https://identitytoolkit.googleapis.com
Percentage of slow responses
100 %
Info
Informational
https://s-gke-usc1-nssi3-44.firebaseio.com
Percentage of responses with status code 1xx
100 %
Info
Informational
https://s-gke-usc1-nssi3-44.firebaseio.com
Percentage of endpoints with method GET
100 %
Info
Informational
https://s-gke-usc1-nssi3-44.firebaseio.com
Count of total endpoints
1
Info
Informational
https://s-gke-usc1-nssi3-44.firebaseio.com
Percentage of slow responses
100 %
Info
Informational
https://securetoken.googleapis.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://securetoken.googleapis.com
Percentage of endpoints with content type application/json
50 %
Info
Informational
https://securetoken.googleapis.com
Percentage of endpoints with content type text/html
50 %
Info
Informational
https://securetoken.googleapis.com
Percentage of endpoints with method OPTIONS
50 %
Info
Informational
https://securetoken.googleapis.com
Percentage of endpoints with method POST
50 %
Info
Informational
https://securetoken.googleapis.com
Count of total endpoints
2
Info
Informational
https://securetoken.googleapis.com
Percentage of slow responses
100 %
Info
Informational
https://tirfe-app-default-rtdb.firebaseio.com
Percentage of responses with status code 1xx
100 %
Info
Informational
https://tirfe-app-default-rtdb.firebaseio.com
Percentage of endpoints with method GET
100 %
Info
Informational
https://tirfe-app-default-rtdb.firebaseio.com
Count of total endpoints
1
Info
Informational
https://tirfe-app-default-rtdb.firebaseio.com
Percentage of slow responses
100 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of responses with status code 2xx
97 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of responses with status code 4xx
1 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with content type application/javascript
36 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with content type application/json
47 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with content type image/png
6 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with content type text/html
6 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with method GET
63 %
Info
Informational
https://tirfe-shop.vercel.app
Percentage of endpoints with method POST
36 %
Info
Informational
https://tirfe-shop.vercel.app
Count of total endpoints
46
Info
Informational
https://tirfe-shop.vercel.app
Percentage of slow responses
72 %
Info
Informational
https://unpkg.com
Percentage of responses with status code 2xx
50 %
Info
Informational
https://unpkg.com
Percentage of responses with status code 3xx
50 %
Info
Informational
https://unpkg.com
Percentage of endpoints with content type text/javascript
50 %
Info
Informational
https://unpkg.com
Percentage of endpoints with content type text/plain
50 %
Info
Informational
https://unpkg.com
Percentage of endpoints with method GET
100 %
Info
Informational
https://unpkg.com
Count of total endpoints
2
Info
Informational
https://unpkg.com
Percentage of slow responses
100 %
Info
Informational
https://www.google-analytics.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://www.google-analytics.com
Percentage of endpoints with content type text/plain
100 %
Info
Informational
https://www.google-analytics.com
Percentage of endpoints with method POST
100 %
Info
Informational
https://www.google-analytics.com
Count of total endpoints
7
Info
Informational
https://www.google-analytics.com
Percentage of slow responses
22 %
Info
Informational
https://www.googletagmanager.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://www.googletagmanager.com
Percentage of endpoints with content type application/javascript
100 %
Info
Informational
https://www.googletagmanager.com
Percentage of endpoints with method GET
100 %
Info
Informational
https://www.googletagmanager.com
Count of total endpoints
1
Info
Informational
https://www.googletagmanager.com
Percentage of slow responses
100 %
Info
Informational
https://www.gstatic.com
Percentage of responses with status code 2xx
100 %
Info
Informational
https://www.gstatic.com
Percentage of endpoints with content type text/javascript
100 %
Info
Informational
https://www.gstatic.com
Percentage of endpoints with method GET
100 %
Info
Informational
https://www.gstatic.com
Count of total endpoints
6
Info
Informational
https://www.gstatic.com
Percentage of slow responses
78 %
Alerts
Risk=High, Confidence=Medium (1)
https://cdnjs.cloudflare.com (1)
Vulnerable JS Library (1)
GET https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js
Risk=Medium, Confidence=High (6)
https://identitytoolkit.googleapis.com (1)
Content Security Policy (CSP) Header Not Set (1)
OPTIONS https://identitytoolkit.googleapis.com/v1/accounts:signInWithPassword?key=AIzaSyBgXU6N4cMV2q-d3XeFzvgFT98gJ1GM7Ws
https://www.google-analytics.com (1)
Session ID in URL Rewrite (1)
POST https://www.google-analytics.com/g/collect?v=2&tid=G-SBF6WVQJY4&gtm=45je6b91h1v9260400784za208zd9260400784xf1&_p=1794416464944&gcd=13l3l3l3l1l1&npa=0&dma=0&cid=1817518744.1794416468&frm=0&ngs=1&pscdl=noapi&rcb=7&sr=1280x720&uaa=x86&uab=64&uafvl=Not-A.Brand%3B99.0.0.0%7CGoogle%2520Chrome%3B157.0.8103.39%7CChromium%3B157.0.8103.39&uam=&uamb=0&uap=Windows&uapv=19.0.0&uaw=0&ul=en-us&_s=1&tag_exp=115616986~115938466~115938469~118897920~118897930~119793973~119863601~120213116~120385422~120412528~120420414~120469145~120469153~121246026~121246034~123329125~124170881&sid=1794416467&sct=1&seg=0&dl=https%3A%2F%2Ftirfe-shop.vercel.app%2F&dt=%E1%89%B5%E1%88%AD%E1%8D%8C%20%E2%80%94%20%E1%8B%A8%E1%88%B1%E1%89%85%20%E1%8A%A0%E1%88%B5%E1%89%B0%E1%8B%B3%E1%8B%B0%E1%88%AD%E1%8D%A3%20%E1%8A%A6%E1%8A%95%E1%88%8B%E1%8B%AD%E1%8A%95%20%E1%8C%88%E1%89%A0%E1%8B%AB%E1%8A%93%20%E1%8B%B4%E1%88%8A%E1%89%A8%E1%88%AA%20%E1%89%A0%E1%8A%A2%E1%89%B5%E1%8B%AE%E1%8C%B5%E1%8B%AB&en=page_view&_fv=1&_nsi=1&_ss=1&_ee=1&tfd=4087
https://tirfe-shop.vercel.app (4)
CSP: Wildcard Directive (1)
GET https://tirfe-shop.vercel.app/
CSP: script-src unsafe-inline (1)
GET https://tirfe-shop.vercel.app/
CSP: style-src unsafe-inline (1)
GET https://tirfe-shop.vercel.app/
Sub Resource Integrity Attribute Missing (1)
GET https://tirfe-shop.vercel.app/
Risk=Medium, Confidence=Medium (3)
https://checkout.chapa.co (1)
Missing Anti-clickjacking Header (1)
GET https://checkout.chapa.co/checkout/payment/GAClC8VbANSngBRHvTKhjuznimSkyy5pnD9lGeosZ17T6
https://tirfe-shop.vercel.app (2)
Application Error Disclosure (1)
GET https://tirfe-shop.vercel.app/language/first.json
Cross-Domain Misconfiguration (1)
GET https://tirfe-shop.vercel.app/js/common/firebase-config.js
Risk=Low, Confidence=High (2)
https://www.google-analytics.com (1)
Server Leaks Version Information via "Server" HTTP Response Header Field (1)
POST https://www.google-analytics.com/g/collect?v=2&tid=G-SBF6WVQJY4&gtm=45je6b91h1v9260400784za208zd9260400784xf1&_p=1794416464944&gcd=13l3l3l3l1l1&npa=0&dma=0&cid=1817518744.1794416468&frm=0&ngs=1&pscdl=noapi&rcb=7&sr=1280x720&uaa=x86&uab=64&uafvl=Not-A.Brand%3B99.0.0.0%7CGoogle%2520Chrome%3B157.0.8103.39%7CChromium%3B157.0.8103.39&uam=&uamb=0&uap=Windows&uapv=19.0.0&uaw=0&ul=en-us&_s=1&tag_exp=115616986~115938466~115938469~118897920~118897930~119793973~119863601~120213116~120385422~120412528~120420414~120469145~120469153~121246026~121246034~123329125~124170881&sid=1794416467&sct=1&seg=0&dl=https%3A%2F%2Ftirfe-shop.vercel.app%2F&dt=%E1%89%B5%E1%88%AD%E1%8D%8C%20%E2%80%94%20%E1%8B%A8%E1%88%B1%E1%89%85%20%E1%8A%A0%E1%88%B5%E1%89%B0%E1%8B%B3%E1%8B%B0%E1%88%AD%E1%8D%A3%20%E1%8A%A6%E1%8A%95%E1%88%8B%E1%8B%AD%E1%8A%95%20%E1%8C%88%E1%89%A0%E1%8B%AB%E1%8A%93%20%E1%8B%B4%E1%88%8A%E1%89%A8%E1%88%AA%20%E1%89%A0%E1%8A%A2%E1%89%B5%E1%8B%AE%E1%8C%B5%E1%8B%AB&en=page_view&_fv=1&_nsi=1&_ss=1&_ee=1&tfd=4087
https://www.gstatic.com (1)
Strict-Transport-Security Header Not Set (1)
GET https://www.gstatic.com/firebasejs/10.12.2/firebase-app-compat.js
Risk=Low, Confidence=Medium (5)
https://developer.chapa.co (1)
Server Leaks Information via "X-Powered-By" HTTP Response Header Field(s) (1)
GET https://developer.chapa.co/test/testing-mobile
https://checkout.chapa.co (2)
Big Redirect Detected (Potential Sensitive Information Leak) (1)
POST https://checkout.chapa.co/checkout/payment-submit/GAClC8VbANSngBRHvTKhjuznimSkyy5pnD9lGeosZ17T6
Cookie No HttpOnly Flag (1)
GET https://checkout.chapa.co/checkout/payment/GAClC8VbANSngBRHvTKhjuznimSkyy5pnD9lGeosZ17T6
https://www.googletagmanager.com (1)
X-Content-Type-Options Header Missing (1)
GET https://www.googletagmanager.com/gtag/js?id=G-SBF6WVQJY4
https://tirfe-shop.vercel.app (1)
Cross-Domain JavaScript Source File Inclusion (1)
GET https://tirfe-shop.vercel.app/
Risk=Low, Confidence=Low (1)
https://www.gstatic.com (1)
Timestamp Disclosure - Unix (1)
GET https://www.gstatic.com/firebasejs/10.12.2/firebase-database-compat.js
Risk=Informational, Confidence=High (3)
https://tirfe-shop.vercel.app (3)
Authentication Request Identified (1)
POST https://tirfe-shop.vercel.app/api/admin-login
Information Disclosure - Information in Browser localStorage (1)
GET https://tirfe-shop.vercel.app/
Information Disclosure - Information in Browser sessionStorage (1)
GET https://tirfe-shop.vercel.app/
Risk=Informational, Confidence=Medium (5)
https://developer.chapa.co (1)
Content-Type Header Missing (1)
GET https://developer.chapa.co/docs/testing-mobile/
https://tirfe-shop.vercel.app (4)
Information Disclosure - Suspicious Comments (1)
GET https://tirfe-shop.vercel.app/js/common/globals.js
Modern Web Application (1)
GET https://tirfe-shop.vercel.app/
Retrieved from Cache (1)
GET https://tirfe-shop.vercel.app/js/common/firebase-config.js
Session Management Response Identified (1)
POST https://tirfe-shop.vercel.app/api/gateway?fn=create-session
Risk=Informational, Confidence=Low (1)
https://tirfe-shop.vercel.app (1)
Re-examine Cache-control Directives (1)
GET https://tirfe-shop.vercel.app/
Appendix
Alert Types
This section contains additional information on the types of alerts in the report.

Vulnerable JS Library
Source	raised by a passive scanner (Vulnerable JS Library (Powered by Retire.js))
CWE ID	1395
Reference	
https://owasp.org/Top10/2021/A06_2021-Vulnerable_and_Outdated_Components/
Application Error Disclosure
Source	raised by a passive scanner (Application Error Disclosure)
CWE ID	550
WASC ID	13
CSP: Wildcard Directive
Source	raised by a passive scanner (CSP)
CWE ID	693
WASC ID	15
Reference	
https://www.w3.org/TR/CSP/
https://caniuse.com/#search=content+security+policy
https://content-security-policy.com/
https://github.com/HtmlUnit/htmlunit-csp
https://web.dev/articles/csp#resource-options
CSP: script-src unsafe-inline
Source	raised by a passive scanner (CSP)
CWE ID	693
WASC ID	15
Reference	
https://www.w3.org/TR/CSP/
https://caniuse.com/#search=content+security+policy
https://content-security-policy.com/
https://github.com/HtmlUnit/htmlunit-csp
https://web.dev/articles/csp#resource-options
CSP: style-src unsafe-inline
Source	raised by a passive scanner (CSP)
CWE ID	693
WASC ID	15
Reference	
https://www.w3.org/TR/CSP/
https://caniuse.com/#search=content+security+policy
https://content-security-policy.com/
https://github.com/HtmlUnit/htmlunit-csp
https://web.dev/articles/csp#resource-options
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
Missing Anti-clickjacking Header
Source	raised by a passive scanner (Anti-clickjacking Header)
CWE ID	1021
WASC ID	15
Reference	
https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/X-Frame-Options
Session ID in URL Rewrite
Source	raised by a passive scanner (Session ID in URL Rewrite)
CWE ID	598
WASC ID	13
Reference	
https://seclists.org/webappsec/2002/q4/111
Sub Resource Integrity Attribute Missing
Source	raised by a passive scanner (Sub Resource Integrity Attribute Missing)
CWE ID	345
WASC ID	15
Reference	
https://developer.mozilla.org/en-US/docs/Web/Security/Defenses/Subresource_Integrity
Big Redirect Detected (Potential Sensitive Information Leak)
Source	raised by a passive scanner (Big Redirect Detected (Potential Sensitive Information Leak))
CWE ID	201
WASC ID	13
Cookie No HttpOnly Flag
Source	raised by a passive scanner (Cookie No HttpOnly Flag)
CWE ID	1004
WASC ID	13
Reference	
https://owasp.org/www-community/HttpOnly
Cross-Domain JavaScript Source File Inclusion
Source	raised by a passive scanner (Cross-Domain JavaScript Source File Inclusion)
CWE ID	829
WASC ID	15
Server Leaks Information via "X-Powered-By" HTTP Response Header Field(s)
Source	raised by a passive scanner (Server Leaks Information via "X-Powered-By" HTTP Response Header Field(s))
CWE ID	497
WASC ID	13
Reference	
https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/01-Information_Gathering/08-Fingerprint_Web_Application_Framework
https://www.troyhunt.com/shhh-dont-let-your-response-headers/
Server Leaks Version Information via "Server" HTTP Response Header Field
Source	raised by a passive scanner (HTTP Server Response Header)
CWE ID	497
WASC ID	13
Reference	
https://httpd.apache.org/docs/current/mod/core.html#servertokens
https://learn.microsoft.com/en-us/previous-versions/msp-n-p/ff648552(v=pandp.10)
https://www.troyhunt.com/shhh-dont-let-your-response-headers/
Strict-Transport-Security Header Not Set
Source	raised by a passive scanner (Strict-Transport-Security Header)
CWE ID	319
WASC ID	15
Reference	
https://cheatsheetseries.owasp.org/cheatsheets/HTTP_Strict_Transport_Security_Cheat_Sheet.html
https://owasp.org/www-community/Security_Headers
https://en.wikipedia.org/wiki/HTTP_Strict_Transport_Security
https://caniuse.com/stricttransportsecurity
https://datatracker.ietf.org/doc/html/rfc6797
Timestamp Disclosure - Unix
Source	raised by a passive scanner (Timestamp Disclosure)
CWE ID	497
WASC ID	13
Reference	
https://cwe.mitre.org/data/definitions/200.html
X-Content-Type-Options Header Missing
Source	raised by a passive scanner (X-Content-Type-Options Header Missing)
CWE ID	693
WASC ID	15
Reference	
https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/compatibility/gg622941(v=vs.85)
https://owasp.org/www-community/Security_Headers
Authentication Request Identified
Source	raised by a passive scanner (Authentication Request Identified)
Reference	
https://www.zaproxy.org/docs/desktop/addons/authentication-helper/auth-req-id/
Content-Type Header Missing
Source	raised by a passive scanner (Content-Type Header Missing)
CWE ID	345
WASC ID	12
Reference	
https://learn.microsoft.com/en-us/previous-versions/windows/internet-explorer/ie-developer/compatibility/gg622941(v=vs.85)
Information Disclosure - Information in Browser localStorage
Source	raised by a passive scanner (plugin ID: 120000)
CWE ID	359
WASC ID	13
Information Disclosure - Information in Browser sessionStorage
Source	raised by a passive scanner (plugin ID: 120000)
CWE ID	359
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
Session Management Response Identified
Source	raised by a passive scanner (Session Management Response Identified)
Reference	
https://www.zaproxy.org/docs/desktop/addons/authentication-helper/session-mgmt-id/
