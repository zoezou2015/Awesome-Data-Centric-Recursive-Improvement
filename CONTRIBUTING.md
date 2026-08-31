# Contributing to Awesome Data-Centric Recursive Improvement

Thanks for helping maintain this companion list for **_Data-Centric Recursive
Improvement for Foundation Models: A Survey_**.

## What belongs here

This repository contains only works **cited by the survey**. A paper belongs
here if it uses evaluation feedback to update a data-related object, introduces
a reusable data / evaluation / control operator for recursive improvement, or
analyzes closed-loop risks (contamination, reward hacking, evaluator
dependence, model collapse, unstable updates, irreproducibility).

Place each paper in its primary stage of the **signal–decision–update** loop,
and list it only once per section:

- **Evaluation Signals** — what signal diagnoses the system
- **Orchestration Decisions** — who decides how to act on the signal
- **Execution Mechanisms** — what object is updated (PT / SFT / RL & PO / OPD / context & memory)
- **Failure Modes** / **Future Directions** — the cross-cutting reliability audit

## Entry format

Edit `README.md` directly and match the surrounding entries:

```markdown
- [Title](link) `Year` `Venue`
```

- Use the canonical paper page, preferring arXiv `abs/`, DOI, OpenReview, or
  official proceedings pages.
- `Venue` uses the short form already used in the list (e.g. NeurIPS, ICLR,
  CVPR, ACL); use `arXiv` for preprints and technical reports.
- Preserve the existing section structure and the newest-first ordering.

## How to contribute

1. Fork the repository and create a branch.
2. Edit `README.md` directly.
3. Open a pull request describing the paper and its section.

For taxonomy changes, restructuring, or batch updates, open an issue first.

## Pull request checklist

- [ ] The paper is cited by the survey.
- [ ] The entry is in the correct section and follows the required format.
- [ ] The paper is not already listed.
- [ ] All paper, code, project, image, and anchor links work.

## License

By contributing, you agree that your contribution is licensed under the
repository's [Apache License 2.0](LICENSE).
