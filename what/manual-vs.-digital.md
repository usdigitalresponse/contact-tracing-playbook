---
description: Why not just do it with an app?
---

# Manual vs. digital

[Exposure notification \(also known as digital contact tracing\)](%20https://medium.com/u-s-digital-response/understanding-digital-contact-tracing-limitations-implications-and-recommendations-fb54d23f586c) is a new and largely untested automated approach to contact tracing. 

Exposure notification uses information shared via mobile device to notify people who might have had contact with someone infected. While manual contact tracing can take time due to the need for individual interviews, exposure notification makes it possible to identify hundreds or thousands of at-risk persons almost immediately. This is usually done by logging “close contact” events between Bluetooth-enabled mobile phones. If someone is reported to be sick, their log of contact events would be used to alert anyone physically near them within the infectious period. Note that if the application only goes so far as alerting potentially affected individuals, and does not assist with interviews, testing, and follow-up monitoring, it’s better described as [“Exposure Notification”](https://harper.blog/2020/04/22/digital-contact-tracing-and-alerting-vs-exposure-alerting/).

## Advantages of exposure notification

* Immediate, once automated
* Based on objective distancing data
* Doesn't require a human workforce, making it cheaper and safer

## Challenges of exposure notification

#### Adoption remains low

According to research, [60–80 percent adoption](https://ethics.harvard.edu/files/center-for-ethics/files/white_paper_5_outpacing_the_virus_final.pdf) is required to make exposure notifications effective. This level of adoption would require massive, population-level awareness, trust, and engagement of the sort few apps or features on the market enjoy. For reference, Android’s latest version, “Pie”, took a [year to achieve 20% adoption](https://venturebeat.com/2019/10/23/android-pie-passes-20-adoption-after-12-months/). However, iOS has [60% market share](https://gs.statcounter.com/os-market-share/mobile/united-states-of-america) and a faster adoption cycle.

Here are the principles that are critical for apps or settings to achieve adoption:

* **Data privacy.** People are understandably wary of sharing private health and location data with corporations and the government. To address this, solutions should implement solutions like [contact event numbers and decentralized local storage](https://tcn-coalition.org/). This [unified set of data and privacy guidelines for contact tracing and exposure notification](https://contacttracingrights.org/) was created to educate developers and inform end-users of the data rights they should expect any effective solution to respect.
* **Interoperability.** Apps should be capable and willing to share data formats to enable data to be aggregated for broader public health use. Apple and Google allow one app per jurisdiction \(state, city, or county\) to deploy exposure notifications APIs, meaning there could be dozens of apps available. No single app is likely to reach 60%+ adoption, but all apps working together have a much better chance. Developers should use openly published protocols and work collaboratively to ensure their solutions are verifiable and interoperable. 
* **Trustworthy.** Brand matters. If an app is nefarious or perceived as such, it could create broad public distrust and lowering likelihood that _any_ exposure notification technology gets adopted.

#### False positives

Even with 100% adoption, opt-in, and Bluetooth enablement, there are still challenges with efficacy.

A false positive occurs when a contact is notified who wasn't at meaningful risk of transmission. This can happen for a variety of reasons including:

* The app isn’t aware there’s a wall between you and someone infected.
* Not every contact is a transmission.

False positives can hurt adoption due to distrust. For example, if someone chooses to quarantine, but doesn’t get sick, there’s a strong incentive to stop using it. Tests can alleviate this problem by limiting quarantines to those that are sick, but still create disincentive given the time, discomfort, and potential cost needed for the test.

#### False negatives

A false negative occurs when an app fails to register a transmission. These happen for a variety of reasons, including:

* An infected person transmitted the virus without being in close contact \(e.g., by touching the same surface\). 
* Transmission occurred via someone who didn't have the app.

### Other challenges

* Bluetooth must always be on, your phone must always be in your pocket, and powered on.
* [19% of the US doesn’t have a smartphone](https://www.pewresearch.org/internet/fact-sheet/mobile/). [Rural areas have 71% smartphone adoption](https://www.pewresearch.org/internet/fact-sheet/mobile/) and [53% of those over the ages of 65 have a smartphone](https://www.pewresearch.org/internet/fact-sheet/mobile/), meaning over half of them won’t be able to be notified of a potential exposure or notify close contacts if they’re infected
* For both exposure notifications and manual contact tracing ubiquitous, cheap, fast, and accurate testing is critical. Otherwise, false positives and quarantines will be significantly higher than needed. For exposure notifications, this means decreasing public trust and lower adoption.

## Summary

Given these challenges, exposure notification technology is a fragile, unproven method to inform those exposed. It’s critical that governments aggressively ramp up manual contact tracing as an immediate solution.  


\[Good link: [https://www.cdc.gov/coronavirus/2019-ncov/downloads/digital-contact-tracing.pdf](https://www.cdc.gov/coronavirus/2019-ncov/downloads/digital-contact-tracing.pdf)\]

{% page-ref page="asymptomatic-cases.md" %}



