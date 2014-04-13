# Installs screenFetch from it's official repository

[screenFetch][scf] is a "Bash Screenshot Information Tool". This handy Bash script can be used to generate one of those nifty terminal theme information + ASCII distribution logos you see in everyone's screenshots nowadays. It will auto-detect your distribution and display an ASCII version of that distribution's logo and some valuable information to the right. 

![screenshot](https://raw.github.com/vivaserver/ansible-screenfetch/master/screenfetch-hooray.png)

![screenshot](https://raw.github.com/vivaserver/ansible-screenfetch/master/screenfetch-hohoho.png)

![screenshot](https://raw.github.com/vivaserver/ansible-screenfetch/master/screenfetch-slug.png)

![screenshot](https://raw.github.com/vivaserver/ansible-screenfetch/master/screenfetch-slum.png)

## Requirements

A Debian or Ubuntu-based system.

## Dependencies

No role dependencies, only Git.

## Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vivaserver.screenfetch }

## License

MIT

## Copyright

(c)2014 Cristian R. Arroyo

[scf]: https://github.com/KittyKatt/screenFetch
