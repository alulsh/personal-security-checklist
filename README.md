# Personal Security Checklist

Take the following steps to secure your devices and accounts.

## Laptop or computer security
- [ ] Use a strong complex password to login to your computer
- [ ] Configure your computer to require a password after 5 minutes of inactivity
- [ ] Configure your computer to require a password on wake
- [ ] Learn the keyboard shortcut to lock your computer - [Windows logo + L](https://support.microsoft.com/en-us/help/12445/windows-keyboard-shortcuts) (Windows), [control + shift + power/escape](http://www.macworld.co.uk/how-to/mac/how-lock-mac-3639053/) (Mac), or [ctrl + alt + L](https://askubuntu.com/questions/126782/keyboard-shortcut-for-lockscreen-not-working) (Linux)
- [ ] Mac: [add keychain status to your menu bar](http://osxdaily.com/2011/02/10/lock-mac-desktop-via-menu/) (`open /Applications/Utilities/Keychain\ Access.app/Contents/Resources/Keychain.menu/`) for easy screen locking
- [ ] Make a habit of locking your computer when you step away from it
- [ ] Encrypt your hard drive via [FileVault](https://support.apple.com/en-us/HT204837) (Mac), [BitLocker](http://www.windowscentral.com/how-use-bitlocker-encryption-windows-10) (Windows), or [LUKS](http://www.pavelkogan.com/2014/05/23/luks-full-disk-encryption/) (Linux)
- [ ] Enable your operating system's firewall
- [ ] If you use Google's Chrome browser and sign in with your Google account, [disable saved passwords](https://support.google.com/chrome/answer/95606) and the ["Smart Lock for Passwords"](https://support.google.com/accounts/answer/6197437) feature - use your password manager instead
- [ ] Mac: Enable [stealth mode](http://osxdaily.com/2015/11/18/enable-stealth-mode-mac-os-x-firewall/)
- [ ] Enable a device tracking and recovery program like [Find My Mac](https://support.apple.com/explore/find-my-iphone-ipad-mac-watch) or [Prey](https://preyproject.com/)
- [ ] Securely store and encrypt your physical backups
- [ ] Update your operating system to the latest version
- [ ] Update your applications to the latest versions
- [ ] Mac: Don't use your Apple ID to login to your computer, [if hacked, it can be used to remotely wipe your Macbook](https://www.wired.com/2012/08/apple-amazon-mat-honan-hacking/). Instead use a regular Macbook login.
- [ ] Mac: Don't forget to frequently `brew update && brew upgrade` for Homebrew

## Smartphone security
- [ ] Use a long passcode on your phone - 12+ characters, preferably alphanumeric
- [ ] Require a passcode immediately after sleep
- [ ] Enable [Find My iPhone](https://www.apple.com/icloud/find-my-iphone.html) or [Android Device Manager](https://www.google.com/android/devicemanager) to use remote wipe if your phone is stolen or lost
- [ ] iPhone: Enable erase data after 10 bad passcode attempts (take good backups!)
- [ ] iPhone: If you're really, really paranoid don't enable Touch ID
- [ ] iPhone: Install and enable [Ka-Block!](https://itunes.apple.com/us/app/ka-block!-block-ads-tracking/id1037173557?mt=8) for mobile Safari to enable content blocking (ad blocking) on your phone. Use Safari with Ka-Block! instead of the Chrome iOS app for safer mobile web browsing.
- [ ] Android: Don't use [common and predictable lock patterns](http://www.androidauthority.com/lock-pattern-predictable-636267/)
- [ ] Android: Encrypt your hard disk
- [ ] Android: Install and enable the [uBlock Origin add-on](https://addons.mozilla.org/en-US/android/addon/ublock-origin/) for Firefox on Android for safer mobile web browsing
- [ ] Frequently update your operating system and apps, especially security patches
- [ ] Frequently backup your phone and [encrypt your backups](https://support.apple.com/en-us/HT205220)

## Network security
- [ ] Find a reputable VPN service with a laptop & mobile phone client to use for hostile networks (e.g. unencrypted wifi) or as an everyday privacy guard
- [ ] Install the [HTTPS Everywhere](https://www.eff.org/Https-everywhere) extension in your browser to prevent inadvertent HTTP connections
- [ ] Install an ad blocker like [uBlock Origin](https://github.com/gorhill/uBlock) ([Firefox](https://addons.mozilla.org/firefox/addon/ublock-origin/), [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en) or [Ka-Block!](https://github.com/dgraham/Ka-Block) ([Safari](https://safari-extensions.apple.com/details/?id=com.kablock.osx-UYW4V22L7E)) - internet ads are a common malware vector
- [ ] Enable [plugin click-to-play](http://arstechnica.com/information-technology/2016/04/edge-to-follow-chromes-lead-make-flash-ads-click-to-play/) on all your browsers, not just your default browser, to protect against Adobe Flash vulnerabilities

## Account security
A strong complex password is at least 16 characters long (the longer the better) and has several special characters (`!@#$%^&*()`). Two factor authentication (2FA) protects your account even more than a strong password.

- [ ] Use a password manager like [1Password](https://1password.com/) or [Encryptr](https://spideroak.com/solutions/encryptr)
- [ ] Use a [diceware passphrase](http://world.std.com/~reinhold/diceware.html) as the encryption passphrase for your password manager
- [ ] Add all of your account usernames and passwords to your password manager
- [ ] Rotate all of your old or insecure passwords with strong passwords generated automatically via 1Password
- [ ] Make sure every password for every account is unique
- [ ] Replace any accurate questions to security question with false answers (store false answers in 1Password)
- [ ] Download a 2FA app on your smartphone like [Google Authenticator](https://en.wikipedia.org/wiki/Google_Authenticator)
- [ ] Enable 2FA or two step verification on every account where available (see 2FA audit section) - add the software token to both your smartphone and [1Password](https://support.1password.com/one-time-passwords/)
- [ ] **Immediately store your 2FA backup and recovery codes in 1Password**

## 2FA Audit
Make sure 2FA or two step verification is enabled on all of the following accounts:

- [ ] [Google](https://myaccount.google.com/security/signinoptions/two-step-verification)
- [ ] Amazon
- [ ] Facebook - [enable Login Approval](https://www.facebook.com/settings?tab=security&section=approvals)
- [ ] [GitHub](https://github.com/settings/security)
- [ ] [Dropbox](https://www.dropbox.com/account/#security)
- [ ] Apple ID
- [ ] Slack - all of your Slack teams!
- [ ] Twitter - two step verification with SMS
- [ ] Yahoo! - two step verification with SMS
- [ ] LinkedIn - two step verification with SMS

This is an incomplete list! For more information about two factor authentication, see [twofactorauth.org](https://twofactorauth.org/), [Turn It On](https://www.turnon2fa.com/), and [#LockDownURLogin](https://www.lockdownyourlogin.com/).
