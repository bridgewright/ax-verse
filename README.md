# AX Verse

**Enterprise AI systems designed around evidence, operational constraints, and adoption.**

I am Taehyun Kim, a consultant at Boston Consulting Group and an independent AI product builder based in Seoul. I work on problems that sit between business judgment and technical delivery: defining the decision that matters, separating probabilistic work from deterministic controls, and building an evaluation harness before claiming that a system works.

AX Verse is the public index for three independent products. Each began as a case study based exclusively on public information. None was commissioned, endorsed, or reviewed by the companies discussed in the underlying research.

## Products

| Product | Problem | System | Evidence |
| --- | --- | --- | --- |
| [GAAP–IFRS Suite](https://github.com/bridgewright/gaap-ifrs-suite) | Accounting-standard conversion and research depend on scarce professionals who understand both local generally accepted accounting principles and Korean International Financial Reporting Standards. | A deterministic trial-balance conversion engine and a grounded retrieval service that returns source paragraphs with citations. | 177 automated tests across conversion, reconciliation, retrieval, citation fidelity, and fallback behavior; evaluated locally against 10,922 source paragraphs. |
| [Regulatory Incident Response](https://github.com/bridgewright/regulatory-incident-response) | A financial institution must produce several consistent regulatory and stakeholder documents within strict deadlines after an electronic-finance incident. | One structured incident record drives reportability decisions, filing drafts, customer notices, executive reports, privacy notices, and deadline tracking. | 25 automated tests, 14 legal scenarios, and reconstructions of eight publicly reported incidents. |
| [Alfboard](https://github.com/bridgewright/alfboard) | Enterprise AI deployments stall when discovery is repeated manually and field evidence does not return to the product team. | A voice interview collects evidence from four stakeholder groups and turns one validated discovery contract into an executive deployment brief and a product input document. | Deterministic schema validation, a complete nine-interview example, and a measured reduction from 27 tool calls to two in the launch path. |

## How I Build

1. **Define the operational decision.** I begin with the decision a user must make, rather than with a model capability.
2. **Narrow the scope.** I select the smallest workflow that can produce material value with the data and authority that are actually available.
3. **Separate judgment from control.** Language models extract, interpret, and draft. Deterministic code owns dates, amounts, thresholds, reconciliation, and schema validation.
4. **Design for missing information.** Unknown values remain unknown. A system should request review or refuse to produce an output instead of inventing certainty.
5. **Let evaluation change the design.** Tests are not a final demonstration. They are part of the product-design loop and must be capable of exposing a flawed assumption.

## What These Projects Demonstrate

- Translation of ambiguous enterprise problems into explicit workflows and measurable acceptance criteria
- Engineering judgment about where a language model is appropriate and where deterministic controls are required
- Product discipline across problem framing, implementation, evaluation, documentation, and deployment readiness
- Honest reporting of evidence, limitations, and unresolved operational risk

## Boundaries

These repositories are independent portfolio projects. They are not production systems, professional advice, or substitutes for review by qualified accounting, legal, security, or deployment professionals. Product-specific limitations and third-party rights are documented in each repository.

The products originated in [AX Wars](https://github.com/bridgewright/axwars), a time-bounded build sprint. AX Wars is retained as an archive; the repositories linked above are the canonical maintained sources.

## Contact

- [LinkedIn](https://www.linkedin.com/in/taehyun-kim-299aa2227/)
- [GitHub](https://github.com/bridgewright)
- Email: thk119914@gmail.com

## License

The original material in this repository is available under the MIT License. Product repositories contain separate notices for third-party standards, official forms, trademarks, and source material.
