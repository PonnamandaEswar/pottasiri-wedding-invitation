# Pottasiri Family — Bride-side Wedding Invitation

A separate, mobile-first static invitation for Sai Prasanna and Mohan. It reuses the couple photo and blessing artwork from the groom-side site, presents Sai Prasanna first, and invites guests on behalf of Sri Pottasiri Srinivasa Rao and Smt. Nagendra.

## Bride-side RSVP

The RSVP form opens WhatsApp to **+91 99895 83370** with the guest's name, attendance choice, guest count, and optional message. The guest must tap **Send** in WhatsApp. The site does not store RSVP submissions.

## Add the bride-side music

Copy your own MP3 file into this folder beside `index.html`, and name it exactly `wedding-music.mp3`. The invitation attempts to start the song when a guest taps **Open Invitation**. Mobile browsers generally block audible autoplay before a user gesture, so sound cannot be guaranteed before that tap.

## Publish as a separate Netlify site

1. Add `wedding-music.mp3` to this folder before publishing.
2. Sign in to Netlify and create a new project using drag-and-drop/manual deploy. Upload this whole folder (with `index.html`, `images/`, and `wedding-music.mp3`).
3. Rename the Netlify project to a name such as `pottasiri-wedding` if available. Its default link will look like `https://pottasiri-wedding.netlify.app`.

The invitation details are from the bride-side card: Saturday, 21 November 2026; Sumuhurtham 08:52 PM, Mithuna Lagnam; dinner from 07:30 PM; Sri Balaji Grand Convention Center, Beeramguda, Hyderabad.
