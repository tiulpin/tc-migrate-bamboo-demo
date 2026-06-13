# tc-migrate-bamboo-demo

Minimal Go module with a **Bamboo Specs** plan (`bamboo-specs/bamboo.yml`, two stages `Build` → `Test`) used to exercise `teamcity migrate`'s Bamboo path end-to-end: stage→job flattening, cross-stage dependencies, `checkout` removal, `script` tasks, and `${bamboo.*}` → `%param%` substitution.
