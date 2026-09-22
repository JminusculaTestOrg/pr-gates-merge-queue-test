# findings/

One marker file per PR. `PRGATE_PASS` or `PRGATE_FAIL`.

The stub gate scans this directory at the evaluated commit, so a merge group's
verdict is the union over every PR in the group — and the filename attributes
each finding back to its PR.
