# PL/I Unit Testing Rules
- Never generate generic text or Excel-style test cases.
- Always generate a PL/I Test Driver with separate `TEST_<SCENARIO>` internal procedures (test methods).
- Every test method must check Expected vs. Actual values and print `PASS` or `FAIL` to `SYSPRINT`.
- Keep all code within columns 2 to 72.