# Recall Contacts — Feature Reference

> iPhone contacts app. Find anyone by hashtag, place, or context. No spelling required.

**Platform:** iOS (iPhone, iPad, Mac via Catalyst)  
**Price:** Free  
**App Store:** https://apps.apple.com/us/app/recall-contacts/id6758255331

---

## Core Concept

Most contacts apps assume you remember how someone's name is spelled. Recall assumes you remember the context instead. Tag people with hashtags the moment you meet them. Search by that context later and find them instantly.

---

## Tier 1 — Core Features

### Hashtag Tagging

Add hashtags to any contact to describe how you know them. Tags can be anything: places (#NYC, #Tokyo), events (#Frieze, #schoolrun, #wedding), relationships (#doctor, #mentor), contexts (#ramen, #rooftop, #2024). There is no fixed taxonomy — you invent the tags that match your memory.

Tags are stored locally on your device and also written back to the notes field of the contact in Apple Contacts, making them portable and permanent.

### Multi-Tag Search

Search using one or more hashtags simultaneously. Type `#NYC #gallery` and Recall instantly filters your contacts to only those tagged with both. The more tags you add, the narrower and more precise the result. No need to remember a name — remember the context.

### Contact List

A clean, scrollable list of all your contacts with their tags visible at a glance. Colour-coded Super Tags (VIP, Family, Work, Parents, Friends) appear as coloured chips. Custom hashtags appear alongside them. The list sorts alphabetically or by recency.

### Contact Detail View

Tap any contact to open their full detail view. From here you can call, FaceTime, FaceTime Audio, message, or WhatsApp them with one tap. Add or remove tags. View all tagged context. Quick Recall gives you immediate access to the most relevant actions.

### Swipe to Tag

The fastest way to tag contacts at scale. Swipe right on a contact in the list to tag it. Works like a card-swipe flow — ideal for processing hundreds of contacts quickly. Swipe left to skip. The tag keyboard includes autocomplete so you can re-use existing tags without retyping.

### Tag Autocomplete

As you type a hashtag, Recall suggests existing tags from your collection. This keeps your tagging consistent and fast — no duplicates like `#newyork` and `#NYC` for the same concept. Autocomplete also shows tag frequency so you know how many contacts carry each tag.

---

## Tier 2 — Power Features

### Smart Groups

Every hashtag you create automatically becomes a Smart Group. Tap the `#NYC` group and see every contact you've tagged with it. Groups update in real time as you add and remove tags. There is no manual group management — groups are simply a view of your tags.

### Smart Group Filter Bar

A horizontal filter bar at the top of your contact list shows your most-used tags as quick-access chips. Tap one to instantly filter. Tap multiple to intersect. Clear with one tap. Designed for fast navigation without opening search.

### Quick Recall

From the contact detail view, Quick Recall surfaces the most context-relevant actions based on the contact's tags and your interaction history. One-tap access to call, message, FaceTime, WhatsApp, or share a vCard — without navigating menus.

### One-Tap Actions

Every contact detail view has one-tap buttons for: Call, FaceTime, FaceTime Audio, Message, WhatsApp, Email, and Share Contact (vCard). No nested menus. The most common action for each contact is always visible.

### FaceTime Integration

Call any contact via FaceTime video directly from Recall. The FaceTime button appears prominently in the contact detail view alongside the standard call button.

### FaceTime Audio

Make FaceTime Audio calls (audio-only over internet) directly from Recall. Useful as an alternative to a standard cellular call, especially internationally.

### WhatsApp Actions

Open a WhatsApp conversation with any contact directly from their detail view. Requires WhatsApp to be installed on the device.

### Kids & Parents Mode (Parent Mode)

Attach your children's names to school parent contacts. Tag a contact `#mum #Luca #Ella` and search `#Luca` to find that child's parent instantly. Designed for parents who know every child at school pickup but struggle to remember the parent's name. This feature bridges the gap between the name you know (the child) and the contact you need (the parent).

### Power User Mode

An advanced settings mode that surfaces additional customisation options for users who want granular control over the app's behaviour. Toggle individual features, adjust display density, and configure tag management preferences.

### Review Queue

A dedicated swipe-through interface for reviewing old or untagged contacts. Swipe right to tag. Swipe left to skip. Swipe up to delete. The fastest way to clean up an address book that has accumulated years of contacts with no context.

### vCard Sharing

Share any contact as a vCard directly from the contact detail view. The share sheet includes all standard iOS share destinations. Useful for quickly passing contact details to someone else.

### Date Stamp Insertion

Insert the current date as a tag automatically when adding context to a contact. Useful for recording when you met someone — `#2024-06-15 #ArtBasel` — so you can filter contacts by the approximate time you met them.

---

## Tier 3 — Experience Features

### Three Visual Themes

Recall offers three distinct visual themes:

- **Dark Mode** — the default. Black background, white text, high contrast. Designed for low-light environments and extended use.
- **iOS Native Mode** — adapts to the system's current Light or Dark appearance. Uses standard iOS colours and feels familiar to iPhone users.
- **Paper Mode** — a warm off-white, low-contrast, reduced-motion theme. Designed for users who find high-contrast displays tiring. Particularly useful for dyslexic and light-sensitive users.

### Paper Mode

Paper Mode is Recall's low-stimulation theme. Warm off-white backgrounds, reduced border contrast, and relaxed typography. Intended as a calmer alternative to dark or stark white interfaces. Preferred by many dyslexic and neurodivergent users.

### iOS Native Mode

A theme that inherits the system's Light or Dark appearance setting. Recall renders using standard iOS UI elements and colours in this mode, making it feel native and familiar.

### Dynamic Type Support

Recall fully supports Apple's Dynamic Type system. All text in the app scales with the font size set in iOS Settings → Display & Brightness → Text Size. This includes support for the Accessibility extra-large text sizes. Designed so that users who depend on large text can use Recall without any reduction in functionality.

### Contact Photos

Contact photos from Apple Contacts are displayed in the contact list and detail view. If a contact has no photo, their initials are shown in a placeholder. Photos help with visual recognition — particularly useful for users who remember faces better than names.

### In-App Contact Creation

Create new contacts directly inside Recall without leaving the app. The contact is saved to Apple Contacts so it appears in the Phone app and across iCloud. You can immediately add hashtags during creation.

### Fast Alphabetical Scrolling

A vertical index bar on the right side of the contact list lets you jump instantly to any letter. Tap A to go to the top of the A contacts. Tap Z to jump to the bottom. Essential for large contact lists.

### Onboarding Flow

A short, clear onboarding sequence introduces the core concept — tag contacts, search by hashtag — without requiring a tutorial video or manual. Designed to get users tagging within the first two minutes.

### Tag Usage Statistics

View a breakdown of all your tags and how many contacts carry each one. Sorted by frequency. Useful for auditing your tagging system and identifying tags you've outgrown or want to consolidate.

### Tag Limits

Recall enforces sensible tag limits per contact to encourage focused, useful tagging rather than over-tagging. Limits are generous enough for real-world use.

### Mac Catalyst Support

Recall is available on iPad via the App Store and runs natively on Mac via Mac Catalyst. The Mac version supports keyboard navigation and takes advantage of the larger screen for the contact list layout.

### Donation / Newsletter Integration

Recall includes an in-app link to support the developer via Buy Me a Coffee. There is also an optional email newsletter signup for Recall updates and feature news.

---

## Accessibility

Recall was built by a dyslexic developer and designed from the ground up with neurodivergent users in mind.

- **Dyslexic-friendly mode** — high contrast tones, specialist letter spacing, and reduced visual clutter
- **Dynamic Type** — all text respects iOS system font size, including Accessibility sizes
- **Paper Mode** — low-stimulation theme for light-sensitive and dyslexic users
- **Context-first search** — never requires correct spelling to find a contact
- **Screen reader compatible** — all interactive elements are labelled for VoiceOver
- **Keyboard accessible** — full keyboard navigation supported on Mac Catalyst

---

## Privacy

- No account required to use the app
- No email address needed
- No cloud sync (data stays on device)
- No contacts data sent to any server
- No analytics on your personal contacts
- Tags are stored locally and also written to Apple Contacts notes field
- Deleting the app does not delete your tags — they remain in Apple Contacts

---

## Platform Support

- **iPhone** — iOS 15.0 or later
- **iPad** — iPadOS 15.0 or later
- **Mac** — macOS 12.0 or later via Mac Catalyst
- **Language** — English
- **Price** — Free

---

## Frequently Asked Questions

**Does Recall replace my iPhone contacts app?**
No. Recall layers on top of Apple Contacts. Your Phone app remains unchanged. Recall is for finding and organising.

**Do my tags sync across devices?**
Tags are stored locally. Because Recall writes tags back to the Apple Contacts notes field, they sync via iCloud if you have iCloud Contacts enabled.

**What if I delete Recall?**
Your hashtags remain in the notes field of your Apple Contacts. Your data stays with you.

**Is it really free?**
Yes. Free to download with no subscription or account required.

**Is there an Android version?**
Currently iOS only.

**Does it work with a large contact list?**
Yes. Designed for photographers and networkers with hundreds or thousands of contacts.

**Is my data private?**
Completely. No data leaves your device. Recall never connects to any external server with your contact information.

---

*Recall Contacts — https://recall-contacts.com*  
*Created by Paul Barbera — https://paulbarbera.com*
