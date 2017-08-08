# Get back to work Ronald!
Come at me bro.

## Usage
This requires root access to your machine to work. The first thing you need to
do is make the website `nyan.cat` redirect to a server running on localhost:

Open your hosts file on your mac.
```
sudo vim /etc/hosts
```

Add the following entry:
```
127.0.0.1 nyan.cat
```

Then, you will need to install this tool which serves the html page:
```
pip install get-back-to-work-ronald
```

If you don't have python of installed you can probably install it using:
```
brew install python
```

After that, just run the server in the background:
```
sudo nohup get-back-to-work-ronald &
```

You need to run the server as root for it to bind on port 80.
