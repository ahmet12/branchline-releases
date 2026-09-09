# Branchline Privacy Notice — Purchased Licenses

Version: paid-2026-09-09

## Who handles your information

Ahmet Kılıç, an individual developer in Türkiye operating under the brand Kylindravia, is responsible for Branchline's licensing and private-support records. Contact [kylindravia@gmail.com](mailto:kylindravia@gmail.com) with “Branchline privacy” in the subject. This notice explains processing for purchased licenses; it is not a request for blanket consent. Free personal invitations have a separate notice.

## Repositories and optional assistance

Branchline works with repositories on your Mac. Git network operations use the Git hosts and credentials you configure. Repository paths, source code, remote URLs and Git credentials are not sent to the licensing service or to Lemon Squeezy for activation.

Optional commit-message assistance previews its destination and request before you choose Send. The request may contain selected staged file paths and diffs. Your chosen endpoint receives it; a local command receives it through standard input and may communicate externally itself. Your provider's handling applies. Buying or activating a license does not enable or authorize assistance requests.

## Purchase and license verification

Lemon Squeezy handles checkout as merchant of record. It and its payment providers process the checkout information you supply, including contact, billing and payment details, along with connection and transaction information, to handle the purchase, receipt, license delivery, taxes, fraud checks and refunds. Their own notices and legal duties apply. Branchline does not collect payment-card details in the app.

The developer can access order and customer details through Lemon Squeezy for purchase support, refunds and necessary administration. Branchline's service sends a purchased license key to Lemon Squeezy for validation and retrieves the corresponding license, order and product information. Provider responses and signed order/license notifications can contain customer contact and billing information; the service processes those responses transiently but does not copy those fields or complete notification payloads into its licensing database or application logs. The Mac's random installation identifier is not forwarded to Lemon Squeezy.

The licensing database stores only the purchase and license references needed to manage access: order/license/product identifiers, a keyed digest of the license key, purchase and update-cutoff dates, device allowance, status and revision, verification dates, and active random installation identifiers with their activation dates. It stores no raw key, customer email, billing address, payment-card data or repository contents. These linked references are not claimed to be anonymous.

## Activation and local storage

Activation, requested license checks and deactivation send your key and a random installation identifier to Branchline's service. Deactivation deletes that Mac's active installation entry. The request contains no hardware serial number, contact email, app password, repository data or application version.

Ordinary connection metadata, including the IP address, reaches Cloudflare as the hosting provider. The service temporarily uses a keyed digest of the IP address to limit excessive requests. Worker application logging is disabled; neither the IP address nor its digest is written to the licensing database.

On your Mac, nonsynchronizing Keychain records hold the key, signed receipt, random installation identifier, deactivation/revocation state and last recorded license-check time. Separate records of accepted personal and purchased terms include the notice version, a fingerprint of the bundled texts and the acceptance time. Acceptance records are not uploaded. Uninstalling does not automatically erase Keychain records.

## Support, diagnostics and providers

Private support uses the developer's Kylindravia Gmail mailbox and local Mac. It receives contact details, messages and attachments you choose to send. Purchase contacts are not added to a developer marketing list or used for advertising. A diagnostic report is prepared and previewed locally; saving it does not upload it. Automatic stability reporting is off by default. The separate, optional setting described below enables it. Your own macOS diagnostic-sharing settings are separate.

GitHub issues and their attachments are public. Review what you submit; do not include license keys, Git credentials, private code or unreviewed logs. Private reports are not published without permission.

Cloudflare hosts licensing and its database. Lemon Squeezy provides checkout, purchase records and license verification. GitHub hosts downloads, the signed update feed, public documents and issues. Google provides the developer's Gmail mailbox. These providers receive the information needed for their services and may process it outside Türkiye, including in the United States and through subprocessors. A European database location does not mean all processing remains in Europe.

Update checks and downloads request public resources from GitHub. Automatic checks are opt-in; system-profile reporting is disabled. Requests include connection metadata and the updater's user agent, but no license key, receipt or repository contents. Reading this notice inside Branchline makes no network request. Opening a purchase, web or email link uses the selected external application and its services; Lemon Squeezy My Orders signs you in there without giving Branchline that login.

Provider notices: [Lemon Squeezy](https://www.lemonsqueezy.com/privacy), [Cloudflare](https://www.cloudflare.com/privacypolicy/), [Cloudflare processing terms](https://www.cloudflare.com/cloudflare-customer-dpa/), [GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement) and [Google](https://policies.google.com/privacy). Their separate transaction, network, security and backup records follow their applicable policies. Deleting a Branchline record cannot immediately erase every provider record.

## Purposes, collection and retention

Activating a purchase, enforcing its device/update allowance, moving a device and handling requested support use information necessary to establish or perform the license agreement (KVKK Article 5(2)(c)). Minimal security and administrative records serve the legitimate interest of protecting the service, subject to your fundamental rights (Article 5(2)(f)). Specific legal duties or the establishment, exercise or protection of a right may require limited records on the corresponding basis (Article 5(2)(ç) or (e)).

Information is collected electronically from your chosen checkout and activation requests, Lemon Squeezy purchase/license responses and notifications, and messages you send. No special-category information is requested for ordinary licensing or support. Do not send identity documents, bank details or passwords for routine support. Accepting the terms is not consent to advertising, optional assistance or international transfers.

Purchase and license entitlement records remain while needed to honor or resolve the perpetual license, including reactivation. The end of the update period does not delete them. There is no automatic expiry-based deletion of purchased entitlements. Fully refunded, disabled or disputed records are reviewed on a deletion request; a minimal record may remain where needed to prevent reactivation of a refunded key or meet a specific obligation or claim. The reason and scope of a restriction on deletion will be explained when responding to the request.

Active installation entries remain until the corresponding Mac is deactivated or support releases it. Minimal notification-processing records contain only a payload digest, resource reference and processing/retry dates and counts. Completed entries are removed after 90 days; pending entries remain until reconciled. Recent database states may remain in Cloudflare D1 recovery history for up to seven days. There is no additional routine database export; a temporary export for a maintenance or recovery task is deleted when that task is verified complete.

Closed support correspondence and local copies are removed within 90 days of closure; unneeded sensitive attachments are removed sooner. A particular dispute or legal obligation may require a limited record for longer. Lemon Squeezy separately retains purchase, payment and customer records under its policy and legal obligations; Branchline does not promise the same 90-day period for those records. Public issue retention follows GitHub's controls. Records on your Mac remain under your control; deactivation and uninstalling are not complete data-deletion requests.

## Requests and your rights

Contact the private address above to ask whether your data is processed, request details of purposes and recipients, seek correction or deletion where applicable and notification to recipients, object to adverse solely automated decisions or seek remedies for unlawful processing. Human review of license restrictions is available. Where applicable, you may also request restriction, access or a portable copy of your data.

Use your purchase email address where possible and identify the order; do not initially send the full key or an identity document. Only proportionate verification will be requested if necessary. Requests are answered as soon as practicable and, for KVKK requests, within 30 days. Applicable complaint and other legal remedies remain available. For records controlled separately by a provider, its privacy contact and rights process also apply.

Changes receive a new notice version. Existing acceptance records are not rewritten. Review the notice supplied with a later release for new processing before using a new optional feature.

## Optional crash and hang reporting

Settings → Diagnostics explains this feature before you enable it. With your separate, revocable permission, Branchline sends technical crash reports and macOS-provided hang/CPU/disk diagnostics to Kylindravia’s Sentry project to diagnose stability problems. Reports include the app version/build, macOS version, CPU architecture, technical stack traces, timestamps and recent operation types/stages (for example, Pull started or failed). The app excludes repository and branch names, user file paths, source code, diffs, terminal output, arbitrary error messages, credentials, license information and account identity. Screenshots, session recording, automatic network breadcrumbs and tracing are disabled. This preference is independent of activation, purchases and optional assistance. macOS determines which hang diagnostics are available; delivery is not guaranteed for every freeze.

Sentry (Functional Software, Inc.) is an additional service provider. The selected data storage region is the European Union. A request necessarily reaches Sentry with connection metadata such as an IP address; the project is configured not to store IP addresses in events. EU storage does not mean all processing remains in the EU: provider security records, support and subprocessors may involve other countries. See [Sentry service data processing](https://sentry.io/legal/dpa/) and [Sentry privacy](https://sentry.io/privacy/). The free service retains events for up to 30 days; provider security/backup records can have separate retention.

Turning the setting off stops collection and discards pending local reports. Already sent reports cannot be recalled by the app. Temporary local crash/cache records are used for delivery after relaunch and are separate from the report file you can preview and export manually. Contact kylindravia@gmail.com for a report-related request, with the report ID if available; no persistent user or license identifier is attached. Test reports are explicitly labelled and do not crash the application. Existing acceptance records are not changed by enabling or disabling this preference.
