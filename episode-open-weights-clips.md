# Clip Candidates: Open-Weights Episode

Companion to [episode-open-weights-transcript.md](episode-open-weights-transcript.md). The episode's spine matches the Kimi-K3 blog: own your evals, cost per task, harness over model, gateway as the control point. Clips are ordered by strength within each bucket.

## Short clips (30-60s, standalone hooks)

1. **"Cost per token is a head fake."** (Khawaja, PAC theorem section) "What you really want to pay attention to is cost per task... open models are one-fifth the price, but when we run our tests, they're about half as cheap at the end of the day." The single strongest clip; the thesis of the blog in one breath, ends on a counterintuitive stat.
2. **"Everybody starts with ZDR, and almost everybody ends with ZDR."** (Khawaja, plus Daniela's "ZDR is table stakes" response) Sharp, quotable, differentiated security take.
3. **The watermelon.** (Khawaja) "Green on the outside, red on the inside... LLM can be a judge, but not judge, jury, and executioner." Vivid metaphor, complete arc in about 45 seconds.
4. **The emissions test.** (Daniela) Public benchmarks vs. car makers' special test mode. Perfect "own your evals" hook, mildly spicy.
5. **"Claude Code can really amplify the stupid inside of you."** (Khawaja) Funniest line in the episode, and it lands the harness-matters point plus the Databricks study.
6. **"We're all food critics and we're not really eating anything."** (Khawaja) Closer-style clip about model-release fatigue; pairs directly with the blog's "you cannot out-read the firehose."
7. **"Token improvement plan."** (Khawaja) Short, punchy culture joke that carries the ship-to-production message.

## Medium clips (1.5-3 min, substance)

8. **"Evaluate models while you sleep."** (Daniela) Human-labeled golden rules, automated benchmark, new model drops at midnight and gets scored overnight. The full eval-vision segment.
9. **The pen.** (Daniela's "it's just the model, right?" setup, Khawaja's "what am I actually evaluating?", the pen/cursive analogy, then the human + harness breakdown.) Best two-hander moment; natural back-and-forth.
10. **"Fast tier isn't fast where you think."** (Daniela) TTFT slower on fast tiers, speculative decoding theory, more turns eating the throughput gain. Real benchmark finding, mirrors the blog's latency section, and the clip most likely to get engineer shares.
11. **"Inference is where databases were 20 years ago."** (Khawaja) Million-TPS rack, Postgres on EC2, self-hosting economics, supply chain, security. The commoditization arc is a self-contained story.
12. **"Prompting like a caveman."** (Khawaja) Boris quote, agent-prompts-your-agent, the weekend RDMA loop with Codex reviewing Claude. Strong for the BuffCon promo specifically.

## Sequencing

- Lead with #1 or #4 when the Kimi-K3 blog publishes: same message, two formats.
- Hold #12 for the week before BuffCon.
- Use #9 as the anchor if posting one longer cut.
