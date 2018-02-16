## Layer 0 - PEBKAC

### Generals
[\_] Make sure _CapsLock_ is off. (Same for _ScrollLock_ and _NumLock_)
[\_] Check the file permissions.
[\_] Are you **really** on the host you think you are?
[\_] Are you doing the test from the **right machine|vlan**?
[\_] Are you testing with **the right user account**?
[\_] Is that a _file_, a _directory_, a _hard link_, a _symbolic link_, or a _mountpoint_?

### Command line
[\_] Type it again (without using cut-and-paste) and see if you get the same results. (good way to find a typo or a unicode "whitespace" char)
[\_] Use cut-and-paste to copy that variable name (or URL, commmand line, etc.) to see if it was entered correctly.
[\_] Is the screen **paused** via _ctrl-s_? (press _ctrl-q_ to find out)

### Does your test gear test what you think it tests?
  [\_] What happens when you run the exact same test on a _known-good_ and a _known-bad_ element?
  [\_] Do you get the results you expect **both** ways?

### You can get to the web site?
  [\_] Are you working in "off-line" mode?
  [\_] Can you get to a different web site?
  [\_] Do you have DNS issues? Try _dig_-ing that site name.
  [\_] Network issues? Can you ping 8.8.8.8?

### Are the binaries **really** the ones you think are running?
  [\_] Did you install in single user mode when /opt wasn't mounted?
  [\_] Can you check the md5 or sha1 checksum vs. a machine that is running properly?
