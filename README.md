# trivy-demo
here is some vulnerabilites that the trivy is able to detect 
┌─────────┬────────────────┬──────────┬────────┬───────────────────┬────────────────────────┬──────────────────────────────────────────────────────────────┐
│ Library │ Vulnerability  │ Severity │ Status │ Installed Version │     Fixed Version      │                            Title                             │
├─────────┼────────────────┼──────────┼────────┼───────────────────┼────────────────────────┼──────────────────────────────────────────────────────────────┤
│ django  │ CVE-2019-14234 │ CRITICAL │ fixed  │ 1.11.0            │ 1.11.23, 2.1.11, 2.2.4 │ Django: SQL injection possibility in key and index lookups   │
│         │                │          │        │                   │                        │ for JSONField/HStoreField                                    │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2019-14234                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2019-19844 │          │        │                   │ 1.11.27, 2.2.9, 3.0.1  │ Django: crafted email address allows account takeover        │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2019-19844                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2020-7471  │          │        │                   │ 1.11.28, 2.2.10, 3.0.3 │ django: potential SQL injection via StringAgg(delimiter)     │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2020-7471                    │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2025-64459 │          │        │                   │ 5.2.8, 5.1.14, 4.2.26  │ django: Django SQL injection                                 │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2025-64459                   │
│         ├────────────────┼──────────┤        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2019-14232 │ HIGH     │        │                   │ 1.11.23, 2.1.11, 2.2.4 │ Django: backtracking in a regular expression in              │
│         │                │          │        │                   │                        │ django.utils.text.Truncator leads to DoS                     │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2019-14232                   │
│         ├────────────────┤          │        │                   │                        ├──────────────────────────────────────────────────────────────┤
│         │ CVE-2019-14233 │          │        │                   │                        │ Django: the behavior of the underlying HTMLParser leading to │
│         │                │          │        │                   │                        │ DoS                                                          │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2019-14233                   │
│         ├────────────────┤          │        │                   │                        ├──────────────────────────────────────────────────────────────┤
│         │ CVE-2019-14235 │          │        │                   │                        │ Django: Potential memory exhaustion in                       │
│         │                │          │        │                   │                        │ django.utils.encoding.uri_to_iri()                           │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2019-14235                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2019-3498  │          │        │                   │ 1.11.18, 2.0.10, 2.1.5 │ python-django: Content spoofing via URL path in default 404  │
│         │                │          │        │                   │                        │ page                                                         │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2019-3498                    │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2019-6975  │          │        │                   │ 1.11.19, 2.0.11, 2.1.6 │ python-django: memory exhaustion in                          │
│         │                │          │        │                   │                        │ django.utils.numberformat.format()                           │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2019-6975                    │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2020-9402  │          │        │                   │ 1.11.29, 2.2.11, 3.0.4 │ django: potential SQL injection via "tolerance" parameter in │
│         │                │          │        │                   │                        │ GIS functions and aggregates...                              │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2020-9402                    │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2022-36359 │          │        │                   │ 3.2.15, 4.0.7          │ An issue was discovered in the HTTP FileResponse class in    │
│         │                │          │        │                   │                        │ Django 3.2...                                                │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2022-36359                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2025-57833 │          │        │                   │ 4.2.24, 5.1.12, 5.2.6  │ django: Django SQL injection in FilteredRelation column      │
│         │                │          │        │                   │                        │ aliases                                                      │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2025-57833                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2025-64458 │          │        │                   │ 5.2.8, 5.1.14, 4.2.26  │ Django: Denial-of-service vulnerability in Django on Windows │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2025-64458                   │
│         ├────────────────┼──────────┤        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2017-12794 │ MEDIUM   │        │                   │ 1.10.8, 1.11.5         │ python-django: Possible XSS in traceback section of          │
│         │                │          │        │                   │                        │ technical 500 debug page                                     │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2017-12794                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2018-14574 │          │        │                   │ 2.0.8, 1.11.15         │ django: Open redirect possibility in CommonMiddleware        │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2018-14574                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2018-7536  │          │        │                   │ 2.0.3, 1.11.11, 1.8.19 │ django: Catastrophic backtracking in regular expressions via │
│         │                │          │        │                   │                        │ 'urlize' and 'urlizetrunc'                                   │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2018-7536                    │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2019-12308 │          │        │                   │ 1.11.21, 2.1.9, 2.2.2  │ django: missing URL validation by AdminURLFieldWidget leads  │
│         │                │          │        │                   │                        │ to generation of clickable unsafe...                         │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2019-12308                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2019-12781 │          │        │                   │ 2.1.10, 2.2.3, 1.11.22 │ Django: Incorrect HTTP detection with reverse-proxy          │
│         │                │          │        │                   │                        │ connecting via HTTPS                                         │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2019-12781                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2021-33203 │          │        │                   │ 2.2.24, 3.1.12, 3.2.4  │ django: Potential directory traversal via ``admindocs``      │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2021-33203                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2024-45231 │          │        │                   │ 5.1.1, 5.0.9, 4.2.16   │ python-django: Potential user email enumeration via response │
│         │                │          │        │                   │                        │ status on password reset                                     │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2024-45231                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2025-48432 │          │        │                   │ 5.2.2, 5.1.10, 4.2.22  │ django: Django Path Injection Vulnerability                  │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2025-48432                   │
│         ├────────────────┼──────────┤        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2018-7537  │ LOW      │        │                   │ 2.0.3, 1.11.11, 1.8.19 │ django: Catastrophic backtracking in regular expressions via │
│         │                │          │        │                   │                        │ 'truncatechars_html' and 'truncatewords_html'                │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2018-7537                    │
├─────────┼────────────────┼──────────┤        ├───────────────────┼────────────────────────┼──────────────────────────────────────────────────────────────┤
│ jinja2  │ CVE-2019-10906 │ HIGH     │        │ 2.10              │ 2.10.1                 │ python-jinja2: str.format_map allows sandbox escape          │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2019-10906                   │
│         ├────────────────┼──────────┤        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2020-28493 │ MEDIUM   │        │                   │ 2.11.3                 │ python-jinja2: ReDoS vulnerability in the urlize filter      │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2020-28493                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2024-22195 │          │        │                   │ 3.1.3                  │ jinja2: HTML attribute injection when passing user input as  │
│         │                │          │        │                   │                        │ keys to xmlattr...                                           │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2024-22195                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2024-34064 │          │        │                   │ 3.1.4                  │ jinja2: accepts keys containing non-attribute characters     │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2024-34064                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2024-56326 │          │        │                   │ 3.1.5                  │ jinja2: Jinja has a sandbox breakout through indirect        │
│         │                │          │        │                   │                        │ reference to format method...                                │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2024-56326                   │
│         ├────────────────┤          │        │                   ├────────────────────────┼──────────────────────────────────────────────────────────────┤
│         │ CVE-2025-27516 │          │        │                   │ 3.1.6                  │ jinja2: Jinja sandbox breakout through attr filter selecting │
│         │                │          │        │                   │                        │ format method                                                │
│         │                │          │        │                   │                        │ https://avd.aquasec.com/nvd/cve-2025-27516                   │
└─────────┴────────────────┴──────────┴────────┴───────────────────┴────────────────────────┴──────────────────────────────────────────────────────────────┘
