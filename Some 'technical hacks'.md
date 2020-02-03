# Technical hacks

Just some stuff which, from my experience, which isn't known by many that would make some things easier.

## 1. Blackboard without BoilerKey

Blackboard is (for me) one of the most important tools I use as a Purdue student, as it's where one gets the course materials and grades. So it's often annoying when BoilerKey pops up whenever you want to use Blackboard, but there is an easy workaround.

Open Blackboard. When you get into this screen:

![Opening Blackboard screen](/assets/blackboard_1.png)

choose the *Other account login* option, **NOT** the Purdue Account login option. This will take you to a username/password screen (notice that there is no mention of BoilerKey anyway). Enter your *regular* Purdue Career Account username and password (not the BoilerKey pin,push sequence) and it should load up!

Note that this does not give access to other parts of Purdue's sites (like myPurdue); a BoilerKey is still required in these cases.

## 2. 'Free' printing

If you don't want to use your free $40 allowance while printing, one option is to find a departmental printer that is not locked down. One of such printers lies in the Keedy lab in the Math building (6<sup>th</sup> and 7<sup>th</sup> floors), which also contain a couple of PCs that can be used (note that only Windows machines can be used; Linux only works if you're a Math grad student/faculty). You can use these computers or alternatively print from your own machine by following the instructions [here](https://www.purdue.edu/science/scienceit/Printing.html). Alternatively, if you are a CS student, the Lawson and HAAS printers are free for students. Just don't abuse the printers.

## 3. Administrator access on university machines

Most ITaP machines come with *standard* permissions for each user. While this is usually enough for most users, if you're like me and want to install advanced applications (or even modify existing programs), this may not be enough.

The only computers which are configured to allow adminstrative permissions are the ones on Lawson (CS) and Beering (College of Education; third floor), which could be very useful if you want to play games or install your own programs. Note that in any case, the programs that you install will be removed once you log out.

## 4. VPN without Cisco
### Using the built-in OS option
It is possible to configure Windows and Mac so that you can use the VPN without having to use Cisco's tool. This is helpful since it's very straightforward to enable and disable the VPN this way, and it is also seamless. See https://engineering.purdue.edu/ECN/Support/KB/Docs/ITaPVPNManualSetupvia.
### SSH tunnling
As an alternative, this is a fairly advanced method of getting a VPN. Note that while the standard ITaP method works just fine, this method has some advantages:

* It can be significantly faster
* No third-party applications required
* It's possible (easily using Firefox) to limit the VPN to a browser (so that you do not need to run VPN on the whole machine)

Instructions coming soon.
