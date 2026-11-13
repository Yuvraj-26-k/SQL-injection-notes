# SQL Injection Study Notes

**Beginner web-security notes, with examples and defensive reasoning.**

The original [sqli.txt](sqli.txt) contains study material on query construction,
injection categories, lab examples and prepared statements. It is preserved
unchanged. These are learning notes, not a disclosed vulnerability or a claim
of professional penetration-testing experience.

## Read or clone

Open [the original notes](sqli.txt) on GitHub, or:

```sh
git clone https://github.com/Yuvraj-26-k/SQL-injection-notes.git
cd SQL-injection-notes
```

No executable lab, dependency installation or automated testing is included.
Use only an isolated environment you own or are authorized to assess when
experimenting with the concepts.

## Technical review notes

Some original wording is informal or oversimplified and remains subject to
review. SQL is a query language, not a database itself. A delayed response alone
does not establish SQL injection; control tests and environmental explanation
are necessary. Correctly parameterized values address a major injection cause,
but they are not a universal guarantee for every dynamic query construction.
Input validation is a supporting control rather than a substitute for safe
query construction.

Study against primary references:

- [OWASP SQL Injection Prevention Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/SQL_Injection_Prevention_Cheat_Sheet.html)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)

## Next steps

Add a versioned local lab, separate observations from assumptions, document
negative tests and remediation, and link references to individual claims.
[Cybersecurity Field Notes](https://github.com/Yuvraj-26-k/cybersecurity-field-notes)
has report templates for that future work. No material or Git history is moved
or consolidated by this documentation update.
