# Keep Your Source Files in Google Drive

Companion to the [LinkedIn Content Partner project instructions](LinkedIn-Content-Partner-Project-Instructions.md) | By Crystal Jones

Your resume and career stories change. Keep them in one Google Drive folder and connect Drive to your AI. The AI reads your files straight from Drive, so it always works from your latest version, and you never re-upload anything.

## Set up your folder

1. **Create one folder.** In Google Drive, create a folder named something like "LinkedIn Content Sources."
2. **Save your sources as Google Docs.** Put these in the folder:
   - Your master resume
   - Your career stories
   - A short list of your target roles
   - A post inspiration list: one running Google Doc of articles, blog posts, and LinkedIn posts about your field. For articles and blog posts on the open web, save the link. For LinkedIn posts, LinkedIn articles, and anything behind a paywall, save the full text and the link, because your AI can't read those from a link. Over time, this list becomes a library of post ideas.
3. **Name files so you can find them fast.** For example: "Resume - Master," "Career Stories," "Target Roles," "Post Inspiration List."

## Connect Google Drive

Turn on the Google Drive connector in your AI:

- **Claude:** Settings > Connectors > Google Drive
- **ChatGPT:** Settings > Plugins > Google Drive
- **Gemini:** Settings > Personal Intelligence > Connected Apps > Google Drive

Sign in with the Google account that holds your folder and approve access.

## Point your project at the folder

In the [project instructions](LinkedIn-Content-Partner-Project-Instructions.md), replace the SOURCE MATERIAL section with this:

```text
SOURCE MATERIAL
My source files are in my Google Drive folder named [folder name]: my resume, my career stories, my target roles, and my post inspiration list. Read them from Drive every time you plan or draft, so you always use the latest version. My inspiration list has links to articles and blog posts, plus the full text of LinkedIn posts, LinkedIn articles, and paywalled articles, each with its link. When an entry is only a link, open it and read it. If you cannot read a link, tell me, and I will add the full text to my list. When I paste something into the chat and say "save this idea in your memory for a future post," remember it and include it when you plan my calendar. I will also add it to my inspiration list. Never invent results, numbers, employers, titles, or experiences. If a post needs a detail you do not have, ask me for it. Put anything you are unsure of in [brackets] so I can check it.
```

## Keep your files current

- **Edit in Drive, not in the AI.** Your Drive folder is the master copy.
- **Add to your inspiration list as you read.** Then ask: "Check my post inspiration list for new entries and give me 3 Point of view post ideas."
- **If the AI can't open a link, add the full text.** Your AI can read most links, but some sites block AI tools. The AI will tell you when it can't read one. Copy the article's text into your inspiration list under its link.
- **LinkedIn posts and articles need the full text.** Your AI can't read LinkedIn from a link, so copy the post or article into your inspiration list with its link. If you're mid-conversation, you can also paste it into the chat and say "Save this idea in your memory for a future post."
- **If a draft quotes old details, say so.** For example: "Re-read my resume in Drive. I updated it."

## Ground rules

- **Keep your career stories complete.** Don't strip anything out of your source files. The project instructions tell the AI to keep employers anonymous in your posts: no names, no industry, and no details that could identify them, unless you say it's okay to name the employer.
- **Use the Google account you'll keep.** If you connect a work or school account, you lose access to your files when you leave.
