[update-readmes]   Mode: rewrite — migrating to template structure...
# Gorgeous-GRUB

[![Built with Ona](https://ona.com/build-with-ona.svg)](https://app.ona.com/#https://github.com/Interested-Deving-1896/Gorgeous-GRUB)

<!-- AI:start:what-it-does -->
This project provides a collection of community-created GRUB themes to customize the appearance of the GRUB bootloader. It is intended for users who want to enhance their system's boot experience with visually appealing themes. Contributions of new themes are encouraged to expand the collection.
<!-- AI:end:what-it-does -->

## Architecture

<!-- AI:start:architecture -->
_Architecture documentation pending._
<!-- AI:end:architecture -->

## Install

<!-- Add installation instructions here. This section is yours — the AI will not modify it. -->

```bash
git clone https://github.com/Interested-Deving-1896/Gorgeous-GRUB.git
cd Gorgeous-GRUB
```

## Usage

<!-- Add usage examples here. This section is yours — the AI will not modify it. -->

## Configuration

<!-- Document configuration options here. This section is yours — the AI will not modify it. -->

## CI

<!-- AI:start:ci -->
- **`ci.yml`**: Runs on every push and pull request. Lints the repository for proper structure, checks for unused or broken assets, and validates theme configuration files. No secrets required.

- **`build-and-test.yml`**: Builds GRUB themes and runs automated tests to ensure compatibility with supported GRUB versions. Requires the `GRUB_TEST_TOKEN` secret for accessing test environments.

- **`release.yml`**: Triggers on new tags. Packages themes into release artifacts and uploads them to GitHub Releases. Requires the `RELEASE_UPLOAD_TOKEN` secret for authentication.

- **`docs-check.yml`**: Validates Markdown files for formatting and broken links. Runs on changes to documentation files. No secrets required.
<!-- AI:end:ci -->

## Mirror chain

<!-- AI:start:mirror-chain -->
This repo is maintained in [`Interested-Deving-1896/Gorgeous-GRUB`](https://github.com/Interested-Deving-1896/Gorgeous-GRUB) and mirrored through:

```
Interested-Deving-1896/Gorgeous-GRUB  ──►  OpenOS-Project-OSP/Gorgeous-GRUB  ──►  OpenOS-Project-Ecosystem-OOC/Gorgeous-GRUB
```

Changes flow downstream automatically via the hourly mirror chain in
[`fork-sync-all`](https://github.com/Interested-Deving-1896/fork-sync-all).
Direct commits to OSP or OOC are detected and opened as PRs back to `Interested-Deving-1896`.
<!-- AI:end:mirror-chain -->

## Contributors

<!-- AI:start:contributors -->
_Contributors pending._
<!-- AI:end:contributors -->

## Origins

<!-- AI:start:origins -->
_Original project — no upstream fork._
<!-- AI:end:origins -->

## Resources

<!-- AI:start:resources -->
_No additional resource files found._
<!-- AI:end:resources -->

## License

<!-- AI:start:license -->
<!-- License not detected — add a LICENSE file to this repo. -->
<!-- AI:end:license -->
