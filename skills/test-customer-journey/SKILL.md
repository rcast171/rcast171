---
name: test-customer-journey
description: "Use for website/application readiness, lead-capture flows, directories, calculators and release checks."
---

# Test customer journey




Follow the user’s approved scope. Preserve unresolved conflicts and report only observed actions and checks. Complete preparation before requesting any necessary review. Existing authorization remains valid; do not request approval again for an already approved action. A completed draft alone is not authorization to publish, install, or send.

1. List the actual user journeys and intended outputs from approved requirements. Distinguish visual controls from connected behavior.
2. Check public/signed-out access separately from owner preview and custom-domain routing.
3. Test each primary route, action and form with clearly marked synthetic data, checking actual destination and saved result when authorized.
4. Check mobile layout, keyboard use, validation, error handling and translated routes. Test calculations against known values and units.
5. Record expected versus observed behavior with evidence, severity and reproduction steps. Do not count HTTP 200 alone as a successful journey.
6. Repair within authorized scope, repeat affected checks and report untested boundaries. Return a release decision for review.

Required output: Journey test matrix, defects and observable release evidence.

Behavior check: A contact button opens a form but no submission reaches storage. Pass navigation; fail lead capture; don't claim CRM integration.
