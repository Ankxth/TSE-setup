# TSE Offer Generator — Installer

Download and run this to install the TSE Offer Generator app on your
computer. This repository contains only the installer — there's no
source code or setup required beyond running it.

---

## Download

Go to the **[Releases](../../releases)** page and download
`TSE_Offer_Generator_Setup.exe` from the latest release.

## Installing

1. Double-click `TSE_Offer_Generator_Setup.exe`
2. Click through the setup wizard (the defaults are fine for everyone —
   just keep clicking Next)
3. On the last screen, make sure **"Launch TSE Offer Generator now"** is
   checked, and click Finish

That's it. A shortcut is added to your Start Menu, and to your Desktop
if you checked that box during setup — use either one to open the app
from now on.

Nothing else needs to be installed separately. The one exception:
if this is an older or locked-down Windows computer, the installer may
briefly install a small Microsoft component called "WebView2 Runtime"
automatically partway through — this is normal and only happens if your
computer doesn't already have it (most do).

## First time opening the app

The very first time it opens, you'll see a **"Set up your first
account"** screen instead of a normal sign-in — this only appears once,
on a brand-new install. Choose a username and password, add your email
if you'd like to be able to use "Forgot password" later, pick **Admin**,
and click **Create account & sign in**.

Once you're signed in, if you need a second account (for example, to
also test as a regular engineer rather than an admin), go to the **Team**
page in the sidebar and create one from there.

## Forgot your password?

Click **Forgot password?** on the sign-in screen, enter your username,
and check the email you added to your account for a 6-digit code. This
only works if an email address was added and verified on your account —
if you skipped that step, ask an admin to reset your password from the
Team page instead.

## Connecting to your company's shared server

If your company has set up a shared server (so offers sync between
everyone's laptops), an admin connects to it once from inside the app:
**Settings → Company server sync**. If the server itself hasn't been set
up yet, there's a full step-by-step guide for that right there in the
same Settings page too.

If you're just using the app on your own laptop for now, you can skip
this entirely — everything works fully offline.

## Uninstalling

Uninstalling this app **permanently deletes every offer and account
stored on this computer** — you'll see an explicit warning about this
before it proceeds, separate from Windows' normal "are you sure"
prompt. If this computer syncs with a company server, that server's own
copy of your offers is unaffected — only what's stored locally on this
computer is removed.

## Getting a newer version later

When a new version is released, download the newer
`TSE_Offer_Generator_Setup.exe` from the **[Releases](../../releases)**
page and run it the same way — it installs over the existing version and
keeps all your data (your offers, accounts, and settings are stored
separately from the app itself, so updating never loses anything, unlike
uninstalling).

## Something not working?

- If the app doesn't open at all, there's a log file at
  `%APPDATA%\TSE Offer Generator\launch_log.txt` that records what
  happened — send that along with a description of the problem.
- For anything else, contact your development/IT contact directly.