# Security policy

## Reporting a vulnerability

Email **security@cowboy.com** with enough detail to reproduce the issue: the
affected host or repository, the steps you took, and what you observed. A proof
of concept helps; a video is rarely necessary.

We aim to acknowledge a report within **3 business days** and to tell you what we
intend to do about it within **10 business days**. We will let you know when the
issue is resolved.

Please do not open a public GitHub issue, pull request or discussion for a
security problem. That discloses it to everyone who can read the repository
before we can fix it.

## What is in scope

Anything reachable from outside Cowboy: our public websites and storefronts, the
mobile app API, the admin interface and the accounts behind them.

## What we ask

- Give us a reasonable window to fix the issue before you publish it.
- Do not access, change or delete data that is not yours. If you reach customer
  data by accident, stop and tell us what you saw.
- Do not run denial of service tests, send spam, or use social engineering,
  phishing or physical attacks against our staff or offices.
- Keep your testing proportionate. Automated scanning at volume looks the same to
  us as an attack, and we will treat it as one.

We do not currently run a paid bug bounty. We will credit you if you would like
that, and we will not pursue action against anyone who follows the guidance above
in good faith.

## Where else to find this

The same contact is published at
[cowboy.com/.well-known/security.txt](https://cowboy.com/.well-known/security.txt)
and on our other public hosts, per RFC 9116. If you find a Cowboy address that
disagrees with this one, this file is the current one - and we would like to know
about the stale copy too.
