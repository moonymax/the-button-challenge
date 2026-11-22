# The One-Button Challenge

> **Heads-up:** Claude can build this in a matter of minutes. So the goal is to
> **build your own capability**, not to have done this challenge. Don't let those
> minutes fool you: if you are a complete beginner, this can take you **several
> weeks**, and that is normal.

**Who it's for:** beginners.

## Your goal

Build a website that anyone in the world can open from a link. The page has one button and a number. When someone clicks the button, the number goes up by one, and everyone who visits sees the same number. Each browser can only add one click. If someone clicks again, their click is taken back and the number goes down by one. Clicking a third time adds it back, and so on, like a "like" button.

**Example:** You open the site and see "42." You click and it says "43." Your friend opens the link on their phone and also sees "43." They click, and now it's "44" for both of you. You click again, and it drops to "43," because your click was undone.

## Rules

- No AI tools: no ChatGPT, Claude, Copilot, or anything similar.
- No frameworks: only plain JavaScript, HTML and CSS.
- Google, YouTube, tutorials, and forums are all allowed.
- Visitors should not have to sign up or log in.
- It can be free. You shouldn't need to pay for anything.

## You've succeeded when

- You can send someone a link and it works on their device.
- The number is the same for everyone and survives closing the page.
- Clicking from the same browser switches between counted and not counted, so one browser can never add more than one, even after reloading or closing the page. A different browser (or a private window) may count as a new visitor; that is fine.

**Why aim for one hour?** Once you can build this in under an hour, you have a decent familiarity with the request–response model between a client and a server, and with basic DOM interactions. Modern frameworks like Next.js hide a lot of these details, but they also make it much, much easier to write real applications.

## Hints for the very beginners

**Split up the problem** into these steps:

1. **Create the button.**
2. **Make it so that other people interact with the "same" button.**
3. **Make it publicly accessible.**
4. **Make it count each browser only once.**
