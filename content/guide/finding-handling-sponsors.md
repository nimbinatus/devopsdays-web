+++
weight = 15
date = "2023-11-06T23:40:47-06:00"
title = "Finding and Handling Sponsors"
aliases = []
+++

---

## Finding/Handling Sponsors

Sponsors pay the bills. You rely on them. So what can you do to find them and keep them satisfied?

- post on social media such as LinkedIn.
- find local meetups/companies that can help you.
- if you're looking for a contact of a specific company that sponsored before, ping the devopsdays core organizers to see if they can help.
- talk to the other organizers on Slack - many of them work at sponsors!
- write a blog on the website to promote your event.

Sponsors will usually ask you the following; best to have this information ready.

- Projected number of attendees
- Industries/Companies represented (share only in aggregate)
- What they get with what level of sponsorship (refer them to your sponsor page or prospectus)
- If they can buy a speaker spot (NO, but they can submit a talk and they can suggest open space topics onsite)
- If you provide a badge-scanning mechanism (you’re not obligated to, and we do not recommend providing one. For more information see the [QR codes section](#qr-codes-and-badge-scanning) below.)
- If they will have electricity & network at the venue (you should make sure the answer here is yes)
- If they can get a monitor (let them bring their own or rent one themselves)
- Where to ship their stuff and pick it up (don't take responsibility and let them handle that directly with the venue)
- What size of table they have? (find out from the venue and say they have to fit behind the one table)
- Where their table will be located (produce a map and optionally let them choose in the order they signed up)

From experience, we found that it helps to have a dedicated local organizer or two act as the contact with the sponsors to track prospects, payment, and giving them discount codes.

When they sponsor they need to supply:

- a logo for the website & a URL to link it to (if they're a new sponsor)
- an email address of a contact you can reach
- a Twitter handle for you to thank (very optional)
- the invoice details (including VAT in Europe)

In return you'll :

- send the official invoice (as applicable)
- once payment has been received, provide the registration discount code
- put the logo online (adding it if it's new) once they've paid
- link this sponsor from your page on the website once they've paid

On the registration page, have them select the special sponsor ticket with their discount. Many of the sponsor contacts are traveling from event to event, so you may have to follow up with them a bit so they sign up their crew in time for your badge printing. Make sure you make the invoices "due on receipt" or provide Paypal links so sponsors don't wait months to pay you.

### QR Codes and badge scanning

Sponsors will often ask if attendee badges can be scanned. Using QR codes to receive attendee information is quick and efficient for sponsors, but can be problematic for organizers and raise privacy concerns from attendees. We strongly discourage you from using scannable badges at your event.

There are two primary methods of badge scanning:

The first and most common method used by conferences is to have badges with codes that simply store a UUID. When sponsors scan badges with the designated app, they get the UUID. Later these are given to the organizers and used to generate a list of contacts. Many conferences use this because it protects attendee data and it also forces sponsors to use specific software or devices for an additional cost (more revenue for the event). However, this practice violates one of our DevOpsDays [rules](#essential-rules-for-organizing): we do NOT ever give out or sell lists with contact details of attendees.

The second method is to encode attendee data directly into the QR code (e.g., using the common VCF format). This method does not require organizers to distribute attendee information and allows sponsors to receive the information directly. But it also means that anyone with a QR code scanner can get that information and organizers will need to be extremely cautious that attendee information is not shared without their consent. Should you choose to implement this, the following are required:

- Attendees must be informed that their information will be encoded, including which details (email, phone, etc) will be included.
- Attendees must be informed of and provided a method to opt-out. This could be done during registration and QR codes not printed on the badges of those who opt out, or you could provide stickers to cover QR codes.
- Sponsors must be informed that badges may only be scanned with consent from attendees, and you must enforce this in practice.

Additionally, we recommend that QR codes be printed on the back side of badges and that badges have two points of contact with lanyards to help ensure that QR codes are only visible when an attendee shares it.

Even with the [rules](#essential-rules-for-organizing) and guidance above, we strongly discourage the use of scannable badges.

---
