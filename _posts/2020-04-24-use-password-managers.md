---
title: "Use Password Managers"
date: 2020-04-24
---

Password managers are the tools (desktop and mobile apps) that help you store your passwords and other confidential
information securely. Some of the tools are available for free, whereas some tools require you to pay a monthly fee.
Once you download and install a password manager in all your devices, the passwords are automatically synced in all your
devices. This article tries to convince you to use a password manager and insists you use one, even if you are not
convinced.

### Why should I use a password manager?

Password managers don’t just store your passwords. They also help you:

* Generate a secure, random password for different websites
* Remind you of duplicate, weak, old and previously breached passwords
* Automatically fill login forms as well as input fields in your mobile app
* Automatically change any password for many services
* Sync your passwords across all your devices automatically

### What can I store in a password manager?

Here is a list of the stuff you could store in a password manager:

* Login information like username, password, and email address
* Password for your mobile banking apps
* Bank and credit card information
* Any kind of secure note
* Your SSH Keys
* Server credentials if you are a web developer
* Signing keys and app signing certificates if you are an app developer

### What if I lose all my devices?

As a courtesy, most managers store a copy of your encrypted vault on their servers. Don’t worry, good password managers
are open source, and audited by a third-party security team. The encrypted vault can only be opened with your master
password. Even if you lose access to all your devices, you can access your vault by logging into their service using
your email address, and your master password will be used to unlock your vault.

### But… is my data safe with them?

Yes, password managers encrypt all your information using a master password and store it as a secure vault. The master
password is the only thing you need to remember to access your vault. Whenever you make any change, the entire vault is
once again encrypted, and then synced across your devices. Then the password manager apps installed on your devices need
to re-open the vault using your master password. Not even the service providers, ISP, or intruders in the network can
see your information. Your master password is never sent online; it is only used to unlock the secure vault locally on
your device.

It is essential to use a trusted password manager that is regularly audited by independent security researchers. Like
any other software, a random password manager downloaded from the internet may not be as secure as it should be.

### I can remember everything. Do I still need a password manager?

That’s the problem right there. It is tough to remember long, random passwords for individual websites. If it is easy to
remember, either the password is too short, or it follows a pattern. You might be able to remember passwords for a dozen
services, but when you need to think of a few more new passwords, you start developing a pattern. If one or more of your
passwords are breached, the pattern might be used to brute-force other passwords.

If you are a developer, you know you cannot remember everything. It is humanely impossible to generate and remember
complex, random passwords every time you create a new database user for your web app, or when you need to spin-off a new
VPS, or when you need to generate a new SSH key-pair. You know you can’t remember the content of your SSH Keys, all your
API Keys, or the client secrets of the third-party services you use.

Even if you can remember a password, you cannot fill a login form as accurately and as fast as a password manager would.

### What if I am still not convinced that I need a password manager?

Password managers also let you share your vault with your family members, so you might want to keep some notes for them
in case of your untimely demise.

Told ya! Even if you aren’t convinced that you need a password manager, you should use a password manager.

### Which password manager should I use?

There are several dozens of choices when it comes to picking a password manager. *Update 2021:* Today I recommend
Bitwarden (Vaultwarden, if you self-host).