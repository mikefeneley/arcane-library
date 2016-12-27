**Standardize Technology**
<hr>

Welcome to the high stakes world of software politics and drama. The most important thing that has ever happened and will ever be. (Vim>Emacs) == True

I think the open source software industry would be better of if more hours were spent improving, debugging, and auditing existing standardized tools instead of continuous reinvention of solutions for problems that have already been solved.

The easiest place to see the benefits are in cryptography. Nobody suggests that small teams try to invent new cryptosystems or reimplement existing cryptosystems because of the probability of failure is near 1 and even if successful, nobody will believe it until the code has been thoroughly tested and auditing by many teams of professional cryptographers. Inventing new cryptography is just not an effective use of one’s time.

That said, I do think there is value in trying to roll your own crypto, but the benefit comes from personal development, not in what you produce. I think similar principles apply to software in general. When deciding how to optimally spend one’s time, lean towards improving existing and widely used products than trying to invent something new.

I think more man hours would be allocated to this task if certain agreed upon tools were chosen to be the standard for a particular task. For example, one tool I like is rsync which provides synchronization of files across multiple systems. In addition to rsync, there is synctoy, free file sync, synkron, unison, syncless, and jfilesync. If all the effort put into writing these tools went in to extending, debugging, and optimizing rsync, we would have a much better single tool with an agreed upon interface for using.

I want to put together a list of tools/protocols/languages I think should become the accepted standards for a wide range of applications. To meet the criteria for consideration, it should be open source. Being extensible is a very useful quality because it reduces the chance that a new tool will need to be developed to replace the existing tool to improve its functionality and application range. Ideally, the software uses a permissive license. GPL is not ideal license because of restrictions on its use in commercial products. For tools it is preferable if a command line version of the tool exists. GUIs are not inherently bad, but a GUI wrapped around a base CLI product is better than one which solely exists as a GUI. 

I also think that many of the tools in widespread use should be phased out. Instead of having Perl, PHP, and Python we should all agree to a single scripting language. All the time spent writing similar libraries for each language should instead be spent porting functionality from the other languages that may be missing in the agreed upon language. Ditto for low level hardware languages, operating systems, development tools etc.

This is a brainstorm, so if you have a comment/suggestion, send me an email. The list WILL be biased towards things I like, but I am will try to go into the reasons why everything is on the list.

**Operating Systems**

- Linux: Debian, ArchLinux, Gentoo

- Unix: OpenBSD, FreeBSD

**Programming Languages**

- System Level Programming: C, C++

- Scripting Languages: Python

**Software Libraries**

- C++: Boost, Standard Library 

**System Management**

- File Synchronization: rsync

**Software Development**

- Text Editing: vim, emacs

- Compilers: gcc, clang

**Network**

- Layer 3 Transport Libraries:

- Layer 3 Encryption Libraries:  OpenSSL


- Browser: firefox

**Web**

- Web Server: Apache, Nginx

