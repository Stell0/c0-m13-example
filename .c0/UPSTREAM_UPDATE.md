# Upstream update review

Upstream: https://github.com/Stell0/ns8-czero.git

Baseline: `130b3eb285c99216b20ab144515e12500fcce94e`
Target: `4af1d703e786f9f4f6b3f09120b99f9380a31b99`

Only registered files are considered. Review tests before merging.

## `build-images.sh`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- build-images.sh
```

## `containers/czero-app/Containerfile`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- containers/czero-app/Containerfile
```

## `containers/czero-postgres/Containerfile`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- containers/czero-postgres/Containerfile
```

## `scripts/sync-upstream.py`: already-current

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- scripts/sync-upstream.py
```

## `scripts/check-core-release.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- scripts/check-core-release.py
```

## `.github/workflows/sync-upstream.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- .github/workflows/sync-upstream.yml
```

## `.github/workflows/test-local.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- .github/workflows/test-local.yml
```

## `.github/workflows/publish-images.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- .github/workflows/publish-images.yml
```

## `.github/workflows/test-module.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- .github/workflows/test-module.yml
```

## `.github/workflows/publish-core.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- .github/workflows/publish-core.yml
```

## `.agents/skills/c0-contribute-upstream/SKILL.md`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- .agents/skills/c0-contribute-upstream/SKILL.md
```

## `.agents/skills/c0-create-feature/SKILL.md`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- .agents/skills/c0-create-feature/SKILL.md
```

## `.agents/skills/c0-develop-core/SKILL.md`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- .agents/skills/c0-develop-core/SKILL.md
```

## `.agents/skills/c0-upgrade-from-upstream/SKILL.md`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- .agents/skills/c0-upgrade-from-upstream/SKILL.md
```

## `imageroot/actions/configure-module/validate-input.json`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/actions/configure-module/validate-input.json
```

## `imageroot/actions/create-module/40scheduler`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/actions/create-module/40scheduler
```

## `imageroot/actions/get-configuration/20read`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/actions/get-configuration/20read
```

## `imageroot/actions/get-configuration/validate-output.json`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/actions/get-configuration/validate-output.json
```

## `imageroot/actions/restore-module/20persist-settings`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/actions/restore-module/20persist-settings
```

## `imageroot/actions/restore-module/30validate-backup`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/actions/restore-module/30validate-backup
```

## `imageroot/actions/restore-module/80start-services`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/actions/restore-module/80start-services
```

## `imageroot/bin/czero_retrieval_config.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/bin/czero_retrieval_config.py
```

## `imageroot/bin/module-cleanup-state`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/bin/module-cleanup-state
```

## `imageroot/bin/module-dump-state`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/bin/module-dump-state
```

## `imageroot/systemd/user/czero-postgres.service`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/systemd/user/czero-postgres.service
```

## `imageroot/systemd/user/czero-worker.service`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/systemd/user/czero-worker.service
```

## `imageroot/systemd/user/czero.service`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/systemd/user/czero.service
```

## `imageroot/update-module.d/60scheduler`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- imageroot/update-module.d/60scheduler
```

## `scripts/normalize-core-sdist.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- scripts/normalize-core-sdist.py
```

## `scripts/select-core-source.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- scripts/select-core-source.py
```

## `.github/workflows/test-core-renovate.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- .github/workflows/test-core-renovate.yml
```

## `tests/development/core-renovate.mjs`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- tests/development/core-renovate.mjs
```

## `.github/workflows/test-core-consumer.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- .github/workflows/test-core-consumer.yml
```

## `tests/core_consumer_runtime_probe.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 4af1d703e786f9f4f6b3f09120b99f9380a31b99 -- tests/core_consumer_runtime_probe.py
```
