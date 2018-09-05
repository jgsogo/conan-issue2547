# conan-issue2547

Work on [issue 2547](https://github.com/conan-io/conan/issues/2547):

```
git clone https://github.com/jgsogo/conan-issue2547.git issue2547
cd issue2547
conan export opus/ plex/stable
conan export gnutls/ plex/stable
cd libidn
conan create . plex/stable --build=missing
```
