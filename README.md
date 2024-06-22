# better-vivaldi-android

My recommendations for the ultimate configuration of the Vivaldi Browser on Android :)

**NOTE:** This project can be found on both [Codeberg](https://codeberg.org/Magnesium1062/better-vivaldi-android), which will act as the main & preferred way to contribute, and [GitHub](https://github.com/Retold3202/better-vivaldi-android).


# General -> Search engine

**Standard Tab** -> `DuckDuckGo` ✅

**Private Tab** -> `DuckDuckGo` ✅

# General -> Search Engine Settings

**Allow Search Suggestions in Address Field** -> ❌

**Show Search Engine Suggestion** -> ❌

# General -> Allow background audio playback

**Allow background audio playback** -> ✅

# General -> Password Manager

**Save passwords** -> ❌

**Auto Sign-in** -> ❌ *(You should not save info in your browser like this for security reasons, use a dedicated password manager like Bitwarden or Proton Pass instead)*

# General -> Payment methods

**Save and fill payment methods** -> ❌

**Manually verify every time you pay using autofill** -> ✅

# General -> Addresses and more

**Save and fill addresses** -> ❌

# Tabs -> Automatically Close Tabs

**Automatically Close Tabs** -> `One Day` ✅

# Privacy -> Tracker and Ad Blocking

**Default Blocking Level** -> `Block Trackers and Ads` ✅

Sources -> Manage Tracker Blocking Sources:

* **DuckDuckGo Tracker Radar** -> ✅

* **EasyPrivacy** -> ✅

<br>

Sources -> Manage Ad Blocking Sources:

* **ABP anti-circumvention list** -> ✅

* **AdBlock Warning Removal List** -> ✅

* **Allow ads from our partners (support Vivaldi)** -> ❌

* **EasyList** -> ✅

* **Remove annoyances, can break sites (Fanboy's Annoyance List)** -> ✅

* **Remove cookie warnings (Easylist Cookie List)** -> ✅

# Privacy -> Privacy and security

**Always use secure connections** -> ✅

**Access payment methods** -> ❌

**Preload pages** -> `No preloading` ❌

**Use secure DNS** -> ✅

Use secure DNS -> **Choose another provider** -> Pick a private, secure, & reputable DNS provider of your choice, I would recommend setting up your own [NextDNS](https://nextdns.io) configuration if you are able to (See my recommendations for NextDNS [here](https://codeberg.org/Magnesium1062/nextdns-settings), otherwise I would recommend [Quad9](https://quad9.net/): `https://dns.quad9.net/dns-query` *(Even if you have a private/secure DNS provider set on your OS/network level, make sure to still set it here too like this, so that you can take advantage of [Encrypted Client Hello](https://blog.cloudflare.com/announcing-encrypted-client-hello))*

**Touch to Search** -> `Off` ❌

Touch to Search -> **Include surrounding text in Google searches** -> ❌ *(Should be default)*

**Clear session browsing data on exit** -> ✅

Clear session browsing data on exit:

* **Browsing History** -> ✅

* **Cookies and site data** -> ❌ *(I don't think this is worth it, causes far too much breakage & issues without being easily overridable)*

* **Cached images and files** -> ✅

* **Close open tabs** -> ✅

<br>

**Broadcast IP for best WebRTC performance** -> ❌ *(Don't set this if you have to call on the web through services like Discord & Zoom)*

# Appearance -> Show Keyboard Accessory View

**Show Keyboard Accessory View** -> ❌

# Web Pages -> Accessibility

**Show zoom option in main menu** -> ✅

**Force enable zoom** -> ✅

**Simplified view for web pages** -> ✅

# Web Pages -> Site settings

Permissions -> **Location** -> `Blocked` ❌ 

Permissions -> **Camera** -> `Blocked` ❌ *(Obviously don't set if you use sites that need camera access, but you can still set exceptions for sites if needed)*

Permissions -> **Microphone** -> `Blocked` ❌ *(Obviously don't set if you use sites that need microphone access, but you can still set exceptions for sites if needed)*

Permissions -> **Notifications** -> `Blocked` ❌

Permissions -> **Embedded content** -> `Blocked` ❌

Permissions -> **Motion sensors** -> `Blocked` ❌

Permissions -> **NFC devices** -> `Blocked` ❌

Permissions -> **USB** -> `Blocked` ❌

Permissions -> **Clipboard** -> `Blocked from reading clipboard` ❌

Permissions -> **Virtual reality** -> `Blocked` ❌

Permissions -> **Augmented reality** -> `Blocked` ❌

Permissions -> **Your device use** -> `Blocked` ❌

Content -> **Third-party cookies** -> `Block third-party cookies` ❌

Content -> **JavaScript** -> `Blocked` ❌ *(This **will** cause breakage, but it heavily improves privacy & security, so I'd recommend blocking it if possible and if you're willing to re-enable JavaScript on sites that need it)*

Content -> **Pop-ups and redirects** -> `Blocked` ❌ *(Should be default)*

Content -> **Intrusive ads** -> `Blocked on some sites` ❌ *(Should be default)*

Content -> **Protected content** -> `Blocked` ❌ - https://www.eff.org/deeplinks/2017/10/drms-dead-canary-how-we-just-lost-web-what-we-learned-it-and-what-we-need-do-next

Content -> **Third-party sign-in** -> `Blocked` ❌

Content -> **Auto-verify** -> `Blocked` ❌

Content -> **Background sync** -> `Blocked` ❌

Content -> **Autoplay Videos** -> `Blocked` ❌ *(Should be default)*

# Web Pages -> Downloads

**Ask where to save files** -> ✅ *(Should be default)*

# Web Pages -> Notifications

General:

* **All "General" notifications** -> ✅

* **Browser** -> ❌

* **Active downloads** -> ✅

* **Private** -> ✅

* **Playing media** -> ✅

<br>

Other:

* **VivaldiNotificationChannel** -> ❌

# Web Pages -> Stay in browser

**Stay in browser** -> ✅

**Disable PWA install prompts** -> ✅ *(Should be default)*

# Speed Dial

On Vivaldi's Start Page/Speed Dial, feel free to remove the built-in sponsored links.

# Bookmarks

Similarly, I'd also recommend deleting the built-in sponsored bookmarks, as well as the `Vivaldi` folder.

# vivaldi://flags

**#android-open-pdf-inline** -> `Enabled`

**#block-insecure-private-network-requests** -> `Enabled`

**#content-settings-partitioning** -> `Enabled`

**#enable-parallel-downloading** -> `Enabled`

**#enable-site-per-process** -> `Enabled`

**#reduce-accept-language** -> `Enabled`

**#strict-origin-isolation** -> `Enabled`

**#third-party-storage-partitioning** -> `Enabled`

# Additional recommendations

* Use a (reputable) VPN. I would recommend either [Mullvad](https://mullvad.net/) or [ProtonVPN](https://protonvpn.com/).

* Use a (reputable) anti-virus if possible, such as [Hypatia](https://f-droid.org/packages/us.spotco.malwarescanner/). **NOTE:** You should install Hypatia through the [DivestOS Official Repo](https://divestos.org/fdroid/official/?fingerprint=E4BE8D6ABFA4D9D4FEEF03CDDA7FF62A73FD64B75566F6DD4E5E577550BE8467) instead of F-Droid's main repo, as it will allow you to receive quicker updates directly from the developer. It's also recommended to use [F-Droid Basic](https://f-droid.org/en/packages/org.fdroid.basic/) as your F-Droid client of choice.