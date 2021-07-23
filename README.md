# Freenom renew

Simple script to renew freenom domains:

```sh
pip install -r requirements.txt
python3 run.py <IP>
```

It goes over all your domains, changing the first record to the given IP.

It is very convenient if your first record is an A with an IP and every other is a CNAME pointing to it (such as WWW).

Feel free to do a pull request if you want to extend its functionality.