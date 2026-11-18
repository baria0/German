# The method

The fastest way to speak a language is not to study it like a school subject. It is to **use it every day, with feedback**, and to let grammar and vocabulary grow out of real communication. This repo is built on eight principles.

## 1. Speak from day one (output with feedback)

You learn to speak by speaking. Every session the main task is you producing German: telling, explaining, arguing, role-playing. Producing language forces you to notice what you cannot say yet ("the gap"), and the correction right after closes it.

## 2. Lots of understandable input (i+1)

Your brain acquires language from input you understand **almost** completely: about 90 to 95 percent known, the rest guessable from context. That is why the input in [RESOURCES.md](RESOURCES.md) is levelled (Super Easy German, Nicos Weg A2, nachrichtenleicht) and moves up as you improve. 20 to 30 minutes a day, every day, beats 3 hours on Sunday.

## 3. Chunks, not single words

Native speakers do not build sentences word by word. They combine ready-made pieces: *Das kommt darauf an*, *Ich hätte gern ...*, *Meiner Meinung nach ...*. We learn **whole phrases you will actually say**, with the grammar already inside them. Example: if you know *Ich wohne seit Mai 2024 in Darmstadt*, you already "know" the rule "seit + present tense" without studying it.

## 4. Retrieval and spaced repetition

Remembering something is what makes it stick, not re-reading it. So every session starts with a quiz on your own mistakes and phrases, and the deck in [vocab/chunks.tsv](vocab/chunks.tsv) goes into Anki, which shows each card just before you would forget it.

## 5. Grammar on demand

No grammar chapters in a fixed order. Each session picks the **one** grammar point your mistakes show you need most, explains it in a few lines and drills it right away. The plan has a "grammar spotlight" per week as a guide, but your mistakes have priority.

## 6. Mistakes are data

Every mistake goes into [MISTAKES.md](MISTAKES.md) with an ID. It comes back in later sessions until you get it right three times in three different sessions. Then it is retired. You will literally see your typical errors disappear.

## 7. Use Darmstadt

You live in Germany. That is free immersion that most learners pay for. Each week has a small **real life mission** (order only in German, make a phone call, write an email to the Studierendensekretariat). When people switch to English, say: *Sprich bitte Deutsch mit mir, ich lerne gerade.*

## 8. Consistency beats intensity

A daily 60 minutes for 5 months is about 150 hours, which is roughly what it takes to get from A2 to B1. Skipping kills progress more than anything else. On bad days do the minimum (10 minutes), but never zero.

---

## German and English at the same time: does it work?

**Short answer: yes, in this form.** Learning two new languages from zero at the same time is slow and confusing. But that is not your situation: your English is already strong, and your German is A2. So we are not learning two languages, we are **learning German through English** and polishing English as a side effect. That works well because:

- **English and German are close relatives** (both Germanic). Many words are similar (*Haus/house, Wasser/water, finden/find, Hand, Arm, Name*). English is a much better bridge to German than Turkish for vocabulary.
- Every explanation, translation and discussion about German happens in English, so you read and write English every day.
- Translating German into **natural** English (not word by word) is itself an advanced English exercise.

### How we do it

| What | Rule |
|---|---|
| Sessions | Run in German. Explanations and corrections in English. |
| Translations | Every correction gets a 🇬🇧 line. For texts and dialogues the English is folded away (see below): **try the German first, then check**. |
| English corner | 3 minutes per session: you translate a corrected German sentence into idiomatic English; Claude upgrades your English. |
| English mistakes | Logged in `MISTAKES.md` with category `EN`, recycled like German mistakes. |
| Ratio | About 80 percent German practice, 20 percent English work. German stays the priority. |

**Why folded English and not always visible?** If the English is right there, your eyes jump to the easy language and your brain skips the German. You remember more when you first struggle with the German, then reveal the translation. In session logs it looks like this:

> **Ich bin mir nicht sicher, ob ich morgen Zeit habe.**
> <details><summary>🇬🇧 English</summary>I'm not sure whether I'll have time tomorrow.</details>

### Watch out: interference

When two related languages live in your head, they leak into each other. The typical leaks for you:

| Leak | Wrong | Right |
|---|---|---|
| English "since" tense into German | *Ich habe seit 2024 in Darmstadt gewohnt.* | *Ich wohne seit 2024 in Darmstadt.* (present tense) |
| German tense into English | *I live in Darmstadt since 2024.* | *I have been living in Darmstadt since 2024.* |
| English word order into German | *Morgen ich gehe zur Uni.* | *Morgen gehe ich zur Uni.* (verb always in position 2) |
| German "bekommen" into English | *I will become a new job.* | *I will get a new job.* |

## False friends (German vs English)

| German | Means | Not |
|---|---|---|
| bekommen | to get, receive | to become (= werden) |
| also | so, therefore | also (= auch) |
| eventuell | possibly, maybe | eventually (= schließlich) |
| aktuell | current | actual (= tatsächlich) |
| das Gift | poison | gift (= das Geschenk) |
| der Chef | boss | chef (= der Koch) |
| sensibel | sensitive | sensible (= vernünftig) |
| fast | almost | fast (= schnell) |
| wer / wo | who / where | where / who (careful, they look swapped) |
| ich will | I want | I will (= ich werde) |
| das Handy | mobile phone | handy (= praktisch) |
| die Note | grade (at uni) | note (= die Notiz) |
| der Rat | advice | rat (= die Ratte) |
| konsequent | consistent | consequent |
| spenden | to donate | to spend (= ausgeben) |

## Your advantages as a Turkish speaker

You already have tools that English speakers do not.

| German feature | Turkish help |
|---|---|
| **Verb at the end** in subordinate clauses: *..., weil ich heute **arbeiten muss**.* | Turkish is verb-final: *çünkü bugün çalışmam gerekiyor.* The German Nebensatz feels natural to you. |
| **Akkusativ** (direct object): *Ich sehe **den** Mann.* | Like *belirtme hâli* `-(y)i`: *Adam**ı** görüyorum.* |
| **Dativ** (to whom, direction): *Ich gebe **dem** Mann das Buch.* | Like *yönelme hâli* `-(y)e`: *Adam**a** kitabı veriyorum.* |
| Location with Dativ: *in **der** Stadt* | Like *bulunma hâli* `-de`: *şehir**de*** |
| Sounds **ü, ö** | Same as Turkish ü, ö. |
| **sch, tsch** | Same as Turkish ş, ç: *Schule* ≈ "şule", *Deutsch* ≈ "doyç". |
| Separable verbs: *Ich **rufe** dich morgen **an**.* | Turkish also builds meaning at the end of the sentence. Think of the prefix as the "ending". |

**Your real challenges** (we will focus on these): grammatical gender (der/die/das, Turkish has none), articles in general, adjective endings, the two "ch" sounds (*ich* vs *ach*), the German "r", and V2 word order in main clauses.

**Tip for gender:** always learn nouns with their article and a colour in your head (der = blue, die = red, das = green). Never learn *Tisch*, always learn *der Tisch*.
