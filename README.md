<p align="center">
  <a href="https://ag.tavardt.com/ca/">
    <img src="https://ag.tavardt.com/img/tavardt-banner.png" alt="TAVARDT" width="1024" />
  </a>
</p>

# Mobile SEO and Responsive Design Validator

[![Mobile SEO Validator](https://img.shields.io/badge/TAVARDT-Mobile%20SEO-5b3cf5.svg)](https://tools.tavardt.com/ca/mobile-seo-checker/)
[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)

Audits mobile-first indexing readiness, meta viewport directives, fixed-width layout overflow, font legibility, and touch ergonomics.

***

## Risk Vectors and Operational Impact in Mobile Web Experience

Web assets lacking appropriate viewport configuration fail Google mobile-first benchmarks and lose critical organic visibility across Canadian markets. Defective layouts force horizontal scrolling and produce substandard mobile customer journeys.

Disabling user scaling creates compliance liabilities under web accessibility mandates and frustrates visually impaired visitors. Rigid pixel widths and minute typography increase bounce rates and weaken search discovery performance.

***

## Core Technical Audit Capabilities

* **Viewport Directive Analysis**: Inspects meta viewport tags for presence, device-width configuration, initial scale, and locked zooming, deducting up to 45 points when missing.
* **Horizontal Overflow Detection**: Scans CSS definitions for hardcoded container widths exceeding 450px that trigger horizontal scrolling on mobile viewports.
* **Typography and Legibility Audit**: Identifies sub-scale font size declarations under 12px, penalising unreadable text up to 15 points.
* **Interactive Touchpoint Quantification**: Maps links, buttons, and form inputs to evaluate touch ergonomics and interface density across mobile viewports.
* **Touchscreen Icon Validation**: Confirms the declaration of apple-touch-icon links in the HTML head, deducting 5 points when absent.
* **Mobile Ergonomics Rating**: Calculates an objective 0 to 100 quality score categorising results into SATISFACTORY, ADVISORY, or UNSATISFACTORY.
* **Smartphone Emulation Engine**: Performs live HTTP inspection using an authentic Safari mobile User-Agent string to guarantee accurate responsive evaluation.

***

## Installation and Execution

Requires Python 3.8 or higher utilizing only Python standard libraries.

```bash
git clone https://github.com/TAVARDT-Canada/mobile-seo-tester-ca.git
cd mobile-seo-tester-ca
python mobile_seo_tester.py https://company.ca
```

To output structured JSON for automated integration and continuous mobile compliance audits:

```bash
python mobile_seo_tester.py https://company.ca -j
```

***

## Technical Frequently Asked Questions

### 1. How does a missing or malformed meta viewport tag impact mobile-first indexing?
Search engine crawlers evaluate web pages exclusively using mobile viewport emulation. When the viewport tag is absent or lacks device-width declarations, mobile browsers default to desktop dimensions, triggering severe ranking penalties for non-responsive layouts.

### 2. Why does the auditor penalise disabling user zooming with locked scalability settings?
Disabling user scaling creates critical accessibility barriers under WCAG guidelines for users requiring magnification to read content. Modern search engine algorithms flag locked viewports as usability defects that degrade the overall mobile experience score.

### 3. How do hardcoded container widths exceeding 450px harm mobile page performance?
Elements with fixed CSS pixel widths wider than 450px force horizontal viewport scrolling on modern mobile screens. Horizontal overflow breaks responsive design grids and causes immediate mobile usability failures in automated search engine evaluations.

### 4. What operational risks are associated with typography declared under 12px?
Text rendered below 12px requires manual zooming or excessive effort to decipher on high-density smartphone screens. Automated mobile audits deduct usability points for sub-scale fonts to guarantee effortless reading without user intervention.

### 5. Why is configuring an apple-touch-icon important for mobile brand discovery?
The apple-touch-icon directive ensures that browsers and mobile operating systems render high-resolution brand icons when users bookmark web apps to home screens. Omitting this link produces generic lettermark tiles and diminishes brand recognition across mobile bookmark ecosystems.

***

## Mobile SEO and Responsive Architecture Advisory

For multi-region digital portals requiring strict alignment with Google Mobile-First Indexing and W3C Responsive Standards, consult the engineering team at **TAVARDT**.

***

## Useful Links

* **Corporate Portal:** https://ag.tavardt.com/ca/
* **Diagnostic Suite:** https://tools.tavardt.com/ca/
* **Technical Contact:** https://ag.tavardt.com/ca/contact/

***

### License
Distributed under the MIT License. See the LICENSE file for complete terms.

***

© 2026 TAVARDT. All rights reserved.
