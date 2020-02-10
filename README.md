# Xbox Remote Power

This is a little script that can turn your Xbox One on remotely. It works over both LAN and WAN, provided you have port 5050 forwarded to your Xbox One.

## How to use

You need three things for this to work:

- Python 2 or 3 installed
- IP address of your Xbox One
- Live device ID of your Xbox One

To find the IP of your Xbox, go to Settings -> Network -> Advanced settings.
To find your Live device ID, go to Settings -> System -> Console info.
NOTE: It's probably a good idea to keep this information a secret!

If you want to use this over the internet, you'll also need port 5050 forwarded to your Xbox One.

Run the script as follows, replacing [ip address] with the IP of your Xbox One and [live id] with your Live device ID.

```bash
python xbox-remote-power.py -a [ip address] -i [live id]
```

Alternatively, you can also run the script without any arguments and you'll be prompted for the IP and Live device ID.

```bash
python xbox-remote-power.py
```

## Note

This is a fork from the project hosted in <https://github.com/Schamper/xbox-remote-power>
