## Remarkable Hacks Setup

```
ssh root@10.11.99.1
sh -c "$(wget https://raw.githubusercontent.com/ddvk/remarkable-hacks/master/patch.sh -O-)"
sh -c "$(wget https://raw.githubusercontent.com/ddvk/remarkable-stylus/master/patch.sh -O-)"
cd ../remarkable_news
make install_nyt_hq
```