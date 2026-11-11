# sast-triage consumer smoke test

Runs the published `lansiquo/sast-triage` GitHub Action exactly as a user would, pinned by tag on a real runner. Updated by the Software Factory's Release Bot after each release (approval A-14).

- `clean`: a project with no findings; the Action must pass.
- `p1`: a project with a planted P1 (`os.system` on user input); the gate must fail.
