## Layer 0 - PEBKAC

- Make sure CapsLock is off. (Same for ScrollLock and NumLock)

- Type it again (without using cut-and-paste) and see if you get the same results. (good way to find a typo or a unicode "whitespace" char)

- Use cut-and-paste to copy that variable name (or URL, commmand line, etc.) to see if it was entered correctly.

- Check the file permissions.

- Are you really on the host you think you are?

- Are you doing the test from the right machine?

- Are you testing with the right user account?

- Does your test gear test what you think it tests?
  - What happens when you run the exact same test on a known-good and a known-bad element?
  - Do you get the results you expect both ways?

- Is that a file, a directory, a hard link, a symbolic link, or a mountpoint?

- Is the screen paused via Ctrl-S? (press CTRL-Q to find out)

- You can get to the web site? Are you working in "off-line" mode?

- Are the binaries really the ones you think are running?
  - Did you install in single user mode when /opt wasn't mounted?
  - Can you check the md5 or sha1 checksum vs. a machine that is running properly?

