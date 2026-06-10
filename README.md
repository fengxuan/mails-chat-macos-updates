# MailsChat macOS Updates

This repository is the public Sparkle update source for MailsChat macOS.

It is intentionally separate from the private app source repository. The private repository builds, signs, notarizes, and tags releases. GitHub Actions then pushes the public update snapshot into this repository.

## Expected contents

- `mailschat/mac/appcast.xml`
- `mailschat/mac/MailsChatMac-*.zip`
- optional release notes files copied alongside each published archive

## GitHub Pages

Enable GitHub Pages from the `main` branch root.

Default Pages base URL:

```text
https://fengxuan.github.io/mails-chat-macos-updates/
```

Sparkle feed URL examples:

```text
https://fengxuan.github.io/mails-chat-macos-updates/mailschat/mac/appcast.xml
https://downloads.canyin.uk/mailschat/mac/appcast.xml
```

If you want existing installed clients to keep polling the current `downloads.canyin.uk` path, attach that custom domain to this repository's GitHub Pages site instead of changing the app feed URL immediately.
