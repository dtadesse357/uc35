# Skill: Figma Make to Code

## Purpose
Decision framework and execution instructions for when to
deliver a Figma Make site as-is versus rebuilding it as
clean HTML in Antigravity.

## Trigger
"convert figma to code for [client name]" or
"should I rebuild [client name] site"

---

## Step 1 — Run the Decision Check

Answer these questions:

| Question | Yes | No |
|---|---|---|
| Is this a Premium $799 package? | Rebuild | Can deliver as-is |
| Did client request code ownership? | Rebuild | Can deliver as-is |
| Does site need custom features? | Rebuild | Can deliver as-is |
| Is Figma Make output low quality? | Rebuild | Can deliver as-is |
| Does client need their own hosting? | Rebuild | Can deliver as-is |

If ANY answer is Rebuild → proceed to Step 2
If ALL answers are Can deliver as-is → deliver Figma Make version

---

## Step 2 — Extract From Figma Make

Before rebuilding, extract the following from the
Figma Make version:

- Exact color hex codes used
- All copy (headlines, body text, CTAs, form labels)
- Section order and structure
- Any unique layout decisions
- Client contact info as shown

Document all of this before writing a single line of code.

---

## Step 3 — Brief the Builder Agent

Activate builder.md with the following info:
- Client name and niche
- All extracted copy from Step 2
- Exact color hex codes
- Any special layout notes
- Delivery package tier

Tell the builder: "Match the Figma Make design as closely
as possible in clean single-file HTML."

---

## Step 4 — Quality Check

After build is complete:
- Open both the Figma Make version and the HTML version
  side by side
- Check that all sections match in order
- Check that copy matches exactly
- Check that colors match
- Check mobile responsiveness of HTML version
- Run deploy-checklist.md

---

## Step 5 — Deliver

- HTML version saved to
  ~/Documents/UC35/clients/[client-name]/index.html
- Deploy to Vercel
- Send live link to client
- Collect final 50% payment
- Pitch $75/month maintenance retainer

---

## When Figma Make Version Is Good Enough

For Starter and Standard packages where client does not
request code — the Figma Make live link can be the
final deliverable. In this case:

1. Refine the Figma Make output (copy, colors, content)
2. Publish the Figma Make site
3. Connect client domain if applicable
4. Deliver the live link
5. Collect final payment
6. Pitch retainer

This saves 4-6 hours of build time per project.
