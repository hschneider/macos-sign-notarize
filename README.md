

![macos-sign-notarize-script](https://marketmix.com/git-assets/macos-sign-notarize/macos-sign-notarize-script.jpg)

# macos-sign-notarize

**Automate Apple's Sign- and Notarization-Process from commandline.** 

With this scripts, you can easily sign and notarize macOS Apps, PKGs and DMGs. No more commandline parameters to remember. Just setup the baked-in credentials and you are good to go. 

## sign

Setup:

```bash
# Setup.start
#
# The ID of your "Developer ID Application", assigned to your Keyring.
# This is usually your first- and lastname:
#
ID="Your Name"  
#
# Setup.end
```

Usage:

```bash
./sign application.app
```

## notarize

Setup:

```bash
# Setup.start
#
USR="name@domain.com"           # Your Apple dev account's email address
PWD="xxxx-xxxx-xxxx-xxxx"       # Your app specific password, NOT your login password
TEAM="xxxxxxxx"                 # Your dev team ID
#
# Setup.end
```

Usage:

```bash
./notarize application.app
```

