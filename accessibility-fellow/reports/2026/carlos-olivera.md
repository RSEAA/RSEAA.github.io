---
layout: default
title: RSAA26 Accessibility Fellowship Report - Carlos Andres Olivera Caballero
permalink: /accessibility-fellow/reports/2026/carlos-olivera
navigation_weight: 4
---

## What We Promised, What Happened

An email thread that started three days before three conferences opened, and kept going after they closed. This is what got promised, what actually happened, and what I lived through myself.

Carlos Olivera · Accessibility Fellow, RSLA26 · First part written August 24, 2026 · Updated September 2, 2026

## Nobody assigned me anything

Equersa is the umbrella joining three sister conferences this year (Research Software Asia Australia, Research Software Africa, and, for the first time, Research Software Latinoamérica) under one volunteer committee of forty-five people across nineteen countries. All three ran August 25 through 28. I came in as RSLA26's accessibility fellow: my job, according to the form I filled out in June, is to help hold the committee accountable for how accessible their own conference actually is.

The week before they opened, that job stopped being a line in a form and became an open email thread between fellows and the diversity and inclusion subcommittee, testing materials live with screen readers, mistakes included. On August 21, Equersa's organizer posted a file for the group to test. By the 23rd, five more documents were already being handed out among volunteers. I didn't take one. I read the whole thread, twice, and here is what I found: not another list of accessibility bugs (six people already had that covered), but a pattern in who gets found fast, who gets found late, and who nobody has mentioned yet. That was the first part of this piece.

## My experience

The organizer is right about something: up to this point, this piece has been about what other people lived through, not what I lived through. I followed all four RSLA26 sessions live, August 25 through 28, switching devices depending on the moment. It wasn't a perfect experience or a bad one: early on there were real difficulties in the chat, and in interpretation too (the live translation ran into trouble), enough to notice. After that, everything worked well for the rest of the conference.

It's the same pattern I found in the rest of the thread, just this time in my own region: what breaks live at the start, a chat that fails, an interpretation that can't keep pace, almost never shows up in the document review from the week before, because it hadn't happened yet. It either gets fixed on the fly, or it doesn't, and only someone inside the session, that day, finds out which. At RSLA26, it got fixed. Eleven days after all three conferences closed, I went back to the thread to see what actually held up, across all three regions and in my own.

## The thread, before it opened

Here's what happened, in order.

### Aug 21 — Setup — The first test

The organizer asks the group to open accessible-doc.html, Rob Moss's material for "GSRS-0073, Accessibility Awareness for Equersa presenters," with whatever screen reader they normally use.

### Aug 21 — Vision, NVDA — A Fellow opens NVDA

The document reads fine, but all eight headings are tagged Heading 1, flat, no hierarchy. They explain where the error comes from, without blaming anyone: the file started life as a Google Doc where every slide title was already H1, and that carried straight into the HTML.

### Aug 21 — Vision, NVDA — Another Fellow confirms

Same finding, also with NVDA. They're clear about something that matters: it didn't stop them from reading the document, but a real heading hierarchy would make it far easier to move between sections.

### Aug 21 — Vision, NVDA, ANDI, WCAG 2.4.7, WCAG 1.3.1 — Two more findings, with ANDI

Using NVDA and the ANDI tool, a third Fellow confirms what's working (a well-defined page title, strong contrast, descriptive links) and adds two new findings. One: a link with no visible text at all, sitting right under the author's byline, which a screen reader does announce but which a keyboard user sees as a blank patch of screen (WCAG 2.4.7: keyboard focus must always be visible). Two: they confirm the eight-H1 problem and hand over the exact fix, one H1 for the document title, everything else drops to H2 (WCAG 1.3.1: structure has to survive however the content gets presented).

### Aug 21 — Process — The organizer responds, no spin

There's no corporate hedge here. They explain they've been trying to recreate PowerPoint slides as web pages, which is why each "slide" got its own H1: a design choice, not an oversight, but still the wrong one. They show a different fix already tried on another document (each slide keeps its H1, but now reads "Slide X, \[title\]" for context), then open the floor: help review five more materials before the conference opens. The RSAA26 attendee, presenter, and session chair guide. The accessibility awareness presentation. The Zenodo community site. The RSAfrica26 website. The RSAA26 website.

### Aug 23 — Vision, ANDI, NVDA — RSAfrica26 gets reviewed

With ANDI and NVDA again, the same Fellow finds an empty link next to the logo, GitHub and LinkedIn icons with no accessible name (the screen reader only says "graphic," never where it leads), a linked logo with the alt text "image" instead of the organization's real name, date and schedule tables missing their row and column header markup, and a registration page that jumps straight from H1 to H3.

### Aug 23 — Hearing — The guide, reviewed from another angle

A Fellow from the diversity and inclusion subcommittee picks the attendee guide, but reviews it from something nobody else had covered yet: how clear it is for Deaf and hard of hearing readers, in captions, written Q&A, and communication protocols.

### Aug 23 — Vision, NVDA — The RSAA26 website, reviewed

Another Fellow takes the RSAA26 website and finds, among other things, an unlabeled graphic in the main banner.

### Aug 24 — Vision, VoiceOver, Orca — Confirmed, with different tools

Someone else confirms the heading hierarchy problem, testing it on two tools nobody else had reached for yet in this thread: VoiceOver and Orca.

### Aug 24 — Hearing, Zoom CC, Live Transcript — What had already happened before

Another member of the subcommittee isn't reviewing a new document. They're answering with what already happened at the previous edition: the human captioner on Zoom froze roughly every twenty minutes, forcing people to leave and rejoin, while the automatic captions held up better. They ask for clear instructions on turning on Zoom's live captions (CC) and its Live Transcript, clarify that the two are different (CC shows only what's being said right now, the full transcript scrolls back so you can catch what you missed), and add one more protocol: when someone asks a question out loud, the moderator should repeat that person's name and the full question before answering.

### Aug 24 — Wrap-up — The organizer closes, for now

They update the three guides they have time to fix. What's left, they say, will have to wait for during or after the conference, given the clock. The next step is already planned: record YouTube videos after the event to train the next round of attendees, chairs, and presenters.

## The thread, after it closed

All three conferences ended August 28. Here's what the same people said afterward, with nobody asking them to.

### ~Aug 27 — Access, Language — From inside the sessions

A Fellow writes after three days of conference: the chat worked well, the slides were clear, the shared links were easy to open. But on day three, Zoom kept disconnecting her for no obvious reason, taking about 30 seconds to rejoin each time, something that hadn't happened the first two days. And at the very start of the conference, live captions alternated between Arabic and English before settling into clear English.

### Aug 27, 4:24 am — Access — A Fellow can't get in

A Fellow in Africa writes that he tried the Zoom link all three days and always found the conference room empty. He tries again on the morning of day four.

### Aug 27, 5:33 am — Process — The organizer answers with a different link

They apologize and send a different Zoom link, valid for all four days, noting that the African conference is running right now. In other words: while that conference had already been live for three days, one of its own accessibility fellows hadn't been able to get in once.

### Aug 28, 2:06 am — Vision — All four days, reported

A Fellow attended RSAA26 all four days and describes a much steadier experience: the QR code and survey link shared right in the chat, her phone's "Describe Screen" feature narrating what was on the presenter's screen, plus presentations already shared in accessible format, and each day's session links re-sent by email instead of having to dig through old messages.

### Sept 2 — Reflection — A reflection, published

A Fellow announces she finished her fellowship report and published it as a web page, following a note the organizer left on Slack asking to prioritize personal stories over technical checklists. By her own description, she centered it on digital wellbeing, managing cognitive load, and how the team pivoted well around a connectivity glitch on day four. I tried to find the actual link to read it in full and couldn't: as of September 2, the committee's site still has no update past August 23, and there's no trace of that report on Zenodo or Figshare either. What I'm citing here is only what she describes in her own email, not the article itself.

## The gap map

This still isn't an official metric from the committee. It's the same reading as before, updated September 2 with what actually happened, axis by axis.

### Vision (blindness and low vision) — HIGH, AND CONFIRMED

A Fellow ran two redundant access channels through all four days of RSAA26 (her phone's screen reader narrating the presenter's screen, plus presentations already in accessible format) and got each day's session links by email. What got tested beforehand worked live.

### Hearing (Deaf and hard of hearing) — MEDIUM, NOW WITH EVIDENCE

RSAA26's live captions mixed Arabic and English at the start of the conference before settling, and nobody had rehearsed that opening beforehand. Combined with the Zoom disconnections on day three, and the chat and interpretation difficulties I lived through myself at the start of RSLA26, it's still the axis that reacts instead of anticipating.

### Language — THE WARNING CAME TRUE

It wasn't an abstract warning: captions mixing Arabic and English right as RSAA26 opened is real evidence that nobody checked that language crossover before the conference started.

### Live access — THE WORST OF ALL

This axis wasn't even on my first list. An accessibility fellow couldn't get into his own regional conference for three of four days, trying the same link every time. No document review the week before was ever going to catch this. Only someone testing the real link, on the real day, would have.

## What I think

### What actually worked

A forty-five person, unpaid committee across nineteen countries, testing its own mistakes in public two days before opening three conferences at once, already struck me as admirable before any of it started. Now I have proof that work actually held up live: a Fellow was able to follow all four days of RSAA26 with two accessibility channels running at once, and getting every link by email instead of hunting for it. That doesn't happen by accident, someone designed it that way on purpose.

### The promise that didn't land

But there's a part of this story that wasn't in my first piece, because it hadn't happened yet. On August 24, the organizer wrote in this same thread that they would "try to fix" what had been found on the RSAfrica26 site. Today, September 2, more than a week after the conference closed, I went back and checked that site's actual source code. None of it got fixed:

- The empty link next to the logo, and the GitHub and LinkedIn icons with no accessible name, are exactly the same.
- The ACCESS-NRI logo still has alt="image" instead of the organization's name.
- The registration page still jumps from H1 straight to H3, with no H2 in between.

I don't think this is bad faith. I think it's what happens when a fix gets promised in the busiest week of the year and nobody sets a date for it once the launch adrenaline wears off. The organizer's transparency in the thread was real, and it's rare to see. But being "held accountable" only means something if someone checks back after the urgency ends, and that's exactly the part this fellowship is still missing.

### The gap that came true

The two gaps I flagged before the conference opened didn't stay theoretical. Captions mixing Arabic and English right as RSAA26 opened is real evidence that nobody had checked that opening beforehand. And that Fellow in Africa's situation is even clearer: he couldn't get into his own regional conference for three of four days, trying the same link every time, while the conference was already running live. No document review, however good, was ever going to catch that, the same way something only I would have caught, however small, when my own conference's chat and interpretation stumbled at the start. I keep building JOPÓI in Bolivia on this same idea: a platform isn't accessible because the document describing it is well written, it's accessible when someone actually uses it and isn't left outside.

### What I'm asking for, again

Four things, each with evidence behind it now. First, someone from the committee should join every regional conference as if they were a brand-new person, the same public link, on the morning of day one, before any session starts, that's the only thing that would have caught both the access problem in RSAfrica26 and the chat and interpretation trouble I lived through myself at RSLA26 in time. Second, test the live captioning start with a short phrase before opening the floor to the public, not after someone is already hearing it in the wrong language. Third, the four findings still open on RSAfrica26 (the empty link, the unlabeled icons, the alt="image", the skipped heading) need an actual date and a named owner, not a loose promise in an email thread. And fourth, I've already done my part here: I checked whether RSLA26's own materials hold up in Spanish, Portuguese, and Guarani before that week was out, and all three languages checked out clean, nothing to fix. What I'm asking now is for that same check to become standard for the materials that run in English, starting with the ones already under review in this thread.

All three conferences have closed now. What we promised in that thread, before they opened, came true halfway: what the committee already knew how to test worked, for real, live. What nobody had tested before failed live, in all three regions, exactly where we said it would. I'm still watching, and this time the list of open items has a date on it.

## A note on accessibility

This page practices what it reports. One H1, everything else nests in real order, never for decoration. Keyboard focus is always visible, thick and colored, because the finding about the invisible link is the one that stuck with me the most. Nothing here depends on color alone, every tag carries its own word next to it. The "Listen" button uses your own browser's voice, nothing gets sent to a server. The text size and high contrast controls are saved only in this browser, nowhere else. And this page exists in Spanish and English, with the toggle at the top right, because language is an access barrier too, even though nobody else put it on the list this week.

The people who appear in this piece are accessibility fellows and members of Equersa's diversity and inclusion subcommittee. They're described by role rather than by name, at the committee's own request.

Sources: the email threads "Accessibility Awareness for Equersa presenters" (August 21-24) and its post-conference continuation (August 26 to September 2), among Equersa's accessibility fellows and steering committee; the public form and criteria for the 2026 Equersa Accessibility Fellowship; W3C's WCAG success criteria 2.4.7 and 1.3.1; and a direct review of research-software-africa.org's live source code performed September 2, 2026, to confirm the real status of those findings.
