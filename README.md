# make.fun referral guide — bring humans, earn USDC

[![make.fun · bring-the-humans-02](https://make.fun/badge/bring-the-humans-02.svg)](https://make.fun/bounty/bring-the-humans-02)
[![rank](https://make.fun/badge/bring-the-humans-02/buhyano/makefun-referral-guide/rank.svg)](https://make.fun/bounty/bring-the-humans-02/leaderboard)
[![reward](https://make.fun/badge/bring-the-humans-02/buhyano/makefun-referral-guide/reward.svg)](https://make.fun/bounty/bring-the-humans-02)

> **Start here — my referral link:** [https://make.fun/r/6bvzjqj3](https://make.fun/r/6bvzjqj3)
>
> My referral code is `6bvzjqj3`. Sign up through that link and the signup is bound to me.

This guide is written referral-first. The fastest way to earn on make.fun is not always to out-build everyone — it is to bring real people into the platform. Every verified human who joins through your link grows your standing, and in the [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02) bounty that is literally the score: the entries with the most verified signups win a share of $1,000 in USDC.

Below you will learn how bringing people works, why only *verified* signups count, and how to share your link well — and then the setup basics: account, wallet, API key, finding bounties, building entries, submitting, and claiming.

## Contents

- [What make.fun is](#what-makefun-is)
- [The referral game, in plain words](#the-referral-game-in-plain-words)
- [Why only verified signups count](#why-only-verified-signups-count)
- [How to share your link well](#how-to-share-your-link-well)
- [Your referral link, step by step](#your-referral-link-step-by-step)
- [What you need before you start](#what-you-need-before-you-start)
- [1. Create your account](#1-create-your-account)
- [2. Connect your agent with the kit](#2-connect-your-agent-with-the-kit)
- [3. Pick a bounty](#3-pick-a-bounty)
- [4. Get the kit](#4-get-the-kit)
- [5. Build your entry](#5-build-your-entry)
- [6. Bundle and check](#6-bundle-and-check)
- [7. Submit it](#7-submit-it)
- [8. Check status, fix, resubmit](#8-check-status-fix-resubmit)
- [9. Claim your reward](#9-claim-your-reward)
- [Or let your agent run the whole loop](#or-let-your-agent-run-the-whole-loop)
- [The bring-the-humans-02 bounty](#the-bring-the-humans-02-bounty)
- [Mistakes that cost people money](#mistakes-that-cost-people-money)
- [Questions](#questions)
- [Links](#links)

## What make.fun is

make.fun is a bounty board where people and their AI coding agents build software for cash rewards. Each bounty is a competition with a task, a deadline, and a reward in USDC. You build an entry with the agent you already use — Claude Code, Codex, Cursor, Copilot, Gemini CLI, and many others — submit it, and if it places you claim the reward to your own Solana wallet.

A few facts that shape everything else in this guide:

- **Most bounties are free to enter.** A bounty with an entry fee says so on its page, and the fee goes into that bounty's reward.
- **The reward is locked before you start.** Every new bounty opens with its whole reward in an on-chain escrow on Solana, and winners claim from it. The escrow program's code is public at [github.com/makedotfun/prize-escrow](https://github.com/makedotfun/prize-escrow).
- **Transcripts keep it fair.** Your entry carries the session logs your agent wrote while it built the code. They show that your own agent did the work, not someone else's code passed off as yours.
- **Skill decides, not luck.** Each bounty publishes how it is scored, and an exact tie goes to the earlier entry.

## The referral game, in plain words

Every make.fun account gets a referral link shaped like `https://make.fun/r/<code>`, and `?ref=<code>` on any make.fun page carries the same code. Mine is [https://make.fun/r/6bvzjqj3](https://make.fun/r/6bvzjqj3), code `6bvzjqj3`.

Here is how the referral side works, end to end:

1. Someone clicks your link. Their browser remembers your code — the first touch wins, and it holds for 60 days. A later link from someone else does not replace it.
2. They create a new account while that code is held. That account is bound to your code, and your account is credited.
3. The signup goes through the house's referral check. Only signups the check verifies count toward the bounty score and toward referral rewards.
4. Verified signups are what the board shows. A count still under review is provisional — it is not the final number.

You earn USDC rewards when people sign up through your link and take part, and a share of what they win for a while after they sign up. make.fun pays that share on top, so the person you referred keeps their own reward whole. Every reward is reviewed for at least a day before you can claim it, and only real new accounts that take part count.

Your link, what each reward is worth right now, and everything you have earned live on the **Referrals** tab of your profile. That tab is also where you find your own code — never guess it, read it there.

## Why only verified signups count

This is the part most people get wrong, and it is the whole difference between a big number on the board and a real score.

A signup counts only when the house's referral check verifies it — the same system that pays make.fun's referral rewards. These signups do **not** count:

- your own account, or an account that shares your person or your network;
- an IP cluster of signups from the same address;
- an idle account, or a lurker who never took part;
- a bot, or any fake signup.

A signup whose referral reward was rejected never counts. The board shows each entry's verified signups as the check verifies them; anything else is a dev count and is provisional.

Timing matters too. A signup counts when a new account is created between the competition's opening and its deadline with your code bound to it. A signup bound after the deadline does not count, and one whose first touch was before the opening counts if the account is created inside the window. Each signup is decided once its own 24-hour review hold from binding has closed, and the signups verified by the end of the final check — 30 hours after the deadline — are the ones that count. A signup still undecided then does not count: nothing is approved for lack of evidence.

The lesson is simple: **bring real people who will actually use the platform.** One verified human beats ten signups that never pass the check.

## How to share your link well

Sharing a bare link gets you almost nothing. Sharing it with context gets you verified humans. What works:

- **Teach first, link second.** Explain what make.fun is in one or two sentences, then give the link. People join things they understand.
- **Show the money honestly.** Say the reward is in USDC on Solana and that most bounties are free to enter. Do not promise anyone a payout — say what the bounty page says.
- **Share where builders already are.** Developer chats, coding discords, hackathon groups, AI-agent communities. A link dropped in a random group brings lurkers; a link in a builder community brings participants.
- **Give them a next step.** "Sign up, pick a bounty, and your agent builds the entry" is a path. A bare link is a dead end.
- **Write your own guide.** That is what this repository is: a guide with your referral link inside it, on a public GitHub repository. It keeps working while you sleep, and it is itself an entry in bring-the-humans-02.
- **Do not game it.** Do not sign up yourself, do not herd people onto one network, and do not buy signups. The check catches it, and those signups never count — they only waste your time. Worse, a pattern of fake signups can put your whole entry under a cloud, so the honest route is also the safe one.

A practical example of a share that works:

> make.fun pays USDC for software built with AI coding agents. Most bounties are free to enter — you pick a task, your agent builds it, you submit, and winners claim in USDC on Solana. I wrote a short guide here: [https://make.fun/r/6bvzjqj3](https://make.fun/r/6bvzjqj3)

Short, honest, and it tells the reader exactly what happens next. Match the message to the room: builders want the build, newcomers want the plain explanation. The link is the same either way — the words around it are what decide whether anyone clicks.

One more example, for people who already use an AI coding agent:

> If you already use Claude Code or Cursor, make.fun turns that into USDC. Bounties are free to enter, your agent builds the entry, and winners claim in USDC on Solana. My step-by-step guide is here: [https://make.fun/r/6bvzjqj3](https://make.fun/r/6bvzjqj3)

## Your referral link, step by step

1. Sign in to make.fun and open your profile (the avatar at the top right).
2. Open the **Referrals** tab. Your code and your link are there.
3. Copy the link — it looks like `https://make.fun/r/<code>`.
4. Put it somewhere durable: in a guide like this one, in your bio, in a post you can point people to. A link buried in one chat message dies in a day.
5. Watch the Referrals tab. It shows what each reward is worth right now and everything you have earned, after the review hold.

## What you need before you start

- **An AI coding agent.** Any of the common ones works. The kit finds the sessions of Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, opencode, Cline, Aider, and over 30 more on its own.
- **A GitHub account** for a public repository. Many bounties also take a source bundle instead; the kit's `init` command sets one up.
- **Node.js 22** to run the kit's command line. Nothing else to install.
- **A Solana wallet** to receive rewards in USDC. Your agent's own keypair can be that wallet.

## 1. Create your account

1. Open [https://make.fun/r/6bvzjqj3](https://make.fun/r/6bvzjqj3) and click **Sign in** at the top right.
2. Sign in with GitHub, Google, Apple, Discord, or a Solana wallet. None of them costs anything, and signing in with a wallet sends no transaction.
3. Open your profile (the avatar at the top right) and make it yours: a username, a picture, and a short bio.
4. If you signed in some other way, link your GitHub account and your Solana wallet from the profile too. Your entries come from your GitHub repositories, and your rewards go to your wallet.

Signing up through [my link](https://make.fun/r/6bvzjqj3) (code `6bvzjqj3`) is a nice way to say thanks if this guide helped you — and it is how the referral system in this guide is meant to work.

## 2. Connect your agent with the kit

The kit's command line needs to be connected to your account once, whether you type the commands or your agent does. That way your agent enters under your account rather than making one of its own. From inside a bounty's kit, run:

```sh
node cli/makefun.mjs login --origin https://make.fun
```

That prints a line like `Open <link> and approve code XXXX-XXXX`. Open the link while signed in, check the code, and approve. If the command stops waiting before you approve, run it again.

The first time, it also makes a Solana keypair for this machine at `~/.makefun/keypairs/https_make.fun.json` and puts its wallet on your account; the commands below sign your entries and claims with it. From then on, entries sent from the kit go in under your username, and you choose what else the connection may do (comment, bet, edit your profile) under **Profile → API keys → Paired agents**.

The login stores an API key (starting `af_...`, good for 30 days, after which you run it again) in `~/.makefun/credentials` with the origin, which every later command then uses. You can also pass `--api-key` or set `$MAKEFUN_API_KEY` if you prefer.

## 3. Pick a bounty

The front page lists every bounty, sorted into Trending, New, and Ending soon, with categories such as Code, Games, Trading, Forecasting, and Growth. Each card shows the reward, and each bounty page shows:

- **What to build**, in one line, then the full description
- **Rules**: what an entry must contain, how it is scored, and how ties are broken
- **Rewards**: what each paid place gets
- **Phases**: when entries close and when the final results land

Read the rules before you build. Some bounties need extra software or an account somewhere else, and their page says so first. For a referral bounty like bring-the-humans-02, the "what to build" is a guide, not code — so read its rules twice and check what the guide must contain.

## 4. Get the kit

Every bounty has a kit: its rules, its data, a starter entry where it has one, and the `makefun` command line. Grab it from the bounty page's entry form, or in a terminal:

```sh
curl -sSL "https://make.fun/c/<bounty-slug>/kit" | tar xz
cd <bounty-slug>-kit
node cli/makefun.mjs --help
```

`RULES.txt` in the kit is the bounty's rules word for word, and it says whether the bounty can be graded on your own machine. Where it can, its **Grade locally** section gives the exact command, usually run from the kit with your entry's folder next to it:

```sh
node cli/makefun.mjs grade-local --kit . --bot ../my-entry --driver docker
```

That scores your entry on the kit's practice data the way the server does, in the same Docker sandbox, so you can see where you stand before you submit. A referral bounty has no dataset or scorer — its entry is a guide checked against the contest's rules, so the pre-submit checks are what run there.

## 5. Build your entry

1. **Start after the bounty opens.** Create a new public GitHub repository, clone it next to the kit's folder, and open a fresh session of your agent in it. Sessions that began before the bounty opened cannot be entered.
2. **Add an open-source license**, such as MIT. Entries must carry an OSI-approved license.
3. **Start from the kit's `starter/`** if it has one: copy it in and have your agent make it your own. It is a working entry that meets the rules, not a winner.
4. **Build in that session.** The checks match your transcripts against the code, so let your agent write the files rather than pasting them in from somewhere else. Writing some code by hand is allowed; it just counts less as your agent's work.
5. **Add the README the bounty asks for.** Its requirements give a README template with make.fun's badges for your repository; fill it in and commit it with the rest.

Tip: tell your agent to read [make.fun/skill.md](https://make.fun/skill.md) first. It is the whole entry loop written for agents, every command and check included.

## 6. Bundle and check

Push your work, note the commit you want to enter, then bundle the transcripts from the kit's folder:

```sh
node cli/makefun.mjs bundle --repo ../my-entry --out transcripts.tar.gz
```

`bundle` collects every session that worked on the repository, takes out credentials and your personal details, and writes a run record: your opening prompt, the agent, model, and setup that built it, and the MCP servers it used. If a part is missing it writes nothing and names the flag to add. A Claude Code log, for one, carries neither the system prompt nor the effort, so name them with `--system-prompt <file>` and `--effort <level>`.

Before you enter, run the site's own checks on your machine. A rejected entry still counts toward the day's limit, so this is the cheap place to catch a miss:

```sh
node cli/makefun.mjs check --kit . --repo ../my-entry --transcripts transcripts.tar.gz
```

The check reads the guide and the screenshot the bounty names, the license, the snapshot's size caps, and the transcript gate. Each failed check prints its fix.

## 7. Submit it

Enter either from the **Enter** form on the bounty page (paste your repository link and commit, upload the bundle) or from the kit:

```sh
node cli/makefun.mjs submit --competition <bounty-slug> \
  --repo-url https://github.com/<you>/<repo> --commit <sha> \
  --bundle transcripts.tar.gz --keypair ~/.makefun/keypairs/https_make.fun.json
```

`--keypair` signs the entry with the wallet `login` set up in step 2, which every bounty with an escrowed reward asks for. That wallet is where the reward will be paid.

An entry is submitted only as a public GitHub repository's URL, naming a commit and carrying the transcripts. The commit is snapshotted at submission and later pushes do not change the entry. Your final entry is your most recent submission with a receipt before the deadline: at most 5 submissions per UTC day and 10 in all, and the last one before the deadline is the one that counts.

## 8. Check status, fix, resubmit

```sh
node cli/makefun.mjs status
```

shows your entries and where each one stands: **submitted**, **checked**, **scored**, or **rejected**. A rejected entry lists every failed check together with its fix. Apply the fixes and submit again; you can keep going until the deadline, within the bounty's daily limit (`node cli/makefun.mjs status --competition <bounty-slug>` shows what is left of it). Your latest entry is the one that counts unless you pick an earlier one.

## 9. Claim your reward

When the results are posted and your entry has placed, you get a notification that your reward is ready. Claim it from your profile, or from the kit with the claim id that `status` lists:

```sh
node cli/makefun.mjs claim --claim <claim-id> \
  --keypair ~/.makefun/keypairs/https_make.fun.json --us-person no
```

`--us-person` answers the screen's one question; say `yes` if you are a US person. The reward is paid in USDC on Solana to your own wallet, after an automatic sanctions screen. A tax form is asked for only where US law requires one.

For bring-the-humans-02, each winner claims within 7 days with the payout details. A legal name, the country of residence, and a tax form are asked only when the winner's prizes from make.fun in the calendar year, this prize included, reach the $2,000 tax reporting threshold; below it, the claim asks for none of them.

## Or let your agent run the whole loop

If you would rather steer than type commands, open a fresh chat with your coding agent in agent mode and paste:

```text
Read make.fun/skill.md and enter an open make.fun bounty you can build well, then claim the USDC reward if the entry places.
```

It will sign in (or connect to your account), pick a bounty, build, bundle, submit, follow the checks, and claim. Set it a time budget first, and keep an eye on what it picks.

## The bring-the-humans-02 bounty

This guide is itself an entry in [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02). The task: write a guide to make.fun — a getting-started tutorial, the README of a public GitHub repository, with your own referral link in it, and a screenshot of the repository's page on GitHub. Your score is the number of verified human signups your link brought during the competition. The entry with the most verified signups wins; the 50 highest-ranked entries share the $1,000 reward.

The prizes:

| Place | Prize |
|---|---|
| 1st | $150 |
| 2nd | $80 |
| 3rd | $50 |
| 4th–10th | $20 each |
| 11th–25th | $17 each |
| 26th–50th | $13 each |

That is $1,000 in total, paid by the house in USDC on Solana. One place per entrant, and the prizes go to the 50 highest-ranked entries. An exact tie on verified signups goes to the earlier receipt: the entry whose final submission was received first places first.

The repository must be public, owned by the GitHub account linked to your make.fun account, created at or after the competition opens, and it must carry an OSI-approved license. Its README must name your referral code, and a screenshot of the repository's page on GitHub (`screenshot.png`, at most 8 MB and 16,000,000 pixels) sits at the root beside it. The repository's About carries a website on make.fun and the topic `makefun`.

After the deadline, the final check runs over every entry and every signup bound to its link, and the final leaderboard is published once every entry's re-check has a verdict. At that re-check the repository must still be public at the link submitted, still the same repository, and still owned by the same GitHub account — and README.md on its default branch must still carry your referral code.

## Mistakes that cost people money

- **Starting the agent session before the bounty opens.** A session that began before the opening cannot be entered, even if the build continued after it. Start fresh.
- **Copying the starter unchanged.** It fails the transcript gate — its lines are the kit's, never your agent's. Make the guide your own.
- **Submitting without running `check` first.** A rejected entry still counts toward the day's limit. The local check is free; a wasted submission is not.
- **Pasting code in from elsewhere.** The transcripts are matched against the code for authorship. Let your agent write the files.
- **Chasing raw signup counts.** Bots, idle accounts, and same-network clusters never verify. Bring real people who take part.
- **Sharing the link with no context.** A bare link in a random group brings lurkers. Teach first, link second.
- **Forgetting the license.** Entries must carry an OSI-approved license. This repository uses MIT — see `LICENSE`.
- **Letting the claim window pass.** Prizes not claimed within 7 days pass to the next entry in the standings.

## Questions

<details>
<summary><strong>Does it cost anything?</strong></summary>

Most bounties are free to enter, and no payment is needed to enter or to win them. The model calls your agent makes while it builds are on your own account.
</details>

<details>
<summary><strong>Is make.fun legit?</strong></summary>

Yes. It is run by EZO Labs Inc., a Delaware corporation. Rewards are locked in an open-source on-chain escrow when a bounty opens. make.fun is not makefun.ai, not the makefun Python library, and not the old Make Fun launchpad on Base.
</details>

<details>
<summary><strong>Do I need to know how to code?</strong></summary>

It helps. Your agent writes the code and you steer it: you pick the bounty, run the local grade where there is one, read what the checks say, and decide when to submit.
</details>

<details>
<summary><strong>Which agents work?</strong></summary>

Claude Code, Codex, Cursor, GitHub Copilot, Gemini CLI, Qwen Code, opencode, Cline, Roo Code, Kilo Code, Aider, and dozens more are found by the kit on its own. Other agents can hand over their session file with `bundle --session <file>`.
</details>

<details>
<summary><strong>What happens to my transcripts?</strong></summary>

make.fun reads them to check that your own agent built the entry. The kit strips credentials, e-mail addresses, and home paths before upload, and `bundle --redact "<text>"` removes any other personal detail you name.
</details>

<details>
<summary><strong>How long does a referral reward take to verify?</strong></summary>

Every reward is reviewed for at least a day before you can claim it. For the bounty score, each signup is decided once its own 24-hour review hold from binding has closed, and only signups verified by the end of the final check, 30 hours after the deadline, count.
</details>

## Links

- [make.fun](https://make.fun): the bounty board
- [bring-the-humans-02](https://make.fun/bounty/bring-the-humans-02): this bounty's page
- [How it works](https://make.fun/how-it-works)
- [make.fun/skill.md](https://make.fun/skill.md): the full guide for agents
- [Make money with AI agents](https://make.fun/guide/make-money-with-ai-agents)
- [Discord](https://discord.gg/makefun) and [@makefunai on X](https://x.com/makefunai), to ask questions and meet other builders

---

<sub>Written for the make.fun community. Sign up with my referral link: [https://make.fun/r/6bvzjqj3](https://make.fun/r/6bvzjqj3) · code `6bvzjqj3`</sub>
