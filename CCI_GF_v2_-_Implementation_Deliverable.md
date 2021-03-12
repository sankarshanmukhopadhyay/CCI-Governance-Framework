# CCI GF v2 - Implementation Deliverable

![](https://lh5.googleusercontent.com/z4D7GQCku68yt8OzMhgcqz5sfozAxDuuNWdFscEYKaaWJbK4ZbbIVkCFX56djdOFgFJCljkVGvjPC-S6LZ34Xv07p-9BPcxk9mWlRd--vz2FeFxHvjHBd1kR1AdcrSrrL18ztiXA)





 
**COVID-19 Credentials Initiative (“CCI”)**
**Governance Framework V2.0**
**PUBLIC REVIEW DRAFT**
 
 
 
 
**9 NOVEMBER 2020**
 
 
 
 
 
 
This CCI Governance Framework (the “**CCI GF**”) V2.0,
was developed and approved by the CCI Governance Framework Task Force.
The CCI GF Task Force operates within the [Trust Over IP Foundation](https://trustoverip.org/).
 
 
***NOTE:***    *This document includes references and content from the Sovrin Governance Framework Master Document (*[*https://sovrin.org/wp-content/uploads/Sovrin-Governance-Framework-V2-Master-Document-V2.pdf*](https://sovrin.org/wp-content/uploads/Sovrin-Governance-Framework-V2-Master-Document-V2.pdf)*).*




















This page left intentionally blank

**Table of Contents**
[**Acknowledgements**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.na8ipo6bw6tb)    **5**
[**Requirements Notation and Conventions**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.8rjuodva7wjh)    **6**
[**Introduction**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.btm9jj429t4p)    **7**
[**Purpose**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.npcm9nikcsx8)    **9**
[**Scope**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.pjg5xtltz43z)    **9**
[**CCI GF Principles - Three Perspectives**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.4lcl30difuen)    **9**
[**Foundational Principles    1**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.qf019r5s57ex)0
[Openness and Interoperability    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)0
[Accountability    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)0
[Sustainability    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)0
[Maintain Consistent Experience    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)1
[Censorship Resistant    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)1
[Privacy Preserving    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)1
[Protection against coercion    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)2
[Ethical By Design and Default    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)2
[Inclusion By Design and Default    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)4
[Data protection compliance by design and by default    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)4
[**Technology Principles    1**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.a7vu4zl17v69)6
[Privacy By Design    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.atsety6w6cyj)6
[Decentralization By Design    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.6rv559abpv5d)6
[High Availability    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.8w4otx26p891)6
[No Single Point of Failure    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.a3vay4zi0awa)7
[W3C DID Core Compliant    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)7
[W3C VC Data Model Compliant    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)7
[Owner Controlled Storage By Default    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)7
[Anti-Correlation By Design and Default    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)7
[Guardianship and Delegate Confidentiality    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)7
[Security By Design    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)7
[Least Privilege    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)8
[Data Protection By Design and Default    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)8
[Accuracy    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)8
[Integrity and Transparency    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)8
[Authenticated Access    1](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)8
[Purpose Limitation](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)    19
[Data Minimization](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)    19
[Storage Limitation](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)    19
[**Governance Principles**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.jluenf302j99)    **19**
[Lawfulness, Fairness and Transparency    2](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.o59xav46ckfd)0
[Storage Jurisdiction    2](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)0
[Governance Framework Disclosure By Default    2](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.4cpo3dee9pfb)0
[Data Subject or Identity Controller Rights    2](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)0
[Service Provider Attestation to Preserving and Safeguarding Rights    2](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.g1mih4lked8k)1
[Guardianship    2](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.9bgwqpgtjiew)1
[Collective Best Interest    2](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.ft6elcagdfud)2
[**Appendix A: Glossary    2**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.9ohaply9hr3v)**3**
[**Appendix B: Risk Assessment and Management    2**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.f9ltvnpzfmd)**6**
[**Appendix C: Practical Examples - Verifiable Credential Use Cases**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.hwxzluq8jwc2)    **29**
[**Appendix D: Foundational Principles Checklist    3**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.q3p250ubaful)**1**
[**Appendix E: Verifiable Credential Levels of Assurance    3**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.ypt86cegcvpu)**5**
[**Appendix F: Trust Assurance Model    3**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.pvqtez18wjdn)**7**
[**Appendix G: Healthcare Data Security and Privacy    3**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.p176yqv6j7q2)**9**
[**Appendix H: Data Protection legislations    4**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.xk3z679lreyr)**0**
[**Resources & References    4**](https://docs.google.com/document/d/1s7oEESllR9pa4ecXNGfougaHmDBzDBh1KHKvIsy0dPw/edit#heading=h.rlk3alqvgcyg)**2**


# Acknowledgements

The CCI Governance Framework (CCI-GF) has been developed through the contributions of knowledge, experience and expertise of a large number of global individuals. The CCI- GF Task Force would like to acknowledge their contributions and participation in the discussions forums. Key contributors include:

| **Name**           | **Country/Region** | **Name**       | **Country/Region**  |
| ------------------ | ------------------ | -------------- | ------------------- |
| Dele Atanda        |                    | Eric Drury     |                     |
| Ramon Bernabeu     |                    | Rieks Joosten  |                     |
| Jacques Bikoundou  | North America      | Line Kofoed    | The Netherlands     |
| Thomas Cox         | Canada             | Kohei Kurihara | Japan               |
| Oskar Van Deventer | Netherlands        | Indira Mysore  | USA / North America |
| Eddie Kago         |                    | Scott Perry    | USA                 |
| Dennis Landi       |                    | Robin Renwick  | Ireland             |
| Markus Mummert     |                    | Tony Rose      | USA                 |
| Keerthi Thomas     |                    | Ser-Huang Poon | Singapore           |
| Jim St.Clair       | USA                | Alex Tweeddale | UK                  |
| Celia Yeung        | Hong Kong          | Lucy Yang      | Canada              |
| Chris Raczkowski   | Canada             | Sankarshan M   | India               |


The CCI-GF Task Force would like to especially thank Kelly Cooper for her inputs, suggestions and improvements to the readability and structure of this document; Drummond Reed for his wide-ranging expertise in the principles of Self-Sovereign Identity and how they apply to technology interventions around the COVID-19 pandemic; Scott Perry for his contributions on the topic of Risk Assessment and Management; Paul Knowles and The Kantara Initiative for the work on Blinding Identity Taxonomy; Karl Kneis and Mike Vesey for their assistance as chairs of the Ecosystem Foundry Working Group at the Trust over IP Foundation.

# Requirements Notation and Conventions

The following conventions which appear in this document are adopted from the Digital Identity Guidelines ([NIST SP 800-63-3](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-63-3.pdf)) and are to be read alongside IETF RFC 2119 to guide adoption of the CCI-GF.

1. The terms “**SHALL**” and “**SHALL NOT**” indicate requirements which are to be followed strictly in order to conform to the intent of the CCI GF and from which no deviation is permitted.
2. The terms “**SHOULD**” and “**SHOULD NOT**” indicate that among several possible approaches, one is recommended. This does not exclude the others or indicate a preference, nor does it state that a course of action is discouraged but not prohibited.
3. The terms “**MAY**” and “**NEED NOT**” indicate a choice that is allowed within the intents and purposes of the CCI GF
4. The terms “**CAN**” and “**CANNOT**” indicate a possibility and capability, whether material, physical or causal or, in the negative, the absence of that possibility or capability. 




# Introduction

The year 2020 has proven to be a turning point in human history, where a pathogen, SAR-CoV-2, a virus that causes a range of illnesses generally referred to as COVID-19, has significantly and negatively impacted global societies and economies. To facilitate a return to fully functional societies, W3C Verifiable Credentials (a “**VC”** or “**VCs”**) have been identified as a valuable tool. VCs provide a secure, privacy-protecting method for saving valuable and sensitive information as trusted digital data that can be used to enable individuals and societies to manage and recover from the social and economic impacts of the COVID-19 pandemic.
 
For example, a COVID-19 related VC (e.g. virus test, antibody test, vaccination, etc.) for an individual can be recorded as a VC, enabling that individual (the VC “**Holder**”) to privately and securely prove (a digital “**Proof**”) to any other person (a VC “**Verifier**”) their vaccination or test result status. The VC Proof can be cryptographically linked back to the COVID-19 vaccination administrator and VC Issuer (the “**Issuer**”; for example, a trusted medical professional). In this way, the Verifier is able to place *trust* in a known or otherwise trusted Issuer of a VC, via secure, open-source, cryptographic protocols. This process is represented by the following diagram:

![](https://lh4.googleusercontent.com/YtXrUbHf_WNRmYPeg2dfPxilEU4qZ1Zno9nj0g64VIvJ2T7KW55xX2PNm6-Vd1ij7YbmbcMHJDUxTYfFeXdpqKpHgp6ReQ0FPdzydFEqFKBC3on9Vx-1XxfAmGLRklYN2DbDB3T5)


Figure 1:  The Verifiable Credentials Trust Triangle (illustration credit: [https://www.w3.org/TR/vc-data-model/](https://www.w3.org/TR/vc-data-model/))
For more information about VC technology and governance, please refer to [](https://www.w3.org/TR/vc-data-model/#terminology)[W3C Verifiable Credentials Data Model 1.0 Terminology](https://www.w3.org/TR/vc-data-model/#terminology), the [Trust Over IP Foundation](https://trustoverip.org/), and [](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8/edit)[The Sovrin Governance Framework Glossary](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8/edit)**.**
 
The CCI Governance Framework (the “CCI GF”) is an open source document that provides general principles, policies, and guidance for VCs being used for COVID-19 related use cases, with the aim of:
 

- protecting individuals (issuers, holders and verifiers),
- reducing utilization friction,
- ensuring regulatory compliance,
- shaping best practices.

 
CCI GF principles reflect the overarching spirit of VCs, which includes individual control of their personal data, privacy by design, and inclusivity for all people, organizations and cultures. 
The CCI GF is intended to be relevant and applicable in many jurisdictions and circumstances. Because global social, legal, and political landscapes are diverse, the CCI GF is a principles-focused VC governance framework that can be referenced and adopted as a foundational governance document for the widest possible range of jurisdictions and use cases. The CCI GF primarily provides flexible principles, rather than black-and-white rules, allowing people and organizations around the world to utilize the CCI GF in a manner that is suitable for their situation, while following the founding principles and spirit of VCs, particularly: (1) individual control of VCs, (2) privacy and confidentiality by design, and (3) inclusivity for all people, organizations and cultures.
This document is organized into the following sections:

- The 3 overarching principles
    - Foundational Principles
    - Technology Principles
    - Governance Principles
- Appendices
- Resources

The overarching principles provide the logical foundation for grouping additional aspects of the governance framework which relate to accountability, equity, access, privacy and security.
 

# Purpose

The fundamental purpose of the CCI Governance Framework (the “CCI GF”) is to provide an open source set of governing principles and rules to help guide the implementation and use of any COVID-19 associated VCs and their practical application. The document describes an open standards based VC implementation framework to protect issuers, holders, and verifiers; reduce VC utilization friction; assure regulatory compliance; and shape best practices for implementing COVID-19 VC use cases. 
The ultimate goal of the CCI GF is to provide a governance framework for individuals and organizations that utilize VCs to help mitigate the spread of COVID-19 and strengthen our societies and economies. The intended audience of this document includes individuals, governments, NGOs, businesses, healthcare providers, healthcare workers, health insurance companies, public sector and private sector testing labs, and other organizations who need to deal with COVID-19.

# Scope

The CCI GF provides governance for Verifiable Credentials related to any use cases that are directly focused on COVID-19 mitigation and management. This scope includes VCs for identification of individuals (e.g. medical professionals, public health professionals, first responders, patients), laboratory medical test results (e.g. COVID-19 antigen test), wellness assessment results (e.g. body temperature), vaccinations, etc. The Sovrin Governance Framework V2 (the “**SGF V2**”) is the foundational GF on which the CCI GF is based, and all aspects of the SGF V2 are adopted by the CCI GF. From a governance structure perspective, the CCI GF is considered to be a Layer 3 GF, within the Trust Over IP Stack (see slide 20 of the following presentation: [Trust Over IP Primer](https://trustoverip.org/wp-content/uploads/sites/98/2020/05/toip_050520_primer.pdf)).

# CCI GF Principles - Three Perspectives

This governance framework recognizes three distinct categories of principles and requirements necessary to govern safe, fair and equitable implementation of VCs for COVID-19 use cases. 

## Foundational Principles

The Foundational Principles include the core and inviolable aspects of the Governance Framework. Read together, these principles represent the overall policy guidance to which any system which adopts this Governance Framework for its activities agrees to adhere. The principles define the values around which technology will be designed and services will be deployed to end users of the system.

## Technology Principles

The Technology Principles represent the necessary technical choices to be made when transforming the guidelines of the foundational principles into actual end-user centric systems.

## Governance Principles

The Governance Principles are guidelines for governing VC infrastructure based on the Technology and Foundational Principles. The Principles provide specific purpose-oriented statements about the specific roles and process to be put in place in order to enable strong human-centric adoption of the governance framework.

# Foundational Principles
## Openness and Interoperability

The CCI GF strongly advocates, promotes and supports development mechanisms that allow identity Controllers to experience interoperability or portability of their identity data to other networks and systems in alignment with " W3C open standards" for VC and DIDs  

## Accountability

The GF Governance Authority, and possibly other stakeholders, that choose to implement the CCI GF SHALL be accountable for conformance to the purpose, and principles documented in the CCI GF. All entities adopting the CCI GF SHALL be responsible to demonstrate compliance with any other requirements of applicable law within their jurisdiction(s) of operations. Nothing in the CCI Governance Framework requires a VC solution to breach applicable laws or regulations as presently enacted.

## Sustainability

Implementers of the  CCI GF SHOULD strive to be technically, economically, socially, ethically, and environmentally sustainable, and contribute to the improvement of the well-being of people and the environment. Areas of sustainability include:

- Technically: incorporate interoperable, reusable, non-proprietary technologies;
- Economically: VCs should not present an economic burden to obtain and use;
- Socially: VCs should not exclude or dissuade participation by any individual or social groups;
- Ethically: VCs should not preclude ethical concerns or impacts, both potential or real, from being openly and transparently discussed and mitigated;
- Environmentally: implementers should seek for their implementation to minimize any environment impact..
## Maintain Consistent Experience

Developers adopting the CCI GF SHOULD strive to employ consistent design elements, accessibility, and inclusive language so that end-users can have a safe experience regardless of the specific implementation they are using.

## Censorship Resistant

Implementers of the CCI-GF SHALL utilise VC tools, applications, and services that do not discriminate individuals or groups based on race, ethnicity, religion, health, sexual orientation, membership of organisations (e.g., trade union), or personal beliefs and political opinions.
Implementers shall design solutions so that third parties cannot inappropriately modify or revoke VCs or shut down or deny access to VC services without explicit uncoerced authorization from the Identity Controller.

## Privacy Preserving

The principles of decentralized identity embody the concept that personal identity is inherently inseparable from an individual and the ultimate use of that identity is governed by the credentialed identity Controller. As such, the CCI GF SHALL strongly discourage any use of this framework that results in technical or regulatory privacy infraction, such as surveillance, personal tracking, and abuse. 
Identity Controllers SHOULD respect the privacy, rights, and legal protections of the individuals whose VCs they maintain control of, and implement clear accountability and transparency mechanisms. An individual’s right to be forgotten (i.e. the right for their personally identifiable data to be erased) MUST be promptly honored wherever applicable. 
Any VC developer’s priority SHOULD include design standards that enable and support the right to privacy for users.

## Protection against coercion

Those who adopt the CCI GF SHALL facilitate the protection of the users of applications and systems which have adopted the governance framework against forms of coercion. Such coercion can be designed to force the user to act against their own interests. The governance framework MAY encourage adoption of potential counter-measures against coercion, include the following:

1. Require authoritative verifier. 
2. Require evidence collection. 
3. Require enabling anonymous complaints. 
4. Require remote/proxy verification. 
5. Require complying holder agent. 
6. Require what-you-know authentication.

For additional information on the above approaches please see this RFC.

## Ethical By Design and Default

The CCI GF promotes generally accepted best practices of ethical data collection, management and use.  Ethical data usage is underpinned by principles of privacy, agency and equitability that demonstrate fair, transparent and respectful approaches to the acquisition, storage, processing, publication and commercialization of data.  
Organizations that follow the CCI GF SHOULD determine how their actions could be perceived and avoid potential adverse impacts to stakeholders and their reputation in the future, including how their actions may impact on the perception of the CCI GF itself. Data strategies, processing and acquisition approaches SHALL be adapted to ensure the ethical use of data consistently.
The CCI GF ethical data collection, management and use principles are as follows:

1. Private personal or organization information (the “PPOI”) and the identities of natural persons SHALL remain anonymous and private unless otherwise required, unless a PPOI owner otherwise explicitly requests and/or explicitly consents to their data being made available to others, or to further processing, within a clearly defined set of use restrictions,
2. Levels of subject identifiability SHALL be applied carefully, incrementally and appropriately according to reasonable needs and an acceptable level of privacy exposure risk,
3. Any recipient of shared PPOI SHALL treat such PPOI as confidential information;
4. PPOI SHALL be treated as the private property of the appropriate organizations and individuals, with intrinsic value that is respected and protected.
5. Provide individuals with a transparent view of data processing activities and the ability to exercise their rights related to any data processing of PPOI that is not required or permitted by law;
6. Data use activities SHALL be respectful of, and do not interfere with, a person’s self-determination;
7. Data processing approaches and results SHALL not present unfair or prejudicial biases to individuals or groups of individuals. For example, two individuals with the same medical test result status should not be subject to different restrictions based on such test status alone;
8. Set out definitions for data privacy, agency and ownership with a specific ethical context;
9. Recognize that there may be attributable value to PPOI;
10. Adopt principles for allowing transfer of data between data processors and providers at an individual data controller’s request, ensuring rights to data portability;
11. Adopt principles for an open consent process for the use of PPOI or other data;
12. Adopt principles for notification of changes to personal data and change of use of personal data;
13. Adopt principles for correcting data;
14. Adopt principles for erasure of data and ensure fair rights to be forgotten; 
15. Develop policies for arbitration allowing any participating individual or organization the ability to make a claim, and seek recourse for the loss of control of their data.

Organizations that follow the CCI GF SHOULD conduct an ethical impact assessment as per appropriate guidelines, such as those outlined by the European Committee for Standardisation (CEN), Workshop Agreement 17145-2
Privacy-enhancing techniques, including anonymization and pseudonymization, exist and are evolving. Adopters of the CCI GF MUST employ appropriate techniques to  proactively promote ethical data use principles by default.

## Inclusion By Design and Default

Systems and infrastructure that follow the CCI GF must be open to all Individuals and Organizations, on a comparable basis, without exclusion of specific persons, communities, technology limitations, or device availability. Great care for inclusion of underserved populations SHALL be proactively supported and promoted by individuals and organizations that adhere to the CCI GF. Underserved populations include, but are not limited to:

1. Digital limitations (e.g., access to connected devices)
2. Physical or cognitive limitations (e.g., disability or incapacity)
3. Political & social status (e.g., stateless individuals, being a child, a woman, LBTQ+, an Animal, Natural Thing, homeless, etc.)
4. Financial status (e.g., unbanked, unemployed, unemployable)
5. Literacy & language (e.g., low literacy or not speaking a language)
## Data protection compliance by design and by default

The CCI GF provides guiding principles for the practical implementation of decentralized identity use cases for COVID-19. 
For any decentralized identity model to practically work in a real life use case, there must be clarity as to how Decentralised Identifiers (DIDs) and Verifiable Credentials (VCs) fit into global data protection frameworks, such as the General Data Protection Regulation in the European Union.
Given that the VC and DID technical innovations are new, constantly developing, and function in a completely different manner to ‘centralized’ data management models, it is important to clearly lay out:

1. What constitutes personal data in a decentralized identity model, 
2. Who assumes responsibility for managing and controlling this personal data, and 
3. Can decentralized identity enable better data protection compliance by default?

The CCI community have created a [guiding document](https://docs.google.com/document/u/2/d/164S-nNnMHlPZex5lKenuGRhavvt8qeKIdTPHFAD5b_c/) which addresses these overarching questions, drawing on guidance from standardisation initiatives (the International Standards Organisation, German Institute for Standardization, Spanish Data Protection Board, and similar) focused on encryption and hashing, blockchain and distributed ledger technologies, and decentralized identity technology. Specific guidance from these bodies is supplemented by guidance from European Entities such as the European Data Protection Board, the European Parliamentary Research Service, and the European Blockchain Observatory.
That document is applicable to any entity designing VCs, and explains how the architecture of a decentralized identity ecosystem SHOULD be designed to ensure best data protection and privacy protection for individuals (data subjects). For any COVID-19 use case, given the sensitive level of data likely to be contained in VCs, the guidance is particularly pertinent.
The document may be summarised by the following:

1. Personal data should be viewed as any information relating to an identified or identifiable natural person. An identifiable natural person is one who can be identified, directly, or indirectly by the data in question, including both presently, and in the future, taking into account reasonable means, available technologies, and resources required.
2. A hash of personal data is viewed as pseudonymised personal data.
3. Encrypted personal data is viewed as personal data regardless of whether the possibility to decrypt the data remains (existence of decryption key). This is due to the potential of identification of the natural person when coupled to additional data sets (time-stamps, encryption/decryption logs, IP addresses, network related data, additional meta-data, etc). 
4. It is advised that all personal data is maintained off-ledger in compliance with applicable data protection regulations to ensure adequate privacy and data protection for data subjects.
5. Efforts should be made to ensure that the identity holder maintains control (where feasible) of their credentials. In cases where this is not possible, the identity controller shall adhere to its legal obligations, and shall adhere to a adequate governance framework, such as the one currently being read (CCI GF)
6. Any entity considering deployment of a VC based credential system that includes covid related health information (or related health data) shall conduct, dependent on jurisdiction, either a Privacy Impact Assessment (according to [ISO/IEC 29134:2017](https://www.iso.org/standard/62289.html) Information technology — Security techniques — Guidelines for privacy impact assessment) specifications, or a Data Protection Impact Assessment (as per legal requirement of the GDPR, Article 25).
7. Deployers of CCI should attempt to provide the identity holders with credentials that allow for selective disclosure, and preferably through methods such as Zero Knowledge Proofs to ensure best data protection practice.   
https://docs.google.com/document/u/2/d/164S-nNnMHlPZex5lKenuGRhavvt8qeKIdTPHFAD5b_c/

# Technology Principles

The CCI GF promotes technology principles which support the foundational principles outlined in Section 4. The purpose of the technology principles is to identify  necessary technical choices to be made when transforming the guidelines of the foundational principles into actual end-user centric systems.

## Privacy By Design

The design, governance, and operation of CCI credentials SHALL follow the seven principles of Privacy by Design to the greatest extent possible. These principles include: 

1. Proactive not reactive; preventative not remedial
2. Privacy as the default setting
3. Privacy embedded into design
4. Full functionality — positive-sum, not zero-sum
5. End-to-end security — full lifecycle protection
6. Visibility and transparency — keep it open
7. Respect for user privacy — keep it user-centric
## Decentralization By Design

Adopters of the CCI GF SHALL promote the principles of decentralization to the extent considered necessary to address the outcomes desired by the CCI GF. As the business, legal, and technical limitations of decentralization may change over time; the CCI GF Working Group shall continuously examine all points of control, decision, and governance to seek ongoing conformance with this principle.

## High Availability

Adopters of the CCI GF SHALL make efforts to any participating VCs to be designed and implemented within an infrastructure intended to maximize availability for verification and other legitimate uses across multiple output devices ranging from smartphone to paper.

## No Single Point of Failure

Any system which is based on adoption of the CCI GF SHALL mitigate technical and user experience risks originating from any single point of failure. 

## W3C DID Core Compliant

An agent is a piece of software, either acting on an Identity Controller’s device or in a cloud environment, designed to make decisions for the Identity Controller based on permissions set by the Identity Controller. Agents following the CCI GF SHALL be compliant with the W3C DID Core Data Model Specification. In this context, an Agent may be a software program or process used by or acting on behalf of an Entity to interact with other Agents or with distributed ledgers (see Glossary). 

## W3C VC Data Model Compliant

Issuers, Holders, and Verifiers following the CCI GF SHALL issue, hold, and accept VCs that are compliant with the W3C VC Data Model Specification.

## Owner Controlled Storage By Default

Agents SHALL store private data in encrypted data storage, controlled by the Identity Controller by default. Private data storage SHOULD adapt to low- to no-technology environments where control remains with the Identity Controller regardless of device.

## Anti-Correlation By Design and Default

CCI GF designs and implementations SHALL avoid correlation of an Identity Controller, or anything associated with an Identity Controller, without the direct knowledge and informed consent of the Identity Controller.
This is particularly important for architecture which uses distributed ledger technology as a foundational component.

## Guardianship and Delegate Confidentiality

Utilization of a Guardian or Delegate by a CCI GF Identity Owner MAY be confidential and disclosed with required authorization of the Identity Controller (where possible) and the Guardian or Delegate. All instances of Identity Controller, in this document, may be substituted with an authorized Guardian or Delegate.

## Security By Design

The design, governance, and operation of CCI VCs follows the principles of Security by Design and ensures applicable open standards to the greatest extent feasible consistent with the other CCI principles.

## Least Privilege

Access and authorization of the applications, Agents, and network services that use and comprise the CCI GF subscribe to the concept of least privilege.

## Data Protection By Design and Default

Entities that follow the CCI GF, in the processing of data, SHALL adhere to industry best practice data protection principles to the greatest extent feasible. When additional local or transnational data protections apply, entities MUST make every effort to also be consistent with all CCI GF principles. Compliance with the CCI GF does not exclude the need to comply with existing regulations in relevant jurisdictions.

## Accuracy

CCI GF Entity data must be accurate and, where necessary, kept up-to-date. Every reasonable step must be taken to ensure that where personal data is inaccurate it is erased or rectified without delay.

## Integrity and Transparency

CCI GF Entity data processing provides appropriate, measurable security of the data, including protection against unauthorized or unlawful processing, accidental loss, destruction, or damage, using significant technical and organizational measures.

## Authenticated Access

Secure authenticated access to end-user (i.e. Holder) data SHALL be preserved at all times. CCI GF Entity data must, at the minimum, be secured via a PIN or password, but ideally include biometric authentication mechanisms such as fingerprint verification or facial recognition.
PINs and/or passwords requirements SHOULD be sufficiently strong and implement a timeout feature to withstand brute-force attacks.

## Purpose Limitation

For any organization intending to adopt this GF and create an ecosystem using VCs, it will likely need to collect data on customers or patients. As such, Identity Controller information will need to be shared with relevant organizations.
This data is required to be collected for specified, explicit, and legitimate purposes only. Data must not be further processed contrary to this requirement, or repurposed without verifiable approval by a data subject and or Identity Controller. Further processing for archiving purposes in the public interest, scientific and historical research purposes, or statistical purposes, is not considered incompatible with the original processing purposes. Permission for use of anonymized, aggregated, or disaggregated data SHOULD reasonably protect Identity Controller anonymity, and SHALL require approval and/or explicit consent by relevant Identity Controller. 

## Data Minimization

CCI GF Entity data must be relevant and limited to minimum levels of identifiability necessary (starting from a position of anonymity) to the purpose for which it is processed. Data Minimization should ensure that subjects are anonymous by default and that increased levels of identifiability are applied carefully,  incrementally and appropriately according to reasonable needs and a consequently acceptable level of privacy exposure risk.

## Storage Limitation

CCI GF Entity data must be kept in a form which permits identification of Entities for no longer than the minimum duration necessary for processing.

# Governance Principles

The CCI GF embodies the following governance principles. As stated in section 3.3, these principles are the guidelines which enable the scope and nature of roles, processes and trust systems in an information architecture which is built using aspects of the Technology and Foundational Principles. The Governance Principles provide unambiguous statements and assertions around the specific roles and process to be put in place in order to enable a strong human-centric adoption of the governance framework.

## Lawfulness, Fairness and Transparency

CCI GF Entity Data must be processed lawfully, fairly, and transparently to the relevant CCI Entity, or the CCI Entity’s Identity Owner, Guardian, Delegate, or Controller.

## Storage Jurisdiction

Data storage for national level CCI implementations must be in compliance with the government policies regarding the geographical locality of the CCI GF Entity data where relevant.

## Governance Framework Disclosure By Default

CCI GF Entities, SHALL, by default, disclose the Governance Framework under which a Connection is created, an Interaction is performed, or a VC is exchanged. Agents, by default, notify the Identity Owner of conflicts among the Identity Owner’s privacy preferences, the Governance Framework’s privacy policies, and relevant security regulations.

## Data Subject or Identity Controller Rights

Adopters of the CCI GF SHALL accommodate the following rights of any data subject and credential holder:  

1. Right of access provided to the holder's or data subject's own personal data
2. Right to rectification
3. Right to be forgotten (deletion)
4. Right to stipulating processing restrictions (refer to 7.5 Purpose Limitation?)
5. Right to be informed who has received or processed my data or credentials
6. Right to data portability allows holders or data subjects to obtain and re-use personal data or credentials
7. Right to object or to stop processing of personal data or credentials
8. Right not to be profiled or subjected to solely automated decisions

NOTE: these are GDPR principles

## Service Provider Attestation to Preserving and Safeguarding Rights 

VC Issuers that adhere to the CCI GF SHOULD provide clear guidance to users regarding to what level their personal data or credentials are safeguarded or protected. This attestation MAY be legally binding and admissible in a court of law.

## Guardianship 

The CCI GF anticipates that not all individuals have the ability to act on their own behalf, due to temporary and/or permanent incapacitation. In a situation where an individual can not reasonably take action on their own behalf, a Guardian may become formally responsible for the care and wellbeing of said individual, based on the laws and regulations of the relevant jurisdiction, which the CCI GF recognizes. The CCI GF accepts the following definition of Guardianship, which is paraphrased from the Sovrin Governance Framework Glossary V3:
*The legal responsibility of serving as a Guardian. Guardianship maps to the rights and responsibilities defined in prevailing legal constructs such as parent, in loco parentis, legal capacity, and power of attorney. While the term Guardianship applies strictly to natural persons (Individuals) as Dependents, in a more general sense the term can also be applied to Natural Things (such as pets or animals).* 
In keeping with the Guardianship principle as accepted in the Sovrin Governance Framework V2, a Guardian SHOULD:

1. Act in the Dependent person’s best interest.
2. Exercise good judgment and carefully manage responsibilities.
3. Avoid commingling—keep Dependent’s property separate (e.g., separate DIDs, PublicKeys, Wallets, Vaults, etc.).
4. Keep detailed records of all actions taken on behalf of the Dependent.
5. Not violate the Anti-Impersonation principle (section 2.11.5).
6. Be subject to applicable legal structures regarding the granting and revocation ofGuardianships

*[NOTE: Items 1 - 6, above, are adopted directly from the Sovrin Governance Framework Master Document V2.]*

## Collective Best Interest

VC solutions that adopt the  CCI GF SHALL act in the collective best interests of the CCI Community. It does not favor the priorities or benefits of any single Identity Controller, or group of Identity Controllers, over the mission of the CCI Community as a whole.

# Appendix A: Glossary 
## Glossary (attribution Sovrin Foundation [Glossary v3](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8/edit#heading=h.jgdxyglhz3ik))

***Agency***
A service provider that hosts Cloud Agents and may provision Edge Agents on behalf of Entities. Agencies may be Unaccredited, Self-Certified, or Accredited.
***Agent***
A software program or process used by or acting on behalf of an Entity to interact with other Agents or with the Sovrin Ledger or other distributed ledgers. Agents are of two types: Edge Agents run at the edge of the network on a local device; Cloud Agents run remotely on a server or cloud hosting service. Agents require access to a Wallet in order to perform cryptographic operations on behalf of the Entity they represent.
***Business***
An institution (or sometimes, an individual acting as an institution) that seeks to generate economic value by providing goods and services.
***Claims***
Insert text from SGF Glossary
***Confidentiality***
Obligation not to disclose information or the right of an individual to withhold information from others.
***Credential***
A digital assertion containing a set of Claims made by an Entity about itself or another Entity. Credentials are a subset of Identity Data. A Credential is based on a Credential Definition. The Entity described by the Claims is called the Subject of the Credential. The Entity creating the Credential is called the Issuer. The Entity holding the issued Credential is called the Holder. If the Credential supports Zero Knowledge Proofs, the Holder is also called the Prover. The Entity to whom a Credential is presented is generally called the Relying Party, and specifically called the Verifier if the Credential is a Verifiable Credential. Once issued, a Credential is typically stored by an Agent. (In Sovrin Infrastructure, Credentials are not stored on the Sovrin Ledger.) Examples of Credentials include college transcripts, driver licenses, health insurance cards, and building permits. See also [Verifiable Credential](https://www.w3.org/TR/vc-data-model/).
***Data Controller***
As defined by the [EU General Data Protection Regulation](https://en.wikipedia.org/wiki/General_Data_Protection_Regulation) (GDPR), the natural or legal person, public authority, agency, or other body which, alone or jointly with others, determines the purposes and means of the processing of Personal Data.
***Delegate***
An Identity Owner that acts on behalf of another Identity Owner. Formally, a Delegate is the Holder of a Delegation Credential.
***Entity***
A data subject.
***Government***
A federal/national, state/provincial, or local unit of political governance. Governments make, enforce, and adjudicate laws and regulations. They often have a complex internal structure (bureaus, agencies) and special standing in legal systems.
***Guardian***
An Identity Owner who administers Identity Data, Wallets, and/or Agents on behalf of a Dependent. A Guardian is different than a Delegate—in Delegation, the Identity Owner still retains control of one or more Wallets. With Guardianship, an Identity Owner is wholly dependent on the Guardian to manage the Identity Owner’s credentials. 
***Guardianship***
The legal responsibility of serving as a Guardian. In Sovrin Infrastructure, Guardianship maps to the rights and responsibilities defined in prevailing legal constructs such as parent, in loco parentis, legal capacity, and power of attorney. Note that Guardianship is not Impersonation or Delegation. While the term Guardianship in this glossary applies strictly to natural persons (Individuals) as Dependents, in a more general sense the term can also be applied to Natural Things (such as pets or animals). 
***Healthcare Provider***
An institution, often a Business that delivers healthcare-related goods and/or services.
***Healthcare Worker***
An Individual employed by a Healthcare Provider. We assume that the interests of Healthcare Workers are colored by their status as individuals; however, the result is not the simple union of the two perspectives. For example, Individuals may want to travel, and when acting as Healthcare Workers, this is rarely a top priority.
***Identity Controller***
This term refers to the subclassifications of Entity that may be held legally accountable. Identity Controllers include Individuals and Organizations but do not include Things. The actual legal accountability of an Identity Controller for any particular action depends on many contextual factors including the laws of the applicable Jurisdiction, Guardianship, and so forth. 
***Individual***
A natural person, in a legal sense. Individuals are the locus of human rights. They generally value autonomy and privacy. They have health histories and status, and they are the unit of treatment and decision-making for healthcare. They vote, travel, and spend money. They are held legally accountable. In many cases, Individuals are the Holders of VCs. Some individuals are not capable of self-sovereignty due to circumstances; this raises the issue of guardianship.
***Non Governmental Organization (NGO)***
A non-governmental organization that exists to provide services, typically without a profit motive. In some contexts (e.g., refugee camps), NGOs may assume a role that has much in common with a local government.
***Open Standards***
Technical standards that are developed under an Open Governance process; are publicly available for anyone to use; and which do not lock in users of the standard to a specific vendor or implementation. Open Standards facilitate interoperability and data exchange among different products or services and are intended for widespread adoption. Many Open Standards have implementations that are available under an Open Source License.
***Privacy***
State of being undisturbed or free from public attention.

# Appendix B: Risk Assessment and Management

*NOTE:  The content in this section utilizes significant content from material developed by Scott Perry for the* [*Trust Over IP Foundation*](https://trustoverip.org/)*, with specific links provided within the text.*

Any Governance Authority (“***GA***”), or Credential Issuer (“***Issuer***”), which adheres to the CCI GF SHALL make efforts to assess and proactively manage potential risks associated with the issuance, holding and verification of credentials governed by the CCI GF. The level of effort applied to risk assessment and management SHALL be determined exclusively by the relevant GA or Issuer along with potential advisors, and should be based on whatever risk mitigation such entity considers to be reasonable for the associated stakeholder group. The following guidelines for a GA or Issuer are recommended for risk assessment and management efforts. As such, any GA or Issuer:

1. SHOULD identify key risks that MAY negatively affect the achievement of the GF's purpose within its scope,
2. SHOULD include a Risk Assessment process output that provides an assessment of each key risk that the GF is designed to address and mitigate,
3. SHOULD assess which Roles and Processes are vulnerable to each risk and how they are affected,
4. SHOULD include a Risk Treatment Plan (RTP) for how identified risks are treated (e.g. mitigated, avoided, accepted or transferred),

[Reference: [](https://wiki.trustoverip.org/display/HOME/ToIP+Governance+Metamodel)[ToIP Governance Metamodel](https://wiki.trustoverip.org/display/HOME/ToIP+Governance+Metamodel)]

If a GA or Issuer is unfamiliar or not comfortable completing a risk assessment process, along with an appropriate risk management plan, it is recommended that capable advisory support be engaged. However, any decision on how to proceed with this process is at the total discretion of the GA or Issuer. Ultimately, the results of any risk assessment and management effort should be published as one or more supporting documents that are readily available for any credential Issuer, Holder and/or Verifier to review in full.
The CCI GF offers the following list of potential risk categories for assessment in Table 1 (see next page). This list is not comprehensive, and other categories may be required for specific situations. Similarly, any number of the risk categories in Table 1 may be determined to be unnecessary. The ultimate range of risk categories considered by any GA or Issuer can only be decided by such GA or Issuer, potentially with input from qualified advisors and stakeholders.
**Table 1:  Sample Risk Items**
[For a more comprehensive list or potential risk items, see: [ToIP Risk Assessment List](https://wiki.trustoverip.org/display/HOME/Identity+and+Verifiable+Credential+Risks?preview=%2F65735%2F65736%2FRisk+Assessment+Matrix+Template.xlsx)]

| **Governance Authority Risks**                                                 |
| ------------------------------------------------------------------------------ |
| 1. Lack of competence to perform role                                          |
| 2. Lack of appropriate authority                                               |
| 3. Ecosystem Lacks Jurisdictional Acceptance                                   |
| 4. Ecosystem Lacks Industry Acceptance                                         |
| 5. Ecosystem Allowing Inappropriate Actors to Participate in Network           |
| **Issuer Risks**                                                               |
| 6. Credential Issued without sufficient basis                                  |
| 7. Credential Issued before appropriate proofing of basis                      |
| 8. Credential Issued in the wrong format or structure                          |
| 9. Credential issued to impostors                                              |
| 10. Issuer Practices Not Accepted by Ecosystem                                 |
| **Verifier Risks**                                                             |
| 11. Lack of consistent verification practices                                  |
| 12. Evidence of verification incomplete or in incorrect format                 |
| 13. Verifier Practices Not Accepted by Ecosystem                               |
| 14. Suspended Credential Being Accepted                                        |
| 15. Revoked Credential Being Accepted                                          |
| **Credential Registry (Ledger) Risks**                                         |
| 16. Lack of competence to perform role                                         |
| 17. Unavailable registry                                                       |
| 18. Inappropriate access writes to registry                                    |
| 19. Breach of registry                                                         |
| 20. Exploited Use of Stolen Credentials                                        |
| 21. Credential Registry Not Accepted by Ecosystem                              |
| **Credential Holder Risks**                                                    |
| 22. Counterfeit Credentials Being Created                                      |
| 23. Credential Holder Given Inappropriate Access Rights                        |
| 24. Imposter Using Valid Credential                                            |
| 25. Credential Wallet Private Key is Compromised                               |
| 26. Credential Holder's Private Data is Compromised                            |
| 27. Social Engineering Attacks Successfully Gather Credentials by Perpetrators |
| **Utility Operation Risks**                                                    |
| 28. Stewards Not Abiding by Governance Practices                               |
| 29. Inadequate Infrastructure Supporting Steward Operations                    |
| 30. Inadequate Network Throughput Supporting Steward Operations                |
| 31. Inadequate Network Availability Supporting Steward Operations              |


Deeper analysis of risks items and their potential impacts is beyond the scope of the CCI GF V2, because it is necessary for this work to be done by relevant GAs and Issuers. However, a simple approach to risk assessment can be calculated using the approach below, which follows guidance from the ToIP Governance Metamodel previously referenced. The potential impact (“***I***”) of any risk item is the product of the likelihood (“***L***”) of a risk incident occurring multiplied by the outcome severity (“***S***”) that would be incurred due to such incident. Quantitative values for *likelihood* and *severity* should be assigned by the risk assessment team, and resulting values can be partitioned into numerically scaled groupings of LOW, MEDIUM and HIGH *impact*.
*L* x *S = I*
The above approach for estimation of risk impact can then be used to show a distribution of risk items by plotting the risks items in a two dimensional table, such as the sample table shown in Figure X. This visualization enables the risk assessment team to have a consolidated view of all risk items, and start to develop a risk management plan for the set of risk items that are considered to be critical for inclusion in such a plan.
<SHALL create plan for HIGH risks and SHOULD create a plan for MEDIUM risks>


![](https://lh5.googleusercontent.com/xgCW2JuGcjtzIISZUUj5norwB1hxXuX3wLfzor0xpjZPnV5LUD9M1EQ1gaS1e-Tve-PJupzug_4ovrCV-b1TpoUMv5zjEByDM84vDoEUpcSzQtqpPS10PGL1QaO4GJvXwFWZY3d5)


Figure X:     Simple illustration of a Risk Assessment Matrix 
(Reference: ToIP Governance Metamodel)

# Appendix C:    Practical Examples - 
# Verifiable Credential Use Cases

The CCI Use Case Implementations Workstream at Covid Credentials Initiative has produced a set of use cases around usage of verifiable credentials specific to COVID-19 pandemic. These scenarios are designed to establish the attributes present in a technology architecture created using verifiable credentials and digital identity. A selection of these use cases are included in the appendix to enable the reader to relate the principles and aspects of the governance framework in practical applications of technology interventions.
The listed use cases are not exhaustive but rather to be taken as an indicative one - demonstrating the potential and possibility of a secure, privacy-preserving system based on open standards.

## UC 00: Creating and Maintaining Local Assurance Communities (LACs) [[description](https://docs.google.com/document/d/1y6OJcxWmUbhuYulzsggphMgNhHwIDafTULUDq2v5u7o)]

An important part of implementing a Verifiable Credentials based system is the governance authority. This role is undertaken by an organization which has the regulatory authority to direct, control and approve the entire set of workflows involved in enabling a digital identity centric VC based system around health status.
This use case was originally designed by Rieks Joosten (TNO) and Oskar van Deventer (TNO) as part of an effort to focus on the question, “what is locally needed for trustworthy (Covid-19 and other) credentials ****to be actually used”. Credentials may provide privileges, like physical or digital access, there is a risk that untrustworthy credentials provide illegitimate privileges, or that credentials that should provide such privileges do not work. 
The concept of Local Assurance Community (“***LAC***”) is introduced to help organize trust ‘locally’ (e.g. within a specific domain, jurisdiction, etc.) by capitalizing on the fact that the parties that will constitute the LAC have already established assurance mechanisms (e.g. based on proximity and familiarity) on which such trust can be based. This enables e.g. issuers to be accredited to issue credentials of type X under the specifics (and governance) of a LAC.


## UC 2: Proof of Covid-19 status or, Immunity by Exposure   [[solution](https://docs.google.com/document/d/19T1v3YyiU-N0Xe-Gij3ymVzJTMUpRLvFQSCU00n_OZU/edit?ts=5e7ccf3e#heading=h.d2h5elxrlnqp) | [VC schema](https://docs.google.com/document/d/1F5TLvAqCxj1kaPuPe6JhdECixwpbhKpEAb8eeQuDGT4/edit#heading=h.ppf3i61y3kbc)]

The adoption of various software patterns to respond to the COVID-19 pandemic include a situation where an individual will need to present their health status upon request. Such a presentation is linked with access to services and this is required by regulations in place locally.
The multiple forms and facets of this scenario was analysed and documented by Antti Kettunen, Michael Corning, Andre Kudra, Dakota Gruener and Markus Mummert. The simplest description of this use case is that Bharat wants to prove, either face-to-face or remotely, that he has recovered from a COVID-19 infection (e.g., so he can drive a car for a rideshare app without being a disease vector).
Documents:

- Antti Kettunen: [](https://docs.google.com/presentation/d/1qmEMEg0i-Iw16xHoNI8xXEi7kJ3Jg_90eGtoWMMPksM)[[use cases CCI] Credential mapping to segmentation](https://docs.google.com/presentation/d/1qmEMEg0i-Iw16xHoNI8xXEi7kJ3Jg_90eGtoWMMPksM)
- Michael Corning: [](https://docs.google.com/document/d/1gTv5appx0ki3_i9knj1jtTo5u2cS5kbSwYN52gpi584)[CCI Back to Work Verifiable Presentation](https://docs.google.com/document/d/1gTv5appx0ki3_i9knj1jtTo5u2cS5kbSwYN52gpi584)
## UC 11: Verify the Verifier  

While the self-governance and management of verifiable credentials makes it very easy to disclose information based on notice/consent mechanism, it is important to validate that the entity requesting the information (in the form of credentials) is actually authorized to do so. This scenario was conceived and designed by Alex Blom (Bloqzone), Sterre den Breeijen (TNO), Oskar van Deventer (TNO), Randy Zhang and Will Abramson (Edinburgh Napier University)
The use case focuses on the question “**how do we reduce the risk that Verifiers make draconian requests for COVID-19 credentials**”. COVID-19 credentials may be useful e.g. to health-safely support access to vulnerable elderly in care homes by their family, caretakers and volunteers. However, they are not supposed to be used to harass citizens for them at situations where this would not be needed. It also follows that if adequate verification information is not provided by the verifier the individual can revoke consent and disallow sharing of the information.
Link: [](https://docs.google.com/document/d/1PQvDm1ssKypH9X1CV97sStOxfnnSpzLKyDEPJ_bAp7E)[https://docs.google.com/document/d/1PQvDm1ssKypH9X1CV97sStOxfnnSpzLKyDEPJ_bAp7E](https://docs.google.com/document/d/1PQvDm1ssKypH9X1CV97sStOxfnnSpzLKyDEPJ_bAp7E)

# Appendix D:    Foundational Principles Checklist

The CCI GF espouses guiding principles that shape the development, adoption and implementation of Verifiable Credentials used in the effort to overcome the challenges presented by the COVID-19 pandemic.
 
Organisations that adopt the CCI GF model are strongly urged to adhere to these same principles.
 
Below is a checklist that can help an organization evaluate its level of adherence to the CCI GF principles.

| **1.**     **OPENNESS & INTEROPERABILITY**                                                                                                                                                                                                                                                                                                                                                                                        | **REQUIRED** |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| The CCI GF strongly advocates, promotes and supports development mechanisms that allow identity controllers to experience interoperability or portability of their identity data to other networks and systems in alignment with " W3C open standards" for VC and DID.<br>RESOURCES:<br>·        [W3C standards](https://www.w3.org/standards/#:~:text=W3C%20standards%20define%20an%20Open,are%20available%20on%20any%20device.) |              |
| **Can you demonstrate openness and interoperability in your solution?**                                                                                                                                                                                                                                                                                                                                                           | **Y / N**    |
| **If no, please provide justification for this decision.**                                                                                                                                                                                                                                                                                                                                                                        |              |

##  
| **2.**     **ACCOUNTABILITY**                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | **REQUIRED** |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| The GF Governance Authority, and possibly other stakeholders, that choose to implement the CCI GF SHALL be accountable for conformance to the purpose, and principles documented in the CCI GF. All entities adopting the CCI GF SHALL be responsible to demonstrate compliance with any other requirements of applicable law within their jurisdiction(s) of operations. Nothing in the CCI Governance Framework requires a VC solution to breach applicable laws or regulations as presently enacted. |              |
| Can you demonstrate accountability in your solution?                                                                                                                                                                                                                                                                                                                                                                                                                                                    | **Y / N**    |
| **If no, please provide justification for this decision.**                                                                                                                                                                                                                                                                                                                                                                                                                                              |              |

##  
| **3.**     **SUSTAINABILITY**                                                                                                                                                                                                                                                                                                                                          | **RECOMMENDED** |
| ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| Implementers of the  CCI GF SHOULD strive to be technically, economically, socially, ethically, and environmentally sustainable, and contribute to the improvement of the well-being of people and the environment.<br>RESOURCES:<br>·        [United Nations Sustainable Development Goals](https://www.un.org/sustainabledevelopment/sustainable-development-goals/) |                 |
| Can you demonstrate sustainability in your solution?                                                                                                                                                                                                                                                                                                                   | **Y / N**       |
| **If no, please provide justification for this decision.**                                                                                                                                                                                                                                                                                                             |                 |

 

| **4.**     **MAINTAIN CONSISTENT EXPERIENCE**                                                                                                                                                                                   | **RECOMMENDED** |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| Developers adopting the CCI GF SHOULD strive to employ consistent design elements, accessibility, and inclusive language so that end-users can have a safe experience regardless of the specific implementation they are using. |                 |
| Can you explain how your solution addresses consistent user experience?                                                                                                                                                         | **Y / N**       |
| **If no, please provide justification for this decision.**                                                                                                                                                                      |                 |

##  
| **5.**     **CENSORSHIP RESISTANT**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  | **RECOMMENDED** |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| Implementers of the CCI-GF SHALL utilise VC tools, applications, and services that do not discriminate individuals or groups based on race, ethnicity, religion, health, sexual orientation, membership of organisations (e.g., trade union), or personal beliefs and political opinions.<br>Implementers shall design solutions so that third parties cannot inappropriately modify or revoke VCs or shut down or deny access to VC services without explicit uncoerced authorization from the Identity Controller. |                 |
| Can you explain how your solution is censorship resistant?                                                                                                                                                                                                                                                                                                                                                                                                                                                           | **Y / N**       |
| **If no, please provide justification for this decision.**                                                                                                                                                                                                                                                                                                                                                                                                                                                           |                 |

##  
| **6.**     **PRIVACY PRESERVING**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          | **REQUIRED** |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| The principles of decentralized identity embody the concept that personal identity is inherently inseparable from an individual, i.e. “self-sovereign”, and the ultimate use of that identity is governed by the credentialed identity owner. As such, the CCI GF SHALL strongly discourage resists any use of this framework that results in technical or regulatory privacy infraction, such as surveillance, personal tracking, and abuse.  Any VC developer’s priority should include design standards that enable and support the ethical right to privacy for users. |              |
| Can you detail the different tools and approaches you have taken to ensure user privacy?                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   | **Y / N**    |
| **If no, please provide justification for this decision.**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |              |

 

| **7.**     **PROTECTION AGAINST COERCION**                                                                                                                                                                                                                                                                                                                     | **RECOMMENDED** |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| Those who adopt the CCI GF SHALL facilitate the protection of the users of applications and systems which have adopted the governance framework against forms of coercion. Such coercion can be designed to force the user to act against their own interests. The governance framework MAY encourage adoption of potential counter-measures against coercion. |                 |
| Can you demonstrate adoption of counter-measures against coercion?                                                                                                                                                                                                                                                                                             | **Y / N**       |
| **If no, please provide justification for this decision.**                                                                                                                                                                                                                                                                                                     |                 |

 

| **8.**     **ETHICAL BY DESIGN & DEFAULT**                                                                                                                                                                                                                                                                                                                                                                                                                                                      | **RECOMMENDED** |
| ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| The CCI GF promotes generally accepted best practices of ethical data collection, management and use. Organizations that follow the CCI GF SHOULD determine how their actions could be perceived and avoid potential adverse impacts to stakeholders and their reputation in the future, including how their actions may impact on the perception of the CCI GF itself. Data strategies, processing and acquisition approaches SHALL be adapted to ensure the ethical use of data consistently. |                 |
| Can you demonstrate ethical design in your solution?                                                                                                                                                                                                                                                                                                                                                                                                                                            | **Y / N**       |
| **If no, please provide justification for this decision.**                                                                                                                                                                                                                                                                                                                                                                                                                                      |                 |

##  
| **9.**     **INCLUSION BY DESIGN & DEFAULT**                                                                                                                                                                                                                                                                                                                                                | **RECOMMENDED** |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------- |
| Systems and infrastructure that follow the CCI GF must be open to all Individuals and Organizations, on a comparable basis, without exclusion of specific persons, communities, technology limitations, or device availability. Great care for inclusion of underserved populations SHALL be proactively supported and promoted by individuals and organizations that adhere to the CCI GF. |                 |
| Can you demonstrate ‘Inclusion by Design and Default’ principles in your solution?                                                                                                                                                                                                                                                                                                          | **Y / N**       |
| **If no, please provide justification for this decision.**                                                                                                                                                                                                                                                                                                                                  |                 |

 

| **10.**  **DATA PROTECTION BY DESIGN & DEFAULT**                                                                                                                                                                                                                                | **REQUIRED** |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| Decentralized identity ecosystems SHOULD be designed to ensure best data protection and privacy protection for individuals (data subjects). For any COVID-19 use case, given the sensitive level of data likely to be contained in VCs, the guidance is particularly pertinent. |              |
| Can you demonstrate how your solution ensures data protection?                                                                                                                                                                                                                  | **Y / N**    |
| **If no, please provide justification for this decision**                                                                                                                                                                                                                       |              |

 



# Appendix E:    Verifiable Credential Levels of Assurance 

Users of CCI VCs should have a convenient and transparent system to understand and interpret the reliability of any information (the “Claims”) that might be included in a CCI VC. To facilitate this need, the CCI GF offers a basic guideline for Levels of Assurance (the “LOA”) which may be associated with any CCI VC. This Credentials Level of Assurance Framework intends to interact with transnational General Levels of [Identity] Assurance Frameworks 
such as: (a) [UK Government GPG45](https://ntouk.files.wordpress.com/2015/06/gpg-45-validating-and-verifying-the-identity-of-an-individual-issue-2-4-ncsc-web.pdf), (b) [NIST Special Publication 800-63-3 Digital Identity Guidelines](https://pages.nist.gov/800-63-3/sp800-63-3.html), (c) the [European electronic identity and trust services regulation (eIDAS)](http://data.europa.eu/eli/reg/2014/910/oj).
NOTE: It should be emphasized that the content below is provided as basic guidance for Levels of Assurance. A CCI GF Governance Authority and/or VC issuer should 
**Level 0**
At this level, no VC is produced for a given Claim. Level 0 indicates that the information is not included in the CCI GF.
**Level 1**
Claims that are self-attested, with no third-party support or verification, are defined as Level 1 claims. The Issuer is also the Holder and the Subject. Mistakes and fraud for a Level 1 Claim are not mitigated, and a Verifier must assess for themselves may rely purely on the credibility of the person that issues such Claim in a VC.  For example, a person might self-report their weight as 80kg. One value of a Level 1 VC is that it places the Issuer on record. If the Claim is later proved false, this can affect the Issuer’s reputation, although it is possible that the Issuer may be an impersonator. Many police departments require officers to make written assertions (Claims) about their own conduct, e.g. “I read the suspect their Miranda rights when I arrested them”. If it is later proved that the officer made a false Claim, the officer can be punished or otherwise held accountable on the basis that they are forbidden by law and their employment contract from making false written Claims. This reduces the overhead on the department of setting up a multitude of elaborate accountability mechanisms specific to each element of officer conduct, relying instead on the “no false Claims” punishment mechanism.
**Level 2**
Claims asserted within a VC by a second-party (Issuer) about the Subject of a VC, where the Issuer is not well known to a Verifier, are considered to be Level 2 Claims. In this situation, a Verifier must use their judgement to assess the credibility and potential accuracy of such VC Claims.  For example, an unknown self-proclaimed medical professional, with no verifiable professional license issued by any appropriate licensing agency in the relevant jurisdiction, might issue a VC with Claims about a person’s medical test results. 
**Level 3**
Claims asserted within a VC by a second-party (Issuer) about the Subject of a VC, where third-party evidence can support that the Issuer has met appropriate professional license requirements in the relevant jurisdiction, are considered to be Level 3 Claims.  A medical professional that has reliably demonstrated their required professional status and valid licences in a verifiable and auditable manner (such as with an associated personal or organizational identity VC that is reasonably demonstrated to be based on qualifying licenses, etc. issued by relevant authorities in the jurisdiction), would be a trusted source of Level 3 Claims for a CCI VC. For example, a COVID-19 test result VC issued by a doctor licensed to provide such test results in a jurisdiction, and where such licenses are verifiable as part of a VC issued by said doctor. Such COVID-19 test credential VC is considered to have a LOA of Level 3. 
**Level 4**
Extraordinary measures beyond Level 3 may be applied allowing CCI GF participants to establish their own guidelines and requirements for Level 4 Claims. These might include posting of bonds or providing guarantees or warranties.

LOA guidelines above represent minimal standards for any LOA system that may be adopted and reported by a CCI VC issuer.  CCI VC Holders and Verifiers must be made aware, by organizations that operate in compliance with the CCI GF, of exact details and implications of what any LOA might mean for CCI VCs they might hold or verify.

# Appendix F:    Trust Assurance Model

The Governance Principles explained in the document aid in raising the level of trust, assurance and credibility enabled within a system designed to be complying with the Technology Principles. For a digital system design such as the ones to be implemented for COVID-19 related technology interventions, the presence of trust is a key aspect. 
Trust can be defined as the “firm belief in the reliability, truth, ability, or strength of someone or something”.  Digital trust is built from three main components: *Cryptographic Trust; Human Trust and Referential Trust.*  *Referential Trust* is established through a trustworthy entity transferring trust upon a third party. The existence of human trust in the technology implementations around COVID-19 depends heavily on the concept of referential trust - through the creation and existence of specific roles. These roles include Trust Anchor; Credential Registry, Governance Authority, Auditor and Audit Accreditor.

![](https://lh5.googleusercontent.com/d2bNm0rfEFFNI9Y7CwZXKpwS9y1xJxCtgpwu4nBbkn1k-sHJmSExXlh15rhtrkA7qr_R-Tej6Iqezoynb24CF_8yMbww-DCFwgbH2QdiGEX91mIEI7Uz2WkyZHph6Q6HO6BvE2kj)


Figure: A Referential Trust Ecosystem (representative illustration)
The ecosystem creates assurance to verifiers, credential holders and relying parties that trust anchors are applying generally accepted trust criteria to their methods and practices by the introduction of accreditation and independent third-party audits that act in their interest.  Relying parties acquire trust from the ecosystem based on the ability of the players to follow through on its commitments and the integrity of its decisions.  Symbols of this trust are stored on a publicly accessible credential registry it can be propagated throughout the ecosystem.

# Appendix G:    Healthcare Data Security and Privacy

Data privacy and security are increasingly a concern in nearly all industries , more so in healthcare. From HIPAA and data breaches to the patient perspective and EHRs, here are some key information to  know about data security and privacy issues in healthcare.

## HIPAA
1. The Health Insurance Portability and Accountability Act (HIPAA), designed to protect healthcare information security and confidentiality , enacted in 1996,  apply to all healthcare providers, health plans and healthcare clearinghouses. 
2. Under the HIPAA privacy rule, patients have a number of rights  on their protected health information. HIPAA violations can come with both civil and criminal penalties.
## Data Breaches
3. The most expensive data breaches occur in the United States and Germany. 
4. Data breaches could cost the healthcare industry as a whole $6 billion each year, according to a [Ponemon Institute report](https://www.ponemon.org/)
5. Criminal attacks are the leading cause of data breaches in healthcare. The number of criminal attacks on healthcare organizations has leapt 125 percent since 2010.
6. There are a multitude of technical issues to consider when safeguarding against data breaches.
7. In addition to addressing the technical side of data security, healthcare organizations must have operational controls in place
8. The high-profile nature of breaches like the Anthem case can drive other healthcare providers to take a second look at their own cybersecurity policies. An Experian Data Breach Resolution and Ponemon Institute found media coverage of data breaches has driven 69 percent of companies to reevaluate and prioritize security.
## The Patient side
9. Healthcare providers are not the only ones concerned with data breaches. Depending on the type of information accessed, patients too can be exposed to risk. A Software Advice survey found that 45 percent of respondents were moderately or very concerned about security breaches involving personal health information.
10. Providers have traditionally safeguarded healthcare data, but it is now spreading beyond the four walls of a hospital or physician's office. Wearables are growing in popularity, but not without concern. A PricewaterhouseCoopers report on wearables found that 86 percent of respondents were concerned this technology would make them more vulnerable to security breaches.
## A Guardian’s Health Care Decision-Making Authority: Statutory Restrictions
11. State guardianship statutes generally grant guardians broad authority to make health care decisions for incapacitated persons and contain language similar to the Uniform Guardianship and Protective Proceedings Act (“UGPPA”), which states that a guardian may “consent to medical or other care, treatment, or service for the ward.  However, the statutes limiting that authority vary broadly between states in the U.S. Local jurisdiction and regional laws and regulations should be consulted as far as guardianship is concerned for VC process , because healthcare VC is another medical record.
## Data accuracy related to self-testing for medical conditions - example
12. Covid - There are questions about the general accuracy of available covid antibody tests, potential high rates of false positive and what kind of immunity antibodies might confer. Some in the medical community believe that  without professional guidance, it could be easy for a non-expert to jump to the conclusion that they’re immune when they aren’t. If the tests are purely recreational, there’s probably not too much harm that can come from them. But if at-home tests results become the basis for re-entering the workforce or other consequential policy decisions, people might feel pressured to falsify their results. If there’s a lot that depends on the real accuracy of the result, then this has big problems.
13. In general , companies developing  verifiable credentials for home-based medical tests  need to be aware of these concerns on data integrity and accuracy and implement risk mitigations in the solutions to appropriately capture and communicate these concerns to the users of these VCs. 
14. While developers of VC are not medical experts and this GF is not meant to serve as a medical guidance, it is important to understand the risks in the process and appropriately capture and communicate them to the stakeholders to enable informed decision making.


# Appendix H: Data Protection legislations

Over 80 countries and independent territories, including nearly every country in Europe and many in Latin America and the Caribbean, Asia, and Africa, have now adopted comprehensive data protection laws.  Some sample key legislations to know from around the world are as follows:

**Canada** 
Personal Information Protection and Electronic Documents Act (PIPEDA)

**Europe**
General Data Protection Regulation (GDPR) - 2018

**Germany**
Both federal and state enacted legislations

**Philippines**
Privacy and personal data protection in the country. Modeled after the EU Data Protection Directive and the Asia-Pacific Economic Cooperation (APEC) Privacy Framework.
Companies implementing verifiable credentials need to be aware of what to expect from these legislations (current & new) and make sure the solutions developed adequately cover these requirements to meet local , regional and global requirements. 

**Switzerland**
Not a member of  EU or EEA. Partially implemented the EU Directive on the protection of personal data in 2006.Right to privacy is guaranteed in article 13 of the Swiss Federal Constitution,  Swiss Federal Data Protection Act (DPA)[17] and the Swiss Federal Data Protection Ordinance (DPO).

**United Kingdom**
The Data Protection Act 2018 updates data protection laws in the UK. It is a national law which complements the European Union's General Data Protection Regulation (GDPR).

**United States** 
Health Insurance Portability and Accountability Act (HIPAA) - 1996. In addition , there are state legislations. 
The HITECH Act, enacted in 2009, is designed to promote the adoption and meaningful use of healthcare information technology. The legislation also addresses privacy and security concerns, as well as strengthens enforcement of HIPAA rules.








# Resources & References

For further exploration of the concepts, technologies and philosophies which converge in the health-related credential ecosystem, please see links below:
 
**Verifiable Credentials**

- [W3C Verifiable Credentials Data Model 1.0 Terminology](https://www.w3.org/TR/vc-data-model/#terminology)
- Characteristics of Safe Credentials: [https://www.evernym.com/blog/introducing-safe-credentials/](https://www.evernym.com/blog/introducing-safe-credentials/)

**Identity**

- Blinding Identity Taxonomy: An approach from the Kantara Initiative to aid schema issuers and data controllers to flag attributes which may contain identifying information.
- [https://docs.kantarainitiative.org/Blinding-Identity-Taxonomy-Report-Version-1.0.html](https://docs.kantarainitiative.org/Blinding-Identity-Taxonomy-Report-Version-1.0.html) 

**Healthcare Data Security & Privacy**

- NHS (UK) - Records Management Code of Practice: [https://www.nhsx.nhs.uk/media/documents/NHSX_Records_Management_Code_of_Practice_2020_3.pdf](https://www.nhsx.nhs.uk/media/documents/NHSX_Records_Management_Code_of_Practice_2020_3.pdf) 
- 50 things to know about healthcare data security & privacy covering HIPAA, data breaches and Electronic Health Records: [https://www.beckershospitalreview.com/healthcare-information-technology/50-things-to-know-about-healthcare-data-security-privacy.html](https://www.beckershospitalreview.com/healthcare-information-technology/50-things-to-know-about-healthcare-data-security-privacy.html)

**Trust**

- Trust Assurance Model: Governance Principles to aid in raising the level of trust, assurance and credibility enabled within a system designed to be complying with the Technology Principles of a digital system design: [https://wiki.trustoverip.org/display/HOME/GSWG+Trust+Assurance+Task+Force](https://wiki.trustoverip.org/display/HOME/GSWG+Trust+Assurance+Task+Force) 
- Risk Assessment and the mitigation of residual risk. Guidance can be found at: [](https://www.rsa.com/content/dam/en/white-paper/rsa-digital-risk-report-2019.pdf)[https://www.rsa.com/content/dam/en/white-paper/rsa-digital-risk-report-2019.pdf](https://www.rsa.com/content/dam/en/white-paper/rsa-digital-risk-report-2019.pdf)
- Levels of Assurance Framework: convenient and transparent system to understand and interpret the reliability of any information (“Claims”) that might be included in a CCI VC.
    - [UK Government GPG45](https://ntouk.files.wordpress.com/2015/06/gpg-45-validating-and-verifying-the-identity-of-an-individual-issue-2-4-ncsc-web.pdf)
    - [NIST Special Publication 800-63-3 Digital Identity Guidelines](https://pages.nist.gov/800-63-3/sp800-63-3.html)
    - [European electronic identity and trust services regulation (eIDAS)](http://data.europa.eu/eli/reg/2014/910/oj).

**Organisations & Standards**

- Trust Over IP - [Trust Over IP Foundation](https://trustoverip.org/)**.**
- Sovrin - [The Sovrin Governance Framework Glossary](https://docs.google.com/document/d/1gfIz5TT0cNp2kxGMLFXr19x1uoZsruUe_0glHst2fZ8/edit)
- National Institute of Standards and Technology, U.S. Department of Commerce
    - Digital Identity Guidelines - [NIST SP 800-63-3](https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-63-3.pdf)
- Internet Engineering Task Force
    - RFC 2119 - Key words for use in RFCs to Indicate Requirement Levels - [https://tools.ietf.org/html/rfc2119](https://tools.ietf.org/html/rfc2119)
- Hyperledger Aries
- International Standards Organisation
- German Institute for Standardization
- Spanish Data Protection Board

**Data Ethics**

- UK Department for Digital, Culture, Media & Sport - Data Ethics Framework [https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/737137/Data_Ethics_Framework.pdf](https://assets.publishing.service.gov.uk/government/uploads/system/uploads/attachment_data/file/737137/Data_Ethics_Framework.pdf)

