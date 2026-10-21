# 🛡️ UglyShield™
![UglyShield logo](references/uglyshield%20logo.png)

**An open-source layout enforcer for AI-generated visuals.**

*Text first. Layout second. Red Pen before release.*

UglyShield™ helps prevent layout failures in AI-generated images, social media carousels, presentations, and PDFs.

It's not a graphic designer. It's a layout-enforcement system that helps people structure content, identify rendering risks, and catch mistakes before publishing.

## Try UglyShield in 60 seconds

You don't need to write code to try the workflow. Open an AI chat with access to the [UglyShield instructions](SKILL.md), provide the visual, slide, PDF, or text you want reviewed, and try:

> Use UglyShield in Classic mode. Review this visual for missing or misspelled text, cramped layout, weak hierarchy, distorted logos, and any changes to approved wording. Give me a prioritized Red Pen review. Don't change the wording unless I approve it.

For a more detailed review, include the **original approved copy** alongside the generated image or file. UglyShield should distinguish problems it actually inspected from possible problems it could not verify.

Want to make something, not just review it? Ask:

> Use UglyShield in Production mode to make this one-page graphic. Preserve the attached copy exactly and inspect the result before handing it over.

Production requires an AI environment with appropriate creation or editing tools. UglyShield cannot guarantee that a model renders text correctly.

### Install as an AI Skill

The repository already contains the canonical [SKILL.md](SKILL.md) and its supporting [references](references/). If your ChatGPT, Claude, or another AI environment supports importing custom Skills:

1. Download the repository files together (not just `SKILL.md`, which links to references).
2. Keep `SKILL.md`, the `references/` folder, and the `examples/` folder together in one `uglyshield` directory.
3. Package that directory as a ZIP only if your environment requires one, then use that environment's custom Skill upload or installation process.
4. Try: "Use UglyShield to Red Pen this slide without changing approved copy."

If your AI environment does not support custom Skills, you can still provide the [SKILL.md](SKILL.md) instructions and relevant reference files in a conversation. Capabilities and installation steps vary by product and plan; GitHub hosting alone does not install the Skill.

**What UglyShield does:** AI design QA, slide review, layout preflight, visual quality assurance, typography checks, approved-copy preservation, and detection of common AI-generated image errors.

## Why UglyShield Exists

AI can create beautiful visuals while quietly breaking important details.

Common problems include:

- Misspelled or missing text
- Distorted or floating logos
- Overcrowded layouts
- Poor spacing and visual hierarchy
- Inconsistent formatting across slides
- AI confidently approving flawed results

UglyShield helps identify these problems before and after visual generation.

## Two Operating Modes

### 🛡️ Classic Layout Enforcer (Default)

UglyShield's original mission.

- Organizes supplied content
- Checks layout hierarchy and readability
- Flags potential rendering failures
- Preserves the user's wording
- Guides users through improvements
- Performs Red Pen quality checks

Classic mode does not automatically generate finished visuals.

### 🎨 Production Mode (Optional)

When explicitly requested, UglyShield can help produce finished visuals or documents using available tools.

Production mode follows the same layout-enforcement rules and includes quality checks when the finished output is available for inspection.

## The UglyShield Workflow

**1. Text First**

Organize headline, subhead, body, and call to action.

**2. Layout Preflight**

Review spacing, readability, visual hierarchy, content density, and rendering risks.

**3. Visual Production**

Prepare layout-safe instructions or generate the requested artifact when Production mode is authorized and suitable tools are available.

**4. Red Pen Review**

Inspect the result for text errors, missing content, alignment problems, distorted logos, and visual drift.

## Getting Started

1. Download the latest UglyShield release from the repository's Releases section when available.
2. Extract the ZIP file.
3. Follow the installation process for your AI environment, if it supports custom Skills.
4. Ask UglyShield to review your content or layout.

You can also read the main [SKILL.md](SKILL.md) instructions directly.

**Try saying:**

"I'm new. Explain UglyShield and give me training wheels."

Or:

"Check this carousel for layout problems before I generate the images."

## Built to Evolve With AI

UglyShield is designed around layout principles rather than a specific AI model.

Its core workflow can be adapted to newer frontier models and different AI platforms.

Compatibility depends on the tools available in each environment and should be tested as models change.

## Open Source

UglyShield is distributed under the [MIT License](LICENSE).

You are welcome to inspect, use, modify, and contribute to the project under its license terms.

The UglyShield™ name identifies the original project. Licensing the instructions does not automatically grant trademark rights or permission to imply official endorsement.

## Contributing

Feedback, bug reports, layout-failure examples, documentation improvements, and compatibility testing are welcome.

Use GitHub Issues to report problems or suggest improvements.

## Creator

**UglyShield™ was created by Kevin Nalty (Nalts).**

Built to help everyday creators avoid the layout mistakes, rendering glitches, and overly agreeable AI responses that make visual content frustrating.

**Creator:** Kevin Nalty (Nalts)  
**YouTube:** [youtube.com/nalts](https://www.youtube.com/nalts)

UglyShield is an independent open-source project designed to evolve alongside frontier AI models.

---

**UglyShield™ — Because AI shouldn't quietly wreck your layout.**
