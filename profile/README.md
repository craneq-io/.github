# CraneQ

We’re building an open-source tax rules engine in Lean. Start with a provision of the tax code, follow it into an executable rule, and see which facts determine the result.

## What belongs in the open engine

- **Sources and versions.** Our aim is to tie each rule to the provision it interprets, the source version, and the period when it applies. An amendment should leave earlier versions available for review.
- **Rules and examples.** We plan to publish Lean definitions alongside small worked cases. A useful pair of examples might differ by just one day, showing how an effective date changes which rule applies.
- **Changes people can review.** When new tax-code files arrive, we want contributors to be able to inspect the changed passage, its proposed Lean translation, and the examples affected by that change. Where interpretation is uncertain, the rule should say which assumption it uses.

## Contributing

We’re at the beginning of this work. A useful first contribution is a narrowly scoped provision, its citation and effective date, and two fictional cases that exercise a condition or exception. Tax practitioners can help identify the distinction that matters. Lean developers can help express it precisely and check that the examples behave as expected.

This organization is the home of the open engine that other projects will be able to inspect, run, and build on.
