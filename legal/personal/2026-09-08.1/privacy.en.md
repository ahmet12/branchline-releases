# Branchline Privacy Notice

Version: 2026-09-08.1

## Who handles your information

Ahmet Kılıç, an individual developer in Türkiye operating under the brand Kylindravia, is responsible for Branchline's invitation, licensing, and private-support records. Contact [kylindravia@gmail.com](mailto:kylindravia@gmail.com) with “Branchline privacy” in the subject. This notice explains processing; it is not a request for blanket consent.

## Repositories and optional assistance

Branchline works with repositories on your Mac. Git network operations communicate with the Git hosts you configure and use your configured credentials. Repository paths, source code, remote URLs, and Git credentials are not sent to the licensing service.

If you configure optional commit-message assistance, the app previews the destination and request before you choose Send. The request can contain selected staged file paths and diffs. The selected endpoint receives that request; a local command receives it through standard input and may itself communicate externally. Your provider's handling applies. Activation does not enable or authorize assistance requests.

## Activation and local storage

Activation, extension checks, and deactivation send your activation code and a random installation identifier to Branchline's licensing service. The service stores a license identifier, a keyed digest of the code, the current installation identifier, creation/update/first-activation dates, expiry, disabled state, and revision. It does not store the raw code or an email address in the licensing database. Deactivation clears the installation slot; there is no device-history table.

The request contains no hardware serial number, contact email, app password, repository data, or application version. Ordinary connection metadata, including an IP address, reaches the hosting provider. The service uses a temporary keyed digest of the IP address to limit excessive requests. Worker application logging is disabled; the service does not store the IP address or its digest in its licensing database.

On your Mac, nonsynchronizing Keychain records hold the code, signed receipt, random installation identifier, deactivation state, and last recorded license-check time. When you accept the Personal Access Terms, the app also keeps the notice version, a fingerprint of the bundled texts, and the acceptance time in that local record. This acknowledgement is not uploaded. Uninstalling the app does not automatically remove Keychain records.

## Invitations, support, and diagnostics

The developer uses the Kylindravia Gmail account for invitations and private support, and a private local record to associate an invitation contact with its license identifier. That record is not placed in GitHub or a shared cloud spreadsheet. Invitations and email correspondence may contain the personal code; keep them private.

Support receives the contact details, messages, and attachments you choose to send. Branchline's diagnostic report is prepared and previewed locally; saving it does not upload it. The app does not automatically send diagnostics or crash reports to the developer. Your own macOS diagnostic-sharing settings are separate.

GitHub issues and attachments you submit are public. Do not include activation codes, Git credentials, private source code, or unreviewed logs. Private reports are not published without your permission. Invitation contact details are not used for advertising or added to a marketing mailing list.

## Providers and network requests

Cloudflare hosts the licensing service and database. GitHub hosts downloads, the signed update feed, public documents, and issues. Google provides the developer's Gmail mailbox. These providers receive the information needed for those services and may process it outside Türkiye, including through subprocessors. A European database location does not mean all processing stays in Europe.

Update checks request the public feed from GitHub; an update download requests its application archive. Automatic checks are opt-in, and system-profile reporting is disabled. These requests include connection metadata and the updater's user agent, but no activation code, license receipt, or repository contents. Reading this notice inside Branchline does not make a network request. Opening a web or email link uses your selected external application and its services.

Provider information: [Cloudflare privacy](https://www.cloudflare.com/privacypolicy/), [Cloudflare processing terms](https://www.cloudflare.com/cloudflare-customer-dpa/), [GitHub privacy](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement), and [Google privacy](https://policies.google.com/privacy). Their separate network/security records and retention are governed by their applicable policies. Branchline cannot promise that deleting a local record erases every provider record immediately.

This free license does not require a Lemon Squeezy purchase or send activation requests to Lemon Squeezy. A paid offering will have a separate notice for its actual purchase-data processing before sales begin.

## Purposes and collection basis

Invitation delivery, activation, the one-device allowance, extensions, and requested license support use the information needed to establish or perform the license agreement (KVKK Article 5(2)(c)). Minimal security/rate-limit and administrative records serve the legitimate interest of protecting the licensing service, subject to your fundamental rights (Article 5(2)(f)). Data needed for a specific legal obligation or the establishment, exercise, or protection of a right may be kept on the corresponding basis (Article 5(2)(ç) or (e)).

Information is collected electronically from your activation requests, your chosen messages and submissions, and the developer's invitation administration. No special-category data is requested. Do not send identity documents, bank details, or passwords for ordinary support. The terms checkbox is not consent to marketing, optional assistance, or international transfers.

## How long records remain

Daily service cleanup removes expired licenses after 90 days and invitations never activated after 366 days from issue. Minimal administrative audit records expire after 90 days. Recent database states can remain in Cloudflare D1 recovery history for up to seven days. No additional routine export of the licensing database is currently configured.

The developer's invitation/contact mapping is removed within 90 days after access expires or participation ends; unused invitations and their mapping are removed by day 366. Closed support correspondence and its local copies are removed within 90 days after closure. Unneeded sensitive attachments are removed sooner. A specific dispute or legal obligation may require a limited record for longer; the reason and scope will be explained in response to a relevant request. Public issue content is subject to GitHub's controls, and provider security/backup retention may differ.

Records on your own Mac remain under your control. Deactivation releases the server device slot but preserves local history and recovery access; it is not a complete data-deletion request. Contact support before removing license records if you still need to release or recover the device slot.

## Requests and your rights

Contact the private address above to ask whether your data is processed, request details of purposes and recipients, seek correction or deletion where applicable and notification to recipients, object to adverse solely automated decisions, or seek remedies for unlawful processing. Human review of activation restrictions is available through that contact.

Use your invitation email address where possible and identify the request; do not send the complete activation code or an identity document initially. Only proportionate verification information will be requested if needed. Requests are answered as soon as practicable and, for requests under KVKK, within 30 days. Applicable complaint and other legal remedies remain available.

Changes will be identified by a new notice version. Existing acceptance records are not rewritten when the text changes. Review the notice supplied with a later release for any new processing before using a new optional feature.
