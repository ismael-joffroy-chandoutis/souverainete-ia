# 01. State of play: the four layers of dependence

[← Back to index](../README.en.md)

Sovereignty in artificial intelligence is not an object. It is not "a model" that you either own or do not. It is a stack, a chain of layers piled on top of one another, and each one has its owner, its geography, its vulnerability. To know where Europe is free and where it is captive, you have to break this chain apart and ask, at each level, two simple questions: who makes the rules, and who can cut off access?

We will go through them from the most reversible layer to the most locked-in. The order is not a detail: it is the heart of the analysis. Where the lock is weak, Europe has levers. Where it is physical, no political will loosens it in the short term.

---

## Layer 4 (the most reversible): Models and software

This is where everyone always looks, and this is where the dependence matters least.

As of 14 June 2026, no European model sits at the global frontier. The top of the table is held by Claude, GPT-5.5 and Gemini 3.1. Mistral, the European champion, has raised on the order of 4 billion dollars in total, compared to roughly 186 billion for OpenAI and 161 billion for Anthropic. The capital gap is a factor of fifty.

But this lag is largely a false problem, and it has to be stated precisely so as not to fight the wrong battle. First because the model layer is becoming a commodity: distillation, mixture of experts, quantization and publicly available training recipes shrink the gap with the frontier to roughly ten points and three to six months, while the cost per token falls by a factor of ten per year. The proof in reverse is legal: lacking any durable technical barrier, the United States now defends its lead through the law. Second because the raw measure is misleading: Mistral Large 3 posts 43.9% on the GPQA Diamond reasoning benchmark, but in standard mode, with reasoning switched off; its reasoning variants close most of the gap. Mistral, for that matter, does not compare itself to the closed American models but to its open peers, DeepSeek or Kimi.

The real lever of this layer is open weights. Mistral's models are released under the free Apache 2.0 license: you can inspect them, fine-tune them, run them offline, air-gapped. That is a real sovereignty of use, and it is precisely what makes you immune to a remote API cutoff, like the one that hit Fable on 12 June. The French armed forces saw this clearly: a framework agreement signed on 8 January 2026 deploys Mistral in an isolated environment, with data excluded from training.

Two caveats, however. The first: global open weights are dominated by China, not by Europe (DeepSeek and Qwen monopolize the open rankings). The second, deeper one: this software sovereignty never gets past the hardware wall of the layers below. A free model still runs on Nvidia GPUs, through the proprietary CUDA software, etched in Taiwan. Worse, the dependence is circular: ASML, the European monopolist of lithography machines, became in September 2025 the leading shareholder of Mistral, which is also taking on 830 million euros of debt to buy Nvidia chips. The champion of European sovereignty deepens American dependence at the very moment it embodies it.

---

## Layer 3: Compute and electricity

Europe accounts for around 5% of global AI compute, against 70 to 80% for the United States and 11% for China, and that share has been falling since the start of 2025.

But the real bottleneck is no longer capital. The private money exists (more than 200 billion euros of stated interest). What is blocking things is **connection to the electricity grid**: seven to thirteen years of queueing on average across the major European hubs, for industrial electricity roughly twice as expensive as in the United States. Denmark proved this brutally in May 2026: its grid operator had to impose a three-month moratorium on new connections, with 60 GW of pending requests against a national peak of 7 GW. Even the cleanest grid in Europe saturates.

This is where French nuclear power gets cited as a sovereign asset, and you have to be precise so as not to lie. Yes, the French grid is among the least carbon-intensive in the world, around 6 gCO2 per kWh. But "low carbon intensity" does not mean "clean" or "sovereign":

- it is not clean: high-level waste dangerous for tens of thousands of years, with no operational deep geological storage;
- it is not fully sovereign: uranium is imported at close to 100%, notably from Niger and Kazakhstan, with an openly acknowledged neo-colonial dimension;
- it is not climate-proof: the reactors throttle back in summer when the rivers are too warm, and their waste heat is itself a form of local thermal pollution.

It is a real carbon-intensity advantage, and only as such. An underlying advantage, not yet activated, and certainly not an ecological blank check.

On the infrastructure side, Europe's gigafactories (the EuroHPC plan, around 20 billion euros for four to five sites) have, as of mid-2026, no confirmed selection date and no funded site. The only European exascale supercomputer, JUPITER at Jülich, runs 100% on Nvidia GPUs.

---

## Layer 2: HBM memory and critical materials

This is a hard layer, and Europe is absent from it.

High-bandwidth memory (HBM), indispensable to AI chips, is an Asian and American oligopoly: SK Hynix at around 62%, Micron 21%, Samsung 17%, and 0% European. All 2026 production is already sold, under non-cancellable contracts, with a shortage that extends through 2027 and beyond.

The materials are worse still, because they have already been turned into a weapon. China supplies around 98% of imported rare earths and 71% of imported gallium, and controls 60% of global extraction and 90% of refining. Its extraterritorial rule known as the 0.1% rule, which took effect on 1 December 2025, extends this control to any product containing these materials. The price of gallium rose by 365% over the single year 2025. This is not a theoretical dependence: in April 2025, Western factories were brought to a halt for lack of magnets.

### The shortage spills over to consumers

This shortage does not stay confined to datacenters. By reallocating their capacity toward high-bandwidth memory and AI servers, the foundries thinned out ordinary memory, and the price followed. On contracts, DRAM jumped by around 90% over the single first quarter of 2026; at retail, DDR5 modules saw their price multiplied by three to four between the autumn of 2025 and the end of the year. The high-bandwidth memory dedicated to AI now absorbs close to a quarter of DRAM wafer production.

It has to be put without exaggeration, because here the figure is an argument, not a slogan: we are talking about a factor of three to four on certain products and over a precise window, not a factor of twenty. But the political consequence is clear. Anyone who buys a computer in 2026 pays a scarcity premium indirectly caused by datacenter demand. It is a hardware tax, invisible and unvoted: the most industrial layer of the stack, memory, reaches all the way into the wallet of the individual buyer, who funds the compute race in spite of himself.

---

## Layer 1 (the most locked-in): Leading-edge foundry and EUV

We reach the wall, and the central paradox of this whole story.

The wall is that Europe etches no leading-edge chip. Its most advanced node is STMicroelectronics' 18nm FD-SOI at Crolles, several generations behind the 3 and 2 nanometers where AI chips are decided. The industrial record is cruel: the 2022 Chips Act is going to miss its flagship target (the European Court of Auditors projects 11.7% of the global market in 2030, against a target of 20%), and Intel's mega-project at Magdeburg, around 30 billion euros, was cancelled in 2025, the roughly 10 billion in promised subsidies never paid. The Chips Act 2.0, presented on 3 June 2026 with a need estimated at around 120 billion euros by 2035, revives the idea of a sovereign leading-edge foundry, but it is a political intention, not a legal obligation, and nine years of delay at the very least. The only concrete successes are off the leading edge: Infineon opens its Smart Power Fab in Dresden on 2 July 2026 (power chips, not leading-edge logic), and TSMC's ESMC foundry, also in Dresden, will produce in 2027 on mature nodes of 28 to 16 nanometers.

The paradox, now. Europe holds the one global chokepoint that truly counts: **ASML**, an absolute 100% monopoly on EUV lithography machines, without which no one in the world, not TSMC, not Samsung, not Intel, etches an advanced chip. It is the single link where the whole world depends on Europe, the United States included. Its 2026 revenue is expected between 36 and 40 billion euros, its next-generation High-NA machines cost 350 to 400 million euros per unit.

And yet Europe cannot convert this monopoly into sovereignty. Because ASML's machines go to TSMC, Samsung, Intel, never to a European leading-edge foundry. Europe sells the tool that manufactures the power of others, while remaining dependent on that power. It holds the most precious knife in the chain, and does not know how to forge.

---

## What to take away from the state of play

Four layers, a single logic. The further down you go, the harder the lock, and the more captive Europe becomes:

| Layer | Lock | European position |
|--------|--------|---------------------|
| Models / software | Weak (becoming a commodity) | Real lag but catchable; open weights are a genuine lever of use |
| Compute / electricity | Medium (grid, energy) | ~5% of global compute; nuclear is a throttled asset, not a victory |
| HBM / materials | Hard (oligopoly, Chinese weapon) | 0% European, already under pressure |
| Foundry / EUV | Physical (8 to 12 years) | No leading-edge fab; the ASML paradox |

And there is a mechanism to anticipate that will return throughout this document: **each new technological front adds layers of dependence rather than removing them.** Robotics piles a dependence on Chinese magnets and motors on top of the dependence on chips. Space piles a dependence on American launch on top of the dependence on silicon. We will see this in detail in [section 06](06-what-could-flip-the-table.md). The hardware lock is not one point among others: it is the ground on which everything else rests.

*Detailed and dated sources in [`SOURCES.md`](../SOURCES.md).*

[← Back to index](../README.en.md) · [Next: 02, Horizons →](02-horizons.md)
