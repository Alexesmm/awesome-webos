# Safety and Compatibility

Awesome WebOS is a community-curated directory. Inclusion does not mean that a project has been independently audited, tested, or endorsed by its maintainers.

## Installation and safety

Apps installed outside the LG Content Store are unsigned and unreviewed by LG, so you are responsible for what you run on your TV. Please keep these points in mind:

- **Read [safety.md](safety.md) before installing anything.** It covers installation steps, risks, and recovery notes for the projects on this list.
- **Developer Mode is temporary.** It has a time limit of 1000 hours, after which apps installed through it are removed unless you reset the timer in the Developer Mode app. You can also be logged in on only one TV per developer account at a time.
- **Install only from sources you trust.** Prefer the official Homebrew catalog or the project's own repository, and avoid IPK files shared through unknown links.
- **Check requirements first.** Many tools need Developer Mode, Homebrew Channel, or root access, and support varies by webOS version.
- **Rooting carries real risk.** Methods are firmware-specific, can be patched, and may cause instability or affect warranty and support, so verify your model and firmware before proceeding.
- **Be careful with network tools.** VPN clients, DNS blocklists, and filtering tools can break streaming apps or TV features, so note your original settings before changing them.
- **Back up and stay informed.** Do not update firmware on a rooted TV without checking whether your method still works on the new version.

Inclusion in this list is not a security audit or an endorsement. You use these projects at your own risk.

## Before installing software

- Prefer canonical project repositories and official documentation.
- Review installation instructions, permissions, dependencies, and source code when available.
- Check recent project activity and reported issues.
- Avoid third-party mirrors when an official source is available.
- Understand how to reverse changes before modifying system settings.

## Rooting and firmware changes

Root access and firmware modification can increase control over a TV, but may also cause instability, loss of settings or functionality, update problems, security exposure, or a device that requires recovery.

Verify the exact TV model, region, webOS version, and firmware against current documentation. Do not assume that instructions for one model or firmware apply to another. Keep recovery instructions available before making changes.

## Privacy and network filtering

DNS filtering, telemetry controls, and ad blocking can interfere with sign-in, playback, app updates, or other TV services. Apply changes incrementally and record how to undo them. A tool that claims to improve privacy is not necessarily comprehensive or safe; review what it changes and what traffic it can access.

## Version compatibility

LG TVs use different webOS versions, and available features, APIs, and system behavior may vary by webOS version, TV model, region, and firmware. A project working on one TV does not necessarily mean it will work on another, even if the TVs appear to use a similar webOS version.

Before installing or recommending a project:

- Check the project's documentation for its supported or minimum webOS version and any model or firmware requirements.
- Verify your TV's model, webOS version, and firmware in the TV's settings. Menu names and locations can vary by model and software version.
- Do not rely on the model year alone to determine compatibility; verify the specific TV and software versions.
- When documenting compatibility in this repository, state the exact model and webOS version tested, and include the firmware version when it matters. Distinguish confirmed testing from information reported by users.
- Re-check compatibility after a TV firmware update, since an update may change behavior or affect methods that previously worked.

Avoid broad claims such as “works on all LG TVs” unless there is reliable evidence across the relevant models and software versions.

## Reporting vulnerabilities

If you find a vulnerability, contact the project's maintainers privately through their published security-reporting channel when possible. Avoid publishing exploit details that could put users at risk before maintainers have had a reasonable opportunity to respond.

## Disclaimer ⚠️

This repository is provided for informational purposes only. Users are responsible for evaluating third-party software and deciding whether to install it. The maintainers of Awesome WebOS do not guarantee the accuracy, safety, availability, or compatibility of listed resources.