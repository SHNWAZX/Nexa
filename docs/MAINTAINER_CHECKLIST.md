# Maintainer Checklist

Use this checklist before publishing a Nexa build or sharing a release candidate.

## Before release

- Confirm download flows work for both video and audio formats.
- Test the app on a clean install and on an upgrade from the previous release.
- Review permissions and remove any capability that is no longer required.
- Check that error states are readable and do not expose raw stack traces.
- Verify the release notes mention user-visible changes and known limitations.

## After release

- Tag the version in GitHub.
- Attach the expected build artifact or link to the distribution channel.
- Watch the first issue reports for crashes, broken providers, or install problems.
