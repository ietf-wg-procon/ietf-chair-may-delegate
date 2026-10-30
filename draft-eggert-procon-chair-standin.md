---
title: "The IETF Chair Has a Stand-In"
category: bcp
docname: draft-eggert-procon-chair-standin-latest
submissiontype: IETF
consensus: true
v: 3
workgroup: "Process Document Consolidation"
venue:
  mail: "procon@ietf.org"
  github: "ietf-wg-procon/ietf-chair-may-delegate"
  latest: "https://ietf-wg-procon.github.io/ietf-chair-may-delegate/draft-eggert-procon-chair-standin.html"

author:

-
    name: Lars Eggert
    role: editor
    org: Mozilla
    street: Stenbergintie 12 B
    city: Kauniainen
    code: "02700"
    country: FI
    email: lars@eggert.org
    uri: https://eggert.org/

--- abstract

This document defines a stand-in for the IETF Chair, called the
Acting IETF Chair, in case the IETF Chair becomes indisposed.

--- middle

# Introduction {#intro}

The role of the IETF Chair is a single point of failure for the
organization, with no defined processes for allowing others to
quickly and/or temporarily take over aspects of the role if the IETF
Chair becomes partially or fully unable to serve. (The defined
process is that for "mid-term vacancies" per {{Section 3.5
of !RFC8713}}, which can take up to six weeks to complete and only
allows for the permanent replacement of the IETF Chair by another
individual.)

# Acting IETF Chair

This section describes who may serve as Acting IETF Chair if the IETF Chair
becomes indisposed.

## Background

As described in {{intro}}, the IETF Chair role is at the moment a
single point of failure for the organization. If the IETF Chair
becomes indisposed, a recall petition followed by executing
a "mid-term vacancy" replacement would need to be executed to name a
new IETF Chair. This process will likely take several weeks at best,
during which time there is no defined Acting IETF Chair.

{:aside}
> {{Section 7.1.1 of ?RFC8713}} currently prevents NomCom-ineligible IETF
  participants from being signatories on recall petitions. This
  includes anyone serving in a NomCom-selected role. This could be an
  issue, since IESG, IAB and LLC Board members may be first-hand
  witnesses to reasons that would merit an IETF Chair recall, but
  they are currently unable to initiate one directly.

## Selection of the Acting IETF Chair

In case the IETF Chair becomes indisposed, the IESG selects and
announces another Area Director who is willing to serve as Acting IETF
Chair, who then immediately assumes the role of the IETF Chair.
The IETF Chair declares when they become indisposed and when they are
available again. If the IETF Chair is unable or unwilling to do so, or
if there is disagreement, the IESG decides. This does not affect the
recall process in {{Section 7 of RFC8713}}. The Acting IETF Chair
serves until the NomCom appoints a new IETF
Chair or the IETF Chair is available again.

The Acting IETF Chair holds the full role of the IETF Chair, including
the ability to delegate {{?I-D.eggert-procon-chair-delegate}}, and this
section applies to them as it does to the IETF Chair. Delegations made
by the IETF Chair remain in force unless the Acting IETF Chair changes
them.

If the IETF Chair's absence is expected to be short, the Acting IETF Chair
should choose to delay controversial decisions until the IETF Chair is
available again, while allowing other business to proceed.

# Security Considerations

The usual security considerations {{?RFC3552}} do not apply to this
document.

# IANA Considerations

This document has no IANA actions.

# Acknowledgments

These individuals suggested improvements to this document:

- Alvaro Retana
- Brian Carpenter
- Eric Rescorla
- Jari Arkko
- Joel Halpern
- Mike Bishop
- Mirja Kühlewind
- Rob Sayre
- Robert Sparks
- Ted Lemon
--- back
