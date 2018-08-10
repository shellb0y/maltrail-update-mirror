# Maltrail Feeds Mirror
Mirror of [maltrail](https://github.com/stamparm/maltrail) feeds, updated periodically. Currently updated every 6 hours. This mirror is maintained to help users in countries/areas/ISPs with low IP reputation. Some of maltrail's feed sources use cloudflare/similar services which block automated script access to malware update definitions. Users from such areas can use `https://raw.githubusercontent.com/dbinoj/maltrail-update-mirror/master/trails.csv` to get latest malware updates for maltrail.

As of now, there is a size limit of 90MB. If the size cross this limit, download of that trail is skipped. This is done to honor github's file size limit of 100MB/file.

The script used to mirror the trails is located at [dbinoj/maltrail-mirror-script](https://github.com/dbinoj/maltrail-mirror-script).
