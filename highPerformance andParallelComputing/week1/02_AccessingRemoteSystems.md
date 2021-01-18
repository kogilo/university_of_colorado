# Accessing Remote Systems

- Two main ways one interacts with a remote system
  - Logging in
  - File transfer

## Logging in

- authenticate connection through keys, public and private

- Example:

```
  ssh username@remote.hostname
```

- Might have some flsgs after the `ssh`

* Let look at it:

```
man ssh
```

- See ` -X` - Enables x11 forwarding

```
ssh krnuts@login.rc.colorado.edu
```

## File Transfer

- Recommend several ways:
  - scp, sftp, wget, rsync, Globus file transfer
  - scp and sftp are good becuase they are secure
- Example (several ways to to this):

```
scp /home/username/file.txt
username@remote.hostname:/home/username
```

```
scp username@remote.hostname:/home/username/file.txt .
```
