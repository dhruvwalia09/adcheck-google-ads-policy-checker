# AdCheck Rule Library v0.1

| ID | Area | Rule | Detection approach | Default risk | Evidence type |
|---|---|---|---|---|---|
| MR-01 | Misrepresentation | Potential misleading identity/affiliation | Compare supplied business identity/claims for unexplained affiliation or impersonation signals | High | Public requirement + derived check |
| MR-02 | Claims | Potential unreliable claim | Detect improbable outcome promises, then require contextual review rather than automatic violation | High | Public requirement + derived check |
| MR-03 | Relevance | Potential unclear relevance | Compare advertised product/service with supplied destination description | Medium | Public requirement + derived check |
| MR-04 | Offers | Potential unavailable offer | Check whether advertised product/service/offer is represented on destination | High | Public requirement + derived check |
| MR-05 | Ad design | Potential misleading ad design | Flag ad text/creative descriptions that imitate UI elements or obscure ad nature when data is available | High | Public requirement + derived check |
| LP-01 | Destination | Destination may not work | Test URL availability where technically possible; otherwise mark not assessable | High | Public requirement |
| LP-02 | Destination | Potential destination mismatch | Compare displayed/final URL information and supplied redirect/domain information | High | Public requirement + derived check |
| LP-03 | Destination | Destination may not be crawlable | Where technical testing is available, assess basic accessibility; otherwise not assessable | Medium | Public requirement |
| LP-04 | Destination | Destination experience concern | Check supplied page metadata/content for difficult navigation, direct-download/email destinations or similar signals | Medium | Public requirement + derived check |
| LP-05 | Destination | Insufficient original content signal | Flag pages described as duplicated, empty, or primarily redirecting elsewhere | Medium | Public requirement + derived check |
| ED-01 | Editorial | Unclear ad copy | Check whether the core offer and intended action are understandable | Low | Public requirement + quality enhancement |
| ED-02 | Editorial | Excessive/gimmicky formatting | Check supplied text for patterns inconsistent with professional ad presentation | Low | Public requirement + derived check |
| ED-03 | Editorial | Irrelevant/repetitive copy | Check whether text contributes meaningfully to the advertised offer | Low | Public requirement + derived check |
| TC-01 | Technical | Unsupported destination format | Flag destinations that are direct files/email links when prohibited by the relevant destination guidance | High | Public requirement |
| TC-02 | Technical | Missing required inputs | Identify when the tool lacks information needed for a reliable assessment | Low | Quality enhancement |
| AI-01 | AI quality | Unsupported certainty | Prevent AI output from stating that Google will approve/disapprove unless quoting a public rule and clearly qualifying the result | Critical | Independent product safeguard |
| AI-02 | AI quality | Source traceability | Require each policy-related finding to include a public source reference | High | Independent product safeguard |
