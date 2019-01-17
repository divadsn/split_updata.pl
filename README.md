splitupdate (formerly split_updata.pl)
===============

Improved tool for splitting UPDATE.APP for Huawei phones, dockerized by David Sn (@divadsn).

To extract execute:
```
docker run -v $(pwd)/UPDATE.APP:/data/UPDATE.APP -v $(pwd)/output/:/data/output/ divadsn/splitupdate:latest
```

The img files will be extracted in the `./output/` folder.
