# Kitchen OS releases

Update bundles for the kitchen screen (a Raspberry Pi 5 running Kitchen OS, built from the private home-app repo).
Each release `kitchen-os-<version>` carries `kitchen-os-<version>.tar` and its ed25519 signature; `latest.json`
on this branch names the current one. A screen with `UPDATE_URL` pointing at the raw `latest.json` installs it by
itself after checking the signature and checksum. Nothing here is source code and nothing here is secret.
