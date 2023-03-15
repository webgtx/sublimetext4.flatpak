# sublimetext4.flatpak
> Build sublime text 4 with flatpak, help yourself 

So one guy tried to upload sublime text 4 on flathub, but his [pull request](https://github.com/flathub/flathub/pull/2855)
is inactive for about a year
because of some kind of conflict.

That's why I decide to clone pr to a stand-alone repository, first of all for myself.

### How to build and install
Build
```bash
flatpak-builder build-dir com.sublimehq.SublimeText.yaml
```
Test & Install
```bash
flatpak-builder --user \
	--install \
	--force-clean \
	build-dir com.sublimehq.SublimeText.yaml
```

