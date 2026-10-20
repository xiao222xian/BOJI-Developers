# BOJI-Developers

The BOJI team's shared knowledge base.

A repository for recording, organizing, and sharing what we learn. We collect study notes, practical experience, troubleshooting records, and useful references so that the team can find, reuse, and improve them over time.

This repository focuses on documentation and knowledge sharing. It is not an application that needs to be installed or run. The knowledge base is at an early stage, and its structure and content will evolve as we use it.

## What We Record

- **Study notes:** Concept explanations, reading notes, course summaries, and learning reflections.
- **Practical experience:** Procedures, tool guides, project retrospectives, and reusable lessons.
- **Problems and solutions:** What went wrong, how it was investigated, and how it was resolved.
- **Reference materials:** Links to articles, official documentation, papers, and videos, with a brief explanation of why they are useful.
- **Discussions and decisions:** Discussion summaries, decision context, and questions that still need an answer.

Notes do not need to be complete from the start. Capture useful information first, then refine it. Clearly mark claims and procedures that have not been verified.

## Organizing Content

The following is a suggested structure. Create directories as needed; this outline does not mean that every directory or document already exists.

```text
BOJI-Developers/
├── README.md          # Overview and entry point
├── notes/             # Study notes organized by topic
├── guides/            # Practical guides and procedures
├── troubleshooting/   # Problems, investigations, and solutions
├── resources/         # References and recommended reading
└── discussions/       # Discussion summaries and decision records
```

Keep these principles in mind:

- Focus each document on one topic and use Markdown (`.md`).
- Use descriptive filenames, such as `notes/git-basics.md` or `guides/organizing-study-notes.md`.
- Search for existing material before adding a new document. Expand a relevant note when possible.
- Add an index to a directory when its content becomes difficult to browse.
- Mark outdated content and include an updated approach when available.

## Getting Started

### Read or Edit on GitHub

Browse documents directly on GitHub. Once you have collaborator access, use **Add file → Create new file** to add a note, or open an existing document and use the edit button to propose changes.

We recommend submitting changes through a new branch and a pull request so that other members can review and discuss them.

### Work Locally

If you prefer editing locally, install Git and run:

```bash
git clone https://github.com/xiao222xian/BOJI-Developers.git
cd BOJI-Developers
```

Open the repository in your preferred Markdown editor. No project dependencies or running services are required.

## Suggested Note Template

Use the following structure as a starting point. Adapt it to the topic and omit sections that are not relevant.

```markdown
# Document Title

Last updated: YYYY-MM-DD
Status: Draft / Verified / Needs update

## Background
Why is this topic worth recording? When does it apply?

## Main Content
Key concepts, findings, steps, or practical lessons.

## Examples and Verification
Examples, verification methods, applicable conditions, and limitations.

## Open Questions
Unverified points or information that still needs to be added.

## References
Source links, authors, document versions, or access dates.
```

## Contributing

Contributions are welcome: add new knowledge, correct documentation, improve examples, or update broken links.

Contact the repository owner for collaborator access if you need to push branches directly to this repository. Without push access, you can fork the repository and open a pull request, or suggest improvements through an issue.

### Local Contribution Workflow

Make sure any local changes are safely saved before switching branches. Sync the default branch, then create a focused branch for your update:

```bash
git switch main
git pull --ff-only origin main
git switch -c docs/short-description
```

After editing, review your changes and stage only the files you intend to include:

```bash
git diff
git add <paths-to-changed-files>
git commit -m "docs: describe the knowledge added or updated"
git push -u origin docs/short-description
```

Then open a pull request on GitHub and explain:

- What knowledge you added or changed.
- Why the change is useful.
- What sources support it and whether it has been verified in practice.
- Which points still need review or confirmation from other members.

### Content Guidelines

- Write in your own words where possible and credit your sources.
- Distinguish facts, personal experience, and assumptions. Do not present unverified conclusions as established facts.
- For technical notes, include relevant versions, environments, and update dates.
- Review AI-assisted content, especially citations, commands, and key conclusions.
- Keep contributions focused and avoid combining many unrelated changes in one submission.

## Public Content and Privacy

**This is a public repository. Anyone can view its contents and commit history.**

Do not upload passwords, API keys, access tokens, private account details, personal information, client data, or internal documents that have not been approved for public sharing. Use fictional or sanitized data in examples. Link to original resources rather than reproducing copyrighted materials in full without permission.

Before submitting, check document text, attachments, screenshots, and links for sensitive information.

## Roadmap

1. Establish useful categories based on the first set of notes.
2. Add topic indexes and introductory resources over time.
3. Regularly consolidate duplicate content, check broken links, and update outdated information.
4. Refine templates and maintenance practices based on the team's needs.

## License

No license has been added yet. Public visibility does not by itself grant permission to freely republish or redistribute the material. The repository owner will clarify licensing for the knowledge base and any code examples. Third-party materials remain subject to their original licenses and attribution requirements.
