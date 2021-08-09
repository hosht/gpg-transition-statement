Date: 2021/08/09

The old key will continue to be valid for some time, but I prefer all future correspondence to come to the new one. I would also like this new key to be re-integrated into the web of trust.  This message is signed by both keys to certify the transition.

The old key was:

```
pub   rsa4096 2020-03-29 [SC] [expires: 2022-01-10]
      EC8F317E5F9800A0DD89274A357465A932DF7FDA
uid           [ultimate] Takanobu Hoshino <hosh.tknb@gmail.com>
```

The new key is:

```
pub   nistp521 2021-08-09 [SC]
      FB99E51870E6BA225D7C3D8BB9823D8678244335
uid           [ultimate] Takanobu Hoshino <hoshino@hey.com>
sub   nistp521 2021-08-09 [E] [expires: 2022-08-09]
```

To fetch the full key from a public key server, you can simply do:

```
gpg --fetch-key https://keybase.io/hosht/key.asc
```
