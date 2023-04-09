[![MIT License](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/libranet/minimal-github-project/blob/main/docs/license.md)


https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/about-community-profiles-for-public-repositories

# Naming conventions

## General naming conventions
 - use lowercase for filenames whenever possible. No need to SHOUT!
 - always use a proper file-extension, no README, but readme.md
 - Avoid polluting the root of your project-directory.
 - Only keep files in the root if there are really required there.
 - *.yaml* is the official file-extension for YAML-files.

## Naming of the Github-repository: 
  - dashed lowercase, e.g. foo-bar
  - ascii, avoid non-ascii unicode chars
  - use lowercase, avoid capitals (git clone will create a similar named local directory)
  - prefer dashes over underscores

## Required files to optimize Github-UI

- [license.md](https://github.com/libranet/minimal-github-project/blob/main/license.md): 
  - use license-file in the root of the project, as github will introspect this file to enhance the UI.
  - github will not follow symlinks
  - lowercase + use file-extension, e.g license.md
  - the title in the license-file should contain the name of the license, e.g. MIT
  - github will render a summarized view when viewing the license-file:

![image](https://user-images.githubusercontent.com/469509/230784593-b184c331-cea9-4f0c-a215-4ef7c70425d5.png)

- [docs/code-of-conduct.md]()
  - use lowercase
  - github will recognize a code-of-conduct in the docs/-directory.

- [docs/contributing.md](https://github.com/libranet/minimal-github-project/blob/main/docs/contributing.md)
  - use lowercase
  -  github will recognize a readme in the docs/-directory.

- [docs/readme.md](https://github.com/libranet/minimal-github-project/blob/main/docs/readme.md)
  - use lowercase
  - github will recognize a readme in the docs/-directory.

- [docs/security.md](https://github.com/libranet/minimal-github-project/blob/main/docs/security.md)
  - github will recognize a code-of-conduct in the docs/-directory.

- [.github/CODEOWNERS](https://github.com/libranet/minimal-github-project/blob/main/.github/CODEOWNERS)
  - github is not very consistent with uppercasing/lowercasing required filenames
  - CODEOWNERS must be uppercased
- [.github/ISSUE_TEMPLATE]()
  - the directory ISSUE_TEMPLATE must be uppcased 
- [.github/ISSUE_TEMPLATE/bug_report.md](https://github.com/libranet/minimal-github-project/blob/main/.github/ISSUE_TEMPLATE/bug_report.md)
- [.github/ISSUE_TEMPLATE/feature_request.md](https://github.com/libranet/minimal-github-project/blob/main/.github/ISSUE_TEMPLATE/feature_request.md)
- [.github/dependabot.yaml](https://github.com/libranet/minimal-github-project/blob/main/.github/dependabot.yaml)
- [.github/funding.yaml](https://github.com/libranet/minimal-github-project/blob/main/.github/funding.yaml)
- [.github/pull_request_template.md](https://github.com/libranet/minimal-github-project/blob/main/.github/pull_request_template.md)


# Right navigation in Github

![image](https://user-images.githubusercontent.com/469509/230785019-e9c0d1cf-3e9e-4392-bf53-f3502ee9a86d.png)

# Community Standards
[Community Standards](https://github.com/libranet/minimal-github-project/community)  for this project:
![image](https://user-images.githubusercontent.com/469509/230785567-acd9a9ff-27c3-454c-ab04-d379bce66814.png)

# Security Overview
[Security Overview](https://github.com/libranet/minimal-github-project/security)
![image](https://user-images.githubusercontent.com/469509/230786006-2baebd8a-d07e-42a8-9ffd-877d24b2df1b.png)



