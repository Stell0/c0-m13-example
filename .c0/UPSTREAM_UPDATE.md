# Upstream update review

Upstream: https://github.com/Stell0/ns8-czero.git

Baseline: `130b3eb285c99216b20ab144515e12500fcce94e`
Target: `ec940a931bbdd43bf2defe655934a3a3702edb3f`

Only registered files are considered. Review tests before merging.

## `scripts/sync-upstream.py`: review

Your customized file was preserved. Compare the upstream change and port the relevant behavior manually.
After testing, remove this file's needs_review, review_from and review_reason markers; do not replace application customizations blindly.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e ec940a931bbdd43bf2defe655934a3a3702edb3f -- scripts/sync-upstream.py
```

## `.github/workflows/sync-upstream.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e ec940a931bbdd43bf2defe655934a3a3702edb3f -- .github/workflows/sync-upstream.yml
```

## `.github/workflows/test-local.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e ec940a931bbdd43bf2defe655934a3a3702edb3f -- .github/workflows/test-local.yml
```

## `.github/workflows/publish-core.yml`: review

The current workflow was preserved: the native GitHub token cannot update workflow files.
Review and port this change in a maintainer checkout with workflows permission, preserving customizations.
Only use --allow-workflow-updates when the publishing credential has that permission.
After testing, remove needs_review, review_from and review_reason for the resolved migration.

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e ec940a931bbdd43bf2defe655934a3a3702edb3f -- .github/workflows/publish-core.yml
```

## `.agents/skills/c0-upgrade-from-upstream/SKILL.md`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e ec940a931bbdd43bf2defe655934a3a3702edb3f -- .agents/skills/c0-upgrade-from-upstream/SKILL.md
```

## `scripts/normalize-core-sdist.py`: apply

Inspect the upstream change in a trusted upstream checkout:

```sh
git diff 130b3eb285c99216b20ab144515e12500fcce94e ec940a931bbdd43bf2defe655934a3a3702edb3f -- scripts/normalize-core-sdist.py
```
