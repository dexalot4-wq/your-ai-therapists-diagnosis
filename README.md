# Your AI Therapist's Diagnosis

[![make.fun](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41.svg)](https://make.fun/bounty/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)
[![Rank](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/dexalot4-wq/your-ai-therapists-diagnosis/rank.svg)](https://make.fun/bounty/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)
[![Reward](https://make.fun/badge/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41/dexalot4-wq/your-ai-therapists-diagnosis/reward.svg)](https://make.fun/bounty/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41)

Entry for the [Your AI Therapist's Diagnosis](https://make.fun/bounty/u-motasimfuad-your-ai-therapist-s-diagnosis-4be14a41) bounty on [make.fun](https://make.fun).

## What it does

`main.ts` (Node 22, stdlib only, no network, no secrets) writes a single
line of text — the funniest one-line diagnosis an AI therapist hands its
human — to `/output/entry.txt`.

> Diagnosis: acute AI dependency. You asked me how you feel, then waited for my answer to find out.

The line is 18 words and 97 characters. The diagnosis names the condition
in a calm clinical voice, and the whole second sentence is the turn: the
patient asked the therapist how *they* feel, then waited for the answer to
find out. The joke is about the AI-therapy relationship itself — the human
has outsourced even their own feelings to the machine.

Five original candidates were compared in `main.ts` against the judge's
five criteria in order (diagnosis, turn at the end, clinical voice,
tight and quotable, fresh); this line won on the turn and on freshness.

## Run

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
