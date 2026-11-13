# PaperCloth releases

Release downloads and the version list for the PaperCloth installer.

- `v1/versions.json` lists every PaperCloth release (newest first) with the files a server needs: PaperCloth's own jars, attached to the GitHub release of the same name, and its libraries, which are downloaded from Maven. The installer reads this file, so new releases appear in it without a new installer.
- Releases are added by the **PaperCloth Release** workflow in `papercloth-api`; don't edit `versions.json` by hand.

## Install a server

Download the installer and run it, or from a terminal:

```
java -jar papercloth-installer.jar server --dir <folder>
```

The installer downloads the Minecraft server from Mojang. The server needs Java 25.
