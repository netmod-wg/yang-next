# yang-next

Feature requests for future versions of YANG

## Table of Contents

* [Links](#links)
* [Contributing](#contributing)
* [Note Well](#note-well)
* [Issue Tracking](#issue-tracking)


## Links

* NETMOD WG: http://datatracker.ietf.org/wg/netmod/charter/
* IETF Page: https://tools.ietf.org/html/draft-ietf-netmod-opstate-reqs
* Mailing List: https://www.ietf.org/mailman/listinfo/netmod
* Issue Tracking: https://github.com/netmod-wg/opstate-reqs/issues



## Contributing

Before submitting feedback, please familiarize yourself with our current issues
list and review the [working group home page](http://datatracker.ietf.org/wg/netmod/charter/). If you're new to this, you may also want to read the [Tao of the
IETF](https://www.ietf.org/tao.html).

Be aware that all contributions to the specification fall under the "NOTE WELL"
terms outlined below.

1. The best way to provide feedback (editorial or design) and ask questions is
sending an e-mail to [our mailing list](https://www.ietf.org/mailman/listinfo/netmod). This will ensure that the entire Working Group sees your input in a timely fashion.

2. If you have **editorial** suggestions (i.e., those that do not change the
meaning of the specification), you can either:

  a) Fork this repository and submit a pull request; this is the lowest
  friction way to get editorial changes in.
  
  b) Submit a new issue to Github, and mention that you believe it is editorial
  in the issue body. It is not necessary to notify the mailing list for
  editorial issues.
  
  c) Make comments on individual commits in Github. Note that this feedback is
  processed only with best effort by the editors, so it should only be used for
  quick editorial suggestions or questions.

3. For non-editorial (i.e., **design**) issues, you can also create an issue on
Github. However, you **must notify the mailing list** when creating such issues,
providing a link to the issue in the message body.

  Note that **github issues are not for substantial discussions**; the only
  appropriate place to discuss design issues is on the mailing list itself.


## NOTE WELL

Any submission to the [IETF](https://www.ietf.org/) intended by the Contributor
for publication as all or part of an IETF Internet-Draft or RFC and any
statement made within the context of an IETF activity is considered an "IETF
Contribution". Such statements include oral statements in IETF sessions, as
well as written and electronic communications made at any time or place, which
are addressed to:

 * The IETF plenary session
 * The IESG, or any member thereof on behalf of the IESG
 * Any IETF mailing list, including the IETF list itself, any working group 
   or design team list, or any other list functioning under IETF auspices
 * Any IETF working group or portion thereof
 * Any Birds of a Feather (BOF) session
 * The IAB or any member thereof on behalf of the IAB
 * The RFC Editor or the Internet-Drafts function
 * All IETF Contributions are subject to the rules of 
   [RFC 5378](https://tools.ietf.org/html/rfc5378) and 
   [RFC 3979](https://tools.ietf.org/html/rfc3979) 
   (updated by [RFC 4879](https://tools.ietf.org/html/rfc4879)).

Statements made outside of an IETF session, mailing list or other function,
that are clearly not intended to be input to an IETF activity, group or
function, are not IETF Contributions in the context of this notice.

Please consult [RFC 5378](https://tools.ietf.org/html/rfc5378) and [RFC 
3979](https://tools.ietf.org/html/rfc3979) for details.

A participant in any IETF activity is deemed to accept all IETF rules of
process, as documented in Best Current Practices RFCs and IESG Statements.

A participant in any IETF activity acknowledges that written, audio and video
records of meetings may be made and may be available to the public.



## Issue Tracking


Issues are tracked using the following states:

```
               GitHub Status
   +----------------+----------------+
   |      Open      |     Closed     |
   |                |                |
   |                |                |
   |                |                |
   |      New -----------> Dead      |
   |       |        |                |
   |       V        |                |
   |      Open      |                |
   |       |        |                |
   |       V        |                |
   |     Verify     |                |
   |       |        |                |
   |       V        |                |
   |      Edit      |                |
   |       |        |                |
   |       V        |                |
   |     Review --------> Done       |
   |                |                |
   |                |                |
   |                |                |
   |   Editorial -------> Editorial  |
   |                |                |
   |                |                |
   +----------------+----------------+
```

Where the states are defined as follows:

State | Description
----- | -----------
NEW | A submitted issue starts in the NEW state.
OPEN | A first discussion of the issue took place and it was accepted to be a real issue.
VERIFY | The issue was discussed and a resolution emerged that needs to be verified on the mailing list.
EDIT | The issue is waiting for the document editor to make the corresponding changes.
REVIEW | The edits have been done and the changes in the I-D need to be reviewed.
DONE | The edits have been reviewed an the issue has been resolved.
DEAD | The issue was declared dead, e.g., because it is considered outside of the scope or the issue does not seem to require a solution.
Editorial | The issue is a placeholder for an editorial fix that does not require WG discussion to fix.

