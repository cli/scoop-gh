# Deprecated scoop bucket for the GitHub CLI

The GitHub CLI used to publish our own [scoop](https://scoop.sh/) bucket that contained a manifest for installing GitHub CLI.

Since 2020, scoop “main” bucket included the `gh` manifest, and our bucket was no longer needed. We kept updating it for a while with latest GitHub CLI releases, but now this repository will stop being updated in favor of the main scoop bucket.

If you used our own scoop bucket, here is how to transition off of it:

```sh
scoop bucket rm github-gh
scoop install gh
```
