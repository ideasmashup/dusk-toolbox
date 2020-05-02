# dusk-toolbox
Windows 10 utilities to synchronize/migrate/backup/restore apps, files and settings across devices and VMs

## What ?

Tools that work in the shadow of your Windows 10 sessions.

A few (only one at first) minimalisatic background programs that save, migrate and restore everything from files, running apps, settings and other user or workstation specific items between Windows sessions linked by a network.

The toolbox is made of distinct standalone utility programs designed to be:

- modular and minimalistic
- written in Rust to be safe and fast
- cross-platform in the future

The exact [role of each tool and design choices are described here](_docs/specifications.md)

## Why ?

During Covid19 lockdown (April 2020) I started to learn rust and I wanted to build basic system tools with it to practice my newly acquired skills.

I work at @Shadow and I use two "Shadow VMs" as both my gaming PC and dev workstation. These run only Windows 10, so syncing them and other computers (laptops, etc) is done manually, and I want something smoother and good looking. 

Also when the VMs experience a forced shutdown all opened apps and state of work is lost (snapshots aren't possible right now), it's a pain to restore everything manually each time. I sure hope these tools will do it painlessly for me and more!

## Who ?

Me (William ANGER, VP of R&D @Shadow) and whoever wants to help!

Feel free to contact me or add new issues if you have feedback, ideas or want to fix bugs or implement something nice! 
Any PR is always welcome!

## License

I chose to do it as a GPL3 project to allows free contributions from others, to make sure that everything stays free, to make sure that the source code is always open. And also because I'm doing this outside of my work hours as a hobby project!

*If this project becomes useful to more people I hope the community can embrace it and make it even more awesome!*

