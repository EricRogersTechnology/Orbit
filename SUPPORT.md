# Orbit — Support

A life dashboard: one screen that pulls together your day — calendar, reminders, health,
mail, weather, people, money — instead of making you open ten apps to find it.

**Need help?** Email [Eric@EricRogersTechnology.com](mailto:Eric@EricRogersTechnology.com)
and I'll get back to you. Including your device and iOS version helps me answer faster.

For TestFlight beta testers: you can also send feedback directly through the TestFlight
app — screenshot → tap **Send Beta Feedback**.

## Frequently asked

**Why is the app called Orbit but listed as "Orbit Dashboard"?**
Plain "Orbit" was already taken on the App Store. The listing is *Orbit Dashboard*; the
app on your Home Screen is just *Orbit*. The mismatch is intentional.

**Nothing shows on my dashboard — where's my stuff?**
Every source is opt-in, so a fresh install shows Connect buttons rather than data. Tap
Connect on the sections you want and grant the permission when iOS asks. Sections with
nothing to show hide themselves, but a source you've never connected always keeps its
Connect button.

**How do I set up mail?**
Settings → Email → Add Account. Orbit connects directly to your provider over IMAP —
iCloud, Gmail, Yahoo, Fastmail, or any other. For providers that require it, use an
app-specific password rather than your main one; Gmail in particular will not accept an
account password. Passwords are stored in your device Keychain.

**Mail won't connect.**
Nine times in ten this is credentials rather than the app. Email → Settings has a
connection log with passwords redacted — check it for the actual error. If you pasted a
Gmail app password with spaces in it, that's fine, they're stripped automatically.

**Does my data sync across devices?**
Yes — what you create in Orbit syncs across iPhone, iPad, Mac, Apple TV, and Apple Watch
through *your own* iCloud. Mail account settings ride your iCloud too, and the passwords
ride iCloud Keychain, so adding an account on one device sets it up on the others.

**Can I rearrange the dashboard?**
Yes — Customize Dashboard. Reorder sections, group them, and hide what you don't use.
Changing the grouping defaults never touches a layout you've already arranged.

**Which health metrics does it show?**
Only the ones you turn on. Health → Settings lists them all, core metrics on and the
rest off until you enable them. If a newly-enabled metric stays blank, tap Connect again
— it needs re-authorizing.

**Alarms say "Reminder" instead of "Alarm".**
That means alarm permission is off, so Orbit can only post a notification — which Focus
and silent mode can suppress. Grant the alarm permission and it will use a real alarm
that breaks through.

**Where is my data stored? Is it private?**
Everything stays on your device and in your private iCloud. There's no account, no
server of mine, no ads, and no tracking. Mail and other credentials live in your
Keychain. Because Orbit reads a lot of personal information, the
[Privacy Policy](PRIVACY.html) goes through it source by source — worth a read.

**How do I back up?**
Settings → Sync & Backup. Snapshots are taken automatically, and you can export manually
and pick what's included. When restoring, gap-fill is the safe default; replace deletes
and rebuilds the sections you tick, and because the store is iCloud-backed those
deletions reach your other devices.

---

© 2026 Eric Rogers Technology · [Privacy Policy](PRIVACY.html)
