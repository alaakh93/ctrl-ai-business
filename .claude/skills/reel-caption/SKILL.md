---
name: reel-caption
description: Turn a reel script into an Instagram caption in Alaa's fixed CTRL + AI caption format (comment-keyword hook, problem line, what it does, "Think of it like...", three "No more..." lines, credit line, hashtags). Use whenever the user pastes or points to a reel script, video script or voiceover and wants a caption, or says "write the caption", "caption for this reel", "IG caption", "post copy", even if they don't say "reel-caption".
---

# Reel caption

Alaa posts a reel and writes a caption in the same shape every time. The three real captions are in `references/` (`seo.md`, `hallmark.md`, `commercial.md`). Read all three before writing: the format is easiest to hit by matching them, not by following a description. The rules below explain what they have in common.

## Input

A reel script (pasted, or a file path). From it, pull out: the topic or tool, what it does, who it's for, any numbers, license, creator or repo link, and any disclaimer-worthy facts (for example a made-up product or a generic example shown on screen).

## Output structure

Plain text, ready to paste into Instagram. Blocks are separated by one blank line, in this order:

1. **Comment hook (one line).** `Comment "KEYWORD" and I'll send you [the free thing], plus the exact [prompt / command / prompts].` The keyword is one uppercase word naming the topic (SEO, HALLMARK, COMMERCIAL). Use the plain form `and I'll send you the free setup and the exact prompts` when there is no install step.
2. **Hook/problem (2 to 3 short lines).** A statement that stings or surprises the viewer, then one or two lines of concrete detail. Write to the viewer this reel is for and use their situation (a business owner's website, ads and customers; a creator's content; a beginner's first project).
3. **What it is and what it does.** Name the thing, say it's free if it is, and credit who built it. Then one line per capability, each its own line, no bullets, each starting with a verb or "It". About 3 to 5 lines. Use only facts and numbers from the script.
4. **Analogy (one line).** `Think of it like [a person or role] who [has already done the hard part].`
5. **Three "No more..." lines.** Each on its own line, each a pain the viewer has now. Three is the default. A short extra line may follow if the script needs it (for example, "It still covers the normal Google basics too: ...").
6. **Credit / disclosure line.** Whatever the script requires: repo and license (`Repo: github.com/owner/name (MIT)`), a note that a product or example is made up, music and tool credits. Wrap a disclaimer in parentheses when it explains something shown in the video. Skip the line only if the script has nothing to credit or disclose.
7. **Hashtags (one line).** Five tags that fit this reel's topic. Start with `#ai`, then use the tool and topic tags the reel is actually about (`#claude`, `#claudecode`, `#seo`, `#webdesign`, `#blender`). Add `#smallbusiness` only when the reel is aimed at business owners (their website, ads, customers, sales). For other audiences, such as creators, beginners, developers or general AI tips, use a tag that fits them instead (for example `#contentcreator`, `#aitools`, `#automation`). Don't add a tag just to fill the slot.
8. **DM block (only when needed).** If the comment hook promises an install line or exact prompts, add a `---` divider and then `DM (send after the comment):` followed by the actual message the DM automation will send: repo, install command in backticks, example commands. End it with a parenthetical note on prerequisites and a reminder to verify commands the day it goes out. Leave this block out when the hook promises nothing that needs a DM, or when the script doesn't contain the commands.

## Style

- Short sentences. One idea per line. Line breaks do the work that bullets would.
- Plain, spoken, specific. No emojis, no em dashes, no hype words like "game-changer" or "revolutionary".
- Straight quotes. Write the keyword in capitals inside the quotes.
- Second person ("you", "your"), first person only for what Alaa did or will send ("I'll send you").
- Match the length of the examples. The captions run roughly 100 to 170 words before the DM block. Don't pad.

## Don't invent facts

Counts (26 skills, fifty themes), licenses, creator names, repo URLs, install commands and music credits appear in the captions only because they were in the video. Take them from the script. If the hook needs a keyword, pick one from the topic and say which you chose. If something required is missing (no source link for a tool, no commands for the DM), leave a clearly marked `[MISSING: ...]` placeholder and mention it after the caption, rather than guessing.

## Reply format

Give the caption in a single code block so it copies cleanly, then at most two short lines of notes (the keyword you chose, anything marked MISSING, anything the creator should verify). Don't explain the format back to the user.
