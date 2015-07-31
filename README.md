Old avatar menu for Google Chrome. Only Apple Mac OS X.

1. Checkout git repository.
2. Open Automator -> Open Chrome.app -> Check a source code.
3. Save your Application folder.
4. chrome://flags/#enable-new-profile-management -> Disabled
5. chrome://flags/#enable-google-profile-info -> Disable
6. Close Google Chrome.
7. Run your Chrome.app

Source code:
```open -a "Google Chrome.app" --args -disable-new-avatar-menu```