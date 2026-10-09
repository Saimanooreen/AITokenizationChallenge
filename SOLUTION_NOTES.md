# Solution Notes

## Problem statement
Rewrite a long, conversational request for adding CSV export to an existing React analytics table into a shorter, structured prompt without losing requirements.

## Solution approach
- Extracted the objective, functional constraints, technical constraints, and expected implementation/reporting process.
- Removed greeting and repeated task statements.
- Grouped requirements and implementation steps under headings and bullets.
- Kept each explicit behavior and safeguard.

## Preserved requirements
- CSV export button for the existing React analytics table.
- Export rows after the current filters have been applied.
- Respect the existing sort order.
- Export visible columns only and preserve their displayed order.
- Exclude hidden columns.
- Format dates as ISO 8601.
- Do not add packages or dependencies.
- Inspect the project and identify relevant files before changes.
- Implement the feature.
- Report changed files and verification steps.
- Verify existing filtering and sorting continue to work.

## Character-based estimate
- Original: 878 characters → 219.50 estimated tokens.
- Optimized: 612 characters → 153.00 estimated tokens.
- Estimated reduction: 30.30%.

Formula: `estimated tokens = total characters ÷ 4`; `reduction (%) = ((original − optimized) ÷ original) × 100`.

## Validation checklist
- [ ] Every original functional and technical constraint appears in the optimized prompt.
- [ ] Prompt can be understood without the original scenario.
- [ ] No package/dependency addition is requested.
- [ ] Existing filter/sort behavior is explicitly protected and tested.
- [ ] Character counts use the exact text submitted.
- [ ] GitHub repository is public or the evaluator has access, as instructed by the organizer.

## Scope note
This challenge is a prompt-optimization task. No actual React repository was supplied, so this package does not pretend to implement or test the dashboard feature. The optimized prompt instructs the coding assistant to inspect the target project, implement the change, and verify it there.
