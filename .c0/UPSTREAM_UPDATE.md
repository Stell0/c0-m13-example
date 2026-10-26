# Upstream update review

Upstream: https://github.com/Stell0/ns8-czero.git

Baseline: `130b3eb285c99216b20ab144515e12500fcce94e`
Target: `631293d50de6f0faa914554455dbfe61ce623764`

Only registered files are considered. Review tests before merging.

## `build-images.sh`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- build-images.sh
```

## `containers/czero-app/Containerfile`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- containers/czero-app/Containerfile
```

## `containers/czero-postgres/Containerfile`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- containers/czero-postgres/Containerfile
```

## `scripts/sync-upstream.py`: already-current

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- scripts/sync-upstream.py
```

## `scripts/check-core-release.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- scripts/check-core-release.py
```

## `.github/workflows/sync-upstream.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- .github/workflows/sync-upstream.yml
```

## `.github/workflows/test-local.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- .github/workflows/test-local.yml
```

## `.github/workflows/publish-images.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- .github/workflows/publish-images.yml
```

## `.github/workflows/test-module.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- .github/workflows/test-module.yml
```

## `.github/workflows/publish-core.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- .github/workflows/publish-core.yml
```

## `.agents/skills/c0-contribute-upstream/SKILL.md`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- .agents/skills/c0-contribute-upstream/SKILL.md
```

## `.agents/skills/c0-create-feature/SKILL.md`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- .agents/skills/c0-create-feature/SKILL.md
```

## `.agents/skills/c0-develop-core/SKILL.md`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- .agents/skills/c0-develop-core/SKILL.md
```

## `.agents/skills/c0-upgrade-from-upstream/SKILL.md`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- .agents/skills/c0-upgrade-from-upstream/SKILL.md
```

## `imageroot/actions/configure-module/validate-input.json`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- imageroot/actions/configure-module/validate-input.json
```

## `imageroot/actions/get-configuration/20read`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- imageroot/actions/get-configuration/20read
```

## `imageroot/actions/get-configuration/validate-output.json`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- imageroot/actions/get-configuration/validate-output.json
```

## `imageroot/actions/restore-module/20persist-settings`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- imageroot/actions/restore-module/20persist-settings
```

## `imageroot/systemd/user/czero-postgres.service`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- imageroot/systemd/user/czero-postgres.service
```

## `imageroot/systemd/user/czero-worker.service`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- imageroot/systemd/user/czero-worker.service
```

## `imageroot/systemd/user/czero.service`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- imageroot/systemd/user/czero.service
```

## `scripts/normalize-core-sdist.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- scripts/normalize-core-sdist.py
```

## `scripts/select-core-source.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- scripts/select-core-source.py
```

## `.github/workflows/test-core-renovate.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- .github/workflows/test-core-renovate.yml
```

## `tests/development/core-renovate.mjs`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- tests/development/core-renovate.mjs
```

## `.github/workflows/test-core-consumer.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- .github/workflows/test-core-consumer.yml
```

## `tests/core_consumer_runtime_probe.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 631293d50de6f0faa914554455dbfe61ce623764 -- tests/core_consumer_runtime_probe.py
```
