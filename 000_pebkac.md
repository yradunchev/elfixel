## Layer 0 - PEBKAC

[ ] Make sure _CapsLock_ is off. (Same for _ScrollLock_ and _NumLock_)

[ ] Type it again (without using cut-and-paste) and see if you get the same results. (good way to find a typo or a unicode "whitespace" char)

- Use cut-and-paste to copy that variable name (or URL, commmand line, etc.) to see if it was entered correctly.

- Check the file permissions.

- Are you **really** on the host you think you are?

- Are you doing the test from the **right machine**?

- Are you testing with **the right user account**?

- Does your test gear test what you think it tests?
  - What happens when you run the exact same test on a _known-good_ and a _known-bad_ element?
  - Do you get the results you expect **both** ways?

- Is that a _file_, a _directory_, a _hard link_, a _symbolic link_, or a _mountpoint_?

- Is the screen **paused** via _ctrl-s_? (press _ctrl-q_ to find out)

- You can get to the web site? Are you working in "off-line" mode?

- Are the binaries **really** the ones you think are running?
  - Did you install in single user mode when /opt wasn't mounted?
  - Can you check the md5 or sha1 checksum vs. a machine that is running properly?
