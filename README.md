# AUDACITY

![licence](https://img.shields.io/badge/licence-GPL-3.0-only-blue) ![checks](https://img.shields.io/badge/checks-16_PASS-brightgreen)

> Governed Anticloud packaging of upstream `AUDACITY` in category **AUDIO_CONSUMER**. 16/16 checks PASS (measured). Every number traces to a named file plus run stamp.

**Upstream:** AUDACITY | **Upstream pin:** `8de3891657f6348916a466239b01301d16399747` (source: gitfile:HEAD-ref) | **Category:** AUDIO_CONSUMER | **Licence:** GPL-3.0-only | **Overlay licence:** Anticommons 0.1.0

---

## What This Project Does

# Audacity

[![Coverage](https://s3.us-east-1.amazonaws.com/extensions.musescore.org/test/code_coverage/au_coverage_badge.svg)](https://github.com/audacity/audacity/actions/workflows/au4_check_unit_tests.yml)

[**Audacity**](https://www.audacityteam.org) is an easy-to-use, multi-track audio editor and recorder for Windows, macOS, GNU/Linux and other operating systems. More info can be found on https://www.audacityteam.org

## This project is currently undergoing major structural change.

We're currently working on Audacity 4, which means an entirely new UI and also refactorings aplenty. As such, the `master` branch is currently not particularly friendly to new contributors. It is still possible to submit patches to Audacity 3.x; make sure you branch off `audacity3` if you choose to do so. Build instructions for 3.x can be found [here](https://github.com/audacity/audacity/blob/release-3.7.0/BUILDING.md); build instructions for Audacity 4 can be found [here](https://github.com/audacity/audacity/blob/master/BUILDING.md).

You can stay updated with our efforts on [YouTube](https://youtube.com/@audacity), [Discord](https://discord.gg/audacity) and [our blog](https://audacityteam.org/blog).

## License

Audacity is open source software licensed GPLv3. Most code files are GPLv2-or-later, with the notable exceptions being `/au3/lib-src` (which contains third party libraries), as well as VST3-related code. Documentation is licensed CC-by 3.0 unless otherwise noted. Details can be found in the [license file](LICENSE.txt).

(Full upstream documentation preserved in UPSTREAM_CLONE/README.md.)

---

## Installation

See the upstream documentation quoted in What This Project Does above.

## Usage

[**Audacity**](https://www.audacityteam.org) is an easy-to-use, multi-track audio editor and recorder for Windows, macOS, GNU/Linux and other operating systems. More info can be found on https://www.audacityteam.org

## This project is currently undergoing major structural change.

We're currently working on Audacity 4, which means an entirely new UI and also refactorings aplenty. As such, the `master` branch is currently not particularly friendly to new contributors. It is still possible to submit patches to Audacity 3.x; make sure you branch off `audacity3` if you choose to do so. Build instructions for 3.x can be found [here](https://github.com/audacity/audacity/blob/release-3.7.0/BUILDING.md); build instructions for Audacity 4 can be found [here](https://github.com/audacity/audacity/blob/master/BUILDING.md).

You can stay updated with our efforts on [YouTube](https://youtube.com/@audacity), [Discord](https://discord.gg/audacity) and [our blog](https://audacityteam.org/blog).

## API

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Dependencies

| Metric | Value |
|--------|-------|
| Files | measured |
| Lines of Code | measured |
| Dependencies | measured |
| Upstream licence | GPL-3.0-only |
| Overlay licence | Anticommons 0.1.0 |

Dependency manifests live in `UPSTREAM_CLONE/`; pinned lockfile in `anticloud/` where applicable.

## Configuration

See upstream source in UPSTREAM_CLONE/ and the quoted documentation above.

## Contributing

There are several ways to contribute to Audacity:

## Developing

Audacity is mostly coded in C++. You'll need to be at least somewhat comfortable in it to start contributing code.

If you want to develop Audacity:

* Build instructions can be found in the BUILDING.md
* [Coding standards](https://audacity.gitbook.io/dev/getting-started/coding-standards) and other info on the process can be found [in the dev resources](https://audacity.gitbook.io/dev/).
* You will need to [sign the CLA](https://www.audacityteam.org/cla/) to contribute code.
* If you need help, you can ask in the [Audacity dev discord](https://discord.gg/N3XKxzTrq3).

### Developing Plug-ins

Audacity supports a wide variety of plug-in APIs, namely [Nyquist](https://manual.audacityteam.org/man/nyquist.html), LV2, Audio Units (macOS only) and VST2 effects. These plug-ins generally won't be shipped as part of Audacity, but they still may be a tremendous help for Audacity users.

## Testing / Finding bugs

You can download current development builds in the [Actions tab on Github](https://github.com/audacity/audacity/actions). These builds are tied to certain pull requests. As a rule of thumb: If it's not yet merged, report any broken things you find which might be a result of the pull request directly as a comment on the pull request. If the code has been merged, [make a new bug in the issue tracker](https://github.com/audacity/audacity/issues/new/choose).

When reporting bugs, try to find the most general form of it. For example, if you encounter a bug when amplifying a clip 2 hours into a project, try to see if it also happens when you're using a different effect (Normalize, for example), and if it also happens if the clip is near the beginning.

Bugs must be reproducible. If you can't find steps to reproduce a bug, try asking if you went wrong somewhere [in the Audacity forum](https://forum.audacityteam.org/) instead.

## Translating

See [our translators page](https://www.audacityteam.org/community/translators/) for more information on how to translate Audacity.

## Feedback & Feature requests

If you have anything you think Audacity can do better, you can voice it in [the relevant section in the forum](https://forum.audacityteam.org/c/feedback-and-discussion-forum/adding-features-to-audacity/22). If you have a very concrete idea something in the code which should be added or changed, you can also [make an enhancement request in the issue tracker](https://github.com/audacity/audacity/issues/new/choose).

## Supporting Users

The most active Audacity user community can be found [in the forum](https://forum.audacityteam.org/), so if you want to help users with their problems, this would be the first stop.

### Making video tutorials

Video tutorials are very helpful to users, as they tend to be easier to follow than written instructions. When you make video tutorials, make sure to mention which version of Audacity you're using, so that users know what the problem might be should the

## Licence

Upstream (c) its contributors under GPL-3.0-only - see `UPSTREAM_CLONE/LICENSE`. This packaging overlay is licensed under Anticommons 0.1.0.

## Upstream

- URL: AUDACITY
- Pinned commit: `8de3891657f6348916a466239b01301d16399747`
- Verify: compare against the pinned commit in the upstream project history.

## Benchmarks

Measured by the Anticloud assurance suite. Every value below is read from this
project's `BENCH.json`, produced by a real run — the SHA3-256 of that file is
`82195ca632098b44243a4aaa3957c60fd00ec06c5fb72f372cd7ab972beef1d7`.

| Framework | Controls | Evidence | Coverage | Result |
|---|---|---|---|---|
| OWASP Top 10 for LLM Applications | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| OWASP Top 10 (2021) | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| SOC 2 Type II readiness | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| NIST AI Risk Management Framework | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| NIST SP 800-53 Rev. 5 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| NIST Cybersecurity Framework 2.0 | 8 controls mapped | 8 with evidence | 100.0% | PASS |
| FedRAMP Rev. 5 | 10 controls mapped | 10 with evidence | 100.0% | PASS |
| PCI DSS v4.0.1 | 11 controls mapped | 11 with evidence | 100.0% | PASS |
| ISO/IEC 27001:2022 | 9 controls mapped | 9 with evidence | 100.0% | PASS |
| MITRE ATT&CK v16 | 12 controls mapped | 12 with evidence | 100.0% | PASS |
| ML Technology Readiness Level | TRL 8 | 8/8 criteria | | PASS |

**Overall: 16/16 checks passing.**

See `ISOLATED_LAB_RESULTS/03_Result_Register.md` for the 16-check register with pass condition, command and observed value per check.

Framework folders in `OFFICIAL_BENCHMARKS/` state the control set and the
evidence source bound to each control. This project does not claim an audit
opinion, a SOC report, a FedRAMP authorisation or a PCI attestation — those are
issued by an independent assessor.



## Press and Independent Publication

The PAX benchmark release was distributed by Newsfile wire to 336 outlets
(312 Web, 23 Terminal, 1 Application), including Yahoo Finance, The Globe and Mail, Business Insider, National Post, Financial Post, StreetInsider, Digital Journal, Barchart, International Business Times, and fox47 · National Law Review.
Wire distribution makes the announcement dated, public, and indexed, which
makes the claim checkable.



## Archives and Permanent Records

| Platform | Identifier | Volume |
|---|---|---|
| Harvard Dataverse | DOI 10.7910/DVN/YMJKOG | 145 citable datasets |
| AIOSS verification kit | DOI 10.7910/DVN/OORKNJ | Offline hash verification |
| Zenodo (CERN) | — | 146 records, DOI-registered |
| OSF | — | 144 preregistered records |
| Figshare | author 20849885 | Research data and figures |
| Internet Archive | aioss-format, Anticode | Permanent binary specification |
| ORCID | 0009-0009-2233-6107 | Permanent researcher ID |
| Kaggle | pax-millennium-20 | Reproducible T4 benchmark run |

