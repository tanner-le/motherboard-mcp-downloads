# Motherboard for Claude Desktop

Motherboard is Shortscut’s video reference library. Use it in Claude Desktop to save a social post, find a reference for your next edit, or get timestamped feedback on a rough cut.

**[Download Motherboard 0.15.7 for Windows and Mac (.mcpb)](https://github.com/tanner-le/motherboard-mcp-downloads/releases/download/v0.15.7/Motherboard-0.15.7.mcpb)** · [Prerelease notes](https://github.com/tanner-le/motherboard-mcp-downloads/releases/tag/v0.15.7) · [Editor’s guide](EDITOR-GUIDE.md)

## Install

1. Download the `.mcpb` file above. In Claude Desktop, open **Settings → Desktop app** and select **Manage** next to **Extensions**.
2. Open **Advanced settings → Install Extension** and choose the downloaded file.
3. Select **Continue with Google** and sign in with your Shortscut work account. When you see **Connected to Claude**, open a new chat.

## Editor quickstart

Paste this into a new Claude Desktop chat to find a reference the team has already saved.

```text
Search our saved Motherboard library for up to three product demos
that show the result in the opening shot. Give me the Motherboard
link for each one and describe what the viewer sees first.
```

### What to try next

Paste the post link, creator handle, or script lines alongside your prompt. For footage on your computer, [share your export](#share-a-private-export) first.

| What you want to do | Ask Claude |
| --- | --- |
| **Save a social reference** | “Save this post to my Motherboard library. Break down the first 10 seconds shot by shot and link me to the saved video.” Paste a TikTok, Instagram, YouTube, or X link. |
| **Review a rough cut** | “When can a viewer first see what the product does? Give me two trims or shot swaps that would bring that moment forward, with timestamps.” |
| **Study pacing and sound** | “Walk me through the first 15 seconds of this reference. Which cuts land on a word, a beat, or a movement? Give me two ideas to try in my edit.” For a close listen, share a local copy of the reference first. |
| **Match B-roll to voiceover** | “For each script line below, find the matching moment in this screen recording. Give me the in and out times, and flag any shot I still need to record.” |
| **Research a creator** | “Find up to three posts from this creator on TikTok or Instagram that beat their usual views. Link each post and describe how it opens.” |

To keep a social reference with a project, include the name of an existing Motherboard board when you ask Claude to save it. For longer prompts you can copy, open the [editor’s guide](EDITOR-GUIDE.md).

### Share a private export

- **Windows.** Ask Claude “Analyze a video from my PC.” Choose one clip in the browser and click **Analyze selected video**.
- **Mac.** In the Motherboard extension settings, open **Configure → Connected folders** and add your exports folder. Give Claude the file path and ask it to analyze the cut.

The clip you choose goes to Shortscut’s Gemini service for analysis. Each local clip can be up to **30 minutes and 2,000 MiB**. Keep Claude Desktop open for the result and ask follow-up questions in the same chat.

### If you get stuck

- **Sign-in tab didn’t open?** Select **Open sign-in in this browser** on the setup page.
- **Windows file picker didn’t open?** Ask Claude “Give me the picker link for my current job.”
- **Still waiting on a clip?** Ask Claude “Check my current video job.”
