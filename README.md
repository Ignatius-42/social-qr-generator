# Social Profile QR Generator

*"Contre la bêtise moderne"* - Against the tedium of misspelled names and failed LinkedIn searches.

A simple web tool to generate QR codes for your LinkedIn, Twitter, and Instagram profiles. Perfect for conferences, meetups, and networking events.

## Why This Exists

Networking shouldn't be hard. You meet someone interesting, you want to connect, but then comes the awkward dance:

- "What's your name again?"
- "How do you spell that?"
- "Are you the John Smith from Boston or the other one?"
- *5 minutes of searching later...*

This tool fixes that. Generate QR codes for all your profiles, save them to your phone, show the right one when needed. Instant connection. No friction.

## Features

✨ **Three major platforms:** LinkedIn, Twitter/X, Instagram  
🎨 **Branded QR codes:** Platform logo embedded in QR center  
📝 **Clear labels:** Platform name and username shown below QR  
🔒 **100% local** - Nothing uploaded, no tracking  
📱 **Mobile-optimized** - Made for real-world use  
⚡ **Instant generation** - Paste URL, get QR  
💾 **Download or share** directly to WhatsApp  
🎯 **Smart validation** - Checks URLs match the platform  
🔄 **Auto-extraction** - Username pulled from URL automatically

## How to Use

### Before Your Event:

**Option 1: Use Online (Easiest)**
1. **Visit** https://ignatius-42.github.io/social-qr-generator/
2. Select platform (LinkedIn/Twitter/Instagram)
3. Paste your profile URL
4. Generate QR code
5. Share to WhatsApp

**Option 2: Download and Use Offline**
1. Download the `index.html` file from this repository
2. Open in any modern browser
3. Works completely offline

### The WhatsApp Trick:

Create **one WhatsApp group** with just yourself (e.g., "My Social QR Codes"):
- Generate QR for LinkedIn → Share to group
- Clear → Generate QR for Twitter → Share to group
- Clear → Generate QR for Instagram → Share to group

Now all your QR codes are in one place! The platform name and username on each QR make it easy to show the right one.

### At Your Event:

1. Someone wants to connect
2. Open your WhatsApp group
3. Scroll to the right QR (LinkedIn/Twitter/Instagram)
4. Show them the QR
5. They scan → instant connection

No spelling errors, no searching, no awkward exchanges.

## What Makes This Different

Unlike generic QR generators, this tool creates **professional, branded QR codes**:

- **Platform logo** embedded in QR center (still scans perfectly!)
- **Platform name** clearly labeled (LinkedIn/Twitter/Instagram)
- **Your username/handle** displayed below QR
- **High error correction** - Guaranteed scanning even with logo

The result: QR codes that look professional and clearly show what platform they're for.

## Username Display

- **LinkedIn:** Shows your profile slug (e.g., `john-smith`)
- **Twitter:** Shows your handle with @ (e.g., `@johnsmith`)
- **Instagram:** Shows your handle with @ (e.g., `@johnsmith`)

All automatically extracted from the URL you provide!

## Philosophy

This tool respects you:
- No accounts required
- No data collection
- No tracking pixels
- No "sign up to download"
- No dark patterns

Just a tool that does its job. Like software used to be.

## Use Cases

📊 Conferences & meetups  
🎓 Career fairs & recruiting events  
🤝 Business networking  
👥 Social gatherings  
💼 Client meetings  
🎤 Speaking engagements

## Technical

Pure HTML/CSS/JavaScript. Runs entirely in your browser.  
QR codes generated using qrcodejs library with Level H error correction (30% redundancy).  
Platform logos embedded using SVG data URIs.  
Works offline after first load.

## Browser Compatibility

Works in all modern browsers:
- **Desktop:** Chrome, Firefox, Safari, Edge
- **Mobile:** Chrome (Android), Safari (iOS)

Share button uses native Web Share API (mobile-friendly).

## Contributing

Found a bug? Have an idea? Open an issue or submit a pull request!

This project is free and open source - built to help, not to profit.

## License

MIT License - Use it, modify it, share it.

---

*Part of the Ignatius-42 collection: simple, honest tools that respect users.*

Built with the belief that software should serve users, not exploit them.
