# Termux-autosuggestion
Auto suggestions in Termux can be enabled by installing a shell called `fish`. Here are the steps to do so:

1. Open the Termux app and make sure it is up to date. You can update it by running the command `pkg update && pkg upgrade`.

2. Install `fish` by running the command `pkg install fish`.

3. Set `fish` as your default shell by running the command `chsh -s fish`.

4. Restart Termux for the changes to take effect.

5. Once you restart, start typing a command and you should see suggestions pop up automatically based on what you've typed so far.

Note that while `fish` provides powerful autocomplete functionality, it may take some time to get used to if you're used to a different shell like `bash`.
