# EasyCLA is Disabled

EasyCLA is disabled so the organizations that I want EasyCLA to monitor are not monitored.

**Solution:**

This is a known issue. GitHub is set up to permit administrators and organization owners to have maximum flexibility, which includes disabling apps like EasyCLA. Do the following steps to mitigate this problem immediately. Be sure to educate your administrators and organization owners about this GitHub setup and solution.

**Do these steps:**

1. As the GitHub organization owner or administrator, go to the GitHub repository that you want EasyCLA to monitor.
2. Click **Settings** from the top menu.

   ​![Settings](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LuWIT3NfRhMt-F50U5n%2F-LubFsJ38Zif4of6UwPb%2F-LubFvDbsKMSPkqxloFT%2Fcla-github-repository-settings.png?generation=1574764271312268&alt=media)​

   Settings appear with Options in the left pane.

3. Click **Branches** under Options.

   ​![Branches](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LuWIT3NfRhMt-F50U5n%2F-LubG1kU7pxWYG0JGPwu%2F-LubG2T91Sr92nG14RcV%2Fcla-github-options.png?generation=1574764296848870&alt=media)​

   Branch settings appear.

4. Select **master** for the Default branch. **Edit** or **Add rule** for Branch protection rules of your organization.

   ​![Branch Protection Rules](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LuWIT3NfRhMt-F50U5n%2F-LubG1kU7pxWYG0JGPwu%2F-LubG2TBazpSjsubekhV%2Fcla-github-branch-add-rule.png?generation=1574764296981213&alt=media)​

   Branch protection rule settings appear.

5. Select the following checkboxes in Rule settings and click **Create**.

   * Require status checks to pass before merging
   * Require branches to be up to date before merging
   * Include administrators

   ​![Rule Settings](https://firebasestorage.googleapis.com/v0/b/gitbook-28427.appspot.com/o/assets%2F-LuWIT3NfRhMt-F50U5n%2F-LubG1kU7pxWYG0JGPwu%2F-LubG2TDPYj0kfWjTVFF%2Fcla-github-branch-protection-rule.png?generation=1574764300844339&alt=media)​

