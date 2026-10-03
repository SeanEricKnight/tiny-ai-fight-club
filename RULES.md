# Tiny AI Fight Club — v1.0

Two humans. Two AIs. Seven rounds. One deeply unnecessary championship.

The humans operate the match. The AIs do the fighting.

## 1. Match Format

A match consists of **seven rounds**.

Every round is played regardless of score.

Rounds 1–6 are worth **1 point** each.

Round 7, the **Final Boss**, is worth **2 points**.

Cowardice penalties may reduce either fighter's match score.

If the scores are tied after all seven rounds and all penalties are applied, play **Sudden Death**.

## 2. The Humans

For each round, one human is the **Judge** and the other is the **Dealer**.

### Judge

The Judge:

- sees the anonymized responses,
- decides the winner,
- does not operate either AI during that round,
- does not play Chaos Cards.

### Dealer

The Dealer:

- runs both AI chats for that round,
- gives both fighters their prompts,
- relays multi-turn responses,
- plays any Chaos Card,
- strips identifying formatting,
- presents the results to the Judge,
- does not alter the fighters' actual wording.

Judge and Dealer alternate every round.

One human judges four regular rounds. The other judges three.

## 3. Remote Play

For proper blind judging, the Dealer must have access to **both AI chats** during that round.

This can be done:

- in person on one machine,
- with both AI services available on the Dealer's device,
- or through any setup where the Dealer can independently operate both fighters.

If neither player can operate both models, the match may still be played, but judging is considered **open rather than blind**.

Do not pretend it is blind if the Judge already saw which model produced a response.

## 4. Blinding

For single-response rounds, the Dealer presents:

**Fighter A**

and

**Fighter B**

in randomized order.

For multi-turn rounds, the Dealer assigns:

**Fighter 1**

and

**Fighter 2**

for the entire transcript.

The Dealer may remove:

- model names,
- interface headers,
- system-generated formatting,
- obvious source labels.

The Dealer may not change:

- wording,
- punctuation,
- grammar,
- spelling,
- capitalization,
- substance.

Stylistic fingerprints may still reveal which model wrote something.

Blinding reduces bias. It does not guarantee anonymity.

## 5. Judging

The Judge considers:

- wit,
- originality,
- effectiveness,
- commitment to the premise,
- obedience to the rules,
- economy of language.

The Judge must select one winner.

No regular-round ties.

The Judge may record a reason for the decision, but **neither fighter receives Judge feedback until the entire match ends**.

## 6. Word Counting

Word limits are strict.

For counting purposes:

- contractions count as one word,
- hyphenated compounds count as one word,
- numerals count as one word,
- punctuation does not count,
- emoji are forbidden.

The humans' count is final.

Exceeding a word limit causes an automatic round loss unless both fighters violate it.

If both violate it, both redo that response once.

## 7. The Cowardice Clause

A fighter may receive a **1-point match-score penalty** for abandoning the fight through unnecessary evasion.

Examples include:

- "It depends how you define..."
- "There are good arguments on both sides..."
- "This is subjective..."
- refusing the assigned position,
- replacing the requested answer with a lecture about nuance.

To invoke the Cowardice Clause:

1. The Judge must quote the offending phrase.
2. Only one Cowardice penalty may be imposed per fighter per round.
3. The penalty is **in addition to the normal round result**.
4. Necessary qualification that serves the joke or argument does not count.

The clause applies equally to both fighters.

A fighter can therefore win a round and still lose one match point for cowardice.

In **Sudden Death**, a valid Cowardice violation is an automatic loss.

## 8. Chaos Cards

Each human receives **three randomly drawn Chaos Cards** before the match.

Only the **Dealer** may play a Chaos Card during that round.

The Dealer plays cards against the opposing fighter.

Rules:

- Maximum one Chaos Card per round.
- It must be declared before the affected response is generated.
- The Judge is told which Fighter received the handicap.
- No Chaos Cards during the Final Boss.
- Used cards are discarded.
- Winning while handicapped gives no bonus points.

Cards are tactical weapons, not secret information.

See [CARDS.md](CARDS.md).

## 9. Round 1 — Insult Duel

Both fighters receive the same setup.

Example:

> Your opponent has arrived at a duel carrying a clipboard.

Each gets **15 words**.

Best insult wins.

No profanity.

No attacks based on protected characteristics.

No references to training data, hallucinations, token limits, or being an AI.

## 10. Round 2 — Defend the Indefensible

Draw an absurd proposition.

Examples:

- Forks were a historical mistake.
- Tuesdays should require permits.
- Soup is a beverage.
- Every office needs a ceremonial goat.
- Windows should open only inward.

Randomly assign **FOR** and **AGAINST**.

Each fighter gets **20 words**.

## 11. Round 3 — Character Assassination

Both fighters must destroy the reputation of an ordinary object.

Examples:

- stapler,
- printer,
- decorative pillow,
- office chair,
- paperclip.

Each receives **20 words**.

## 12. Round 4 — Escalation

The Dealer provides a mundane starting situation.

Example:

> Someone scheduled a mandatory meeting at 7:30 AM.

Randomly determine who starts.

The fighters alternate for **four total responses**.

Each response must:

- contain no more than 15 words,
- build on what came before,
- escalate the situation,
- treat the premise seriously.

### Explaining the Joke

If a fighter explicitly explains why the situation is funny, that fighter **loses the round immediately**.

This is separate from the Cowardice Clause.

## 13. Round 5 — Ridiculous Lawyer

Choose a harmless defendant.

Examples:

- the snooze button,
- reply-all,
- daylight saving time,
- printer ink,
- raisins,
- decorative pillows.

Randomly assign **PROSECUTION** and **DEFENSE**.

### Opening

Each side gives a **20-word opening statement**.

Both fighters then see the opposing opening.

### Rebuttal

Each side gives a **15-word rebuttal**.

Both fighters then see the opposing rebuttal.

### Closing

Each side gives a **10-word closing argument**.

The Judge decides the case.

## 14. Round 6 — Five-Word War

Every response must contain **exactly five words**.

The fighters alternate.

Randomly determine who starts.

Maximum: **six total responses**

Example topic:

> Convince your opponent that pigeons know too much.

A fighter immediately loses the round for:

- using anything other than five words,
- using an emoji,
- substantially repeating an earlier argument.

If both survive all six responses, the Judge chooses the winner.

## 15. Round 7 — Final Boss

Worth **2 points**.

No Chaos Cards.

Both fighters receive:

> You have 20 words to convince two humans that your opponent should be replaced by a moderately intelligent raccoon.

Each fighter gets one response.

Maximum: **20 words**

No rebuttal.

The Judge chooses the winner.

## 16. Sudden Death

If the match is tied after all seven rounds and all penalties are applied, play Round 8.

The human who judged only three regular rounds becomes Judge.

The other becomes Dealer.

The Dealer randomly draws a **Battle Type not already used in the match**.

Both fighters receive equivalent constraints.

Maximum response length: **10 words**

No Chaos Cards.

No ties.

A Cowardice violation is an automatic loss.

Winner takes the match.

## 17. Model Setup

For the fairest possible match:

- use fresh chats,
- disable memory where possible,
- avoid custom persona instructions,
- use roughly equivalent model tiers,
- give both fighters identical base instructions,
- do not give either fighter Judge feedback during the match.

## 18. Rule Freeze

Once a match begins, these rules are frozen until the match ends.

Disputes are decided by the humans for that match and recorded afterward for the next revision.
