[!IMPORTANT]
Thanks for using my template. You should follow the setup instructions below. All the information you need to make and build your pack after setup is in [CONTRIBUTING.md](CONTRIBUTING.md). After setup, you should replace this README with your own.

## Pack Setup
1. Clone this repository.
2. If you wish to make a Modrinth pack instead of CurseForge, replace `./packwiz cf` in [build.yml](.github/workflows/build.yml) with `./packwiz mr`.
3. Run [packwiz-download-latest.sh](packwiz-download-latest.sh) on Linux to get Packwiz (you will need to give the script execute permissions). If you can't use this script or you're using Windows or Mac, follow the [Packwiz installation instructions](https://packwiz.infra.link/installation/).
4. Follow the [Creating a new modpack](packwiz.infra.link/tutorials/creating/getting-started/#creating-a-new-modpack) section in the Packwiz docs.
5. Commit your changes to main. This will run the GitHub workflow once, giving you a build of your pack in GitHub with the tag `latest-dev` (it should be noted that every time you commit to main, a new build of your pack will be made, overwriting the previous build at `latest-dev`).
6. Delete your local repository and follow [CONTRIBUTING.md](CONTRIBUTING.md).
