# expired-gpg-key
process to extend the expiration of a gpg key

### pre-requisites: gpg key has expired and you reveive errormessage

Step 1: list all available keys (command)<br>
```gpg --list-keys```<br><br>
copy key-id and execute next command<br>
```gpg --edit-key (key id)```<br><br>
you're entering the gpg-console and select the key you'd like to use:<br>
```gpg>key 1```<br>
next step is to define the new expiration period<br>
```gpg>expire```<br>
(follow prompts, last step is to confirm with password)<br>
```gpg>save```

the new expiration period has been defined.
