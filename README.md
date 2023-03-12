# bedrock-void-on-macbookair62
Install Bedrock Linux ontop of Void on a Macbook Air Early 2014 (macbookair6,2)

# Main
Install Void if you havent: Tutorial: https://github.com/aspen-arc/void-on-macbookair62<br>
Then:

```
$ wget https://github.com/bedrocklinux/bedrocklinux-userland/releases/download/0.7.28/bedrock-linux-0.7.28-x86_64.sh
```

Then use install script:

```
$ sudo sh bedrock-linux-0.7.28-x86_64.sh --hijack
```
Reboot.<br>
Now you have Bedrock Linux!

# Extra
You can install stratums with `sudo brl fetch`<br>
Some good starting ones are:
```
$ sudo brl fetch debian -r bookworm # Debian testing
$ sudo brl fetch arch # Arch linux for Aur
```
Then you can use `pacman` and `apt`
Also dont forget to update every once in a while with:
```
$ sudo brl update
```
