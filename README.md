# Surface Pro 3 Documentation

Arch Linux and Antergos on the Microsoft Surface Pro 3. I forked this because I wanted to reflect that there's more stuff working than initially thought.

## Hardware

* [x] [Type Cover 3][#1]
  * [x] keyboard
  * [x] trackpad [*partially*]
* [x] [WiFi][#2] *works, but issues with resume from hibernate*
* [x] [Bluetooth][#2]
* [x] Touch screen with multitouch support
* [x] [N-trig touch pen][#8] *works, even the pressure sensitivity works, but needs configuration tips*
* [x] [Built-in microphone]
* [x] [Speakers]
* [x] [Headphone jack]
* [x] [Cameras][#3]
* [x] MicroSD card reader
* [ ] [MiniDisplay Port] [*untested*]
* [ ] Docking station *not yet released*
* [ ] [Suspend to RAM][#2] [*working, but with issues*]
* [ ] [Suspend to SSD][#2] [*working, but with issues*]


## Software

* [x] [Full disk encryption][#7]
* [x] HiDPI Support
* [x] Multitouch gestures [*touchgreen multitouch gestures working fine on GNOME Shell 3.14 and up*]
* [x] Onscreen Keyboard
* [ ] Rotation recognition and action [*untested, but there's supposedly a way to get it working*]

[#1]: https://github.com/Vistaus/surface3-arch-antergoslinux/issues/1
[#2]: https://github.com/Vistaus/surface3-arch-antergoslinux/issues/2
[#3]: https://github.com/Vistaus/surface3-arch-antergoslinux/issues/3
[#4]: https://github.com/nuclearsandwich/surface3-archlinux/issues/4
[#5]: https://github.com/nuclearsandwich/surface3-archlinux/issues/5
[#6]: https://github.com/nuclearsandwich/surface3-archlinux/issues/6
[#7]: https://github.com/nuclearsandwich/surface3-archlinux/issues/7
[#8]: https://github.com/nuclearsandwich/surface3-archlinux/issues/8


## Reading

@rubiojr's work on Ubuntu https://github.com/rubiojr/surface3-ubuntu-trusty
@rubiojr's kernel https://github.com/rubiojr/surface3-kernel

### Reddit

**Ubuntu 14.04 on the Surface Pro 3 Reddit Thread**

http://www.reddit.com/r/SurfaceLinux/comments/2bhfk5/ubuntu_1404_on_the_surface_pro_3_thread/

**Thread on the Surface Pro 1**

http://www.reddit.com/r/SurfaceLinux/comments/2b1hf6/running_ubuntu_1404_on_surface_pro_1_full_time/

**Ubuntu subreddit**

http://www.reddit.com/r/Ubuntu/comments/26lvqc/ubuntu_on_the_surface_pro_3/

### Kernel related

**Type Cover 2 bug**

https://bugzilla.kernel.org/show_bug.cgi?id=64811

### Hardware

https://www.ifixit.com/Teardown/Microsoft+Surface+Pro+3+Teardown/26595

http://www.anandtech.com/show/8077/microsoft-surface-pro-3-review

http://www.anandtech.com/show/8037/microsoft-surface-pro-3-hands-on-display-performance-preview

https://origin-www.marvell.com/wireless/avastar/88W8897/ (wifi+bt+nfc chip?)
http://wireless.kernel.org/en/users/Drivers/mwifiex
