# telegram-bot-api-build

Cloud build for [tdlib/telegram-bot-api](https://github.com/tdlib/telegram-bot-api).

Builds a static-ish Ubuntu 22.04 x86_64 release binary in GitHub Actions,
avoiding the heavy TDLib compile on low-resource hosts.

Trigger manually from the Actions tab, or push to `main`.
The artifact `telegram-bot-api-ubuntu2204-x86_64.tar.gz` is retained 30 days.
