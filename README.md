# telegram-bot-api-build

Cloud build for [tdlib/telegram-bot-api](https://github.com/tdlib/telegram-bot-api).

Builds an Ubuntu 22.04 aarch64 release binary in GitHub Actions on a native
`ubuntu-22.04-arm` runner, avoiding the heavy TDLib compile on low-resource hosts.

Trigger manually from the Actions tab, or push to `main`.
Artifact `telegram-bot-api-aarch64-linux.tar.gz` is retained 30 days.
