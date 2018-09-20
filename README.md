# nukleus
##### the future of operating systems.

nukleus is a small, container based OS writeen in Rust. Nukleus is also modal: Server Mode and Client Mode. In server mode, the user can create and deploy Docker containers that are running certain tasks, programs, or even a different operating system. In client mode, the user uses a TUI  to interact with and ssh into the deployed containers. From here the user can also use Kubernetes to manage the containers.

nukleus only comes with

 - Docker
 - Kubernetes
 - Drivers
 - A strange hybrid of Vim and Emacs (text editor)
 - An Elisp interpreter, mainly for org-mode support
 - pak, our package manager

## goals

 - Uncomprimising speed - lightspeed is too slow!
 - Itsy-bitsy - we want your files to take up space on your hard drive, not the OS. As of 8-10-18, with documentation, we are 158730.159 times smaller than Windows 10
 - Suitable for older hardware - breathe new life into your old PC
 - Avoiding feature bloat; you get what you need and bot much else (everything rlse can be installed manually)
