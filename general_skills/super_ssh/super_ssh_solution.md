This is an introductory room for getting comfortable using SSH. In this case after launching a server that runs the aforementioned software. We get some instructions to connect using an specific port. A username and a password are provided.

This was the way to obtain the flag:

```bash
ssh -v ctf-player@titan.picoctf.net -p 62400
```

After fingerprinting the keys (accepting on the prompt) and since we used the verbose mode with the flag -v:

```bash
<Up>    ~  ssh -v ctf-player@titan.picoctf.net -p 62400                                     255 ✘  01:23:12  
OpenSSH_9.6p1 Debian-4, OpenSSL 3.1.5 30 Jan 2024
debug1: Reading configuration data /etc/ssh/ssh_config
debug1: Reading configuration data /etc/ssh/ssh_config.d/kali-wide-compat.conf
debug1: /etc/ssh/ssh_config.d/kali-wide-compat.conf line 8: Applying options for *
debug1: /etc/ssh/ssh_config line 21: Applying options for *
debug1: Connecting to titan.picoctf.net [3.139.174.234] port 62400.
debug1: Connection established.
```

A few lines down...

```bash
Welcome ctf-player, here's your flag: picoCTF{s3cur3_c0nn3ct10n_07a987ac}
debug1: channel 0: free: client-session, nchannels 1
Connection to titan.picoctf.net closed.
Transferred: sent 3856, received 3120 bytes, in 0.4 seconds
Bytes per second: sent 9780.6, received 7913.8
debug1: Exit status 0
```
