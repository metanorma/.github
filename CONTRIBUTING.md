## Contributing

https://github.com/riboseinc/oss-guides

### Reporting issues

Reports whose diagnosis is precise get fixed fastest. Please lead with:

* observed behaviour, and the expected behaviour;
* reproduction steps, or the reproduction boundary (what does and does
  not trigger the problem);
* environment: gem versions, or the Docker image tag.

Proposed fixes are welcome as pointers, but please mark them clearly as
unverified suggestions rather than ready-to-merge patches. This applies
especially to AI-assisted reports: a fix that looks correct from a
single-repository reading is often pitched at the wrong layer of the
Metanorma stack, because maintainers weigh changes against design
contracts that span several gems. A report is actionable through its
diagnosis, not its patch.
