# GiftNudge: Spec

**Never miss a birthday, never panic-buy a gift** · #27 of 33 · Wave 3: Seasonal and episodic · Used: A few times a year · Very easy · Revenue potential: Medium · Plans, Trips & Occasions · Source: New (Claude)

## One-liner

A list of the people you buy for, their birthdays and anniversaries, and a running note of gift ideas for each person. It nudges you two weeks before, with your ideas and budget ready.

## Problem / audience

- **Who it's for:** Adults who buy for family, partners and friends, especially whoever in the household 'does the presents'.
- **The problem it solves:** Birthdays sneak up, gift ideas get forgotten, and last-minute gifts cost more.
- **Example:** In March a user notes that their sister mentioned a pottery class. In October GiftNudge reminds them two weeks before her birthday, idea and budget ready.

## MVP features (ship with only these)

1. People list with birthdays, anniversaries and other dates
2. Gift idea notes per person, captured year-round
3. Reminders 2 weeks and 2 days before (user-configurable)
4. Budget per person and per year, with a 'bought' tick
5. Christmas list mode

## Not in MVP

- Gift suggestions by age and interest (affiliate)
- Shared family gift lists to avoid duplicates
- Import birthdays from contacts

## Monetisation

| Model | Detail |
|---|---|
| Free | Up to 10 people, with ads |
| Premium | £1.49/month or £7.99 lifetime: unlimited people, shared lists, budgets |
| Affiliate | Gift ideas linking to retailers, clearly labelled |

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | A reminder before each date |
| Tiny win | Tick 'bought' or add an idea |
| Progress | Who's sorted this year |
| Share | Wishlists shared with family |
| Next step | After a birthday, prompt to jot ideas for next year |
| Cadence | Event-driven; Christmas peak |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Animation and tone: five signature animations

**Playful.** Celebrations, confetti, cute characters, satisfying sounds and mild comic reactions. Nothing tragic.

- Birthday approaching: the gift box shakes a little more each day
- Marked as bought: the ribbon unties itself into confetti
- Idea added: a lightbulb pops above the stickman's head
- Christmas list done: a tiny sleigh flies across
- Under budget: the piggy bank wears a party hat


## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app (needs notifications).
- **Data:** On the device only; shared lists need sync later.
- **Backend:** None for the free version: everything lives on the phone. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Gift ideas by person; Christmas planning; Thoughtful cheap gifts; Remembering dates
- **Shareable output:** Wishlists shared with family

## Risks

Long gaps between uses; Christmas is the main growth window. Contact import needs careful privacy wording.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to the Growth & Maintenance Engine as an app config
