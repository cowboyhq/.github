# .github

Organisation-wide default files for [cowboyhq](https://github.com/cowboyhq).

GitHub shows the files here on every repository in the organisation that does
not carry its own copy - public and private alike - without adding anything to
those repositories' file trees, history, clones or downloads. Changing a default
means changing it once, here.

## What lives here

- **[SECURITY.md](SECURITY.md)** - the short version of how to report a
  vulnerability to Cowboy, linking to the authoritative policy at
  [cowboy.com/pages/security-policy](https://cowboy.com/pages/security-policy).
  The same contact is published in
  [cowboy.com/.well-known/security.txt](https://cowboy.com/.well-known/security.txt)
  on each public host.

  Three places carry the contact and they have to agree: the page, the
  security.txt files, and this file. Change one, change all three. The page is
  the authority - do not let this file grow back into a second full copy.

## What does not

This repository is **public**, which is what GitHub requires for defaults to
apply. Everything committed here is world-readable, permanently, including the
history - so nothing about internal systems, infrastructure, tooling or people
belongs in it. Keep it to documents written for an outside reader.

A licence cannot be defaulted this way and has to sit in each repository. A
repository that defines its own issue templates replaces the defaults here
wholesale rather than merging with them.
