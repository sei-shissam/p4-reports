| OSS Project Report | Response |
  |--------------------|:---------|
| Overview | <hr> |
| Background | spiral-software/spiral-software, Public source repository for the SPIRAL project |
| Application or Library | Manual (ask) |
| Current as of | Date: 08-12-2025 (project queried 0 days ago) |
| OSS-P4/R Outlook | <table class='wrapped' data-mce-resize='false'><colgroup><col/></colgroup><tbody>      <tr><td>Overall</td><td>Project (4.5)</td><td>Product (10.0)</td><td>Protection (3.1)</td><td>Policy (7.0)</td></tr><tr><td><hr style='border: 10px solid gray; border-radius: 5px'/></td></tr><tr><td>MY Checks</td><td>Project (10.0)</td><td>Product (NaN)</td><td>Protection (NaN)</td><td>Policy (10.0)</td></tr><tr><td>OSSF Scorecard</td><td>Project (0.7)</td><td>Product (10.0)</td><td>Protection (3.1)</td><td>Policy (3.0)</td></tr><tr><td>MITRE Hipcheck</td><td>Project (2.7)</td><td>Product (10.0)</td><td>Protection (NaN)</td><td>Policy (NaN)</td></tr>  </tbody></table> |
| DOD CIO Criteria | <table class='wrapped' data-mce-resize='false'><colgroup><col/></colgroup><tbody>      <tr><td>Criteria</td><td>Security (8.1)</td><td>Integrity (0.4)</td><td>Dependencies (0.0)</td><td>Malicious Actors (10.0)</td><td>Long-Term Support (3.5)</td><td>Suitability (9.5)</td></tr><tr><td><hr style='border: 10px solid gray; border-radius: 5px'/></td></tr><tr><td>MY Checks</td><td>Security (NaN)</td><td>Integrity (NaN)</td><td>Dependencies (NaN)</td><td>Malicious Actors (NaN)</td><td>Long-Term Support (10.0)</td><td>Suitability (10.0)</td></tr><tr><td>OSSF Scorecard</td><td>Security (6.2)</td><td>Integrity (0.8)</td><td>Dependencies (0.0)</td><td>Malicious Actors (NaN)</td><td>Long-Term Support (0.4)</td><td>Suitability (9.0)</td></tr><tr><td>MITRE Hipcheck</td><td>Security (10.0)</td><td>Integrity (0.0)</td><td>Dependencies (NaN)</td><td>Malicious Actors (10.0)</td><td>Long-Term Support (0.0)</td><td>Suitability (NaN)</td></tr>  </tbody></table> |
| Summarized Scores By CIO Criteria |   <table class='wrapped' data-mce-resize='false'><colgroup><col/><col/><col/><col/><col/><col/><col/></colgroup><tbody>      <tr><td>Criteria:<br/></td><td>Security</td><td>Integrity</td><td>Dependencies</td><td>Malicious Actors</td><td>Long-Term Support</td><td>Suitability</td></tr><tr><td>MY Checks:<br/></td><td></td><td></td><td></td><td></td><td>Project Forked(false/false)<br/>Problem Reporting(true/true)<br/>Project Abandoned(false/false)<br/>Dependent Projects Abandoned(0/0)<br/></td><td>Restrictive License(s)(0/0)<br/></td></tr><tr><td><a href='https://github.com/ossf/scorecard/blob/main/docs/checks.md'>OSSF Scorecard</a>:<br/>(higher's better) (x)3.2/10.0</td><td>Binary Artifacts(10/3.3)<br/>(x)Branch Protection(0/3.3)<br/>Dangerous Workflow(10/3.3)<br/>(x)Token Permissions(0/3.3)<br/>Vulnerabilities(10/3.3)<br/>(!)Webhooks(NaN/3.3)<br/></td><td>(x)Code Review(2/3.3)<br/>(x)CI Tests(0/3.3)<br/>(x)Fuzzing(0/3.3)<br/>(x)SAST(0/3.3)<br/>(!)Packaging(NaN/3.3)<br/>(!)Signed Releases(NaN/3.3)<br/></td><td>(x)Dependency Update Tool(0/3.3)<br/>(x)Pinned Dependencies(0/3.3)<br/></td><td></td><td>(x)Contributors(3/3.3)<br/>(x)Maintained(0/3.3)<br/>(x)CII Best Practices(0/3.3)<br/>(x)Security Policy(0/3.3)<br/></td><td>License(9/3.3)<br/></td></tr><tr><td><a href='https://github.com/mitre/hipcheck/blob/main/docs/book/src/using/analyses.md'>MITRE Hipcheck</a>:<br/>(score &le; threshold) (x)INVESTIGATE risk rated as 0.75, acceptable below or equal to 0.50</td><td>Binary Artifacts(0.0/0)<br/>Large Commits(0.0/0.02)<br/>Malware Entropy(0.0/0)<br/>(!)Typosquatting(NaN/true)<br/></td><td>(x)Self Reviews(0.7/0.2)<br/>(x)Fuzz Testing(false/true)<br/>(x)Pull Reviews(1.0/0.05)<br/></td><td></td><td>Author Affiliation(0.0/0)<br/></td><td>(x)Commit Activity(86.0/71)<br/></td><td></td></tr>  </tbody></table> |
| Security | <hr> |
| Trusted Source(s) | Source: https://github.com/spiral-software/spiral-software<br>D-U-N-S Availability: Manual<br>Repo or Mirror: Manual |
| Public or Private | Visibility is: public<br>Private is: false |
| Fully Unrestricted | Read-Only: manual<br>Write: manual |
| Login Credentials | Manual |
| Use of Repository Protections | (x)0/10 as branch protection not enabled on development/release branches<br>10/10 as no dangerous workflow patterns detected<br>(x)0/10 as detected GitHub workflow tokens with excessive permissions, and<br>(!) check that webhooks is configured supporting secrets not run |
| Large Commits | Detected no unusually large commits being 0.000 found under or at the 0.02 permitted threshold (Churn) |
| Obfuscated Code | Detected no unusual-looking commits being 0.0 found under or at the 0 permitted threshold (Entropy) |
| Binary Artifact(s) | 10/10 as no binaries found in the repo with binaries potentially containing code being 0 found under or at the 0 permitted threshold |
| Typosquatting Risk | (!)Failed to analyze for typos - can't identify a known language |
| Known Vulnerabilities | 10/10 as 0 existing vulnerabilities detected (open, known unfixed vulnerabilities). And no additional dependent vul(s) detected |
| Integrity | <hr> |
| Peer Reviews | Count pending; and activity is (x)2/10 as Found 3/15 approved changesets -- score normalized to 2 with change requests often lacking approving review prior to merge with 100.000% (x)over the 5.0% threshold and commits too often applied by the author with 69.77% (x)over the 20.0% threshold |
| Use of Code and Security Scanners | (x)0/10 as project is not fuzzed with repository (x)not receiving regular fuzz testing<br>(x)0/10 as SAST tool is not run on all commits -- score normalized to 0, and <br>(x)0/10 as 0 out of 13 merged PRs checked by a CI test -- score normalized to 0 |
| Signed Commits | Manual |
| Cryptographically Signed Commits | 38 of the last 100 commits have a valid cryptographic signature. |
| Cryptographically Signed Releases &amp; Artifacts | (!)-1/10 as no releases found, and<br>(!)-1/10 as packaging workflow not detected; investigate if any such signing(s) are crytopgraphic |
| Dependencies | <hr> |
| Published Software Bill of Materials | SPDX-2.3,Tool: protobom-v0.0.0-20250805170613-cf5b071169fb+dirty,Tool: GitHub.com-Dependency-Graph<br>Language package managers detected: 2 githubactions, 1 github |
| Dependencies Pinned to Version | (x)0/10 as dependency not pinned by hash detected -- score normalized to 0 |
| Dependencies Up to Date | (x)No with no update tool detected; investigate if any dependencies apply to more than the pipeline |
| Number OSS Dependencies | Primary: Total found: 3, dependencies pulled: 3, dependencies unknown: 0<br>Secondary: Total found: (!)0, dependencies pulled: (!)0, dependencies unknown: 0<br>Tertiary and greater (Max search depth realized 1): Total found: (!)0, dependencies pulled: (!)0, dependencies unknown: 0 |
| Number Proprietary Dependencies | Primary: Manual<br>Secondary and tertiary: Manual |
| Malicious Actors | <hr> |
| Author(s) Known to Commit Vulnerabilities | Manual |
| Author(s) Known to Commit Malicious Code | Hipcheck contributors affiliations being 0 found at or under the 0 permitted threshold |
| Long Term Support | <hr> |
| Project Summary | spiral-software/spiral-software, Public source repository for the SPIRAL project |
| Individual or Organization | Organization<br>Details: Name: Not Reported<br>Company: Not Reported<br>Bio: Not Reported<br>Email: Not Reported<br>Blog: Not Reported<br>Geo: Not Reported<br>Source: GitHub |
| Organization Type | Pending, see: https://api.github.com/users/spiral-software/orgs <br>logistics database D-U-N-S code: Manual |
| SLSA Level | Pending: (ask) |
| Best Practices | (x)0/10 as no effort to earn an OpenSSF best practices badge detected |
| Number of Abandoned Project(s) | spiral-software is not archived; 0 of the primary dependencies are abandoned; (!)tertiary (other) dependencies are not checked at this time |
| OSSF's Activity (criticality) Score (work in progress) | 0.28/1.0 (higher's better) |
| Commits | Days since last commit: 32 days, on Fri Jul 11 20:17:02 UTC 2025, reported 0 days ago<br>Days since first commit: 2184 days, on Tue Aug 20 18:26:20 UTC 2019, reported 0 days ago<br>Activity: (x)0/10 with 0 commit(s) and 0 issue activity found in the last 90 days -- score normalized to 0 with most recent activity being 86 weeks (x)over the 71 week threshold |
| Number of Contributors | Core: Count pending<br>Other: 4<br>Organizational diversity: (x)3/10 as project has 1 contributing companies or organizations -- score normalized to 3 |
| Problem Reporting Process | Yes with 11 open issues |
| Vulnerability Reporting Process | (x)0/10 as security policy file not detected |
| Suitability | <hr> |
| License | License: Other<br>SPDX_ID: NOASSERTION |
| License Risk | No restrictive license detected<br>Found (!)1 license(s) yet to be determined suitable: NOASSERTION. <br>Detected no product or dependent license(s) detected  and no impacts potentially reported from dependencies |
| About this report | <hr> |
| Created | Tue Aug 12 21:56:11 UTC 2025 |
| Version | pubRel 250516evie (branch: publicRelease) |
| Analysis Source | Package SBOM: spiral-software_ghapi_sbom.json, 71bdba722fb03337a155610e9f23f8de |
| Analysis ID | SBOM created on 2025-08-12T21:55:32Z (complete) |
| Runtime | Approximately 0 minute(s) (this run), for a total of 0 minute(s) over 1 run(s) |
| Command line | /home/hc_user/.local/bin/scir-oss.sh -l -v -C spiral-software -G spiral-software/spiral-software -P github:sbom |
| Dependency and Scoring depth | 1, 0 |
| Comment/Caveats | I: config image _OSSFSC=/home/hc_user/.local/bin/scorecard<br> I: config image _MITRHC=/home/hc_user/.local/bin/hc<br> I: config setting _OSSSCIRsettings=/home/hc_user/.local/bin/settings<br> I: config setting _MITRHCconfig=/home/hc_user/.local/bin/settings/hipcheck/config<br> I: config setting _MITRHCscripts=/home/hc_user/.local/bin/settings/hipcheck/scripts<br> I: config setting _OSSSCIRlicenseDB=/home/hc_user/.local/bin/settings/mychecks/licenseDB.json<br> I: config setting _OSSSCIRrepoResolveDB=<br> I: env setting _TERTIARY_BLACKLIST='pkg:npm|^npm:'<br> W: could not determine OSSF/criticality_score version<br> I: CA Certificate Trust Store  ()<br> I: SBOM dependencies in 'github' are declared to include transitive dependencies - issue depth is 0 (change with -i)<br> I: Thresholds for OSSF Scorecard scores set at 3.3<br> I: Threshold for OSSF Criticality Score set at 0.2<br> I: Local cache tolerance set to 2 days<br> I: Days active tolerance set to 497 days<br> I: Days for a new project set to 245 days<br> I: Contributors tolerance set to 3 ids<br> W: Some responses may require manual investigation if necessary (look for 'manual')<br> |
| Powered by | OSSF/Scorecard v5.2.1, OSSF/Critical Score unknown, MITRE Hipcheck 3.4.0, grype 0.93.0 db v6.0.3 built on 2025-08-12T04:13:42Z  |
| footnotes | **Data in this report is from public sources and with some being self-reported (e.g., emails, country of origin, names)**.<br> Pending/manual: Check requires manual intervention.<br> Restrictive license: A license that requires code changes be openly published (i.e., copyleft).<br> (!)-1/n: Score could not be valued due to source data.<br> (!)NaN: Score could not be computed due to source data.<br> (!)n: Score indicated a possible risk which requires investigation.<br> (!) not checked: Check is coming soon.<br> (x)m/n: Score did not meet goals and/or thresholds.<br> (x)n: Score did not meet goals and/or thresholds.<br> (x)Yes/No: Score did not meet goals and/or thresholds.<br> (x)true/false: Score did not meet goals and/or thresholds.<br> |

