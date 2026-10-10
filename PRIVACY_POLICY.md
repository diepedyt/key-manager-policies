# Key Manager Privacy Policy

Last updated: 10 October 2026

Key Manager is the BHUB community's Patreon membership and access-management bot. This policy explains how BHUB handles information when the bot verifies memberships, manages access, responds to commands, and accepts feedback.

The service is operated by BHUB, administered by the Discord user **roge4087**. For privacy questions or requests, contact **roge4087 on Discord**. If you cannot send a direct message, ask a moderator in the BHUB Discord server to connect you with the operator, or contact the creator through [BHUB on Patreon](https://www.patreon.com/BHUB4087). Do not post private account information in public channels.

**This is Key Manager's policy.** Discord, Patreon and Luarmor also have their own terms and privacy practices for their services.

## Information the bot handles

**Discord information.** The bot receives Discord account identifiers, usernames or display names, and relevant server, channel, message, interaction and role information. It uses these to identify the person making a request, respond in the correct place, check moderator permissions and assign the configured buyer role.

**Commands and messages.** The bot receives message content made available to it by Discord and checks for its command prefix. Received message objects may be held temporarily in the hosting server's memory by the Discord client library, including messages that do not become commands. The application does not maintain a persistent general chat archive. Specific command inputs, such as affiliate names and account identifiers, can become stored service records when those commands are used.

You can opt out of this message processing by sending `!privacy off` in a direct message to Key Manager and waiting for confirmation. After confirmation, your ordinary server messages and DMs are discarded before the bot's message cache and command handlers. The bot still examines short privacy-control DMs so you can check or change your preference. Discord may still transmit messages to the bot; this setting controls their use by Key Manager. While opted out, attachments and nested reply content are excluded from those privacy controls, and feedback forms are paused.

**Privacy preferences.** The bot stores your Discord user ID on an opt-out list to remember your choice across restarts. It does not store message text in this list. Sending `!privacy on` removes your ID from the list and restores message commands and feedback forms. Sending `!privacy` shows your current setting. These examples use the default `!` prefix; use the bot's configured prefix if it has been changed.

**Patreon information.** Through the creator's authorized Patreon integration, the bot retrieves membership records and linked social-account information. The data includes Patreon member and user identifiers, names, linked Discord identifiers, membership status, charge status and dates, membership start date, next charge date and entitled amount. It periodically refreshes a campaign membership snapshot; this processing is not limited to members who have already clicked Claim. The current integration does not request payment-card numbers, bank credentials or Patreon passwords.

**Account links and referrals.** The bot stores associations between Patreon identifiers and Discord accounts, affiliate names and identifiers, referral points, credited-member identifiers, renewal anchors and bonus days. Older account-link records may contain a Patreon name or email address as the identifier.

**Access and license information.** The bot looks up and updates the member's Luarmor access record. It handles license identifiers or keys, Discord identifiers, expiry and access or ban status. A Luarmor record may also include linked device identifiers, execution or reset counts, notes and ban-related information, including an IP address if supplied by Luarmor. Returned records may be cached in memory, even when the bot's access decision does not use every field.

**Feedback and support.** If you submit a suggestion or bug report, the bot processes the text, selected game, report type, Discord identity and submission identifier. Drafts may be held temporarily while a form is active. Submitted reports are sent to designated staff channels in Discord. Information you voluntarily include in a support request is also used to handle that request.

**Operational records.** The bot maintains request timestamps, cooldowns, duplicate-request identifiers, panel message identifiers and diagnostic or action records. Logs may include Discord identifiers and action outcomes. Configured credentials are redacted from application logging, and provider payloads and license keys are not intended for public command responses or routine application logs.

## Why information is used

We use this information to match Discord accounts to Patreon memberships, verify eligibility, activate or renew access, display account status, manage referrals, enforce moderator permissions, deliver feedback, prevent duplicate actions and abuse, and troubleshoot failures.

The bot makes automated access decisions using membership status, account links, existing access restrictions and expiry information. A mismatch or provider error can delay or prevent a grant. You can ask the operator to review an outcome through the contact routes above.

Key Manager does not track Discord online presence or activities. We do not sell personal information, use message content for advertising or behavioral profiles, or use it to train machine-learning or AI models.

Where applicable law requires a lawful basis, processing necessary to deliver a requested membership service is based on providing that service; permission checks, duplicate prevention and troubleshooting serve our legitimate interests in operating a reliable and secure service. We also process information when required by law. If a separate use requires consent, that consent must be obtained separately. Using the bot does not waive your privacy rights.

## Where information is processed and shared

Information is processed on the bot's hosting server, outside Discord. Account-link, referral, privacy-preference and panel-tracking records are stored there. Temporary caches and runtime state are held in memory; operational logs are also stored on the server.

- **Discord** carries commands, responses, role updates, interactions and staff reports. Staff with access to the designated channels can see submitted feedback and relevant action notices. Public commands and their responses are visible according to the channel's permissions.
- **Patreon** supplies membership and account-connection information through the creator's authorized integration.
- **Luarmor** receives the Discord identifier and access details needed to create or update an entitlement, such as expiry and a subscription note. The bot receives the corresponding access record.
- **Hosting and administration** involve the infrastructure provider and authorized personnel responsible for operating and maintaining the service.

We may disclose information where required by applicable law. A provider's own processing is governed by its policies. Deleting a bot record does not automatically delete a Discord account, Patreon membership or all records held by a provider.

These services may process information outside your country. Contact the operator for information about the service's hosting location and applicable international-transfer arrangements.

## Retention

We keep information for the purposes described above and remove information that is no longer needed, subject to a valid legal retention requirement.

- **Account-link, entitlement and referral records** are retained while needed to provide or reconcile access, maintain referral balances, or prevent duplicate credit. These records do not automatically disappear when you leave a Discord server or cancel a membership. Removal requires operator handling, including in response to a valid deletion request.
- **Patreon snapshots** are replaced when a complete refresh succeeds. The previous snapshot can remain in memory if a refresh fails. Runtime caches are cleared when the bot process ends; cache freshness settings are not a guaranteed deletion deadline.
- **Messages and command-processing state** are normally temporary. Selected command inputs that become account or referral records follow the retention criteria for those records. The bot does not promise that avoiding commands prevents receipt of messages Discord makes available to it.
- **Privacy preferences** remain until you restore processing or the service permanently ceases handling messages for your account. We retain the minimum Discord ID needed to continue honoring an opt-out. A confirmed opt-out removes your cached messages and pending feedback drafts; it does not automatically delete earlier service records or reports already delivered to staff.
- **Feedback form sessions** expire after 15 minutes and are removed during cleanup or when the bot restarts. Reports already sent to staff channels remain in Discord until removed by authorized staff. They are kept while needed to investigate or follow up on the report.
- **Operational logs** are subject to rotation. Routine server logging is configured for daily rotation with seven rotated copies. Relevant incident records may need separate retention while an issue is investigated; they are removed when no longer needed unless law requires otherwise.
- **Backups, if maintained,** may contain earlier records. Deletion handling must account for those copies and prevent a restore from reinstating information that should remain deleted. Contact the operator for information about any applicable backup retention.

## Your choices and requests

Contact **roge4087 on Discord**, or use the alternative contact routes above, to request access to, correction of or deletion of your information, or to question an automated access outcome. Include your Discord user ID and a brief description of the request. We may ask for reasonable verification that the account belongs to you. We will respond within the time required by applicable law and explain any lawful reason a request cannot be fulfilled in full.

Depending on your location, you may also have rights to restrict processing, object to processing, receive a portable copy of information, withdraw consent where processing relies on consent, and complain to your data-protection authority. UK users can contact the [Information Commissioner's Office](https://ico.org.uk/make-a-complaint/).

To stop message processing, DM `!privacy off` to Key Manager and wait for **Message processing is off**. If a command or feedback submission is finishing, wait and retry. If the preference cannot be saved, the bot reports that failure and the previous setting remains in force. DM `!privacy` to check or `!privacy on` to restore processing. Claim buttons remain available because they do not require reading your message content. If you cannot reach the bot, contact the operator through the routes above.

The message-processing opt-out does not cancel your membership, stop the creator's Patreon snapshot refreshes, erase existing account/referral records, or delete reports already sent to staff. There is no automatic data-deletion command. Contact the operator to address those records and any other processing request. Discord permissions control which server channels the bot can access. Disconnecting Discord from Patreon can stop the linked identifier appearing in future successful Patreon refreshes, but does not itself erase existing records. Removing information needed for verification may prevent us from providing linked membership benefits.

Deleting bot data does not cancel a paid subscription. Manage billing and cancellation through the relevant checkout provider.

## Security and policy changes

Connections to Discord, Patreon and Luarmor use encrypted transport. Access to stored records is restricted to service administration, and staff channels are controlled by Discord permissions. No system or transmission can be guaranteed completely secure. Report suspected unauthorized access privately through the contact routes above.

We will update this document when our data practices change and revise the date at the top. Material changes will be communicated through the BHUB community or another appropriate service notice. New uses that require additional permission will not be authorized merely by changing this policy.
