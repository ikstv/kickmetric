# Roadmap

This is a proposed sequence for discussion, not an approved delivery commitment. No delivery dates are assigned. A checked item records completed work only.

## 1. Repository foundation and product definition

- [x] Write the project vision and decision register.
- [x] Create initial branding and a README.
- [x] Establish contribution templates and agent guidelines.
- [ ] Define the initial audience, priority use cases, and MVP boundaries with the owner.
- [ ] Decide licensing and desktop targets.

## 2. Data-source feasibility and licensing review

- [ ] Compare candidate providers for coverage, quality, history, cost, and permitted usage.
- [ ] Assess missing data and whether historical inputs can be reconstructed as known at prediction time.
- [ ] Obtain the owner's approval for data sources and initial leagues.

## 3. Baseline forecasting and historical evaluation

- [ ] Agree on evaluation criteria and simple baselines before choosing more complex models.
- [ ] Design time-ordered evaluation on later, unseen matches and check for leakage.
- [ ] Evaluate probability quality and calibration, report uncertainty, and document limitations.

## 4. Desktop MVP implementation

- [ ] Approve the implementation approach and minimum requirements.
- [ ] Implement the agreed desktop scope using approved data sources.
- [ ] Make forecast inputs, probabilities, and limitations understandable in the interface.

## 5. Validation, packaging, and release preparation

- [ ] Validate behavior, data handling, and usability on the selected desktop targets.
- [ ] Establish packaging, documentation, and a release process.
- [ ] Review readiness with the owner before publishing an application release.

## 6. Future Android exploration

- [ ] Assess mobile use cases, device constraints, and distribution requirements.
- [ ] Evaluate what logic or services can be shared and what needs a separate mobile implementation.
- [ ] Agree on Android scope and architecture with the owner.

Android is a future goal; reuse of a desktop UI is not assumed. See the [decision register](decisions.md) for unresolved choices.
