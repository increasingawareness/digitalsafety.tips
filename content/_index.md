+++
url = "index.html"
+++

 Welcome to digitalsafety.tips, a guidebook aimed at simple solutions to keep people safe, secure, and private in the digital world.

<center>

# <i class="far fa-eye-slash" id="adsandtrackers"></i> Block ads and malicious trackers 


</center>

Ads and trackers follow you around the Internet gobbling up information about you and selling it to various companies. Ads are annoying and a eye-sore. Trackers are not consensual. To avoid these issues, simply use the tools below. 

<center>

## Brave on mobile 

On mobile, use Brave browser to block ads and malicious trackers.


<a href="https://brave.com"><img src="/img/brave.svg" height="200" alt="brave"></a>

Switch the search engine to duckduckgo in Brave's settings.

<a href="https://duckduckgo.com"><img src="/img/duckduckgo.svg" height="100" alt="duckduckgo"></a>


<br>
<br>

## Firefox on desktop

On desktop, use Firefox 

<a href="https://firefox.com"><img src="/img/firefox.svg" height="200" alt="firefox"></a>


with the following extensions:

[ublock origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)
<a href="https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/"><img src="/img/ublocko.png" height="50" alt="ublock origin"></a>


[Privacy badger](https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/)
<a href="https://addons.mozilla.org/en-US/firefox/addon/privacy-badger17/"><img src="/img/privacybadger.png" height="50" alt="Privacy Badger"></a>

[https everywhere](https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/?src=recommended)
<a href="https://addons.mozilla.org/en-US/firefox/addon/https-everywhere/?src=recommended"><img src="/img/httpseverywhere.png" height="50" alt="httpseverywhere"></a>

[cookie autodelete](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/)
<a href="https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/"><img src="/img/cookieautodelete.png" height="50" alt="cookie autodlete"></a>

[Decentraleyes](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/)
<a href="https://addons.mozilla.org/en-US/firefox/addon/decentraleyes/"><img src="/img/decentraleyes.png" height="50" alt="Decentraleyes"></a>

[Bitwarden](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/)
<a href="https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/"><img src="/img/bitwardenext.png" height="50" alt="bitwarden"></a>

Switch the search engine to duckduckgo in Firefox's settings.

<a href="https://duckduckgo.com"><img src="/img/duckduckgo.svg" height="100" alt="duckduckgo"></a>

<br>
<br>

---


# <i class="fas fa-comments" id="chat"></i> Keep conversations yours

## Signal Messenger for Mobile and Desktop



<a href="https://signal.org"><img src="/img/signal.png" height="200" alt="Signal"></a>

</center>

Signal is a fun and peer-reviewed messaging app that allows you to connect in a way that respects you. Signal is non-profit, supports video/audio calls, messaging, Giphy, and group chats. It's available on iOS, Android, MacOS desktop, Windows desktop, and Linux desktop. Make your conversations with people just between you and them, not between you and a company that sees you as a product.

<center>

<br>
<br>

---


# <i class="fas fa-key" id="passwords"></i> Use passwords wisely

</center>

Most people reuse the same password or a variant of the same password. This is actually dangerous. Each account should have a fully unique password. Since it's unlikely that most people will remember a unique string of characters for every login, we use a password manager to store our passwords securely. 

A password manager generates new passwords for you, and stores them until you need them. All you need to remember is one passphrase that protects all the other ones. As long as the password manager has a strong passphrase and a second-factor code to unlock it, the passwords will stay safe.

<br>
<center>

## Create passphrases

<a href="https://en.wikipedia.org/wiki/Diceware"><img src="/img/dice.jpg" height="200" alt="dice"></a>

</center>

A passphrase is usually longer and more memorable than the shorter but harder to remember password. You'll need a master passphrase for your password manager. This is best accomplished with the [Diceware method](https://en.wikipedia.org/wiki/Diceware). This method involves rolling physical die to randomly select 6 to 7 words from a word list. One simply strings these words together, all as one word and creates a mnemonic to remember it. 

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
9. Repeat this process to create the second passphrase for your computer login.
10. Shred the paper that you've carried with you after you've sufficiently memorized both passphrases. With a good mnemonic story, it shouldn't take longer than a week.



<center>

## Bitwarden password manager

<a href="https://bitwarden.com"><img src="/img/bitwarden.png" height="200" alt="bitwarden"></a>

</center>

Bitwarden is a password manager that has undergone security audits, encrypts your passwords without being able to access them, is open source, free, and multi-platform. You can even securely share passwords with others. If you're technically apt, you can even host your own server. I recommend using the app on mobile and the browser plugin on desktop for Firefox.

<center>

<br>
<br>

---
# <i class="fas fa-mobile-alt" id="2fa"></i> Passwords aren't enough. Use 2FA.

</center>

Security is strongest in layers. Your passwords are only the first layer. Most people carry a phone which can easily be used as a second layer. 2FA (2 factor authentication) usually works by entering a code from your phone after using your password to login. This ensures you are the only person who can access the account. Enable 2FA on all the accounts that you can. 

<br>

There are three main types of authentication:

<center>

| Type of authentication                                | How it works                                                                                       |
|-------------------------------------------------------|----------------------------------------------------------------------------------------------------|
| Text message or phone call                            | Get an automated text or phone call and enter the code you read or hear.                           |
| App on your phone                                                  | Copy the time based code from an app on your phone.                                                |
| Specialized device like a Yubikey, Onlykey, or Trezor | Press a button on the device or tap the device to your phone (see [next level steps](#nextlevel)). |

<br>

</center>

Prefer apps and specialized devices over text message authentication. However, text message based 2FA is better than not having any at all.

Go to https://twofactorauth.org/ to see some sites that support 2FA. Most banks, social media networks, and email providers have 2FA.

<center>

<br>

## andOTP for Android

<a href="https://play.google.com/store/apps/details?id=org.shadowice.flocke.andotp"><img src="/img/andotp.svg" height="200" alt="andOTP"></a>

</center>

Important - andOTP has the ability to backup security keys to wherever you would like. It is highly recommended to keep consistent and encrypted backups of your 2FA keys.

<br>
<center>

## Tofu for iOS

<a href="https://itunes.apple.com/app/tofu-authenticator/id1082229305"><img src="/img/tofu.svg" height="200" alt="Tofu"></a>

</center>

Important - 2FA keys are stored on your iPhone's secure keychain, so only iTunes/iCloud encrypted backups will include a backup to these keys. If you're restoring your device from an iTunes/iCloud backup, the app and all keys will be restored as well.

<center>
<br>
<br>

---

# <i class="fas fa-envelope-open-text" id="haveibeenpwned"></i> Sign up for haveibeenpwned

<a href="https://haveibeenpwned.com"><img src="/img/hibp2.png" alt="haveibeenpwned"></a>

</center>

Created by security expert Troy Hunt, "Have I been Pwned?" is a service that keeps tracks of data breaches. Pronounced "pone," pwn is internet slang for "to own" or to conquer to gain ownership. Enter your email at the site to see if any of your accounts have been breached. If anything has been breached in the past, don't panic. Go to the website that was breached and change your password there. Be sure [to subscribe](https://haveibeenpwned.com/NotifyMe) to get notified of further breaches right away. Do this for each email you use.

<center>


<br>
<br>

---


# <i class="fas fa-skull-crossbones" id="phishing"></i> Phishing, scams, remote access



</center>

In general:

- If it sounds too good to be true, it usually is.
- Verify that you are [seeing "https" when visiting websites](https://www.howtogeek.com/181767/htg-explains-what-is-https-and-why-should-i-care/).
- Don't click on links in emails you don't know.
- Don't open or download files from a source you don't know.
- [If it's a supposed government agency, they will get a hold of by official means (the IRS will never call you, they will send you postal mail)](https://www.youtube.com/watch?v=0y5z0kWgBcM).
- Don't be fooled by visual similarities, always verify who is contacting you.
- [Pay attention to browser alerts and security exceptions](https://support.mozilla.org/en-US/kb/what-does-your-connection-is-not-secure-mean).
- [Be very careful of shortened links](https://www.schneier.com/blog/archives/2016/04/security_risks_11.html).

<center>

<img src="/img/phonecall.jpg" height="200" alt="phonecall">

## Inspect emails carefully

</center>

> "Phishing is when a scammer uses fraudulent emails or texts, or copycat websites to get you to share valuable personal information – such as account numbers, Social Security numbers, or your login IDs and passwords. Scammers use your information to steal your money or your identity or both. Scammers also use phishing emails to get access to your computer or network then they install programs like ransomware that can lock you out of important files on your computer. Phishing scammers lure their targets into a false sense of security by spoofing the familiar, trusted logos of established, legitimate companies. Or they pretend to be a friend or family member." -[Federal Trade Commission](https://www.consumer.ftc.gov/articles/0003-phishing)

<center>

<br>

## Don't trust; verify.

</center>

It's relatively easy to trust what people say. When it comes to your personal information remember the above maxim. Verify who people are and what they are doing is essential when dealing with tech support, financial institutions, or businesses. This process helps you avoid [social engineering](https://www.us-cert.gov/ncas/tips/ST04-014). In general, don't allow people to remote access your computer unless your business-place has this setup to begin with. 

<center>

<br>

## Keep it secret; keep it safe.

</center>

As the wise wizard said. Corollaries to this phrase include:

- ["loose-lips sink ships"](https://en.wikipedia.org/wiki/Operations_security)
- ["The Internet is forever"](https://www.inc.com/meredith-fineman/what-we-post-online-is-forever-and-we-need-a-reminder.html)
- ["On a need-to-know basis"](https://www.youtube.com/watch?v=YEiu7uYCfPE)



For more on phishing, check out [this comic](https://theintercept.com/2017/11/19/how-to-protect-yourself-against-spearphishing-a-comic-explanation/) from *The Intercept*.
<center>
<br>
<br>

---

# <i class="fas fa-cloud-upload-alt" id="cloud"></i> Be your own cloud

</center>

Usually, a cloud is comprised of a specific company's servers. Servers are just computers and storage devices that are accessible over a network. In this case, when you access something on Apple's cloud, Dropbox, Google drive, etc., your device is actually logging onto to that company's server and accessing from there. This solves a great many problems, but it creates a few weighty ones too. The weightiest is that your personal data exists on a device controlled by companies that want to make money off of you. 

<br>
 
 <center>

## Syncthing

<a href="https://syncthing.net"><img src="/img/syncthing.svg" height="200" alt="syncthing"></a>

</center>

Syncthing allows you to sync folders and files to each of your devices and work collaboratively with others. You could sync your photos in a family folder, edit files for a collaborative project, or keep the photos on your phone backed up to your main computer. This tool currently works with Android, MacOS, Windows, and Linux. An iOS version does not currently exist. If you need a cloud tool that works with iOS, check out Cryptomator below.

<br>

<center>

## Cryptomator

<a href="https://cryptomator.org"><img src="/img/cryptomator.png" height="200" alt="cryptomator"></a>

</center>

Cryptomator is a tool that works with current cloud providers (Google Drive, iCloud, Dropbox, and more). The main benefit is that your data stays yours---those companies aren't able to access your data since it's encrypted. It works on all the major platforms.

<center>
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

<details>
<summary>Linux</summary>
It depends on what Linux distribution you have and how it have it configured. If you are running Debian, you can install `gnome-packagekit` and the gnome extension [Apt Update Indicator](https://extensions.gnome.org/extension/1139/apt-update-indicator/). This will automatically tell you when updates are available and allow you to update the system graphically.

</details>


<center>

<br>
<br>

---

# <i class="fas fa-user-lock" id="lockitdown"></i> Keep your devices on lock

</center>

Please keep a passcode on your phone! Today, most modern phones (both Android and iOS) also encrypt your data so you can be sure that if you lose your device or if someone steals it, no one else can have access to it. 

<center>

<img src="/img/phonelock.jpg" height="200" alt="phonelock">

</center>

On Windows, you may want to consider using [Veracrypt](https://www.veracrypt.fr/en/Home.html). 

Apple computers also have [FileVault](https://support.apple.com/en-us/HT204837), which protects the data on your Mac. Go into the settings and activate it.

On Linux, you can enable encryption on install.

If you want to learn more about this subject, the EFF has [an excellent guide](https://ssd.eff.org/en/module/keeping-your-data-safe) on keeping your data safe.

<center>

<br>
<br>

---


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

Get close friends and family on Signal, tell them about Brave browser being able to block ads, and show them how to make secure passphrases. This way we can help everyone be safe, secure, and private.

<center>



<br>
<br>

---

# <i class="fas fa-tools" id="othertools"></i> Other tools

</center>

These tools are in addition to the basic tools that I recommend above. You may or may not have a use case for them.

<center>

## Mobile/Desktop: Communicate securely with Wire messenger

</center>

Using a similar protocol to Signal, Wire is a commercial company that allows for secure communication with others. It's free for personal use. You can also use it for your business with their paid plans.

<center>

<a href="https://wire.com/en/products/personal-secure-messenger/"><img src="/img/wire.png" height="100" alt="wire"></a>

<br>

## Desktop: Encrypt files or disks with Veracrypt

</center>

Veracrypt allows one to keep files in a secure container or encrypt whole disks.

<center>

<a href="https://www.veracrypt.fr/en/Home.html"><img src="/img/veracrypt.png" height="100" alt="veracrypt"></a>

<br>

## Mobile/Desktop: Keep your searches and perusing anonymous with Tor

</center>

The Tor browser is an amazing tool that allows one to freely browse the web anonymously. It basically connects to volunteers who operate servers all over the world and encrypt your web traffic in layers like an onion. It does this 3 times so that no one can connect the requester of the data with the data itself. If you would like to be anonymous on the web, the tor browser is your ticket. 



> "Tor protects the network communications. It separates where you are from where you are going on the Internet. What content and data you transmit over Tor is controlled by you. If you login to Google or Facebook via Tor, the local ISP or network provider doesn't know you are visiting Google or Facebook. Google and Facebook don't know where you are in the world. However, since you have logged into their sites, they know who you are. If you don't want to share information, you are in control." -[Torproject FAQ](https://2019.www.torproject.org/docs/faq.html.en#AmITotallyAnonymous)

<center>

<a href="https://torproject.org"><img src="/img/tor.png" height="200" alt="torbrowser"></a>

<br>



---

</center>

<details>
<summary id="nextlevel"><i class="fas fa-laptop"></i> Next Level Steps</summary>

## <i class="far fa-envelope" id="email"></i> Change your email

The following four email providers have shown dedication to keeping your information safe. Pick one and make the migration from less friendly services.

<center>


<img src="/img/Posteo.png" alt="posteo"></a> 

Cost: 12 € per year

---

<img src="/img/ProtonMail.png" alt="protonmail">

Free

---

<img src="/img/Tutanota.png" alt="tutanota">

Free

---

<img src="/img/mailbox.png" alt="mailbox"></a> 

Cost: 12 € per year

---


</center>
 

<br>
<br>

---



## <i class="fab fa-linux"></i> Install Linux

It's not as scary as it sounds.

There are different types of Linux (called distributions). Here are my recommendations:

### [Ubuntu](https://www.ubuntu.com/)

Ubuntu is the easiest to install and use out of the box.

### [Debian](https://www.debian.org/)

Solid choice and number one recommendation.

### [Fedora](https://getfedora.org/)

Popular and long-lasting Linux distribution.

<br>
<br>

---

## <i class="far fa-hdd"></i> Backup your files

No one wants to lose all their data. You can keep encrypted backups on an external hard drive. This allows you to keep a snapshot of your system. If something goes wrong, you can restore to a previous time. For a cross-platform tool, check out [Duplicati](https://www.duplicati.com/). MacOS has the [Time Machine](https://support.apple.com/en-us/HT201250) backup utility available. I recommend using [BorgBackup](https://www.borgbackup.org/) for Linux.


You may want to consider keeping cloud backups. This means that you're storing your files on a company's servers (they take care of redundancy). It's recommended to use software like Cryptomater so that these companies don't have access to the contents of your files.

<br>
<br>

---


## <i class="fas fa-dragon"></i> Upgrade and protect your home network

Most consumer routers are horribly outdated and riddled with bugs. Just recently, the U.S. government advised that U.S. citizens reset their routers since the Russian government attacked and successfully subverted millions of routers throughout the world. Most consumer routers never get updated. These are actually small computers that need regular updates to patch for security issues or bugs.


### PFsense router and Firewall with a Wireless Access Point

PFsense is an open source operating system that specializes as a firewall, router, gateway, and more. Netgate makes PFsense appliances that I recommend. Pick up a wireless router made by Ubiquiti and you should be set.

<br>
<br>

---

## <i class="fas fa-dumpster-fire"></i> Leave Social Media Behind

<br>
<br>

---

## <i class="fab fa-usb"></i> Carry a second-factor token with you



> "When it comes to online security, confusion about the risks can lead people to obsess over obscure threats while ignoring key innovations that could truly protect them. Even highly-targeted users like politicians and activists don’t fully appreciate the scourge of phishing, and many aren’t familiar with an emerging form of two-factor authentication known as “Security Keys” that we hope can stop it in its tracks ... phishing is the silent killer, and relying on a password alone is a recipe for disaster. Two-factor authentication (even with a code delivered by SMS) is still way better than the alternative, but if you’re an at-risk user — like a political figure, celebrity, activist, or journalist — please consider FIDO Security Keys for all your sensitive accounts. Anything less would be uncivilized. 🔐" -Mark Risher's [*Phishing and Security Keys*](https://medium.com/@mrisher_2499/phishing-and-security-keys-b5c8e8e26931)




### Trezor

### Yubikey

### Onlykey


<br>
<br>

---


## <i class="fas fa-network-wired"></i>  You can use a commercial VPN if you want, but remember: "A VPN is an ISP"

<a href="https://mobile.twitter.com/SarahJamieLewis/status/871713517317042176"><img src="img/srah.png" alt="sarahjamielewis"></a>


<br>
<br>

---

</details>

<center>

# <i class="far fa-question-circle" id="faq"></i> FAQ

</center>

##  What kind of phone should I get?
 
Currently, there isn't a "holy grail" of phones that combines all the aspects of digital safety (safe, secure, and private by design). The best option you can have in your hand right now is probably an iPhone or Pixel 3  [according to Daniel Micay](https://www.reddit.com/r/GrapheneOS/comments/bddq5u/os_security_ios_vs_grapheneos_vs_stock_android/ekxifpa?utm_source=share&utm_medium=web2x), a [prominent mobile security developer](https://twitter.com/Snowden/status/1047618052089696257).

## What kind of computer should I get?

### ThinkPad X200, X220, or X230

You can pick one of these up on Ebay for less than $400. They are robust, easy to use, and will last a while.

### Purism Librem Laptop

For a more modern but expensive but modern option, Purism creates really nice laptops pre-installed with Linux. 


## Why should I care about privacy? I don't have anything to hide.

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

## For more tools, head over to [privacytools.io](https://privacytools.io).


---

## About

I'm Grant. For the past many years I've spent a large amount of hours learning more about technology, security, Linux, and network infrastructure. 

My handle is @increasingawareness. You contact me with that username on Wire messenger. I'm not currently on any social media platforms.

This site was aimed at the layperson and was intended to get privacy-security preserving tech into the hands of as many people as possible.

## Credits


- To  Tom Preston-Werner and Jekyll contributors for Lanyon-theme and associated CSS under the [MIT license](https://github.com/jekyll/jekyll/blob/master/LICENSE).
- Font-Awesome used under the [Font Awesome Free License](https://github.com/FortAwesome/Font-Awesome/blob/master/LICENSE.txt).
- To Bjørn Erik Pedersen for the [wonderful static site generator Hugo](https://gohugo.io/) under the Apache 2.0.
- To my family and friends for their patience and support. =)


[^1]: https://theintercept.com/2015/03/26/passphrases-can-memorize-attackers-cant-guess/




