### zap.store Privacy

_Does zap store know which npubs downlaod which apps?_

The relay does not log but currently has access to the device installed apps when querying for updates. 

Artifacts are requested directly from the source by default (e.g. github). This info is shown in the alert dialog on first install. There is a fallback to the zs blossom server (https://cdn.zap.store) though. In the future we should honor npub's blossom server list.

_Does the app dev know which npubs download their app(s)?_
It is possible for file servers gather data and associate IPs with npubs AND share it with devs. Possibly and unlikely.

_Does zapstore know the IP address of the users?_
The zap.store relay does not log IP addresses but there is no way for users to verify. Zap.store recommends all use a VPN, or Tor.

_Is any other information observable by zapstore?_
Searches for apps are observable.

What/is any information recorded by zapstore?
The zap.store relay records none. However this is not currently verifiable.

_In what ways does zapstore use relays?_
In the future users will be able to switch relays, as each relay has its own privacy reputation.

_Does zapstore use its own relay?_
Yes. wss://relay.zap.store.

_How does zapstore know which app versions are installed on the user's device?_
Android allows querying for this information with a permission bundled in the app. 

_is there "delete all my info" functionality?
No personal information is stored. A button to remove local storage will be available soon.

### Questions, Feedback, and Discussion

Utilize https://github.com/zapstore/zapstore/issues/40
