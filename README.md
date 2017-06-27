# IRC Translations

This project attempts to introduce standard, widely-usable translations of all the usual IRC numeric strings. Translations can be hard to implement for IRC server authors – mostly, because those translations don't exist. With this, I'm hoping to make available standard translations for numerics and messages that server authors can use while implementing translated messages for their users.

I'm not sure whether this'll be useful or not, but hey! Hopefully it can let IRC server authors implement translated messages more easily than they'd otherwise be able to.

How I'm doing it is having a `yaml` file containing all the messages that could ever be standardly translated in English. Each language we provide has a copy of that file with the actual messages translated appropriately.

Everything's under the CC0 Public Domain license, so you can use it in your own projects without any trouble!
