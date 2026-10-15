# Upstream update review

Upstream: https://github.com/Stell0/ns8-czero.git

Baseline: `130b3eb285c99216b20ab144515e12500fcce94e`
Target: `849736ab70f441ec05f5124b747fb6f6ef27991e`

Only registered files are considered. Review tests before merging.

## `build-images.sh`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- build-images.sh
```

## `containers/czero-app/Containerfile`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- containers/czero-app/Containerfile
```

## `scripts/sync-upstream.py`: already-current

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- scripts/sync-upstream.py
```

## `.github/workflows/sync-upstream.yml`: already-current

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- .github/workflows/sync-upstream.yml
```

## `.github/workflows/test-local.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- .github/workflows/test-local.yml
```

## `.github/workflows/publish-images.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- .github/workflows/publish-images.yml
```

## `.github/workflows/publish-core.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- .github/workflows/publish-core.yml
```

## `.agents/skills/c0-contribute-upstream/SKILL.md`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- .agents/skills/c0-contribute-upstream/SKILL.md
```

## `.agents/skills/c0-upgrade-from-upstream/SKILL.md`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- .agents/skills/c0-upgrade-from-upstream/SKILL.md
```

## `scripts/normalize-core-sdist.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- scripts/normalize-core-sdist.py
```

## `scripts/select-core-source.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- scripts/select-core-source.py
```

## `.github/workflows/test-core-renovate.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- .github/workflows/test-core-renovate.yml
```

## `tests/development/core-renovate.mjs`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- tests/development/core-renovate.mjs
```

## `.github/workflows/test-core-consumer.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- .github/workflows/test-core-consumer.yml
```

## `tests/core_consumer_runtime_probe.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e 849736ab70f441ec05f5124b747fb6f6ef27991e -- tests/core_consumer_runtime_probe.py
```
