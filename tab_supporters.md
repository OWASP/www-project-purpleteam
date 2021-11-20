---
title: Supporters
layout:  null
altfooter: true
tab: true
order: 3
tags: PurpleTeam
---

## Project Supporters

You can attribute your donation to OWASP PurpleTeam by using [this link](/donate?reponame=www-project-purpleteam&title=OWASP+purpleteam) or the green "Donate" button while on any tab of the OWASP PurpleTeam project page!

### Top Supporters

<small><small>_In order to be recognized as a "Top Supporter" a company or other entity must have donated $1000 or more a) to OWASP while attributing it to PurpleTeam or b) as a restricted gift to OWASP PurpleTeam in the last 12 months._</small></small>

#### All Corporate Supporters

* [PurpleTeam-Labs](https://purpleteam-labs.com/)<sup>(2021)</sup>
* [BinaryMist Ltd](https://binarymist.io)<sup>(2021)</sup>

#### All Individual Supporters

{% assign individual_supporter = site.data.ow_attributions | uniq %}
{% for supporter in individual_supporter %}
* {{ supporter | strip_html | strip_newlines | strip }}
{% endfor %}
* _You want to appear on this list?_
  [Donate to OWASP here! 🤲](/donate?reponame=www-project-purpleteam&title=OWASP+purpleteam)

#### Book Sales (Royalties)

[![BinaryMist Publications](https://user-images.githubusercontent.com/2862029/142711607-16921ccd-469a-40ab-8433-d697b4307e47.png)](https://binarymist.io/publication/kims-selected-publications/)

$1,500.00 of royalties from [BinaryMist Publications](https://binarymist.io/publication/kims-selected-publications/) have been donated to the project between 2018 and 2021.

---

_The OWASP Foundation is very grateful for the support by the
individuals and organizations listed. However please note, the OWASP
Foundation is strictly vendor neutral and does not endorse any of its
supporters._
