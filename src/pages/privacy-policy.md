---
layout: ../layouts/Policy.astro
title: Paisa Privacy Policy
description: How Paisa handles your data. Everything stays on your phone.
---

# Paisa Privacy Policy

**Effective date:** 25 October 2026
**App:** Paisa (Android package `com.twopixellabs.paisa`)
**Developer:** Jaimin Viramgama
**Contact:** [jaiminviramgama152@gmail.com](mailto:jaiminviramgama152@gmail.com)

## The short version

Paisa is an expense tracker that keeps everything on your phone. There is no Paisa account, no Paisa server, no analytics, no ads and no tracking. Paisa does not send your data anywhere. The only time data leaves the app is when you export a file yourself and choose where it goes.

## What Paisa stores, and where

Paisa stores the following **only on your device**, in the app's private storage that other apps cannot read:

- Transactions you record: amount, category, description, payment method, date and time
- Categories, monthly budget, category budgets, savings target and the day your month starts
- Recurring expenses (such as rent or subscriptions) and reminder settings
- App settings, such as whether App lock is on
- Payment alerts waiting for your review (see "Payment detection" below)

We (the developer) never receive any of this. We cannot see, access or recover it.

## Payment detection (optional, Android only)

Paisa can find UPI payments for you by reading payment alerts that arrive on your phone, such as bank SMS shown by your messages app and alerts from UPI apps like Google Pay, PhonePe and Paytm. This feature is **off until you turn it on**, and it needs you to grant Paisa "Notification access" in Android settings.

When it is on:

- Paisa looks at each notification as it arrives, on your phone.
- It keeps only notifications that look like money spent or received (they mention words such as "debited", "paid", "credited" or "received" along with an amount). **All other notifications are ignored and never stored.**
- Notifications that contain a one-time password (OTP) or verification code are always ignored, even if they mention a payment.
- Kept alerts are stored privately on your phone until you add them as transactions or dismiss them. Paisa reads the amount, the payee or sender, and the UPI reference from them.
- Nothing is added to your records without your confirmation.
- Paisa may show its own notification (for example "₹250 paid") so you can add the payment quickly.

You can turn payment detection off at any time in Android Settings → Notification access (or from Paisa's Settings). Payments already found stay in Paisa until you review them.

## Permissions Paisa uses

| Permission | Why |
|---|---|
| Notification access | Payment detection, described above. Optional. |
| Post notifications | Bill reminders you turn on, and alerts for detected payments. |
| Run at startup | Re-schedules the bill reminders you turned on after your phone restarts. |
| Biometric / fingerprint | App lock, if you turn it on. Your fingerprint or face data never reaches Paisa; Android only tells Paisa whether unlocking succeeded. |
| Internet | Included by the app framework Paisa is built on. Paisa does not use it to send or receive your data. |
| Visibility of Google Pay and Paytm | Lets Paisa check whether these UPI apps are installed so it can open them for you. Paisa does not read anything from them. |

## Exports and backups

You can create two kinds of file, only when you ask for them:

- **CSV export:** a spreadsheet of your transactions, readable by anyone who has the file.
- **Encrypted backup:** all your Paisa data, encrypted with a password you choose. Without the password the file cannot be read, and we cannot recover a lost password.

Paisa hands these files to Android's share or save screen, and you decide where they go (for example your Files app, Google Drive or email). Once a file leaves Paisa, the privacy terms of wherever you save or send it apply.

Android's automatic cloud backup is **turned off** for Paisa, so your data is not copied to Google's backup service. If you uninstall Paisa or lose your phone without an exported backup, your data cannot be recovered.

## What we don't do

- We don't collect, sell, rent or share your data, because we never receive it.
- We don't use analytics, advertising IDs, crash-reporting services or third-party trackers.
- We don't require an account, a phone number or an email address.

## Deleting your data

- Delete individual transactions inside the app.
- Settings → Delete all data erases everything Paisa has stored.
- Uninstalling Paisa removes all of its data from your phone.

## Security

Your data lives in Paisa's private app storage. You can add App lock (fingerprint, face or device PIN) so others using your phone can't open Paisa. App lock is a privacy screen: it does not encrypt the data stored on the phone. Encrypted backups are protected with your password.

## Children

Paisa is not directed at children under 13, and we do not knowingly collect information from anyone, including children.

## Changes to this policy

If Paisa's handling of data changes, we will update this page and the effective date above before the change reaches the app.

## Contact

Questions about this policy: [jaiminviramgama152@gmail.com](mailto:jaiminviramgama152@gmail.com)
