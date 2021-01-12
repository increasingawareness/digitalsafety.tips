+++
url = "index.html"
+++

 Welcome to digitalsafety.tips, a guidebook aimed at simple solutions to keep people safe, secure, and private in the digital world.
 
 You can scroll through the site or [click here for a quick summary.](/#summary)

<img src="/img/reading.jpg" alt="person reading">

<center>

# <i class="fas fa-user-shield" id="browser"></i> Browse safely 

Chrome and Safari are two of the safest browsers.

 <a href="https://chrome.com"><img src="/img/chrome.svg" alt="Chrome" height="100" align="center"></a>
 <a href="https://www.apple.com/safari/"><img src="/img/safari.svg" alt="Safari" height="100" align="center"></a>

## Chrome Desktop Add-Ons

These add-ons for Chrome can be useful for a better desktop browsing experience. Chrome can be used across all platforms, whereas Safari is only available on Apple products. 

 [Ublock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm)    
 [Cookie Autodelete](https://chrome.google.com/webstore/detail/cookie-autodelete/fhcgjolkccmbidfldomjliifgaodjagh)  


Note that using any browser on iOS/iPadOS results in using the underlying WebKit browser engine from Apple that powers Safari. The only real advantage to using Chrome on those devices would be to sync bookmarks if you use Chrome elsewhere. If you are in the Apple ecosystem, it would make more sense to just stick with Safari.

## <i class="fas fa-clipboard-check"></i> Browser setup


Switch the search engine to duckduckgo in the browser settings (both Chrome and Safari).

<a href="https://duckduckgo.com"><img src="/img/duckduckgo.svg" height="100" alt="duckduckgo"></a>

If you're not on a Chromebook, or don't want data to be synced with Google, you may want to uncheck 'allow Chrome sign-in.'


<br>
<br>

---

# <i class="fas fa-shield-alt" id="ads"></i>  Block most ads and trackers

[AdguardDNS](https://adguard.com/en/adguard-dns/overview.html) is a service that keeps you safer and reduces intrusive ads.

## Android

On Android, you'll want to go to settings and search for: Private DNS. Add `dns.adguard.com` to the "Private DNS provider hostname" field. Switch airplane mode on and then back off in order to reset the DNS. That's it! You're successfully blocking ads everywhere you go.


## iOS/iPadOS

You'll want to install the [AdguardDNS](https://adguard.com/en/adguard-dns/overview.html) app, following their instructions for setup.

## All other systems (Mac, Windows, ChromeOS, etc.)

Most other systems should be using the Ublock Origin extension in Chrome as discussed above (it can also be used in Microsoft's Edge browser). 

Another option is to use the [AdguardDNS](https://adguard.com/en/adguard-dns/overview.html) app if using a browser like Safari or other desktop browsers that don't support Ublock Origin.

<br>
<br>

---


# <i class="fas fa-comments" id="signal"></i> Keep conversations yours

## Signal Messenger for Mobile and Desktop



<a href="https://signal.org"><img src="https://upload.wikimedia.org/wikipedia/commons/8/8d/Signal-Logo.svg" height="200" alt="Signal"></a>




</center>

Signal is a fun and peer-reviewed messaging app that allows you to connect in a way that respects you. Signal is non-profit, supports video/audio calls, messaging, Giphy, and group chats (and group video). It's available on iOS, Android, MacOS desktop, Windows desktop, and Linux desktop. Make your conversations with people just between you and them, not between you and a company that sees you as a product.

<center>

<br>
<br>

---


# <i class="fas fa-key" id="passwords"></i> Use passwords wisely

</center>

Every account should have its own unique password because it is dangerous to reuse the same password or a variant of the same password across sites. It's unlikely that most people will remember a unique string of characters for every login, so it's recommended to use a password manager to store passwords securely. 

A password manager generates new passwords for you, and stores them until you need them. All you need to remember is one passphrase that protects all the other ones. As long as the password manager has a strong passphrase and a second-factor code to unlock it, the passwords will stay safe.

<br>
<center>

## Create passphrases

<a href="https://en.wikipedia.org/wiki/Diceware"><img src="/img/dice.jpg" height="200" alt="dice"></a>

</center>

A passphrase is usually longer and more memorable than the shorter but harder to remember password. You'll need a master passphrase for your password manager which is best accomplished with the [Diceware method](https://en.wikipedia.org/wiki/Diceware). This method involves rolling physical die to randomly select 6 to 7 words from a word list. One simply strings these words together, all as one word and creates a mnemonic to remember it. 

Despite what you may have heard from other sources, the math behind this method is sound since "a six-word passphrase would take 3,505 years, on average, at a trillion guesses a second."[^1] 

For now, we'll create two passphrases this way: one for your password manager and one for your home computer. Passphrases are mainly good at securing top level information like your computer login, password managers, or keys. For all your accounts (email, bank, social media, etc.), you'll want to use passwords generated with a password manager.

1. Go to [EFF's diceware list](https://www.eff.org/files/2016/07/18/eff_large_wordlist.txt)
2. Roll a die 5 times (or you can roll 5 dice once) and write down the numbers in groups of five on a piece of paper.
3. Do this 6 times. Believe it or not, this is the basis for your first passphrase which will protect your password manager.
4. Once you have done this, find the corresponding words in the word list and write them next to the numbers
5. Create a mnemonic story with the words
6. Write down the 6 generated words on a piece of paper that will fit in your wallet. 
7. This is your master password for your password generator
8. Do not use it anywhere else.
9. Repeat this process to create the second passphrase for your computer login (or if using a passcode on an iPad or phone, use a ten sided die for a ten character passcode).
10. Shred the paper that you've carried with you after you've sufficiently memorized both passphrases. With a good mnemonic story, it shouldn't take longer than a week.



<center>

## Bitwarden password manager

<a href="https://bitwarden.com"><img src="/img/bitwarden1.png" height="200" alt="bitwarden"></a>

</center>

Bitwarden is a password manager that has undergone security audits, encrypts your passwords without being able to access them, is open source, free, and multi-platform. You can even securely share passwords with others. If you're technically apt, you can even host your own server. I recommend using the app on mobile and the browser plugin on desktop.

<center>

<br>
<br>

---
# <i class="fas fa-mobile-alt" id="2fa"></i> Passwords aren't enough. Use 2FA.

</center>

Security is strongest in layers, with passwords being only the first layer in the system. Most people carry a phone which can easily be used as a second layer of security. 2FA (2 factor authentication) usually works by entering a code from your phone after using your password to login, ensuring you are the only person who can access the account. 



<br>

There are three main types of authentication:

<center>

| Type of authentication                                | How it works                                                                                       |
|-------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| Text message or phone call                            | Get an automated text or phone call and enter the code you read or hear.                           |
| App on your phone                                                  | Copy the time based code from an app on your phone or get a push notification.                                                |
| A security key such as a Yubikey | Press a button on the device or tap the device to your phone. |

<br>

</center>




Prefer security keys over apps, prefer apps over text message authentication. Text message based 2FA is better than not having any at all.




<p class="message"><i class="fas fa-exclamation-triangle"></i> Note that security questions don't count as a second-factor. Security questions are very easy to guess or find out about a person, and are extremely risky to use in place of the above  methods. If you must use a security question, I recommend using a random string of characters as the answer to the question. Then save it in your password manager.</p> 

<center>

## Security Keys

</center>

> “Even highly-targeted users like politicians and activists don’t fully appreciate the scourge of phishing, and many aren’t familiar with an emerging form of two-factor authentication known as “Security Keys” that we hope can stop it in its tracks … phishing is the silent killer, and relying on a password alone is a recipe for disaster. 🔐” -Mark Risher’s Phishing and Security Keys

Security keys are the future of authentication. App based or text-message based codes are now considered to be legacy authentication. We are moving to an era when security keys are the main path to both authentication and passwordless systems. A few larger services such as Google, Microsoft, Dropbox, Github, Facebook, and Twitter currently support security keys.  [Dongleauth](https://www.dongleauth.info/) is a site that shows what current services work with security keys. 


<center>

<a href="https://www.yubico.com/product/yubikey-5-nfc/#yubikey-5-nfc"><img src="/img/yubikey.jpg" height="200" alt="yubikey"></a>

</center>

The security key I currently recommend is the [Yubikey 5 NFC](https://www.yubico.com/product/yubikey-5-nfc/#yubikey-5-nfc).


There are a variety of types to fit your needs. Most likely you'll want the Yubikey 5 series which supports the newest standards. If you have a newer Macbook, Chromebook, or 2020 iPad Pro, you'll want to make sure to get a USB-C compatible Yubikey.

You'll want two of them (one is a backup).

<center>

## 2FA Apps


### Aegis for Android

<a href="https://play.google.com/store/apps/details?id=com.beemdevelopment.aegis"><img src="/img/aegis.png" height="100" alt="aegis"></a>
<br>
</center>

<p class="message"><i class="fas fa-exclamation-triangle"></i> Important—Aegis has the ability to backup security keys to wherever you would like. It is highly recommended to keep consistent and encrypted backups of your 2FA keys.</p>

<br>
<center>

### Tofu for iOS

<a href="https://itunes.apple.com/app/tofu-authenticator/id1082229305"><img src="/img/tofu.svg" height="100" alt="Tofu"></a>
<br>
</center>

<p class="message"><i class="fas fa-exclamation-triangle"></i> Important—2FA keys are stored on your iPhone's secure keychain, so only iTunes/iCloud encrypted backups will include a backup to these keys. If you're restoring your device from an iTunes/iCloud backup, the app and all keys will be restored as well.</p>

<center>

Go to https://twofactorauth.org/ to see some sites that support app based 2FA. Most banks, social media networks, and email providers have 2FA.




<br>


<br>
<br>

---

# <i class="fas fa-envelope-open-text" id="haveibeenpwned"></i> Sign up for haveibeenpwned

<a href="https://haveibeenpwned.com"><img src="/img/hibp2.png" alt="haveibeenpwned"></a>

</center>

Created by security expert Troy Hunt, "Have I been Pwned?" is a service that keeps track of data breaches. Pronounced "pone," pwn is internet slang for "to own" or to conquer to gain ownership. Enter your email at the site to see if any of your accounts have been breached. If anything has been breached in the past, don't panic. Go to the website that was breached and change your password there. Be sure [to subscribe](https://haveibeenpwned.com/NotifyMe) to get notified of further breaches right away. Do this for each email you use.

<center>


<br>
<br>

---


# <i class="far fa-envelope" id="email"></i> A Note on Email.

</center>

Email is fundamentally a non-private protocol, you should use Signal Messenger to keep your conversations private.

> Encrypting email is asking for a calamity. Recommending email encryption to at-risk users is malpractice. Anyone who tells you it’s secure to communicate over PGP-encrypted email is putting their weird preferences ahead of your safety.

> -[Latacora](https://latacora.micro.blog/2019/07/16/the-pgp-problem.html#)

This is not to say that email is insecure. Security and privacy are facets of digital safety rather than a simple binary decision. This is why I advocate that **most people should use Gmail and activate Google's [Advanced Protection Program](https://landing.google.com/advancedprotection/).** Email security is important. We sign up for most accounts with an email address which means that all reset-password-links are sent to that email address. If someone has access to your email or successfully phishes your email, it could be game over for the rest of your accounts. As far as mainstream email providers go, Google has by far the best security with its Advanced Protection Program. 

If you object to using Google's services, [Tutanota](https://tutanota.com) supports using security keys and may be a reasonable alternative.

## And what about phishing?
 
 > "Phishing is when a scammer uses fraudulent emails or texts, or copycat websites to get you to share valuable personal information – such as account numbers, Social Security numbers, or your login IDs and passwords. Scammers use your information to steal your money or your identity or both. Scammers also use phishing emails to get access to your computer or network then they install programs like ransomware that can lock you out of important files on your computer. Phishing scammers lure their targets into a false sense of security by spoofing the familiar, trusted logos of established, legitimate companies. Or they pretend to be a friend or family member." -[Federal Trade Commission](https://www.consumer.ftc.gov/articles/0003-phishing)
 
 For more on phishing, check out [this comic](https://theintercept.com/2017/11/19/how-to-protect-yourself-against-spearphishing-a-comic-explanation/) from *The Intercept*.

<br>
<br>


---
<center>

#  <i class="fas fa-chess" id="mindset"></i> Security Mindset



</center>

In general:

- If it sounds too good to be true, it usually is.
- Don't open or download files or click on links in emails from a source you don't know.
- [If it's a supposed government agency, they will get a hold of you by official means (the IRS will never call you, they will send you postal mail)](https://www.irs.gov/newsroom/how-to-know-its-really-the-irs-calling-or-knocking-on-your-door).
- [It's easy to be fooled by visual similarities](https://twitter.com/glenmaddern/status/1278252319646367744?s=20), always verify who is contacting you. Using a password manager and a security key can help with this.
- [Pay attention to browser alerts and security exceptions](https://support.mozilla.org/en-US/kb/what-does-your-connection-is-not-secure-mean).
- ["loose-lips sink ships"](https://en.wikipedia.org/wiki/Operations_security)
- ["The Internet is forever"](https://www.inc.com/meredith-fineman/what-we-post-online-is-forever-and-we-need-a-reminder.html)
- Only hand out information ["on a need-to-know basis"](https://www.youtube.com/watch?v=YEiu7uYCfPE)
- Avoid using [novelty apps](https://business.financialpost.com/technology/tim-hortons-app-tracking-customers-intimate-data) or even [some social media apps](https://www.theverge.com/2020/6/26/21304228/tiktok-security-ios-clipboard-access-ios14-beta-feature).
- Only install apps you need or have reason to trust.


Verifying who people are and what they are doing is essential when dealing with tech support, financial institutions, or businesses. This process helps you avoid [social engineering](https://www.us-cert.gov/ncas/tips/ST04-014). In general, don't allow people to remote access your computer unless your business-place has this setup to begin with. 




<p class="message"><i class="fas fa-exclamation-triangle"></i> Additionally, avoid using "smart" appliances or home assistants (Amazon's Alexa, Google Home, etc.). These are set up to listen in constantly, using the information from your everyday life as a means for profit.</p>




<center>
<br>
<br>

---

# <i class="fas fa-cloud-upload-alt" id="backup"></i>  "Consider each piece of data you create and what would happen if you lost it, or if it leaked to the public at large. Make backups accordingly." -Security Researcher [Alec Muffett](https://medium.com/@alecmuffett/your-cyber-5-a-day-1f9fa1cb3067)
</center>

The cloud is not a bad place to store some types of data. It depends on what you want to do and who you trust. Apple seems fairly reasonable and iCloud may be a good resource for storing family photos or other files. If you have the advanced protection program with Gmail, you also have the same protection if you decide to upload photos (this pertains to security only, not privacy). However, this is all about who you trust to keep your data private. New solutions [are in development](https://github.com/cloudflare/utahfs) to keep data secure in a zero-knowledge way (where the cloud provider can't see your data even if they wanted to). If you want to use tools like Google Drive or Dropbox: that's fine, just remember that someone else may have access to that information.

Keep backups. If you've decided to keep everything in the cloud for backups, it's still recommended to have an offline backup on an external drive to increase redundancy (in information integrity, redundancy is a good thing). Store this someplace safe, and make sure the backup is encrypted. 

Safe ways to backup your data to external media:

- For [iOS/iPadOS](https://support.apple.com/en-us/HT205220)
- For Windows, you'll want to [create a system image](https://support.microsoft.com/en-us/help/17127/windows-back-up-restore) and save it to an external drive [using Veracrypt](https://www.veracrypt.fr/en/Home.html).
- For MacOS, you'll most likely want to use the [integrated Time Machine backup app](https://support.apple.com/en-us/HT201250) (don't forget to check the encrypt backup checkbox). 


Mainstream cloud storage providers:

- https://drive.google.com
- https://icloud.com
- https://dropbox.com

Cloud backup providers that support zero-knowledge backups (where the provider can't see your data) by default:

- https://sync.com (Most platforms)
- https://Borgbase.com (MacOS, only for technical users)
- https://tarsnap.com (MacOS, only for technical users)


<br>
<br>

---


# <i class="fas fa-arrow-alt-circle-up" id="update"></i> Update. Update now! Turn on auto-updates.

</center>
Updating is the digital hygiene equivalent to flossing your teeth. It can be annoying to take a few seconds or minutes to update and restart your devices, but just do it. Vulnerabilities in the code need to be flossed out. There are people actively looking for non-updated software in order to hack it.
<center>

<a href="https://xkcd.com/1328/"><img src="/img/update.png" height="200" alt="XKCD update"></a>

</center>

<details>
<summary>Google Play and Android</summary>

To automatically [update apps](https://support.google.com/googleplay/answer/113412?hl=en) on your Android device:

> Open the Google Play Store app Google Play.
> Tap Menu Menu and then Settings.
> Tap Auto-update apps.
> Select an option:  
> - Auto update apps at any time to update apps using either Wi-Fi or mobile data.  
> - Auto-update apps over Wi-Fi only to update apps only when connected to Wi-Fi.

For the [Android System](https://support.google.com/android/answer/7680439)

> You'll get notifications when updates are available for you. 

</details>

<details>
<summary>Apple iOS</summary>

[For the iOS system:](https://support.apple.com/en-us/HT204204)

> With iOS 12, you can have your iOS device update automatically. To turn on automatic updates, go to Settings > General > Software Update > Automatic Updates. Your iOS device will automatically update to the latest version of iOS. Some updates might need to be installed manually.

[For apps on your iPhone:](https://support.apple.com/en-us/HT202180)

> Tap Settings > [your name] > iTunes & App Store. Turn on the content that you want to automatically download.

</details>


<details>
<summary>Apple MacOS</summary>

> To automatically download updates in the future, choose Apple menu > System Preferences, click App Store, then select ”Download newly available updates in the background.” Your Mac will notify you when updates are ready to install. 

-[Apple Support](https://support.apple.com/en-us/HT201541)

</details>

<details>
<summary>Microsoft Windows</summary>

For Windows 10 app store

> 1. Select the Start  screen, then select Microsoft Store.
> 2. In Microsoft Store at the upper right, select the account menu (the three dots) and then select Settings.
> 3. Under App updates, set Update apps automatically to On.

 
For Windows 8.1 and Windows RT 8.1 app store

> 1. On the Start screen, select Store to open the Store.
> 2. Swipe in from the right edge of the screen, and then tap Settings. (If you're using a mouse, point to the lower-right corner of the screen, move the mouse pointer up, and then click Settings.)
> 3. Tap or click App updates.
> 4. Make sure Automatically update my apps is set to Yes.

-[Windows Support](https://support.microsoft.com/en-us/help/15081/windows-turn-on-automatic-app-updates)

For the [Windows operating system](https://support.microsoft.com/en-us/help/12373/windows-update-faq)

> Windows Update automatically offers updates to eligible devices. To double check that your device is up to date, open Settings  > Update & Security  > Windows Update to see your update status.

</details>



<center>

<br>
<br>

---

#  <i class="fas fa-skull-crossbones" id="eol"></i> "Stop using, even erase, delete or destroy, any software or devices which are past their end-of-life, end-of-support, or for which you can no longer obtain software updates. Make sure to save any data that you want or need." -Security Researcher [Alec Muffett](https://medium.com/@alecmuffett/your-cyber-5-a-day-1f9fa1cb3067)

Every week there are dozens of [new security vulnerabilities reported](https://us-cert.cisa.gov/ncas/bulletins) that need to be patched. Most devices are patched monthly. Devices are complicated and require constant adjustments to code for each specific device that is made. Sometimes there are even issues with the way the hardware is structured on the device. Eventually, devices aren't supported anymore and need to be replaced. Devices without security updates are dangerous and should not be used. 

<br>
<br>

---

# <i class="fas fa-user-lock" id="lockitdown"></i> Keep your devices on lock

</center>

Please keep a passcode on your phone! Today, most modern phones (both Android and iOS) automatically encrypt your data so you can be sure that if you lose your device or if someone steals it, no one else can have access to it. 

You'll want to keep your phone locked with a numbered passcode that is 10 digits or longer:

<center>

<img src="img/passcode.png" alt="passcode tweet">

</center>

On Windows, Bitlocker [can be activated to encrypt your hard drive](https://support.microsoft.com/en-us/help/4502379/windows-10-device-encryption).

Apple computers also have [FileVault](https://support.apple.com/en-us/HT204837), which protects the data on your Mac. Go into the settings and activate it.

ChromeOS is [encrypted by default](https://www.chromium.org/chromium-os/chromiumos-design-docs/protecting-cached-user-data). 

Android devices that were released with Android 10 and later [require encryption](https://source.android.com/security/encryption/file-based) by default. You can also verify this by searching for "encryption" in the settings.

iOS and iPadOS devices [are encrypted](https://support.apple.com/guide/security/encryption-and-data-protection-overview-sece3bee0835/web) as long as there is a passcode in place.

<center>

<br>
<br>

---



<center>

# <i class="fas fa-bullhorn" id="informed"></i> Stay informed

## This Week in Security Newsletter

</center>

From the Security Editor at Tech Crunch Zack Whittaker, the *This Week in Security Newsletter* gives you a weekly overview of security stories from the week.

<center>

<a href="https://tinyletter.com/zackwhittaker"><img src="/img/securitythisweek.png"  alt="This week in security"></a>

## EFF

</center>

> "The Electronic Frontier Foundation is the leading nonprofit organization defending civil liberties in the digital world. Founded in 1990, EFF champions user privacy, free expression, and innovation through impact litigation, policy analysis, grassroots activism, and technology development. We work to ensure that rights and freedoms are enhanced and protected as our use of technology grows."

The EFF has stories out almost everyday about your rights online. Follow them and consider joining to support online freedom.

<center>

<a href="https://eff.org"><img src="/img/eff.svg" height="100" alt="eff"></a>

<br>

## Motherboard

</center>

Motherboard reports on all sorts of tech issues. They have robust security coverage. 

<center>

<a href="https://motherboard.vice.com/en_us"><img src="/img/motherboard.png" height="200" alt="motherboard"></a>

<br>
<br>

---



#  <i class="far fa-handshake" id="teamsport"></i> "The real protection comes when we recognize that privacy is a team sport" -[EFF](https://www.eff.org/deeplinks/2017/01/data-privacy-day-play-privacy-team-sport)

</center>

Get close friends and family on Signal, tell them about being able to block ads, and show them how to make secure passphrases. This way we can help everyone be safe, secure, and private.

<center>



<br>
<br>

---



</center>




<center>

# <i class="far fa-question-circle" id="faq"></i> FAQ

</center>


##  <i id="phone"></i> What kind of phone should I get?

</center>
 
The best option you can have in your hand right now is an Apple iPhone or a current generation Google Pixel with the security features intact according to most security researchers, [including security researcher Daniel Micay](https://www.reddit.com/r/GrapheneOS/comments/bddq5u/os_security_ios_vs_grapheneos_vs_stock_android/ekxifpa?utm_source=share&utm_medium=web2x).

<center>

## <i id="computer"></i> What kind of computer should I get?

</center>

Choices: iPad Pro, Pixelbook Go Chromebook, Macbook air, or a PC that can run Windows 10 S.


### iPad Pro

Apple has gone great lengths to protect their users privacy and security. An iPad Pro paired with the Magic Keyboard is a great choice for the user who wants a solid, long-lasting, all around well-performing device. Additionally, Apple is currently in the process of switching all of their Mac lineup to the same or similar chips that are in the iPad pros. This means native app support for Microsoft Word and other mainstream desktop apps on iPad. The current generation iPad Pros are ahead of Macbooks in terms of security. The iPad Pro (2020) paired with the Magic Keyboard is the current front-runner for digital safety.

### Pixel Book Go Chromebook

ChromeOS is developed first by the open-source team behind Chromium. Google then adds in their stuff to make ChromeOS. Modern Chromebooks like the Pixel Book Go are also able to run Android Apps natively. If you're a developer, you can also run a linux shell and have access to SSH. For an in-depth view at how the Chromium team is approaching security, [read this page.](https://www.chromium.org/chromium-os/chromiumos-design-docs/security-overview)

### Macbook Air

The Macbook Air is the jack-of-all-trades machine in this set of choices. It has a good balance of computing power, traditional desktop computing, and Apple's signature dedication to privacy. It's not as advanced on the security front as the 2020 iPad Pro, but the M1 Mac lineup (the newer ones with the M1 chipset) is the runner up. Additionally, if you think you want to get into programming or like to run shell commands this is most likely the right choice for you.


### PC that runs Windows 10 S


> Windows 10 in S mode is a version of Windows 10 that's streamlined for security and performance, while providing a familiar Windows experience. To increase security, it allows only apps from the Microsoft Store, and requires Microsoft Edge for safe browsing. -[Windows 10 S FAQ](https://support.microsoft.com/en-us/help/4020089/windows-10-in-s-mode-faq)

For more, [visit the Windows 10 S page](https://www.microsoft.com/en-us/windows/s-mode).



<p class="message">If you are a non-techie, feel free to ignore this blurb. Before fellow privacy nerds freak out, I will just say: I agree with you on principle, it would be better for all things to have source code published and code developed in an open democratic way (and copyleft or creative commons). I get it. But, the Linux kernel and distro security management (I'm looking at you Debian), are light-years behind MacOS, AOSP, or Windows. I used to believe that Linux was more secure. That was what the community told me at least. It wasn't until I started digging that I found problems. <a href="https://www.washingtonpost.com/sf/business/2015/11/05/net-of-insecurity-the-kernel-of-the-argument/?noredirect=on">This piece in the Washington Post details the issue pretty well.</a> I don't believe you can have privacy (one of the three aspects of digital safety) without security. Voyeurs would have there way without locks on doors. Privacy can't be had without security. Secrets leak without proper security management.
</p>

> In general, the assumption that open source software is any more secure or even private in practice is totally wrong and not based on reality.

> -Daniel Micay


<center>


## <i id="privacy"></i> Why should I care about privacy? I don't have anything to hide.

</center>

I found that these two quotes best sum up the issue:

>  Over the last 16 months, as I've debated this issue around the world, every single time somebody has said to me, "I don't really worry about invasions of privacy because I don't have anything to hide." I always say the same thing to them. I get out a pen, I write down my email address. I say, "Here's my email address. What I want you to do when you get home is email me the passwords to all of your email accounts, not just the nice, respectable work one in your name, but all of them, because I want to be able to just troll through what it is you're doing online, read what I want to read and publish whatever I find interesting. After all, if you're not a bad person, if you're doing nothing wrong, you should have nothing to hide." Not a single person has taken me up on that offer.  
> - Glenn Greenwald [Why privacy matters - TED Talk](https://www.ted.com/talks/glenn_greenwald_why_privacy_matters)

and

> Arguing that you don't care about the right to privacy because you have nothing to hide is no different than saying you don't care about free speech because you have nothing to say.  
> - Edward Snowden on [Reddit](https://www.reddit.com/r/IAmA/comments/36ru89/just_days_left_to_kill_mass_surveillance_under/crglgh2/)

For more:

- Watch [Greenwald's TED Talk](https://www.ted.com/talks/glenn_greenwald_why_privacy_matters)
- Read Professor [Daniel Solove's paper](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=998565)
- Browse the [Wikipedia article](https://en.wikipedia.org/wiki/Nothing_to_hide_argument) about this issue.

<center>

## <i id="vpn"></i> Should I use a VPN?

</center>

You can use a commercial VPN if you want, but remember: "A VPN is an ISP"

Privacy and anonymity researcher Sarah Jamie Lewis points out that using a virtual private network (VPN) doesn't keep you anonymous. Rather, you're taking the burden of potential surveillance and moving it from your current Internet service provider (ISP) and moving it to another by using a VPN. This doesn't mean "don't use a VPN". It means treat your VPN just like an ISP. If you need anonymity, use the tor browser. VPNs are most useful when you need to securely connect to a network, not if you want privacy.

<center>
<a href="https://mobile.twitter.com/SarahJamieLewis/status/871713517317042176"><img src="img/srah.png" alt="sarahjamielewis"></a>




## <i id="router"></i> More technical step: What kind of router should I get?

</center>

Some consumer routers are outdated and insecure. In 2018, the U.S. government [advised that U.S. citizens reset their routers](https://www.nytimes.com/2018/05/27/technology/router-fbi-reboot-malware.html) since the Russian government attacked and successfully subverted hundreds-of-thousands of routers throughout the world. Most consumer routers never get updated. These are actually small computers that need regular updates to patch for security issues or bugs. Additionally, the power that the ISP retains over the device is significant. Obtaining your own network equipment means that you are in control of your network and increase your digital safety.


### PFsense router and firewall with a wireless access point

[PFsense is an open source operating system](https://www.pfsense.org/) that specializes as a firewall, router, gateway, and more. Netgate [makes PFsense appliances that I recommend](https://www.pfsense.org/products/).

<center>
<a href="https://www.netgate.com/solutions/pfsense/sg-3100.html"><img src="/img/netgate.png" alt="netgate"></a>
</center>

In addition to the router, you'll need a wireless access point for WiFi. Pick up [a wireless access point, like one made by Ubiquiti](https://www.ui.com/unifi/unifi-ap-ac-lite/) and you should be set.

These two pieces of equipment ensure that your network is on the way to being more secure (look into making sure the firewall is turned on for your particular router). Securing a home network is out of the scope of this guide, but you may want to visit https://www.reddit.com/r/HomeNetworking/ and the r/pfsense subreddit to ask questions or get ideas for setups.


<center>

## <i id="protest"></i> How do I securely attend a peaceful protest? 

</center>

<img src="img/clay-banks-TTVRcqoyixs-unsplash.jpg">

</center>

### Disable biometrics temporarily

You'll want to temporarily disable unlocking your mobile device with a fingerprint or face. This will instead require you to enter password the next time you need to unlock your device. Remember that you don't need to unlock your device to use the camera. To do this:


#### On iOS


> [Press and hold the side button and either volume button for 2 seconds.](https://support.apple.com/guide/iphone/set-up-face-id-iph6d162927a/ios)

> After the sliders appear, press the side button to immediately lock iPhone.

> iPhone locks automatically if you don’t touch the screen for a minute or so.

> The next time you unlock iPhone with your passcode, Face ID is enabled again.


#### On Android devices

Open the settings and search for "lockdown" and enable the toggle. The option for lockdown mode will then show up when you hold down the power button from the main menu of your phone or the lock screen.


### Always film encounters with law enforcement

Smartphones [have been instrumental](https://www.youtube.com/watch?v=-FEGcJeGeBg) in exposing police brutality and corruption. [You have the right to film police in the United States](https://www.eff.org/deeplinks/2020/06/you-have-first-amendment-right-record-police). 

### 10 Rules for Dealing with Police

[Useful video presenting possibly life-saving and rights-preserving rules for peacefully interacting with law enforcement.](https://www.youtube.com/watch?v=s4nQ_mFJV4I) 


### Black Lives Matter

Resources I've found helpful:

</center>

- 13th on Netflix ([free on YouTube](https://www.youtube.com/watch?v=krfcq5pF8u8))
- [John Oliver's Segment](https://www.youtube.com/watch?v=Wf4cea5oObY)
- [Washington Post Article](https://www.washingtonpost.com/graphics/2020/opinions/systemic-racism-police-evidence-criminal-justice-system/) on the evidence for systemic racism
- ["How to be an Anti-Racist"](https://www.amazon.com/How-Be-Antiracist-Ibram-Kendi-ebook/dp/B07D2364N5/ref=tmm_kin_swatch_0?_encoding=UTF8&qid=1594270592&sr=8-1)
- ["When They See Us"](https://www.netflix.com/title/80200549) on Netflix

<br>
<br>

---


# <i class="fas fa-list-ol" id="summary"></i> Summary

[ ↑ Back to the top](/)

Steps:

1. [Use Chrome or Safari for your browser](/#browser)
2. [Block most ads and trackers with nextdns or adguardDNS](/#ads)
3. [Communicate securely with Signal Messenger](/#signal)
4. [Use password manager like Bitwarden with a strong passphrase](/#passwords)
5. [Get a Yubikey security key and turn on 2-factor-authentication for your accounts](/#2fa)
6. [Get alerted to accounts that are compromised in a data breach by signing up for haveibeenpwned](/#haveibeenpwned)
7. [Email isn't private, but it can be secure if you use gmail with the advanced protection program](/#email)
8. [Maintain a security mindset and avoid common scams and phishing](/#mindset)
9. [“Consider each piece of data you create and what would happen if you lost it, or if it leaked to the public at large. Make backups accordingly.” -Security Researcher Alec Muffett](/#backup)
10. [Turn on auto updates for your systems and apps](/#update)
11. [“Stop using, even erase, delete or destroy, any software or devices which are past their end-of-life, end-of-support, or for which you can no longer obtain software updates. Make sure to save any data that you want or need.” -Security Researcher Alec Muffett](/#eol)
12. [Passcode lock your devices; turn on encryption](/#lockitdown)
13. [Keep yourself informed](/#informed)
14. [There may be other tools that can keep yourself: here are a few](/#othertools)


FAQ

1. [What kind of phone should I get?](/#phone)
2. [What kind of computer should I get?](/#computer)
3. [Why should I care about privacy? I don’t have anything to hide.](/#privacy)
4. [Should I use a VPN?](/#vpn)
5. [What kind of router should I get?](/#router)
6. [How do I securely attend a peaceful protests?](/#protest)

---

## <i class="fas fa-user" id="about"></i> About

This site was aimed at the layperson and was intended to get privacy-security preserving tech into the hands of as many people as possible. Therefore, it may not meet your needs if you require a higher level of anonymity or have a complex threat model or just are curious about nerdy security things. If your needs are greater than this project, please check out the following:

- [QubesOS](https://www.qubes-os.org/)
- [Tails](https://tails.boum.org/)
- [One-time Pad Encryption](https://en.wikipedia.org/wiki/One-time_pad)
- [GrapheneOS](https://grapheneos.org/)




### Contact

I'm Grant. For the past many years I've spent a large amount of hours learning more about technology, security, Linux, and network infrastructure. 


<a href="https://github.com/increasingawareness">@increasingawareness</a> on Github.  
Wire messenger - @increasingawareness  


## <i class="fab fa-github" id="contribute"></i> Contribute

If you feel that anything on this site needs to be changed, redacted, or added, please feel free to [open an issue](https://github.com/increasingawareness/digitalsafety.tips/issues) or submit a pull request on Github.

## <i class="fas fa-list" id="credits"></i> Credits


- To  Tom Preston-Werner and Jekyll contributors for Lanyon-theme and associated CSS under the [MIT license](https://github.com/jekyll/jekyll/blob/master/LICENSE).
- Font-Awesome used under the [Font Awesome Free License](https://github.com/FortAwesome/Font-Awesome/blob/master/LICENSE.txt).
- To Bjørn Erik Pedersen for the [wonderful static site generator Hugo](https://gohugo.io/) under the Apache 2.0.
- To my family and friends for their patience and support. =)


[^1]: https://theintercept.com/2015/03/26/passphrases-can-memorize-attackers-cant-guess/

<br>


<center>

## Legal

 <p><svg version="1.1" id="Layer_1" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px"
	 width="88px" height="31px" viewBox="0.995 1.495 88 31" enable-background="new 0.995 1.495 88 31" xml:space="preserve">
<g>
	<path fill="#FFFFFF" d="M2.803,1.481L85.928,1.63c1.162,0,2.199-0.173,2.199,2.333l-0.103,27.554H0.705V3.861
		C0.705,2.626,0.823,1.481,2.803,1.481z"/>
	<g>
		<ellipse fill="#FFFFFF" cx="14.887" cy="16.501" rx="11.101" ry="11.172"/>
	</g>
	<path d="M24.271,5.06c3.484,2.592,5.754,6.744,5.755,11.44c-0.001,4.272-1.88,8.095-4.842,10.703h62.853V5.06H24.271z"/>
	<path d="M15.242,4.702C8.769,4.702,3.521,9.984,3.521,16.5c0,6.515,5.248,11.798,11.722,11.798c6.473,0,11.721-5.283,11.721-11.798
		C26.963,9.984,21.715,4.702,15.242,4.702z M15.242,26.086c-5.252,0-9.524-4.302-9.524-9.586c0-1.106,0.189-2.169,0.534-3.158
		l3.725,1.669c-0.1,0.503-0.154,1.026-0.154,1.567c0,4.709,3.492,6.036,5.689,6.036c1.297,0,2.418-0.422,3.296-1.039
		c0.092-0.066,0.179-0.133,0.262-0.199l-1.758-1.848c-0.64,0.556-1.313,0.39-1.47,0.39c-1.788,0-2.537-1.899-2.547-3.421
		l10.266,4.602c0.012,0.002,0.022,0.002,0.032,0.004C21.973,24.069,18.837,26.086,15.242,26.086z M24.419,18.948l-10.587-4.755
		c0.382-0.698,0.989-1.221,1.898-1.221c0.528,0,0.946,0.177,1.276,0.397c0.137,0.1,0.255,0.2,0.355,0.3l1.908-1.978
		c-1.281-1.108-2.739-1.308-3.692-1.308c-2.239,0-3.824,0.976-4.759,2.455l-3.54-1.59c1.704-2.608,4.636-4.337,7.963-4.337
		c5.251,0,9.523,4.3,9.523,9.587c0,0.854-0.113,1.685-0.323,2.474C24.434,18.965,24.428,18.957,24.419,18.948z"/>
	<g>
		<path fill="#FFFFFF" d="M36.739,8.557c0.392,0,0.728,0.059,1.002,0.173c0.276,0.116,0.5,0.268,0.674,0.456
			c0.173,0.189,0.299,0.405,0.379,0.647c0.079,0.241,0.118,0.493,0.118,0.753c0,0.253-0.039,0.503-0.118,0.749
			c-0.08,0.244-0.206,0.462-0.379,0.65c-0.174,0.188-0.397,0.341-0.674,0.456c-0.274,0.115-0.61,0.173-1.002,0.173h-1.452v2.267
			h-1.382V8.557H36.739z M36.36,11.533c0.158,0,0.312-0.012,0.457-0.035c0.147-0.023,0.276-0.069,0.388-0.137
			c0.111-0.068,0.201-0.164,0.269-0.288c0.068-0.124,0.101-0.287,0.101-0.487c0-0.201-0.033-0.363-0.101-0.488
			c-0.067-0.123-0.157-0.22-0.269-0.286c-0.111-0.069-0.24-0.114-0.388-0.138c-0.146-0.024-0.299-0.036-0.457-0.036h-1.073v1.896
			L36.36,11.533L36.36,11.533z"/>
		<path fill="#FFFFFF" d="M44.751,14.398c-0.476,0.417-1.133,0.625-1.972,0.625c-0.851,0-1.509-0.207-1.976-0.62
			c-0.466-0.413-0.699-1.052-0.699-1.913V8.557h1.381v3.934c0,0.171,0.016,0.339,0.045,0.506c0.029,0.165,0.091,0.311,0.185,0.438
			c0.094,0.125,0.225,0.229,0.392,0.309c0.167,0.08,0.392,0.119,0.673,0.119c0.493,0,0.833-0.109,1.021-0.332
			c0.188-0.221,0.282-0.568,0.282-1.04V8.557h1.382v3.934C45.464,13.346,45.226,13.982,44.751,14.398z"/>
		<path fill="#FFFFFF" d="M50.069,8.557c0.301,0,0.572,0.027,0.817,0.081c0.246,0.053,0.459,0.14,0.636,0.26
			c0.176,0.121,0.312,0.282,0.407,0.483c0.099,0.201,0.146,0.45,0.146,0.745c0,0.318-0.071,0.584-0.217,0.796
			c-0.144,0.212-0.355,0.388-0.637,0.522c0.387,0.112,0.676,0.309,0.865,0.589c0.191,0.281,0.286,0.619,0.286,1.015
			c0,0.319-0.062,0.595-0.185,0.829c-0.123,0.232-0.289,0.422-0.498,0.57c-0.207,0.148-0.445,0.257-0.713,0.328
			c-0.269,0.07-0.541,0.105-0.822,0.105H47.11V8.557H50.069z M49.896,11.117c0.246,0,0.447-0.059,0.606-0.178
			c0.157-0.118,0.237-0.309,0.237-0.576c0-0.147-0.026-0.269-0.08-0.362c-0.053-0.095-0.122-0.168-0.211-0.222
			c-0.088-0.053-0.188-0.09-0.303-0.109c-0.115-0.022-0.233-0.032-0.356-0.032h-1.294v1.479H49.896z M49.974,13.802
			c0.135,0,0.264-0.014,0.387-0.04c0.125-0.026,0.231-0.072,0.326-0.133c0.094-0.062,0.168-0.147,0.227-0.254
			c0.056-0.104,0.083-0.241,0.083-0.406c0-0.325-0.093-0.557-0.271-0.696c-0.184-0.138-0.425-0.208-0.724-0.208h-1.505v1.737H49.974
			z"/>
		<path fill="#FFFFFF" d="M55.142,8.557v5.155h3.062v1.169H53.76V8.557H55.142z"/>
		<path fill="#FFFFFF" d="M60.748,8.557v6.324h-1.382V8.557H60.748z"/>
		<path fill="#FFFFFF" d="M66.45,10.244c-0.082-0.132-0.184-0.248-0.307-0.349c-0.125-0.101-0.265-0.179-0.421-0.235
			c-0.153-0.057-0.315-0.085-0.487-0.085c-0.312,0-0.574,0.062-0.791,0.183c-0.217,0.12-0.396,0.283-0.527,0.486
			c-0.137,0.204-0.232,0.436-0.296,0.695c-0.062,0.26-0.093,0.529-0.093,0.806c0,0.267,0.031,0.525,0.093,0.776
			s0.159,0.477,0.296,0.677c0.134,0.201,0.311,0.361,0.527,0.483c0.217,0.12,0.479,0.181,0.791,0.181
			c0.424,0,0.754-0.129,0.99-0.389c0.236-0.26,0.383-0.602,0.437-1.028h1.337c-0.034,0.396-0.126,0.753-0.271,1.072
			c-0.146,0.318-0.34,0.591-0.58,0.815c-0.24,0.224-0.521,0.395-0.846,0.513c-0.322,0.119-0.678,0.178-1.064,0.178
			c-0.48,0-0.914-0.084-1.299-0.252c-0.383-0.17-0.709-0.399-0.972-0.696c-0.265-0.295-0.468-0.641-0.606-1.04
			c-0.143-0.399-0.213-0.829-0.213-1.29c0-0.472,0.07-0.91,0.213-1.314c0.141-0.404,0.344-0.757,0.606-1.058
			c0.263-0.302,0.589-0.537,0.972-0.709c0.385-0.172,0.816-0.258,1.299-0.258c0.347,0,0.675,0.051,0.98,0.15
			c0.309,0.102,0.583,0.248,0.827,0.439c0.243,0.191,0.444,0.43,0.603,0.713c0.16,0.283,0.258,0.608,0.301,0.974H66.61
			C66.586,10.523,66.532,10.377,66.45,10.244z"/>
		<path fill="#FFFFFF" d="M36.615,17.415c0.405,0,0.782,0.064,1.131,0.193c0.35,0.131,0.651,0.326,0.906,0.586
			s0.455,0.584,0.599,0.975c0.144,0.389,0.216,0.848,0.216,1.372c0,0.462-0.059,0.888-0.176,1.274
			c-0.118,0.391-0.295,0.728-0.532,1.012c-0.238,0.283-0.534,0.506-0.89,0.668c-0.354,0.162-0.772,0.244-1.254,0.244h-2.71v-6.324
			H36.615z M36.519,22.569c0.199,0,0.393-0.031,0.581-0.097s0.354-0.174,0.502-0.323c0.146-0.151,0.264-0.349,0.352-0.59
			c0.088-0.242,0.132-0.537,0.132-0.887c0-0.316-0.031-0.605-0.093-0.863c-0.062-0.257-0.162-0.478-0.304-0.658
			c-0.141-0.186-0.326-0.324-0.559-0.422c-0.231-0.099-0.517-0.146-0.858-0.146h-0.984v3.984h1.231V22.569z"/>
		<path fill="#FFFFFF" d="M40.8,19.289c0.141-0.405,0.344-0.759,0.606-1.06c0.265-0.304,0.589-0.537,0.973-0.709
			c0.385-0.172,0.816-0.258,1.298-0.258c0.487,0,0.921,0.086,1.303,0.258c0.383,0.172,0.705,0.405,0.969,0.709
			c0.265,0.301,0.467,0.652,0.605,1.06c0.143,0.403,0.213,0.843,0.213,1.313c0,0.461-0.07,0.892-0.213,1.288
			c-0.141,0.397-0.343,0.746-0.605,1.041c-0.264,0.296-0.586,0.526-0.969,0.694c-0.382,0.168-0.814,0.253-1.303,0.253
			c-0.481,0-0.913-0.085-1.298-0.253c-0.384-0.168-0.708-0.398-0.973-0.694c-0.263-0.295-0.466-0.644-0.606-1.041
			c-0.141-0.396-0.211-0.827-0.211-1.288C40.589,20.132,40.659,19.692,40.8,19.289z M42.062,21.378
			c0.062,0.252,0.16,0.479,0.295,0.68c0.135,0.199,0.312,0.36,0.527,0.48c0.218,0.121,0.481,0.184,0.792,0.184
			c0.312,0,0.576-0.062,0.792-0.184c0.219-0.12,0.395-0.281,0.529-0.48c0.134-0.201,0.232-0.428,0.295-0.68
			c0.062-0.25,0.092-0.509,0.092-0.773c0-0.276-0.029-0.547-0.092-0.807c-0.062-0.261-0.161-0.49-0.295-0.695
			c-0.137-0.203-0.312-0.365-0.529-0.486c-0.216-0.12-0.48-0.182-0.792-0.182c-0.311,0-0.574,0.062-0.792,0.182
			c-0.216,0.121-0.393,0.283-0.527,0.486c-0.135,0.205-0.233,0.437-0.295,0.695s-0.093,0.527-0.093,0.807
			C41.97,20.869,42.001,21.128,42.062,21.378z"/>
		<path fill="#FFFFFF" d="M50.092,17.415l1.47,4.35h0.021l1.391-4.35h1.944v6.324h-1.294v-4.482h-0.019l-1.541,4.482h-1.062
			l-1.54-4.438h-0.019v4.438h-1.295v-6.324H50.092z"/>
		<path fill="#FFFFFF" d="M59.765,17.415l2.35,6.324h-1.436l-0.475-1.408h-2.35l-0.494,1.408h-1.392l2.377-6.324H59.765z
			 M59.844,21.295l-0.793-2.321h-0.019l-0.816,2.321H59.844L59.844,21.295z"/>
		<path fill="#FFFFFF" d="M64.547,17.415v6.324h-1.382v-6.324H64.547z"/>
		<path fill="#FFFFFF" d="M67.603,17.415l2.623,4.242h0.018v-4.242h1.295v6.324h-1.383l-2.613-4.234h-0.018v4.234h-1.295v-6.324
			H67.603z"/>
	</g>
	<path d="M86.853,1H2.147C1.239,1,0.5,1.743,0.5,2.657v28.97C0.5,31.833,0.667,32,0.872,32h87.256c0.205,0,0.372-0.167,0.372-0.373
		V2.657C88.5,1.743,87.761,1,86.853,1z M2.147,1.749h84.704c0.498,0,0.903,0.407,0.903,0.908c0,0,0,20.122,0,28.557H1.245V22.79
		c0-8.436,0-20.133,0-20.133C1.245,2.156,1.65,1.749,2.147,1.749z"/>
</g>


</svg>
Original content of this site is published into the public domain under the creative commons zero. This creator is dedicated to the free exchange of ideas, art, and science.</p>

<p>Additionally, the end-user retains all liability of using the services listed here and will not hold liable digitalsafety.tips or its creators.</p>

<p>Logos and screenshots used under fair-use. This site will comply with DMCA notices or takedown messages. Please contact the site by emailing digitalsafety@tuta.io</p>
</center>
