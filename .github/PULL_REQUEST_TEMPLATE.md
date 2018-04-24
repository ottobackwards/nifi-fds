Thank you for submitting a contribution to Apache NiFi Fluid Design System.

In order to streamline the review of the contribution we ask you
to ensure the following steps have been taken:

### For all changes:
- [ ] Is there a JIRA ticket associated with this PR? Is it referenced
     in the commit message?

- [ ] Does your PR title start with either NIFI-XXXX or NIFIREG-XXXX where XXXX is the JIRA number you are trying to resolve? Pay particular attention to the hyphen "-" character.

- [ ] Has your PR been rebased against the latest commit within the target branch (typically master)?

- [ ] Is your initial contribution a single, squashed commit?

### For code changes:
- [ ] Have you ensured that a full build is executed via npm build at the root nifi-fds folder?
- [ ] Have you ensured that the full suite of tests is executed via npm test at the root nifi-fds folder?
- [ ] Have you written or updated unit tests to verify your changes?
- [ ] Have you written or updated the Apache NiFi Fluid Design System Demo application to demonstrate, provide examples of usage, and to verify your changes?
- [ ] If adding new dependencies to the code, are these dependencies licensed in a way that is compatible for inclusion under [ASF 2.0](http://www.apache.org/legal/resolved.html#category-a)?
- [ ] If applicable, have you updated the LICENSE file, including the main LICENSE file under nifi-fds?
- [ ] If applicable, have you updated the NOTICE file, including the main NOTICE file found under nifi-fds?

### For documentation related changes:
- [ ] Have you ensured that format looks appropriate for the output in which it is rendered?

### Note:
Please ensure that once the PR is submitted, you check travis-ci for build issues and submit an update to your PR as soon as possible.

### Reviewers, please perform the following in order to validate the changes:
- [ ] Checkout the gh-pages branch.
- [ ] Edit the package.json file in the root nifi-fds folder and update the nifi-fds package to point to the pull request at git+https://github.com/<user>/<repo>.git#<branch>.
- [ ] ‘npm install’ in the root nifi-fds folder.
- [ ] ‘npm install’ in the node_modules/nifi-fds folder.
- [ ] ‘npm run build’ in the node_modules/nifi-fds folder.
- [ ] Update the base href element in the index.html in the root nifi-fds folder to ‘/‘.
- [ ] Start a local http-server via ‘npm start’ in the root nifi-fds folder and verify the UI/UX in a browser.