# Fleet Releases

Public CI/CD proxy for the private `Infinity-light/fleet` source repository.

The repository contains workflows and verified release assets only. Source code
is checked out at the exact `repo/ref/source_sha` carried by
`repository_dispatch`. Normal deploy and release requests are sent directly by
`deploy-setup`, so private GitHub Actions minutes are not required.
