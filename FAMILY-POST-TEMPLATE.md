<!--
TEMPLATE FILE -- not a real post.
This lives at the repo root (not inside content/), so Pelican never scans,
builds, or publishes it. Copy what you need into content/private-<slug>.md,
then delete this comment block and any fields/sections you don't use.

This is the Family & Friends (private) post template. Everything
instructional below lives in ONE HTML comment, all the way down to
"END TEMPLATE NOTES". Comments never render -- in GitHub's preview or on
the live Pelican site -- so even if you forget to delete this whole block
before publishing, nothing leaks into the post. Only the front matter
above and whatever you type after the block ends will show.
-->

Title:
Date:
Summary:
Category:
Tags:
Status: hidden
Save_as: private/<slug>.html
URL: private/<slug>.html

<!--
====================================================================
FIELD NOTES
====================================================================
Title (required) -- plain text. Shows as the page heading.

Date (required) -- YYYY-MM-DD or YYYY-MM-DD HH:MM. If you skip this,
Pelican silently drops the post from the build with no error -- always
double check it built by looking for it on /private/ after pushing.

Summary (recommended) -- one or two sentences. Cheap to write now, useful
later on any listing page.

Category / Tags (optional) -- only matters if you actually browse by
these; skip if you don't.

Status -- decide before writing:
  hidden    -- a real Family & Friends post. Gated by Cloudflare Access
              (via Save_as/URL under private/) but not gated by Pelican
              itself; needs Save_as/URL set below.
  draft     -- not ready. Builds to a URL under drafts/ that isn't linked
              from anywhere. Use this + a stable Save_as/URL to share a
              preview link (e.g. for Kerin to sign off) before publishing.
  published -- a normal PUBLIC post, not Family & Friends. If so, delete
              the Status/Save_as/URL lines entirely and let them default.

Save_as / URL -- REQUIRED for anything meant to be private, and they must
both point under private/. Forgetting these is the one mistake that
actually matters: the post becomes merely unlisted, not gated by
Cloudflare Access, and anyone with the link could read it even without
logging in.

====================================================================
PHOTOS
====================================================================
The storage folder and the {static} reference path must match EXACTLY --
Pelican's {static} link resolves directly to a file's path relative to
content/.

Public photo:
  store at:     content/images/filename.jpg
  reference as: ![Caption]({static}/images/filename.jpg)

Private photo (must be under private/ to actually be gated):
  store at:     content/private/<slug>/filename.jpg
  reference as: ![Caption]({static}/private/<slug>/filename.jpg)

====================================================================
FORMATTING CHEAT SHEET -- reference only, none of this needs to survive
====================================================================
# Heading 1
## Heading 2
### Heading 3

**bold**, *italic*, and `inline code`

- bullet
- points

1. numbered
2. list

> A blockquote.

Fenced code block (three backticks alone on a line, then code, then three
backticks alone on a line again):
    ```
    like this
    ```

[External link](https://example.com)
Link to another post on this site: [see this other post]({filename}/other-post.md)

Public photo:  ![Caption]({static}/images/filename.jpg)
Private photo: ![Caption]({static}/private/<slug>/filename.jpg)

Horizontal rule (three dashes alone on a line):
    ---

====================================================================
BEFORE WRITING: MINE FOR MATERIAL
====================================================================
Check these for the date range this post covers:
- [ ] Google Photos -- what did we actually do, and with who
- [ ] Calendar -- events, trips, appointments, milestones you'd otherwise
      forget
- [ ] Location history / Google Maps timeline -- places that show up here
      but not in Photos or Calendar (day trips, new spots, errands worth
      a mention)

====================================================================
PROMPTS -- pick a few, skip the rest
====================================================================
Don't just narrate the photos. Pick 2-4 of these and actually answer them:

Kids
- New skill, word, or habit either kid picked up this period?
- What's made them laugh lately, or what are they obsessed with right now?
- Any milestone worth recording even if there's no photo of it?

Work
- What shipped, changed, or got hard?
- Anything you're proud of, stressed about, or seeing differently?

House / home
- Projects finished, started, or still stalled?
- Anything that changed about how the house, yard, or neighborhood feels?

Life / you
- What's something you thought about a lot this period that isn't
  captured anywhere else?
- Anything you'd want future-you -- or the kids, later -- to remember
  about this specific stretch of time?

====================================================================
END TEMPLATE NOTES -- delete this entire comment block, then write the
real post below.
====================================================================
-->
