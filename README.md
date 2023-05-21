# Boom.Army docs site

Running the hugo theme Doks.

## Commands

- `npm run start` (for dev)
- `npm run build`
- `npm run create -- --kind docs blog/build-diary-9`
- `npm run create blog/<name>/index.md`

## Doks docs

https://getdoks.org

## GPT Blog Post prompts

Get list of commits with `git log --since="7 days ago" --oneline`
Show lines added and removed with `git log --since="8 days ago" --numstat | awk 'NF==3 {plus+=$1; minus+=$2} END {printf("Lines added: %s\nLines removed: %s\n", plus, minus)}'`
Working command for blog post generation:

```
Make a blog post out for a developer diary to update a community of software users based on the following list of commits. The list of commits is from a single developer and he is addressing the community personally. Don't include references to the commit hashes and write in the context of an update on delivery that will be released in a few weeks all at once but isn't available as of today.
```

For tone and style:
`Rewrite this markdown blog post in the style of Hunter S Thompson Gonzo journalism writing for Rolling Stone magazine:`

Once ready output to markdown:

`Turn this post into markdown and output in a code block:`