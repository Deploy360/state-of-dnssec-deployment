# State of DNSSEC Deployment 2016

Sections:

* Executive Summary
* Introduction
* State of DNSSEC Validation
* State of DNSSEC Signing
* State of DANE Deployment
* Conclusion
* Appendix: Resources


## Executive Summary

Summary of key findings throughout the report.
Bullet points and major points to consider.

## Introduction

Brief explanation of what is in the rest of the report.

## State of DNSSEC Validation

Charts and narrative around the state of validation.  Several different aspects.

[A key point is to have metrics that can be updated year-over-year. When we do the 2017 report we want to be able to compare with the 2016 report.]

### Observed usage of DNSSEC validation

Charts showing the validation being performed on the Internet.  

Potential data sources:

* APNIC statistics
* Atlas probe measurements


### Availability of DNSSEC validation in DNS resolvers

List of DNS recursive resolvers commonly used and available and the state of DNSSEC validation in each.

## State of DNSSEC Signing

### Top-level domains

Charts and discussion of signed TLDs, both ccTLDs and gTLDs.  DNSSEC Deployment Maps are an obvious candidate for inclusion here.

### Second-level domains

Charts and discussions about the number of signed domains at the second-level.  Potential sources of data include:

* [Rick Lamb's site](http://rick.eng.br/dnssecstat/)
* [ntldstats.com](https://ntldstats.com/dnssec) - for newgTLDs
* [NIST stats](https://fedv6-deployment.antd.nist.gov/) - for .gov
* Data from SURFnet (Roland) from their research.
* Other sites found on [http://www.internetsociety.org/deploy360/dnssec/statistics/](http://www.internetsociety.org/deploy360/dnssec/statistics/)

The point here is to paint a picture of where we are at right now to the best of our understanding.

## State of DANE Deployment

Discussion and charts about DANE deployment. Potential topics include:

* Observed number of TLSA records
* Number of mail servers publishing TLSA records
* Number of XMPP servers publishing TLSA records

Potential sidebar story here about the case study of DANE usage by mail servers within Germany and the German gov't recommendation.

## Conclusion

Any final remarks.

## Appendix: Resources

Pointers to more information about the topics in the report.