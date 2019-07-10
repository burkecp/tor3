# tor3

An updated TOR proxy client library for python3.

## installation

1. Download the TOR browser application.

2. Generate your HashedControlPassword by running
```tor --hash-password YOURPASSWORD```

3. Edit your torrc file, which is usually located in `/etc/tor`

4. Uncommenting your `HashedControlPassword` (line 60) and replace the password with the one generated above

5. Uncomment your `ControlPort` (line 57) and replace with the proper port.

6. Save and exit

7. Start tor
