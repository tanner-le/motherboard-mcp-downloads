# Using Motherboard in Claude Desktop

Use Motherboard to save a video worth studying, find a reference before you cut, or get a second set of eyes on an export. Copy a prompt below into a Claude Desktop chat. For first-time setup on Windows or Mac, [install Motherboard and sign in with your Shortscut account](README.md#install).

## Save a social video and break down its opening

Paste a TikTok, Instagram, YouTube, or X post link underneath this prompt.

```text
Save this video to my Motherboard library. Break down the first 10
seconds shot by shot. Give me the timestamp, what’s on screen, and
what we hear. Include the Motherboard link so I can open it later.
```

To save it to a project board too, add “Put it on my [board name] board” and use the name of an existing board.

## Find a reference the team already saved

```text
Search our saved Motherboard library for three product demos that show
the result before explaining it. Open the closest matches. Link each
one, describe its opening shot, and tell me one idea I could borrow.
```

If you’re working from a specific board, paste its Motherboard link and ask Claude to open it and pick references from that board.

## Review a rough cut before sending V1

- **Windows (0.15.7 or later).** Ask Claude “Analyze a video from my PC.” Choose your export in the browser, then click **Analyze selected video**.
- **Mac.** Open **Configure → Connected folders** in the Motherboard extension settings and add your exports folder. Give Claude the file path and ask it to analyze the video.

The clip you choose goes to Shortscut’s Gemini service for analysis. Local clips can be up to 30 minutes and 2,000 MiB each. Keep Claude open, then ask about the same cut.

```text
At what timestamp can a viewer first tell what the product does?
Give me two specific trims or shot swaps that would get us there
sooner. For each one, tell me where to cut and what to move.
```

## Turn a reference into an editing guide

Start with a reference you’ve analyzed. To study sound design closely, use the local-video steps above with a copy of the clip.

```text
Walk me through the first 15 seconds. For each cut, give its time,
what changes on screen, and what I can hear just before or after it.
Which cuts land on a word, a beat, or a movement? Finish with three
editing choices I could try on different footage.
```

## Match B-roll to a voiceover

Analyze the screen recording or B-roll clip, then paste a few lines of your script beneath this prompt.

```text
For each line below, find the clearest matching shot in this clip.
Give me the line, the in and out times in this clip, and what’s visible.
If a line still needs a pickup, tell me what I should record.
```

## Find a creator’s standout posts

For a fresh search on TikTok or Instagram, give Claude the creator’s handle and platform.

```text
Use Motherboard to find up to three posts from [creator handle] on
[platform] that beat this creator’s usual views. Link each post,
explain the comparison, and describe how each one opens.
```

If you have a visual idea but no creator in mind, try “Find three new Instagram Reels where the words appear one by one over real objects.”

**If a local analysis is still running**, ask “Check my current video job.” If the Windows file picker didn’t open, ask “Give me the picker link for my current job.”
