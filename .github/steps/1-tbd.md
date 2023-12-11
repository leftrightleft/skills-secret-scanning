<!--
  <<< Author notes: Step 1 >>>
  Choose 3-5 steps for your course.
  The first step is always the hardest, so pick something easy!
  Link to docs.github.com for further explanations.
  Encourage users to open new tabs for steps!
  TBD-step-1-notes.
-->

## Step 1: Enable Secret Scanning

_Welcome to "Introduction to Secret Scanning"! :wave:_

In this step, you will enable secret scanning on this repository. Once secret scanning is enabled, you will add a new credential to see how secret scanning identifies the credential.  

**What is a credential**: In the context of secret scanning, a credential is a plain-text string that autorizes a user to any number of third-party services.  Examples could be AWS secret access keys/ID's, Google API keys, or Stripe API tokens.  View our entire list of supported patterns [here](https://docs.github.com/en/code-security/secret-scanning/secret-scanning-patterns#supported-secrets).

### :keyboard: Activity 1: Enable secret scanning

1. Open a new browser tab, and work on the steps in your second tab while you read the instructions in this tab.
1. In your newly created repository, select **Settings** from the top navigation bar.
1. Under the **Security** section on the left side, select **Code security and analysis**.
1. Scroll to the bottom of this page and select the **Enable** button next to "Secret scanning"
![enable-secret-scanning.png](/images/enable-secret-scanning.png)

**Note:** When you enable secret scanning, the option to enable push protection show up. Don't enable push protection yet. 


### :keyboard: Activity 2: Commit a token

Now that we have secret scanning enabled in this repository, let's commit a new token to see how it works. We'll commit an AWS key and access ID to the repository. Don't worry, this is an inactive token that can't be used to log in to AWS.

1. Like the first activity, you will need to work on these steps in a second browser tab.
1. Click the Code tab in your repository.
1. Select the routes.py file.
1. Click the Edit button to the right.
``` yaml
default:
  aws_access_key_id: AKIAQYLPMN5HNM4OZ56B
  aws_secret_access_key: Rm29CHLQCeaT6V/Rsw3UFWW1/UWQ0lhsWBa3bdca
  output: json
  region: us-east-2
```

1. 
1. Wait about 20 seconds then refresh this page (the one you're following instructions from). [GitHub Actions](https://docs.github.com/en/actions) will automatically update to the next step.
