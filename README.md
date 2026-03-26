# RPG resource pack (public)

This repository exists so **`https://raw.githubusercontent.com/.../RPGResourcePack.zip`** works for **Minecraft clients** (the main server repo is private; GitHub raw URLs do not work for private repos without authentication).

Update flow:

1. In the server project, run `scripts\Build-RPGResourcePack.ps1`
2. Run `scripts\Publish-RPGResourcePack-Public.ps1`
3. Set `resource-pack-sha1=` in `server.properties` to the printed SHA-1
