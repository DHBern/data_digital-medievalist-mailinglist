# Digital Medievalist <dm-l> data

Messages sent to the list since its onset in 2002, stored as text messages for analytical purposes.

The messages are slightly edited (removal of content type, transfer encoding, phishing warning, and redaction of e-mail addresses).

Message headers are also generated, but git-ignored for privacy reasons.

## Regenerating the messages

* Message generation is based on the list archive in Maildir format and the splitting script found at [DHBern/tools-and-scripts/digital_medievalist/split-maildir.xsl](https://github.com/DHBern/tools-and-scripts/blob/main/digital_medievalist/split-maildir.xsl).
* The Maildir may be derived from the [mbox export](https://listserv.uleth.ca/hyperkitty/list/dm-l@uleth.ca/export/dm-l@uleth.ca-2023-04.mbox.gz) using [`mb2md`](http://batleth.sapienti-sat.org/projects/mb2md/).
* Usage of the script is documented in more detail in the file. 
* The mbox export is [quoted-printable encoded](https://en.wikipedia.org/wiki/Quoted-printable) and decoding is advisable (e.g. using `qprint`, see also [DHBern/tools-and-scripts/digital_medievalist/qprint.sh](https://github.com/DHBern/tools-and-scripts/blob/main/digital_medievalist/qprint.sh)).
