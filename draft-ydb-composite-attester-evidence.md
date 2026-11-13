---

title: Composite Attester Evidence 
abbrev: "Composite Evidence"
category: info

docname: draft-ydb-composite-attester-evidence-latest
submissiontype: IETF  
number:
date:
consensus: true
v: 3
area: Security
workgroup: RATS

stand_alone: yes

author:
 -
    fullname: Yogesh Deshpande
    organization: Arm
    email:  Yogesh.Deshpande@arm.com

normative:

...

--- abstract
Attesters can come in a wide variety of shapes and forms. 
For example, Attesters can be endpoints (edge or IoT devices) or complex machines in the cloud.
With the growing complexity of Attesters, an Attester is often a Composite Attester.

This document provides a data format for assembling Evidence of a Composite Attester.

--- middle

# Introduction {#intro}

Attesters can come in a wide variety of shapes and forms.
With technological advancements, Attesters are becoming Composite in nature.
Composite Attester generates Evidence that consists of multiple parts.
For example, in data center servers, it is not uncommon for separate Attesting Environments (AE) to serve a subsection of the entire machine. 
One AE might measure and attest to what was started on the main CPU, while another AE might measure and attest to what was started on the machine's GPU. 
When Attester becomes Composite, there needs to be a standardized way to combine the Evidence to form a Composite Evidence.

The pupose of this draft is to provide a standardized way of constructing Evidence from a Composite Attester.

# Conventions and Definitions

{::boilerplate bcp14-tagged}


# Security Considerations {#security}

TODO Security


# IANA Considerations {#iana}

This document has no IANA actions.


--- back

# Acknowledgments
{:numbered="false"}

TODO acknowledge.
