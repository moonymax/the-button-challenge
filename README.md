# The Button Challenge

> **Heads-up:** an AI assistant like Claude can build this in a matter of minutes.
> That is not the point. The goal is to **build your own capability**, not to have
> finished this challenge. Use AI to learn and to get unstuck, but make sure you
> understand every piece you ship.

## The challenge

Build a web page with **one button** and a **counter**.

- Everyone who opens the page sees the **same** button and the **same** counter.
- When someone presses the button, the counter goes up, for **everyone**.
- Each device can only count **once**. Pressing again from the same device does not
  raise the counter.
- The page is reachable for anyone through a **public link**.

That's it. Stack, language and hosting are your choice.

## Who it's for

Beginners. You don't need prior web or backend experience to attempt it.

## Success criteria

You can set this up in **less than an hour**:

1. You send someone the link.
2. They press the button on their device.
3. You see the counter go up on yours.
4. They press it again, and the counter does **not** go up.

## Hints

Stuck? Try these in order.

1. **Split up the problem.** Create the button first, so it counts on your own screen.
   Then make it so that other people interact with the "same" button: the count has to
   live somewhere all visitors share, not only in one browser.
2. **Make it available publicly via a link.** Put it online so someone else can open it
   from their own device.
3. **Make it count each device only once.** Find a way to recognise a device that has
   already pressed the button, and ignore its later presses.
