<!--
  <<< Author notes: Step 2 >>>
  Start this step by acknowledging the previous step.
  Define terms and link to docs.github.com.
  TBD-step-2-notes.
-->

## Step 2: Review secret scanning findings

_You did Step 1: Enable secret scanning! :tada:_

In the last step, you enabled secret scanning on the repository and committed an AWS credential to the repository.  In this step, you'll first review the secret scanning findings. Afterward, you'll enable push protection which prevents you from accidentally writing credentials to a repository. Finally, you'll attempt to write a new credential to see how push protection works.

**What is push protection**: When code is being written to GitHub (a push), secret scanning checks for high-confidence secrets (those identified with a low false positive rate). Secret scanning lists any secrets it detects so the author can review the secrets and remove them or, if needed, allow those secrets to be pushed.

### :keyboard: Activity 1: Review findings

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
2. Navigate to the **Security** tab in the top navigation bar of your repository.
3. Select **Secret scanning** under the "Vulnerability alerts" heading in left-side navigation bar.

## Step 3: Enable push protection

_You did Step 1: Enable secret scanning! :tada:_

### :keyboard: Activity 2: Enable push protection

1. TBD-step-2-instructions.

### :keyboard: Activity 2: Attempt to push a secret

1. TBD-step-2-instructions.
