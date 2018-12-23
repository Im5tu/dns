# dns

This repository codes the DNS settings for the following domains:

- im5tu.io
- signalone.cloud
- dnbmth.io

And the settings are sync'd between the following providers:

- Cloudflare
- DNSimple*

_*Note:__ _DNSSEC has to be enabled first_

On a pull request, the changes are validated and applied when merged into master.

This repository uses a custom VSTS agent, which can be [found here](https://github.com/Im5tu/octodns-docker).