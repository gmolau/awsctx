# awsctx

Like [kubectx](https://github.com/ahmetb/kubectx), but for AWS profiles. Prompts you to select one of your configured AWS profiles, then sets the default AWS CLI config values based on this profile.

Depends on the AWS CLI and FZF. Works purely through the AWS CLI config mechanism, does not do anything fancy for itself.

## Installation
Simply put the `awsctx` script somewhere in your $PATH, e.g.

```bash
git clone git@github.com:gmolau/awsctx.git /tmp/awsctx
mv /tmps/awsctx/awsctx /usr/local/bin/awsctx
```