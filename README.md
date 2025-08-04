# edk2-source-tarballs
Source tarballs of EDK2 source checkouts + submodules. Avoids need for git.

The GitHub workflow runs nightly. It checks for a new release on the upstream
EDK2 repo, and creates the tarball for it, under a corresponding release on
this repository, if needed. The workflow will do nothing if no new release is
found. But it still has to run nightly since there is no other way to "listen"
for new releases on an upstream repository and trigger the workflow only when
that happens.
