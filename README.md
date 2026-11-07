# TV Setup

TV Setup is an Android phone app that sets up Google TV and Android TV devices. With it, a phone can also be a
controller for Game Sphere, the game player that runs on the TV.

## Download

Get these from the latest [release](https://github.com/salvatoreguytano-cmyk/tv-setup/releases/latest):

- **TV-Setup.apk** goes on your Android phone. Open it, and allow installing from your browser when your phone asks.
- **GameSphere-armv7.apk** and **GameSphere-arm64.apk** are the game player, for 32-bit and 64-bit TV chips. You
  don't usually download these yourself: TV Setup picks the right one for your TV and installs it (Games → Get Game
  Sphere).

## Playing a friend's games

When a friend sends you an invite link:

1. Open the link on your Android phone.
2. Get TV Setup from that page, then tap **Open the invite**.
3. Pick your TV.

TV Setup then puts Game Sphere and Tailscale on the TV and signs the TV in with the invite. Game Sphere opens with
your friend's games. Each invite works for one TV and runs out after 7 days. The TV can reach your friend's game
server and nothing else on their network.

The invite page is [docs/join](docs/join/index.html). The invite sits after the `#` in the link, so it is never sent to
GitHub or to any other website.
