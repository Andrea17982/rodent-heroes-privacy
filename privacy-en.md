# Rodent Heroes — Privacy notice

Last updated: 22 October 2026.

## 1. Controller and contacts

Controller: Andrea Nastro, Prato, Italy.
Privacy contact: <andreanastro1999@gmail.com>.

Rodent Heroes is a game in development (alpha) and is not published yet: this notice applies to the test account
and game data created during tests.

## 2. What we process

**Account.** Account identifier; email address only when you sign in with Google; whether the account is an
anonymous guest; creation, last activity, deletion request and deletion dates. We do not store passwords:
authentication is handled by the provider (Google or anonymous sign-in).

**Game.** Owned heroes and levels, equipment, team, balances and movements (gold, embers, materials, shards),
claimed rewards, daily repeats, drop progress, stages and open battles with their outcome. Open battles keep the
random seeds server-side, which are required to rebuild the outcome and are never sent to the client.

**Purchases.** Product identifier, type, Play order identifier, state (granted or revoked), dates and a
cryptographic fingerprint (SHA-256) of the purchase token. We never receive or store card or payment details:
payment happens on Google Play. The clear-text token is not stored.

**Support.** Granted compensations with reason and operator, and the corresponding movements.

**Technical and security data.** Technical records kept by the hosting provider to run the service and prevent
abuse; anonymous deletion audit (guest yes/no, request and deletion day, accounting movements without any link to
identity).

**Backups.** Encrypted copies of the test database on the controller's disk, outside cloud services, kept for at
most seven days. The encryption key stays in the controller's private folder.

**Rewarded ads and privacy choices.** We are integrating Google AdMob and Google User Messaging Platform
(UMP); ads remain disabled as of this notice. Once enabled, the SDKs may process IP addresses, device and
advertising identifiers, technical information and ad interactions, depending on configuration and privacy
choices. UMP collects and stores privacy choices on the device.
To verify a reward, we send the account identifier to AdMob in `custom_data`; Google returns it in a signed
callback. Our server stores the reward, date, offer and SHA-256 fingerprint of the transaction identifier
to prevent duplicates and enforce the daily limit. The permanent skip entitlement grants the same reward
without requesting a video.

When required by UMP, **Settings → Privacy choices** lets you reopen the options.
Declining personalization does not prevent access to the game; ad availability may vary.
See [how Google uses information from partner apps](https://policies.google.com/technologies/partner-sites?hl=en).
We have not integrated separate analytics or crash reporting tools.

## 3. Purposes and legal bases

- **Providing the game and managing the account** (account and game data): performance of a contract, Art. 6(1)(b) GDPR.
- **Purchases and support**: contract performance and accounting/tax duties, Art. 6(1)(b) and (c) GDPR.
- **Security, abuse and fraud prevention, balance integrity**: legitimate interest, Art. 6(1)(f) GDPR.
- **Legal obligations and authority requests**: legal obligation, Art. 6(1)(c) GDPR.
- **Ads and measurement (only if and when enabled)**: consent, Art. 6(1)(a) GDPR, withdrawable at any time.

## 4. Recipients and transfers

- **Supabase**: database, authentication and server functions. Data may be processed outside the European Union
  under the provider's contractual safeguards (standard contractual clauses).
- **Google**: Google sign-in, Google Play for purchases and refunds, AdMob ads if enabled.
- **GitHub Pages**: hosts this notice; it receives no game data.
- **Authorities**: when required by law.

We do not sell personal data and do not use it for advertising profiling without consent.

## 5. Retention

- Active account: data is kept while the account exists.
- Deletion requested by a linked account: 7 days to change your mind; signing back in cancels the request.
  A guest account is deleted immediately when it signs out or requests deletion.
- After the deadline, game data is deleted in cascade; only the anonymous audit described above remains.
- Backups: at most 7 daily copies on the controller's disk; a deletion may reappear in a backup for up to
  7 days, then it disappears with rotation.

## 6. Security

Encrypted connections (verified TLS), least-privilege database roles, no direct client access to tables, balances
and rewards computed server-side, purchase tokens stored only as fingerprints, encrypted backups (AES-256-GCM).
No system is 100% secure: in the event of a breach likely to entail a risk, we will notify data subjects and the
authority as required.

## 7. Your rights

You may request access, rectification, erasure, restriction, objection and portability, and withdraw consent.
In the game: **Settings → Your data** to export your data and request deletion. Otherwise write to
<andreanastro1999@gmail.com>. You may lodge a complaint with the Italian Garante or your local supervisory authority.

## 8. Children

The game is not intended for children under 14. If a child's account was created by mistake, write to the contact
above for deletion.

## 9. Changes

Version 1.0, 22 October 2026. Material changes will be announced in the game before they take effect.
