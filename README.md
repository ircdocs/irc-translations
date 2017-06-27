# IRC Translations

So, what is this? Basically, it can be difficult for server authors to introduce translations of standard IRC messages because... quite simply, they don't really exist. Sure, some foreign nets have their own custom IRCds, but being able to integrate alternate-language messages natively into regular IRC servers would be really useful.

I'm not sure whether this'll be useful or not, but hey! Hopefully it can let IRC server authors implement translated messages more easily than they'd otherwise be able to.

How I'm doing it is having a `yaml` file containing all the messages that could ever be standardly translated in English. Each language we provide has a copy of that file with the actual messages translated appropriately.

Everything's under the CC0 Public Domain license, so you can use it in your own projects without any trouble!
