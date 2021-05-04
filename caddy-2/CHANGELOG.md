# Changelog since v0.3.0
- Bump caddy to v2.4.0-rc.1 
- Merge pull request #62 from einschmidt/dependabot/github_actions/docker/setup-buildx-action-v1.3.0

Bump docker/setup-buildx-action from v1.2.0 to v1.3.0 
- Bump docker/setup-buildx-action from v1.2.0 to v1.3.0

Bumps [docker/setup-buildx-action](https://github.com/docker/setup-buildx-action) from v1.2.0 to v1.3.0.
- [Release notes](https://github.com/docker/setup-buildx-action/releases)
- [Commits](https://github.com/docker/setup-buildx-action/compare/v1.2.0...0d135e0c2fc0dba0729c1a47ecfcf5a3c7f8579e)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #61 from einschmidt/dependabot/github_actions/docker/login-action-v1.9.0

Bump docker/login-action from v1.8.0 to v1.9.0 
- Bump docker/login-action from v1.8.0 to v1.9.0

Bumps [docker/login-action](https://github.com/docker/login-action) from v1.8.0 to v1.9.0.
- [Release notes](https://github.com/docker/login-action/releases)
- [Commits](https://github.com/docker/login-action/compare/v1.8.0...28218f9b04b4f3f62068d7b6ce6ca5b26e35336c)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #60 from einschmidt/dependabot/github_actions/docker/setup-qemu-action-v1.1.0

Bump docker/setup-qemu-action from v1.0.2 to v1.1.0 
- Merge pull request #59 from einschmidt/dependabot/github_actions/docker/setup-buildx-action-v1.2.0

Bump docker/setup-buildx-action from v1.1.2 to v1.2.0 
- Bump docker/setup-qemu-action from v1.0.2 to v1.1.0

Bumps [docker/setup-qemu-action](https://github.com/docker/setup-qemu-action) from v1.0.2 to v1.1.0.
- [Release notes](https://github.com/docker/setup-qemu-action/releases)
- [Commits](https://github.com/docker/setup-qemu-action/compare/v1.0.2...c308fdd69d26ed66f4506ebd74b180abe5362145)

Signed-off-by: dependabot[bot] <support@github.com> 
- Bump docker/setup-buildx-action from v1.1.2 to v1.2.0

Bumps [docker/setup-buildx-action](https://github.com/docker/setup-buildx-action) from v1.1.2 to v1.2.0.
- [Release notes](https://github.com/docker/setup-buildx-action/releases)
- [Commits](https://github.com/docker/setup-buildx-action/compare/v1.1.2...012185ccbeb554a7f5f987bea0f1a73519b3cdf5)

Signed-off-by: dependabot[bot] <support@github.com> 
- Fix typo 
- Disable shellsheck SC2207 
- Fix shellcheck 2179 
- Merge pull request #58 from einschmidt:Prettify-function

Prettify function 
- Prettify function 
- Merge pull request #57 from einschmidt:Fix-YAML-error

Add new line character to new workflow file 
- Add new line character to new workflow file 
- Merge pull request #56 from einschmidt:Fix-Shellcheck

Fix Shellcheck Error 
- Fix Shellcheck Error 
- Merge pull request #55 from einschmidt:Fix-markdown-errors

Fix markdown errors 
- Fix markdown errors 
- Merge pull request #54 from mdegat01/patch-1

Use `args` as an array not as a string 
- bashio::config does not return arrays, making one 
- Use `args` as an array not as a string

The `args` config accepts an array of strings. But when it uses it it treats it like a single string config by doing `${ARGS}`. It should be doing `${ARGS[@]}` in the run statement of Caddy so all elements of the args array are passed in as individual arguments to `caddy`. 
- Merge pull request #53 from einschmidt:Update-CI

Add pr-label action 
- Add pr-label action 
- Merge pull request #52 from einschmidt/dependabot/github_actions/brpaz/hadolint-action-v1.4.0

Bump brpaz/hadolint-action from v1.3.1 to v1.4.0 
- Bump brpaz/hadolint-action from v1.3.1 to v1.4.0

Bumps [brpaz/hadolint-action](https://github.com/brpaz/hadolint-action) from v1.3.1 to v1.4.0.
- [Release notes](https://github.com/brpaz/hadolint-action/releases)
- [Changelog](https://github.com/hadolint/hadolint-action/blob/master/.releaserc)
- [Commits](https://github.com/brpaz/hadolint-action/compare/v1.3.1...473e36ba306c199243ffe4f1e652a8b60a8fa296)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #51 from einschmidt/dependabot/github_actions/actions/cache-v2.1.5

Bump actions/cache from v2.1.4 to v2.1.5 
- Bump actions/cache from v2.1.4 to v2.1.5

Bumps [actions/cache](https://github.com/actions/cache) from v2.1.4 to v2.1.5.
- [Release notes](https://github.com/actions/cache/releases)
- [Commits](https://github.com/actions/cache/compare/v2.1.4...1a9e2138d905efd099035b49d8b7a3888c653ca8)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #50 from einschmidt:Update-docs

Update DOCS.md 
- Update DOCS.md 
- Merge pull request #49 from einschmidt:Fix_shellcheck

Fix caddy.sh 
- Fix caddy.sh 
- Merge pull request #48 from einschmidt:Update-docs

Update DOCS.md 
- Update DOCS.md 
- Merge pull request #47 from einschmidt:Bump-Base-image-version-to-9.1.7

Update build.json 
- Update build.json 
- Merge pull request #46 from einschmidt:Caddy-fmt

Prettify Caddyfile function 
- Prettify Caddyfile function 
- Merge pull request #45 from einschmidt:Rewrite-Caddyfile-check

Rewrite Caddyfile check 
- Rewrite Caddyfile check 
- Merge pull request #44 from einschmidt:Upgrade-caddy-at-startup

Upgrade caddy at startup 
- Merge pull request #43 from einschmidt:Make-the-share-folder-writable

Add write rights to the share folder 
- Add write rights to the share folder 
- Upgrade caddy at startup 
- Merge pull request #42 from einschmidt:Move-custom-caddy-checks

Move-custom-caddy-checks 
- Fix position 
- Check Caddy at container initialisation 
- Merge pull request #41 from einschmidt:Remove-port-config

Remove port config 
- Remove port config 
- Merge pull request #40 from einschmidt:Bump-base-image-version-to-9.1.6

Bump base image version to 9.1.6 
- Bump base image version to 9.1.6 
- Merge pull request #39 from einschmidt/dependabot/github_actions/docker/setup-buildx-action-v1.1.2

Bump docker/setup-buildx-action from v1.1.1 to v1.1.2 
- Merge pull request #38 from einschmidt/dependabot/github_actions/docker/setup-qemu-action-v1.0.2

Bump docker/setup-qemu-action from v1.0.1 to v1.0.2 
- Bump docker/setup-buildx-action from v1.1.1 to v1.1.2

Bumps [docker/setup-buildx-action](https://github.com/docker/setup-buildx-action) from v1.1.1 to v1.1.2.
- [Release notes](https://github.com/docker/setup-buildx-action/releases)
- [Commits](https://github.com/docker/setup-buildx-action/compare/v1.1.1...2a4b53665e15ce7d7049afb11ff1f70ff1610609)

Signed-off-by: dependabot[bot] <support@github.com> 
- Bump docker/setup-qemu-action from v1.0.1 to v1.0.2

Bumps [docker/setup-qemu-action](https://github.com/docker/setup-qemu-action) from v1.0.1 to v1.0.2.
- [Release notes](https://github.com/docker/setup-qemu-action/releases)
- [Commits](https://github.com/docker/setup-qemu-action/compare/v1.0.1...25f0500ff22e406f7191a2a8ba8cda16901ca018)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #37 from einschmidt/dependabot/github_actions/docker/build-push-action-v2.4.0

Bump docker/build-push-action from v2.3.0 to v2.4.0 
- Bump docker/build-push-action from v2.3.0 to v2.4.0

Bumps [docker/build-push-action](https://github.com/docker/build-push-action) from v2.3.0 to v2.4.0.
- [Release notes](https://github.com/docker/build-push-action/releases)
- [Commits](https://github.com/docker/build-push-action/compare/v2.3.0...e1b7f96249f2e4c8e4ac1519b9608c0d48944a1f)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #36 from einschmidt/dependabot/github_actions/ludeeus/action-shellcheck-1.1.0

Bump ludeeus/action-shellcheck from 1.0.0 to 1.1.0 
- Bump ludeeus/action-shellcheck from 1.0.0 to 1.1.0

Bumps [ludeeus/action-shellcheck](https://github.com/ludeeus/action-shellcheck) from 1.0.0 to 1.1.0.
- [Release notes](https://github.com/ludeeus/action-shellcheck/releases)
- [Commits](https://github.com/ludeeus/action-shellcheck/compare/1.0.0...94e0aab03ca135d11a35e5bfc14e6746dc56e7e9)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #35 from einschmidt/dependabot/github_actions/release-drafter/release-drafter-v5.15.0

Bump release-drafter/release-drafter from v5.14.0 to v5.15.0 
- Bump release-drafter/release-drafter from v5.14.0 to v5.15.0

Bumps [release-drafter/release-drafter](https://github.com/release-drafter/release-drafter) from v5.14.0 to v5.15.0.
- [Release notes](https://github.com/release-drafter/release-drafter/releases)
- [Commits](https://github.com/release-drafter/release-drafter/compare/v5.14.0...fe52e97d262833ae07d05efaf1a239df3f1b5cd4)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #33 from einschmidt:Bump-base-image-version

Bump base image version to 9.1.5 
- Bump base image version to 9.1.5 
- Merge pull request #32 from einschmidt/dependabot/github_actions/actions/stale-v3.0.18

Bump actions/stale from v3.0.17 to v3.0.18 
- Bump actions/stale from v3.0.17 to v3.0.18

Bumps [actions/stale](https://github.com/actions/stale) from v3.0.17 to v3.0.18.
- [Release notes](https://github.com/actions/stale/releases)
- [Commits](https://github.com/actions/stale/compare/v3.0.17...3b3c3f03cd4d8e2b61e179ef744a0d20efbe90b4)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #30 from einschmidt/dependabot/github_actions/docker/build-push-action-v2.3.0

Bump docker/build-push-action from v2.2.2 to v2.3.0 
- Merge pull request #31 from einschmidt/dependabot/github_actions/actions/stale-v3.0.17

Bump actions/stale from v3.0.16 to v3.0.17 
- Bump actions/stale from v3.0.16 to v3.0.17

Bumps [actions/stale](https://github.com/actions/stale) from v3.0.16 to v3.0.17.
- [Release notes](https://github.com/actions/stale/releases)
- [Commits](https://github.com/actions/stale/compare/v3.0.16...996798eb71ef485dc4c7b4d3285842d714040c4a)

Signed-off-by: dependabot[bot] <support@github.com> 
- Bump docker/build-push-action from v2.2.2 to v2.3.0

Bumps [docker/build-push-action](https://github.com/docker/build-push-action) from v2.2.2 to v2.3.0.
- [Release notes](https://github.com/docker/build-push-action/releases)
- [Commits](https://github.com/docker/build-push-action/compare/v2.2.2...9379083e426e2e84abb80c8c091f5cdeb7d3fd7a)

Signed-off-by: dependabot[bot] <support@github.com> 
- Merge pull request #29 from einschmidt:Update-base-image-version

Update-base-image-version 
- Merge pull request #28 from einschmidt:Update-Caddy-version-to-2.4.0-beta.1

Update-Caddy-version-to-2.4.0-beta.1 
- Merge pull request #27 from einschmidt:Add-debug-information

Add-debug-information 
- Add debug informations 
- Update caddy version 
- Update base image version 
- Merge pull request #26 from einschmidt/dependabot/github_actions/release-drafter/release-drafter-v5.14.0

Bump release-drafter/release-drafter from v5.13.0 to v5.14.0 
- Bump release-drafter/release-drafter from v5.13.0 to v5.14.0

Bumps [release-drafter/release-drafter](https://github.com/release-drafter/release-drafter) from v5.13.0 to v5.14.0.
- [Release notes](https://github.com/release-drafter/release-drafter/releases)
- [Commits](https://github.com/release-drafter/release-drafter/compare/v5.13.0...e5ccf147077e46b0225a80bbe314d795d77bb7a2)

Signed-off-by: dependabot[bot] <support@github.com> 
