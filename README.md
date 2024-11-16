# End of internship presentation

The goal of the video is to make a short presentation of what happened during your internship. The video has to last 4 to 5 minutes. It must contain a presentation using any tool at your disposal (Powerpoint, Prezi, Keynote...), and a frame containing your face, or even better you as a whole

The content must respect the following rules:

- There’s a new member coming to the administration council : you need to explain the global context of the company, its specific context, the challenges, the content and the results of your internship project(s).
- The new member must be able to understand what you’re explaining.
- Looking to promote people internally, the administration council is there to listen to YOU. It is important that you show your implication on the project, your qualities (technical as much as anything else).

## Building the slides

The slides are generated from a markdown file, this is done with [marp](https://marp.app/) either with the vscode plugin or from the cli:

```bash
npm install -g @marp-team/marp-cli
```

Watch for file changes:

```bash
marp --watch test-slides.md
```

or start a server:

```bash

marp -s ./
```



