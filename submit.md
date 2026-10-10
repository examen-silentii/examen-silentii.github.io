---
layout: page
title: Submit
permalink: /submit/
---

*Submissions are not yet open. This page describes the process that will apply.*

## Article types

- **Examination.** A full report of an independent test of a piece of scientific software or a public research dataset.
- **Response.** A reply from the maintainers of the examined software or data, published alongside the examination it answers.

## Requirements for an examination

Every examination must:

1. **Identify exactly what was tested**, including the name, version or release, and where it was obtained.
2. **Explain why it matters**: the tool or dataset must be widely used, or used in work where an error would have consequences.
3. **Include a reproducible test**, with code, data and instructions sufficient for a reviewer to rerun it, archived in a public repository.
4. **Use an independent reference**, and explain why it is independent of what is tested, declaring any shared code, methods or ancestry.
5. **Report the result plainly**: what is wrong, how large the error is, and whether the tool or dataset signalled the problem.
6. **Report the maintainers' response**, or state that none was received (see below).

## Notifying maintainers before submission

Authors must report the issue to the maintainers of the examined software or data, through their usual channel such as an issue tracker or mailing list, before submitting to ExSil, and must allow a reasonable time for a reply. Where a problem could be a security vulnerability, authors must follow the project's security policy and must not publish details before it permits.

If the maintainers do not respond, or the project is no longer maintained, the article may still be submitted, stating what was attempted.

## How to submit

Submissions will be made by opening an issue in the journal's submissions repository on GitHub, using the template provided, with a link to the manuscript and to the archived test materials.

## Review

Each examination is reviewed openly on GitHub by at least two reviewers, who rerun the test and check the requirements above. The maintainers of the examined software or data are invited to respond.
