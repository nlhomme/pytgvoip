# Python based Telegram VOIP calls

## Warning: Despite the v1.0 release, the tgcall.py script has not been fully tested
## the script seems to work since it show no error and connection is notified to Telegram,
## but I havent been able to make a call (yet).

## Build with Docker
```
docker build --rm -t nlhomme/pytgvoip .
```

You need to register an app on Telegram's website, retrieve the API id and hash.
Then you can call someone.
```
python3 tgcall.py api_id api_hash phone_number user_id dbkeyofyourchoice
```
