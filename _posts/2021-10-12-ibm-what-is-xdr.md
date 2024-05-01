---
layout: post
title:  "SI.com - 2021 // What is XDR?"
date:   2021-10-12 17:51:10 +0000
categories: tech
tags: xdr, infosec 
---

_originally published on IBM [securityintelligence.com](https://securityintelligence.com/posts/what-is-extended-detection-response/), 2021-10-12._

Extended detection and response (XDR) is a security solution that delivers end-to-end visibility, detection, investigation and response across multiple security layers. Core components of an XDR architecture include federation of security signals, higher-level behavioral and cross-correlated analytics, and closed-loop and highly automated responses. This creates a truly unified experience supported by a solutions architecture that equals more than the sum of its parts. Security teams are able to get more value from an XDR that meets the following criteria:

-   Supports open standards
-   Delivers advanced analytics
-   Provides a simpler, unified analyst experience
-   Streamlines operations
-   Enhances response through automation

An XDR solution can achieve improved visibility across an organization’s networks, endpoints, SIEM and more via open-system integration. Open source standards can help move the industry away from expensive and wasteful ‘rip and replace’ programs. Instead, an open approach helps organizations get more out of their existing investments.

An XDR solution can also offer more automation and AI enrichments at all levels of detection, analytics, investigation and response. Automation throughout the threat life cycle can dramatically reduce mean time to detect (MTTD) and mean time to recovery (MTTR). Not only does reducing these metrics have a direct relationship to mitigating the cost of a data breach, it also frees up time for analysts to do more human-led activities like investigation. An XDR solution also bolsters investigation with a unified view of threat activity, a single search and investigation experience and consistent enrichment with threat intelligence and domain expertise.

## Is XDR Just Another Acronym or a Fundamental Market Shift?

For many decades now, emerging threats have put organizations at risk. As the IT landscape evolved and threat actors found new ways to attack, security teams needed to find new ways to detect and respond to threats.

Today, this evolving theme of complexity continues. And the list of point solutions being deployed to overcome these burgeoning threats goes on and on — from SIEM, to cloud workload protection, to endpoint detection and response (EDR), to network detection and response (NDR) and more. While these investments each do their part to solve immediate and dire issues, in combination they’ve created a bigger challenge: how to use and get value from them together.

This is why we call them point tools; they were made to address specific challenges. Now that security teams face a myriad of challenges, it’s never been more critical to have them work in concert. Without doing so, limited security operations resources will continue to be spread thin, total cost of ownership will continue to increase and the process of pinpointing and responding to threats will continue to be time-consuming and inefficient.

Extended detection and response (XDR) is the beginning of a shift towards uniting multiple siloed solutions and reducing the complexity that impedes fast detection and response. As stated in the blog [Gartner Top 9 Security and Risk Trends for 2020](https://www.gartner.com/smarterwithgartner/gartner-top-9-security-and-risk-trends-for-2020/): “The primary goals of an XDR solution are to increase detection accuracy and improve security operations efficiency and productivity.” Gartner identified XDR as the number one security and risk trend at the end of 2020, suggesting now is the moment when all this complexity — too many tools, too many alerts, too little time — is coming to a head, with XDR as a response.

## What Are The Different Approaches to XDR?

Industry analysts have outlined two different approaches to extended detection and response: native and hybrid. Native XDR is a suite that integrates with a vendor’s other solutions to collect telemetry and execute response actions. Hybrid or open XDR is a platform that integrates with various vendors and third parties to collect telemetry and execute response actions.

Vendors have been taking different approaches to what is under the hood of XDR, so to speak. For instance, does XDR = EDR plus additional capabilities? Or is it EDR plus NDR, or some other combination? It might be too soon to tell where the market will land as the technology is nascent, but the delineation between native and hybrid XDR is one thing the industry seems to agree on.

## How Does XDR ‘Extend’ SIEM?

For some readers, SIEM may have immediately come to mind as you perused the qualities of XDR. There are some key differences between the two. Correlation and alerting tend to be fully automated, employing use cases that are provided and tuned by the vendor. Lastly, incident response tends to focus on highly repeatable actions that can be automated, such as sending a suspicious file to a sandbox for detonation, enriching an alert with threat intelligence or blocking an email sender tied to phishing emails. This approach differs from [SOAR](http://www.ibm.com/products/qradar-soar), which can be broadly customized with custom playbooks and used to unite people in addition to technology.

XDR in many ways can extend the detection and response capabilities that are today enabled by SIEM. In fact, SIEM can play an integral role to support an XDR architecture in gathering, organizing and assessing massive amounts of data for SOC analysts. In this capacity, XDR builds on the data and events flowing through your SIEM solution. By bringing together the capabilities of multiple point solutions, XDR can take SIEM analytics one step further and amplify the outcome. As an example, when you receive analytics from a SIEM, endpoints and networks separately, it can be like having three different witnesses to an attack. XDR helps you immediately bring all three witnesses together and create one complete story — helping an analyst see more clearly across multiple sources.

XDR is not just a place where you consolidate security signals but a place where you can run more advanced, correlated analytics. As [The Forrester Wave for Security Analytics Platforms, Q4 2020](https://www.ibm.com/account/reg/us-en/signup?formid=urx-48770) asserts, security analytics and endpoint detection and response have been on a “collision course” for some time. Bringing together these capabilities with XDR can provide “highly enriched telemetry, speedy investigations, and automated response actions.” Behavioral analytics or machine learning analytics can also enrich content, increase accuracy and lead to automated response actions.

## How Does XDR Compare to MDR?

Even though XDR vendors are striving to untangle the complexity problem, it will take time to make inroads. Compounding this challenge is the skills shortage. The dire need for talent to run security analysis and investigations leads many organizations to utilize a partner for [managed detection and response (MDR) services.](https://securityintelligence.com/posts/managed-detection-and-response-provider-outcomes/)

MDR is an approach to managing sophisticated detection and response tools — whether via endpoint, network or SIEM technology. Some MDR providers include proactive threat hunting to reveal undetected threats faster. Research from [EMA](https://www.ibm.com/account/reg/us-en/signup?formid=urx-46315) conducted in 2020 found that 94% of respondents not already using an MDR service were currently evaluating or had plans to evaluate MDR services over the next 18 months.

MDR services can provide critical skills and advanced threat intelligence, plus rapid response with 24/7 SOC coverage. As Jon Oltsik, senior principal analyst at [ESG](https://www.esg-global.com/blog/why-xdr-must-include-mdr?utm_campaign=Data%20Protection%202018&utm_medium=email&_hsmi=118680228&_hsenc=p2ANqtz--q3kkVG10zbdQ6Hrw48UYz2yPEEqqlHpVl5ozTsiRGnMYFjZzoBSkyla5ijBgP9AK6CM0aCWERxytzhb8PW_7FOIjGtg&utm_content=118680228&utm_source=hs_email), stated, “XDR success still seems to be based on human expertise,” making MDR an invaluable companion to XDR for customers who could use a helping hand.

## How Does XDR Support Customers With Zero Trust Aspirations?

If you set up a game of security buzzword bingo, there’s no doubt you’d come across both zero trust and XDR. There’s industry chatter around these powerful security frameworks with good reason — one concept can help enforce the other.

[Zero trust](https://www.ibm.com/security/zero-trust) is a framework that starts with an assumption of compromise, then continuously validates the conditions for connection between users’ data and resources to determine authorization and need. XDR provides an essential function to zero trust by continuously monitoring for incidents and responding in the most targeted way possible to avoid disruption to the business.

How so? XDR enables analysts to determine if their organization is under attack and figure out as quickly as possible what’s happening, what will happen next and how to prevent that from unfolding. Instead of placing blind trust in a system and saying the controls are enough, with XDR you constantly monitor the places where things could go wrong.

In this way, XDR is ensuring that zero trust security controls are working. The ‘never trust, always verify’ zero trust methodology is supported by verification. When it comes to detecting and responding to threats, as well as improving protection policies based on insights, a zero trust framework and an XDR solution can work hand in hand. And it’s exactly why identity tools, such as identity and access management (IAM), will play a critical role tying into XDR solution architectures to ensure the appropriate user-centric context is being employed for threat detection and response.

## What Should Customers Look for in an XDR Solution?

Your XDR should be an open, extensible solution that enables your organization to get more from its existing investments. Look for integrations with third parties that will save your organization from a costly and unrealistic rip-and-replace approach. Cloud-native solutions are also critical for extending cloud visibility.

XDR goes far beyond being an improved EDR solution; it should instead be your end game for threat detection and response activities — as part of a unified platform. Reaching that level of maturity is a goal that takes time, with the basics in place and a clear strategy as prerequisites for how to get started with XDR. With powerful automation, artificial intelligence and expert-built detection and prescribed response actions available through a unified user experience, security teams can counter attacks across silos — mitigating risk and resolving threats fast.

Ultimately, XDR makes it easier for the people managing and responding to threats on a daily basis to do the work. Open standards mean we can better serve customers and the community, preventing time and dollars lost to ripping and replacing technology. Advanced analytics, constantly updated threat intelligence and a streamlined user workforce empower analysts to be more efficient and spend their valuable time on investigations — not gathering the data.

[People and culture](https://securityintelligence.com/posts/the-importance-of-people-and-culture-within-the-security-operations-center/) are the keys to the SOC. By uniting threat detection data and tools and strengthening ability and context for fast incident response, XDR enables the collaboration and openness that helps teams thrive.

_**Learn more about realizing a vision for XDR in ‘[Beyond Endpoints: A Case for Open XDR’](https://www.rsaconference.com/library/Presentation/USA/2021/beyond-endpoints-a-case-for-open-xdr), presented at the RSA Conference 2021.**_

Offering Manager - Threat Detection & Response
