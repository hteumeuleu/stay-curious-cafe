# “Email” with Mark Robbins and Rémi Parmentier 

Examples and notes for Mark and Rémi's talks at Stay Curious Café on May, 5th 2021.

## Session 1: A Single Email

Looking at how a single email can purposefully render differently across email platforms, showing we’re not stuck in the 90’s anymore.

### Introduction

* [A Single Email](https://useparcel.com/e/bc910fb8-b746-4a3c-9fd7-397ec83f387f) by Mark and Rémi
* An email is not just HTML and CSS. It’s a MIME format that contains a common header (with fields like _From_ and _Date_) and a message body that can be in plain text, HTML or even AMP.

### Accessibility

* Demo of a plain text email in Thunderbird
* Demo of an HTML email in Thunderbird
* [VoiceOver video demo](https://youtu.be/XLP-0uid-SY)

### Responsive and Interactive

* Emails are not stuck in the 1990s
* Demo of an interactive and responsive email in Yahoo’s desktop webmail
* Some things like media queries can become tricky because it targets the window's viewport, not the webmail's email viewport.

### Grid Layout

* Demo of a CSS Grid Layout in Apple Mail

### Dark Mode

* Demo of an email adjusted by Outlook.com’s dark mode
* We can add dark mode using `@media (prefers-color-scheme:dark)`…
* …But we get the same kind of conundrum than with responsive media queries. We can target Outlook.com using `[data-ogsb]` selectors.

### AMP

* Demo of an AMP email in Gmail’s desktop webmail

### Links

* [Parcel](https://useparcel.com)
* [Can I email](https://www.caniemail.com)
* [HowToTarget.email](https://howtotarget.email)

---

## Session 2: Experimental Email

Looking at how we can push email clients to their limits creating visual artworks and playable games. 

### Pixel Art and CSS Art (in emails)

#### Images Off Pixel Art

* [Images Off Emails Examples](https://imgur.com/a/ATAdThu)
* [LEGO City Undercover Email](https://useparcel.com/e/9b41a78a-cbdd-45e7-92fb-f0757447b8f4) ([Gist mirror](https://gist.github.com/hteumeuleu/3818eded96f066d7b48a83c732c89156))
* Great trend in HTML emails until responsive came along. WebKit and Blink rendering makes this kind of slicing hideous with thin lines everywhere.

#### CSS Art

* [CSS Art Collection on CodePen](https://codepen.io/collection/XmpLYx) by Mark Robbins
* [Pure CSS Avocados](https://codepen.io/juliepark/pen/dBXXNZ) by Julie Park
* [Mona Lisa in VML](https://gist.github.com/hteumeuleu/3818eded96f066d7b48a83c732c89156) via [svg-vml.net](https://web.archive.org/web/20100302191425/http://www.svg-vml.net/Joconde.htm)
* [Live Coding a CSS Avocado](https://useparcel.com/e/5939d7e3-02ac-450e-af73-5988aeb818a6)
* [CSS Bullet Points in Bulletin Email](https://reallygoodemails.com/emails/-welcome-to-bulletin)