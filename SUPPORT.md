# Support

For a bug, [open the bug report form](https://github.com/ahmet12/branchline-releases/issues/new?template=bug-report.yml).
For an improvement, [open the feature request form](https://github.com/ahmet12/branchline-releases/issues/new?template=feature-request.yml).
Search existing reports first; adding a useful detail to an existing report helps keep the discussion together.

English and Turkish reports are welcome. You do not need an app license to participate.
Please keep each issue focused on one problem or request. This repository accepts product
feedback; application source changes are maintained separately.

## Private support

For activation, device changes, purchase questions, or a report that cannot be shared
publicly, email **[kylindravia@gmail.com](mailto:kylindravia@gmail.com?subject=Branchline%20support)**.
Include “Branchline” in the subject so it reaches the right product's support queue.
English and Turkish are welcome. Support is provided by Ahmet Kılıç, the independent
developer behind Kylindravia.

Read how invitations, license records, and support correspondence are handled:
[Privacy Notice](legal/personal/2026-09-09/privacy.en.md) ·
[Gizlilik Bildirimi](legal/personal/2026-09-09/privacy.tr.md).
For access duration, moving Macs, and recovery access, see
[Personal Access Terms](legal/personal/2026-09-09/terms.en.md) ·
[Kişisel Kullanım Koşulları](legal/personal/2026-09-09/terms.tr.md).

Do not post your contact details, activation code, purchase information, or sensitive
report in an issue. Never send passwords, Git credentials, or usable access tokens.

For a suspected security problem, follow [the security reporting guidance](SECURITY.md).

## What makes a useful bug report

Include the Branchline version and build from **Branchline → About Branchline**, your
macOS version, the steps that lead to the problem, and what you expected to happen.
Use a small example repository when possible. You do not need to share your real repository.

Screenshots and diagnostic reports are optional. Review every attachment for private
code, paths, remote URLs, credentials, and identifying details before posting it.

**Help → Diagnostic Report…** prepares a report locally and shows a preview before saving.
It includes app/macOS versions, display preferences, anonymous repository counts, and
operation states. It excludes repository names and paths, branch names, remote URLs,
commit and file content, error messages, environment variables, and credentials.
Preparing or saving it does not upload it. Attach a reviewed report only if it helps explain the problem.

## Optional crash and hang reports

In Branchline 0.4.1 or later, open **Settings → Diagnostics** and enable
**Share crash and hang reports** on each Mac where you want reporting. It is off by
default. **Send Test Report** checks delivery without crashing the app; its report ID
can help locate your test. After a real crash, reopen Branchline so a pending report
can be sent. macOS controls hang diagnostics; not every freeze is reported.

Reporting sends technical stack traces and recent Git operation types to Kylindravia's
Sentry project. Repository contents and credentials are excluded. You can turn reporting
off at any time. See the [privacy notice](legal/personal/2026-09-09/privacy.en.md).
The local **Help → Diagnostic Report…** export remains a separate, manually shared report.

## Reading issue status

| Label | Meaning |
| --- | --- |
| `status: triage` | Received; awaiting review. |
| `status: needs-info` | More information is needed to investigate. |
| `status: confirmed` | The problem has been reproduced or the request accepted for consideration. |
| `status: planned` | Selected for future work; no release date is promised. |
| `status: in-progress` | Work is underway. |
| `status: released` | Available in a published version, linked from the issue. |

`bug` and `enhancement` describe the kind of report. A status label is not a support
response-time guarantee. Release notes will identify shipped fixes.
