<!--
TEMPLATE FILE -- not a real post.
This lives at the repo root (not inside content/), so Pelican never scans,
builds, or publishes it. Copy what you need into content/private-<slug>.md,
then delete this comment block and any fields/sections you don't use.

This is the Family & Friends (private) post template. It's a process
checklist as much as a YAML skeleton -- work through it top to bottom.
-->

Title:
Date:
Summary:
Category:
Tags:
Status: hidden
Save_as: private/<slug>/index.html
URL: private/<slug>/

<!--
FIELD NOTES

Title (required) -- plain text. Shows as the page heading.

Date (required) -- YYYY-MM-DD or YYYY-MM-DD HH:MM. If you skip this, Pelican
silently drops the post from the build with no error -- always double check
it built by looking for it on /private/ after pushing.

Summary (recommended) -- one or two sentences. Cheap to write now, useful
later (excerpts, feeds) even though nothing shows it prominently today.

Category / Tags -- optional, just for your own organization.

Status -- pick one:
  hidden     Real Family & Friends post, ready now. (default for this template)
  draft      Not ready -- needs review (e.g. a sign-off) before anyone but you
             sees it. Keep Save_as/URL below pointed at the FINAL destination
             even while draft, so the link you share doesn't change later.
             Flip to "hidden" (or "published") when it's approved -- nothing
             else needs to change.
  published  Only if this should go on the PUBLIC homepage instead of Family
             & Friends. If so, delete the Status/Save_as/URL lines entirely
             and let them default.

Save_as / URL -- REQUIRED for anything meant to be private, and they must
both point under private/<slug>/. Forgetting these is the one mistake that
actually matters: the post becomes merely unlisted, not gated by Cloudflare
Access, and anyone with the link could read it even without logging in.
-->

<!--
PHOTOS

Public photos  -> content/images/
                  ![Caption]({static}/images/filename.jpg)

Private photos -> content/private-<slug>-images/
                  ![Caption]({static}/private/<slug>/filename.jpg)
                  This keeps the image itself gated under /private/ along
                  with the post text -- an image pulled from content/images/
                  would leak publicly even inside an otherwise-private post.

No footer to add -- the "text or email me" contact line appends automatically
to anything whose URL starts with private/.
-->

## Before writing: mine for material

Check these for the date range this post covers:

- [ ] Google Photos -- what did we actually do, and with who
- [ ] Calendar -- events, trips, appointments, milestones you'd otherwise forget
- [ ] Location history / Google Maps timeline -- places that show up here but
      not in Photos or Calendar (day trips, new spots, errands worth a mention)

## Prompts -- pick a few, skip the rest

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
- What's something you thought about a lot this period that isn't captured
  anywhere else?
- Anything you'd want future-you -- or the kids, later -- to remember about
  this specific stretch of time?

## Draft

<!-- Write the actual post below this line. -->
