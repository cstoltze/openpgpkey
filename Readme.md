# Overview

This is a [Web Key Directory](https://wiki.gnupg.org/WKD) server. It serves my open PGP key on the openpgpkey.stoltze.family subdomain.

Here's the full [link](https://openpgpkey.stoltze.family/.well-known/openpgpkey/stoltze.family/hu/5oxfm5wdbe4z6am3pjgojeg7fo75czkj): (as of 2023-09-06). Clicking the link will download the key. It doesn't open a webpage.

## To use with PGP

To load the key into gpg use:

```bash
gpg --locate-key coleman@stoltze.family
```

The same command works to refresh the key information. This is useful if you've
recently [renewed your
subkeys](https://github.com/drduh/YubiKey-Guide#renewing-sub-keys) because they expired.
