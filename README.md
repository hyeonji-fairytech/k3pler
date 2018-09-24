# k3pler proxy

![k3pler](https://github.com/KeyLo99/k3pler/blob/master/etc/k3plerbg3_splash.png "k3pler")

Android network connection blocker and packet analyzer built on top of local HTTP proxy.

### Features
* Show network traffic in a list (HTTP Request/Response)

![network-traffic](https://github.com/KeyLo99/k3pler/blob/master/etc/page1.png "network-traffic")

* Gives details about requests/responses with abbreviations in list.
(eg: ```example.com ~ C [H/1.1] _S_ {time}```)
(C -> Connect | H/1.1 -> HTTP version | _S_ -> Success)
* Blacklist connection after getting detailed information
* Edit/Remove item at blacklist - clear blacklist

![blacklist](https://github.com/KeyLo99/k3pler/blob/master/etc/page2.png "blacklist")

* Settings:
    ```
    Proxy Port: Local Proxy port for connection
    Max. Buffer: Maximum response buffer size in bytes
    Match Type:
        Full: Block if request URI equals blacklist item
        Keyword: Block if request URI contains blacklist item
    Blacklist Response: Response status which will be sent to blocked address
    Splash Screen: Show splash screen when app starts
    ```

![settings](https://github.com/KeyLo99/k3pler/blob/master/etc/page3.png "settings")

* Shows instructions of configuring proxy (WIFI / Mobile Network)

### Licenses
* [Android v7 RecyclerView Library](https://developer.android.com/topic/libraries/support-library/packages) `(Apache 2.0)`
* [LittleProxy 1.1.2](https://github.com/adamfisk/LittleProxy) `(Apache 2.0)`
