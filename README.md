# glance-conformance

Live conformance fixture for [@mattstack/glance](https://github.com/m4ttstack/glance).

Branches and pull requests here are created and cleaned up by the conformance
harness. Nothing in this repository is precious.

The `controllable` CI job fails when a branch contains a file named
`fail-marker`, which is how the harness gets a deterministically failing job
to exercise retryJob and fetchJobTrace against.
