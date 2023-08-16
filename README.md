# sepolicies
policy modules for a systemd-based gentoo box with selinux on

The selinux-systemd combination in gentoo is experimental, nothing would work out of the box.  
Some extra care is needed in order to login via tty or via pty(sshd).   
Here are the SELinux policy modules I'm using to modify the behaviour of gentoo's strict version of the SELinux policy.

## the objective
There once was a play.coker.com.au, where you would've had root access via ssh on a debian machine with armoured SELinux;
for learning and self-amusement purposes I'd like to replicate such experiment.

I'll eventually put here the instructions and configs/modules/ansible to make such a box reproducible.
