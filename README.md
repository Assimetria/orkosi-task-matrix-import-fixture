# Harbour Notes — the GitHub import fixture of the Orkosi release matrix

A two-page static site (`index.html`, `about.html`, `styles.css`) the task matrix imports from GitHub on every run
(`backend/tests/e2e/task-matrix/lib/import-door.js`): the import births a product, its first build must go green on the
test copy, and one code row is filed on it. The ONE source of these files is the Orkosi repository
(`backend/tests/e2e/task-matrix/fixtures/github-import/`); the public mirror `Assimetria/orkosi-task-matrix-import-fixture`
is written by `scripts/sync-task-matrix-import-fixture.sh` and never edited by hand. Nothing here is a real service.
