<h1 align="center">
    <a href="https://github.com/fehawen/hax">
        <img alt="scrot" src="https://user-images.githubusercontent.com/36552788/85957099-d8ac0900-b98a-11ea-98ae-b000d27a206a.png" width="960">
    </a>
    <br>
</h1>

# Hax

Generate a zero-config h4xx0r 1337 \ >_< / 0Hh y3h setup.

## Install

Installation's made easy by the `Makefile`.

```sh
make install
```

Add `~/bin` to your `PATH` as that's where hax is installed to.

## Usage

Once installed, run `hax -h` for details on how to use it.

Or run it with the defaults with `hax`, but read the notes below first.

## Pal

You'll need `pal` as this is where we get the colors from. It also allows us to change colors on the fly. Head on over [here](https://github.com/fehawen/pal) to get `pal` up and running, it's done in a heartbeat.

## Font

The font used in the screenshots is `JetBrains Mono` which you'll find [here](https://www.jetbrains.com/lp/mono/)

## Other dependencies

* i3wm
* polybar
* conky
* xsetroot
* pacman (Arch Linux) (or change the scripts & commands to match your packgage manager)
* ... Perhaps something else I've forgotten to mention

## Notes

The widths, heights, paddings, and offsets for `conky` and `i3` and `polybar` etc are *mostly* hard coded, meaning they won't work very well on varying screen sizes. Unless of course your screen size happens to match mine exactly. I'm on a `3200x1800` pixel screen, so you'll have to fiddle around with the configs to suit your needs.

This can all be made dynamic of course, at least to *some* extent. The tricky part, or one of them at least, is getting the conky panels to match the screen's height (we want them full height - no more, no less). But fixing all that to happen automagically is not something I'll be looking into right now.

With some fiddling you'll be able to adjust the conky, i3 and polybar config details in `hax` to suit your screen, I hope.

## FAQ

> "This is a joke, right?"

Yes, of course it is.