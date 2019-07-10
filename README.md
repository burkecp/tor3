# tor3

An updated TOR proxy client library for python3

## installation

1. Download the TOR browser application

2. Generate your HashedControlPassword by running
```tor --hash-password YOURPASSWORD```

3. Edit your torrc file, which is usually located in `/etc/tor`

4. Uncomment your `HashedControlPassword` (line 60) and replace the password with the one generated above

5. Uncomment your `ControlPort` (line 57) and replace with the proper port (see [control-spec.txt](https://gitweb.torproject.org/torspec.git/tree/control-spec.txt) if you are unsure which port to use)

6. Save and exit

7. Restart tor
