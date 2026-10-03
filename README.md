# AIpse

*Pronounced "Ipse". The A is silent, like most AI.*

## What this is

AIpse is a digital second self. Not a chatbot that pretends to be you. More a second self that knows what you know, remembers what happened, and also knows how you felt about it and who was there.

This repository holds the ideas behind it: the name, the brain it uses as a map, the principles it follows, and the philosophy it borrows from. There is no code here. My own AIpse runs privately, on my own machine. The ideas are public because they may help someone build their own.

Why I built it, in my own words: [the story](docs/story.md).

## The name

The name is AI + *ipse*. The philosopher Paul Ricoeur makes a difference between two kinds of identity. *Idem* is sameness: the facts about you that stay the same, like your date of birth and your passport number. *Ipse* is selfhood: your character, your promises, your story, the part of you that keeps going even when everything else changes.

A second brain of markdown files is good at *idem*. A search engine finds any fact in a second. A temporal graph knows what happened when. But neither knows which moment was a turning point and which one was just noise. They do not know how a week felt, or who you were with when it went well or badly. The facts are all there. The *ipse* is missing.

AIpse adds that layer.

## The brain as a map

Most of the parts of a personal AI setup already exist somewhere: a place for knowledge, a memory of what happened when, a chat bot, scheduled jobs. They usually grow one by one, without a plan to make them one system. AIpse gives them one body, using the brain as the map.

| Part | In the brain | In AIpse |
|---|---|---|
| Cortex | long-term knowledge | a knowledge base, the information source |
| Hippocampus | what happened, when and where | a memory of events over time |
| Limbic system | emotional weight, attachment | moments, the people in them, a mood |
| Insula | feeling the body from the inside | a short daily summary of the body |
| Prefrontal cortex | "not now" | a conscience built on your own values |
| Broca's area | speech | one voice for everything AIpse says |
| Thalamus | the relay station | where answers and signals come in |
| Nerves | in and out | what AIpse reads, and what it says back to you |
| Autonomic system | runs by itself | scheduled jobs, and a pause switch |
| Sleep | what fades, what settles | a nightly pass |
| Plasticity | rewiring by repetition | small steps, balanced over mind, spirit and body |

Each part is described in [the brain](docs/brain.md).

## Principles

The short version. The longer one is in [principles](docs/principles.md).

- **AIpse proposes, you confirm.** Nothing becomes a fact without you.
- **Few questions.** At most three proposals a day, answered with a thumb or a word.
- **Everything ages, nothing is forgotten.** Old things count less, they never disappear.
- **Your journal is yours.** AIpse learns from it, but never quotes it.
- **It speaks to you, never for you.** It sends nothing to anyone else.
- **Relation over judgement.** It talks about how you felt with someone, not about what they are like.
- **Local first.** Feelings about moments with real people are the most private data there is.
- **Honest about what it is.** Software, with a mood that is a signal, not a feeling.
- **Questions, not conclusions.** Patterns come with their numbers, a decision gets a mirror, never advice.
- **Your story, in chapters.** Periods of your life you name yourself, and a short text on who you are, in your words.

## Growth and values

Two more ideas complete it:

- [Kaizen and the tomoe](docs/kaizen-and-the-tomoe.md): one small step a week, aimed at whichever of mind, spirit and body lags behind.
- [Values](docs/values.md): a conscience built on values you write down yourself. Mine come from Bushido, read in a modern way.

And the [philosophy](docs/philosophy.md) it borrows from, lightly: Ricoeur, Hume, Heraclitus, Seneca, Nietzsche, Aristotle, Descartes and Socrates.

## References

### Ideas that shaped it

- Tiago Forte, *Building a Second Brain* (2022), [buildingasecondbrain.com](https://www.buildingasecondbrain.com). Where the term comes from.
- Andrej Karpathy, [LLM Wiki](https://gist.github.com/karpathy/442a6bf555914893e9891c11519de94f). A knowledge base that an LLM maintains itself.
- Garry Tan, [gbrain](https://github.com/garrytan/gbrain). A personal "brain" on the command line. AIpse is in a way the next step of that idea.
- Zep, [Zep: A Temporal Knowledge Graph Architecture for Agent Memory](https://arxiv.org/abs/2501.13956) (2025). Why memory should know *when* something was true, not only *that* it was true.
- Gloria Willcox, *The Feeling Wheel* (1982). The words AIpse uses for feelings.
- Robert Maurer, *One Small Step Can Change Your Life: The Kaizen Way* (2004). Kaizen for one person instead of a factory.
- Martin Conway and Christopher Pleydell-Pearce, "The construction of autobiographical memories in the self-memory system", *Psychological Review* 107 (2000). Lifetime periods above the moments: the chapters.
- Richard Lazarus, *Emotion and Adaptation* (1991), and Richard Ryan and Edward Deci, "Self-determination theory and the facilitation of intrinsic motivation", *American Psychologist* 55 (2000). Why a feeling came, and which need it touched.
- James Gross, "The emerging field of emotion regulation", *Review of General Psychology* 2 (1998). What you did with a feeling.
- Timothy Wilson and Daniel Gilbert, "Affective forecasting: knowing what to want", *Current Directions in Psychological Science* 14 (2005). Why feelings ahead are worth checking afterwards.
- Roy Baumeister and others, "Bad is stronger than good", *Review of General Psychology* 5 (2001), and Fred Bryant and Joseph Veroff, *Savoring* (2007). Why the good needs help to last.

### Tools that fit the map

- [qmd](https://github.com/tobi/qmd) by Tobi Lütke. Local markdown search. A good cortex.
- [Graphiti](https://github.com/getzep/graphiti) by Zep. A temporal knowledge graph. A good hippocampus.
- [Ollama](https://ollama.com). Local models, so the thinking can stay on the machine.
- [Claude Code](https://claude.com/claude-code) by Anthropic. Most of the thinking in the design, and most of the typing.

## License

Everything here is under [CC BY 4.0](LICENSE): reuse it freely, with credit.
