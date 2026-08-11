# The Fitness Studio Health Check

A campaign concept for [bsport](https://pro.bsport.io), built around the research in their Fitness Studio Playbook.

## Live pages

| | |
|---|---|
| **Landing page and quiz** | https://jo-nikolic.github.io/bsport-studio-health-check/ |
| **Campaign assets** | https://jo-nikolic.github.io/bsport-studio-health-check/assets/ |

## The idea

bsport's strongest converting segment is studios adopting management software for the first time — owners who are running on spreadsheets, messages and memory. That audience doesn't respond well to a product pitch, but they do respond to being told, specifically, what's costing them money.

So the campaign leads with a diagnostic instead of a demo.

Thirteen questions, about two minutes, and the studio owner gets told which of four places they're losing members:

1. **The front door** — people find them, then hit a form, a DM, or a third-party app
2. **The second visit** — a good first class, no follow-up, and they quietly never return
3. **The timetable** — a waitlist on Thursday, four people on Tuesday
4. **The revenue ceiling** — full classes, flat revenue, one thing to buy

The result is useful on its own, which is what earns the email address. It also gives sales real context before the first conversation, and segments the contact into one of four nurture tracks automatically.

## What's in this repo

```
index.html          Landing page and quiz — questions, scoring, results screen
assets/index.html   Campaign creative — organic social, paid, retargeting, emails
```

Both are single self-contained files. No framework, no build step, no dependencies beyond a webfont.

## How the quiz works

Four profile questions set context and lead scoring. Eight diagnostic questions score against the four archetypes, two questions each. A final question captures intent.

Each archetype is scored as a percentage of its own maximum, so no category is favoured by having more questions attached to it. Where two tie, the earlier stage of the member journey wins — there's little point fixing pricing if people can't book you at 9pm.

Anyone signalling they're actively comparing systems skips the nurture sequence and gets a booking link instead.

## Notes

- This is an unsolicited concept prototype. It isn't affiliated with, commissioned by, or endorsed by bsport.
- Scoring runs entirely in the browser. The email capture and booking buttons are not connected to a backend — this demonstrates the flow, it doesn't operate it.
- All statistics are drawn from bsport's Fitness Studio Playbook, a survey of 550 boutique fitness members across the UK, France, Germany, and the US.
- Photography and brand assets belong to bsport.

---

Built by **Jovana Nikolic**
