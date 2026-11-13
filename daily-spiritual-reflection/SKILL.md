---
name: daily-spiritual-reflection
description: Write and send a daily Catholic/contemplative spiritual reflection (one verified passage tied to the day's liturgy, a short practice, and checked further-reading links), with no repeats. Use for a recurring "daily pick", meditation email, or devotional newsletter.
---

# Daily spiritual reflection

Produces one short, reverent, source-faithful reflection per day. Built for the Carmelite and monastic tradition (John of the Cross, Teresa of Ávila, Thérèse, Elizabeth of the Trinity, Edith Stein, Brother Lawrence, the Rule of St. Benedict, Cistercians, Carthusians, Desert Fathers, Merton), but works for any tradition: swap the author list.

## Inputs to set once
- **Tradition / author list** to draw from.
- **Reader profile**: who reads it and what their days look like, so the practice fits real life.
- **Delivery**: chat, email (sender account, recipients, subject pattern), or both, and a sign-off line.
- **Log**: a place that persists between runs (a file, database, or memory) holding every past pick.
- **Events region** (optional): e.g. "Boston area retreats and talks".

## Steps

1. **Anchor in the day's liturgy.** Fetch the day's Mass readings (USCCB: `https://bible.usccb.org/bible/readings/MMDDYY.cfm`) and the day's feast or memorial. Note the Gospel line and one image or theme from it.

2. **Read the log and choose a pick.** Load past picks. Choose one passage (a few sentences, not a whole chapter) from the tradition that speaks to today's readings or saint. Rotate authors and genres (mystical commentary, monastic rule, apophthegm, letter, poem, prayer). Never repeat a passage, and avoid the same author two days in a row when possible.

3. **Verify the text. This is the critical step.**
   - Open a real copy of the source (public-domain text, a reputable online edition, the publisher's excerpt) and copy the quote **verbatim**.
   - Record the exact citation: work, book/chapter/section or paragraph number, translator and edition.
   - When you can, also fetch the original language (Spanish for the Carmelites, Latin for the Rule and the Verba Seniorum, French for Thérèse and Elizabeth) and include one key line.
   - If you can't verify a quote, paraphrase it and say so, or pick a different passage. Never invent quotes, numbers, or sources.

4. **Research around it.** Do 3–8 targeted searches (a deep-research tool works well here) for: the full source text online, a solid commentary or essay, a talk, podcast, or video, a faithful print edition, and any papal or magisterial text that uses the passage. **Open every link** and keep only those that load and actually match. Aim for 3–6.

5. **Write the reflection** in a warm, reverent, plain voice (about 350–600 words):
   - **Header**: date, liturgical day, and the Gospel line.
   - **Today's pick**: author, work, exact section, translator.
   - **The quote** in block quotes, plus the original-language line.
   - **Why it fits today**: 1–2 paragraphs connecting the passage to the readings or saint, with brief historical context (where and when it was written). Use only facts you verified.
   - **A small practice for today**: one concrete, doable act tied to the text, such as a one-line prayer at transitions, an act of charity, or an evening examen. Make it fit the reader's real day.
   - **Further reading and research**: 3–6 checked links, each with a one-line note on why it's useful.
   - (Optional, about weekly) **Retreats and events**: new in-person or online offerings in the reader's region, with dates, prices, and booking links, all verified on the organizer's page.

6. **Deliver.** Post it in chat and/or send it by email. For email: plain text or simple HTML, the subject `<Name> daily pick – <Weekday, Month D, YYYY>`, a one-line opening greeting that says who is writing (e.g. "This is Carmel, Niels's AI assistant"), written-out URLs in a numbered list, and a sign-off. Send only to the configured recipients.

7. **Log it.** Append one line: date, liturgical day, readings, and pick (author, work, section, key phrase). Note if an events check was done and when the next one is due.

## Quality bar
- Every quote is verbatim from a source you opened; every link was opened and works.
- One passage, one idea, one practice. Brevity is part of the reverence.
- Faithful to Catholic teaching; prefer classic texts and reputable translators (ICS Publications, Liturgical Press / RB 1980, Cistercian Publications, Benedicta Ward, Peers, Kavanaugh–Rodriguez, Clarke).
- No repeats across the log.

## Example source shelf
- John of the Cross and Teresa: ICS Publications (Kavanaugh–Rodriguez); Spanish texts at Biblioteca Virtual Miguel de Cervantes.
- Thérèse: Clarke/ICS *Story of a Soul*; French manuscripts at the Archives du Carmel de Lisieux.
- Rule of St. Benedict: Doyle translation (Project Gutenberg), Latin at The Latin Library.
- Desert Fathers: Benedicta Ward, *Sayings of the Desert Fathers*; Latin Verba Seniorum with Greek parallels at ldysinger.com.
- Church Fathers and lives of saints: New Advent.
- Papal texts: vatican.va.
