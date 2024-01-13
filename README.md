# OpenSource_blog
Made for Open Source Computing course assignment on running open source software.

Running open-source software consists of several entangled processes. Below is a simple overview of the key components.

Release Numbering:

In Open-Source projects, release numbering follows a structured convention such as semantic versioning. Versions are typically expressed in a “MAJOR.MINOR.PATCH” format, where each increment signals the scope of changes. Major versions denote compatibility-breaking updates, minor denote backward-compatible enhancements, and patch signifies backward-compatible bug fixes.

Release Branches:

Development and stabilization are often separated using release branches. For a GitHub repo, these branches are created from the main development line (usually the `master` branch) to finalize a release version. They allow last-minute fixes and release preparations without disrupting the work on upcoming versions.

Stabilizing Release:

A stabilizing release phase focuses on refinement and bug fixes to ensure the new release is reliable and performs well. Contributors might address issues raised from community feedback during this phase.

Packaging:

Packaging involves assembling the software for distribution. This can include generating binaries or creating packages compatible with various operating systems. GitHub repositories often use tools like GitHub Actions to automate package creation and distribution.

Testing and Releasing:

Testing is integral to Open-Source Software releases and involves automated tests (unit, integration) and community-driven testing to identify issues. This iterative process continues until the release meets quality standards. The release is then tagged in the GitHub repo, signaling its readiness for production use.

Maintaining Multiple Release Lines:

Open-Source Software projects often have to maintain several release lines, ensuring that critical updates and security patches are backported to older, still-supported versions. This is managed through separate branches for each line on GitHub.

Release and Daily Development:

Daily development continues on the `master` branch, with snapshot releases (nightly builds) providing a glimpse of the latest work.

Managing Participants:

Participants in Open-Source Software projects are managed through permissions on GitHub repositories. Main contributors, or 'committers', have direct write access. The broader community can submit changes through pull requests, which maintainers review and merge.

Fork:

Forking on GitHub allows the creation of a project's copy. Contributors can experiment with changes in their fork and later propose these changes to the original repository through pull requests. 

This Django blog application repository is based on another github repo name this https://github.com/YashMarmat/Blog-App-django-v3.git.