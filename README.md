# Is Windows on ARM Ready?

This project tracks whether popular applications and development platforms natively support Windows on ARM64.

## Inclusion Criteria

In order to be included in the listings, an application must (1) be something that a large portion of the Windows userbase has heard of and (2) have a version for Windows. For development platforms, it should be something most Windows developers have heard of. In the case of a framework built upon an existing language/platform, it is only eligible for inclusion once the language/platform has native support for ARM64. (So, for example, until .NET supports ARM64, ASP.NET Core can't be listed.)

## Acceptance Criteria

In order to be marked as having an ARM version, an application must (1) have an ARM64 version (2) that is officially supported, (3) available via the same channel as the x86 version, and (4) does not require any additional steps to get the ARM64 version versus the x86 version. Forks, nightly builds, and hidden downloads do not qualify.

## Entry Format

All entries are JSON files with the following format:

```json
{
  "name": "<name of application>",
  "armVersion": false, // or true
  "link": "<url to product page>"
}
```
