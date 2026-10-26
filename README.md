# Kristofer Jussmann

I am **Kristofer Jussmann (Ker102)**, an agent security and reliability engineer based in Estonia. I make AI agents safe to run and test whether they actually work: agent harnesses and evaluation, scoped agent permissions, AI-assisted infrastructure security, and secure cloud platforms on Azure and AWS.

[Projects](#featured-projects) · [Open source](#open-source-contributions) · [Case studies](https://kristoferjussmann.me/case-studies) · [Portfolio](https://kristoferjussmann.me/projects) · [Blog](https://kristoferjussmann.me/blog) · [LinkedIn](https://www.linkedin.com/in/kristofer-jussmann-ker102/) · [GitHub activity](#github-activity)

*Last updated: October 2026*

## Featured projects

| Project | What it is | Result | Links |
|:--|:--|:--|:--|
| **Harneloop**<br>Active open-source alpha | Framework for improving agent harnesses: agents inspect what they produced, trace where it went wrong, test a candidate change in isolation, and keep it only if the test improves. | Agent improvement becomes a test discipline instead of trial and error; first applied to the ViperMesh Blender agent. | [Case study](https://kristoferjussmann.me/case-studies/harneloop) · [Project site](https://harneloop.kaelux.dev/) · [Repository](https://github.com/Ker102/Harneloop) |
| **ViperMesh**<br>Active private product | 3D workspace with a Blender agent that works through about 130 constrained, validated tools and an MCP layer instead of writing open-ended Blender Python. | Against the Anthropic x Blender MCP baseline on the same model: faster on 6 of 7 live tasks and about 90% fewer agent tokens. | [Case study](https://kristoferjussmann.me/case-studies/vipermesh) · [Open-source connector](https://github.com/Ker102/vipermesh-blender) |
| **nullstate-cli**<br>Active open-source alpha | Purple-team CLI that attacks Terraform-defined infrastructure in local cloud emulators, applies a deterministic fix, and replays the attack to prove the fix holds. | On AWS LocalStack the exploit worked before the fix and was blocked on replay. The verdict comes from the replay, not the model. | [Repository](https://github.com/Ker102/nullstate-cli) · [Case study](https://kristoferjussmann.me/case-studies/nullstate) |
| **Private Secure AI Automation Platform**<br>Archived | Private n8n platform and OpenClaw personal agent on Azure Container Apps, with private networking, managed identity, passwordless CI/CD, and remote access over Tailscale. | Built and ran it, traced an idle-cost failure to my own design, tore it down with full exports, and documented a cheaper rebuild. | [Case study](https://kristoferjussmann.me/case-studies/private-azure-platform) |
| **OpenRoot**<br>Active non-profit | Developer community I founded: a developer program, a newsletter, and an open-source GitHub organization where members build in public. | 30+ members in the GitHub organization, a first partnership, and hackathons and workshops planned with partners. | [openroot.dev](https://openroot.dev) · [GitHub organization](https://github.com/OpenRootdev) |

**More work:** [PromptTriage](https://github.com/Ker102/PromptTriage) (prompt research and evaluation), [n8n Automation Atlas](https://github.com/Ker102/n8n-workflows-36k) (workflow dataset and retrieval, [dataset on Hugging Face](https://huggingface.co/datasets/Ker102/n8n-mega-workflows)), [Crosswind Console](https://github.com/Ker102/Crosswind-Console), [StoryForge](https://github.com/Ker102/StoryForge), and [Examplayer](https://github.com/Ker102/Examplayer). The [full portfolio](https://kristoferjussmann.me/projects) has the rest.

## Open-source contributions

| Project | Contribution | Status |
|:--|:--|:--|
| [Cap](https://github.com/CapSoftware/Cap) | Moved the caption word utilities into a shared `cap-project` module so the copies that had drifted apart now agree ([#3295](https://github.com/CapSoftware/Cap/pull/3295)); a follow-up makes the number of words per caption segment configurable ([#3296](https://github.com/CapSoftware/Cap/pull/3296)). | 1 merged, 1 open |
| [OpenWhispr](https://github.com/OpenWhispr/openwhispr) | Fixed dropped keyboard taps between rows on mobile ([#2388](https://github.com/OpenWhispr/openwhispr/pull/2388)); a second PR adds automatic API-key fallback for dictation ([#2461](https://github.com/OpenWhispr/openwhispr/pull/2461)). | 1 merged, 1 open |
| [Prowler](https://github.com/prowler-cloud/prowler/pull/10347) | Fixed a 404 in the OCI audit-retention check by creating the audit client in the tenancy home region, with regression tests. | Merged |
| [Excalidraw for Obsidian](https://github.com/zsviczian/obsidian-excalidraw-plugin/pull/2864) | Proposed a Focus Embed Timer script, built on [focus-embed-timer](https://github.com/Ker102/focus-embed-timer), my own zero-dependency timer for Obsidian, Excalidraw, and Markdown embeds. | Open |
| [Graphiti](https://github.com/getzep/graphiti) | Traced non-OpenAI endpoint failures to client routing ([#1339](https://github.com/getzep/graphiti/pull/1339)); a second PR makes the MCP read tools accept scalar group IDs ([#1354](https://github.com/getzep/graphiti/pull/1354)). | Superseded upstream, 1 open |
| [Mozilla Firefox](https://www.mozilla.org/firefox/) | Working on a hard graphics driver bug in Firefox. | In progress |
| [Matplotlib](https://github.com/matplotlib/matplotlib/pull/31308) | Mentored a second-year computer-science student through their first upstream contribution, a merged documentation fix. | Merged (mentor) |

## Background

**Founder, OpenRoot — present.** Non-profit developer program, community, and newsletter with 30+ members in its GitHub organization.

**Founder and Lead AI Engineer, [Kaelux](https://kaelux.dev) — 2024 to present.** Research lab and consultancy for AI systems, automation, and cloud engineering work with collaborators and business clients.

**Estonian Defence Forces — 2024 to 2025.** Completed mandatory military service while continuing technical project development.

**Credentials:** Microsoft Certified: Azure Administrator Associate (AZ-104), DataCamp AI Engineering for Developers Associate, Anaconda Machine Learning Foundations, Docker Foundations, GitHub Foundations (GH-900), Microsoft Applied Skills: Azure Administration, and Cambridge C1 Advanced English. Next: SC-500 and Terraform Associate.

## Technical focus

- **Agent security:** scoped agent permissions, constrained tool surfaces, MCP, attack-and-replay testing, threat modelling, and keeping the model out of the security verdict.
- **Agent reliability and evaluation:** agent harnesses, artifact-aware evaluation, trace-backed diagnosis, LLM-as-judge checks, and benchmarks that keep their negative results.
- **Cloud and infrastructure security:** Azure, AWS, Google Cloud, Terraform, LocalStack, Docker, Kubernetes and K3s, GitHub Actions, OIDC, managed identity, private networking, and cost controls.
- **AI infrastructure:** vLLM, self-hosted models, retrieval-augmented generation, vector search, and Hugging Face datasets.
- **Languages and tools:** Python, TypeScript, Rust, SQL, Bash, PowerShell, React, Astro, FastAPI, Three.js, and the Blender Python API.

## GitHub activity

<a href="https://github.com/Ker102">
  <img src="metrics.plugin.isocalendar.svg" width="480" alt="Ker102 GitHub contribution calendar" />
</a>

[View my GitHub profile](https://github.com/Ker102) · [Browse all repositories](https://github.com/Ker102?tab=repositories)

## Writing and profiles

[Personal site](https://kristoferjussmann.me) · [Blog](https://kristoferjussmann.me/blog) · [Case studies](https://kristoferjussmann.me/case-studies) · [Portfolio](https://kristoferjussmann.me/projects)

[LinkedIn: Kristofer Jussmann](https://www.linkedin.com/in/kristofer-jussmann-ker102/) · [Hugging Face: Ker102](https://huggingface.co/Ker102) · [Dev.to: Ker102](https://dev.to/ker102) · [Hashnode: Ker102](https://hashnode.com/@ker102)

For collaboration or engineering work: [kristoferjussmann@gmail.com](mailto:kristoferjussmann@gmail.com)
