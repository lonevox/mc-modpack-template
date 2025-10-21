> [!IMPORTANT]
> Thanks for using my template. You should create a new repository from this template then follow the setup instructions below. After setup, you should replace this README with your own.

## Pack Setup
1. In your repository in GitHub, go to **Settings**, **Pages**, then set **Branch** to `main` and then hit **Save**. To use pages with a non-enterprise GitHub account, your repository needs to be public.
2. Go to **Actions** and wait for the `pages-build-deployment` workflow to finish.
3. Finish [Setting up your local environment](CONTRIBUTING.md#setting-up-your-local-environment).
4. If you wish to make a Modrinth pack instead of CurseForge, replace `./packwiz cf` in [build.yml](.github/workflows/build.yml#L23) with `./packwiz mr`.
5. Edit [pack.toml](pack.toml) to your liking. You can find all the options for the pack file [here](https://packwiz.infra.link/reference/pack-format/pack-toml/). You'll likely want to change `name`, `author`, and `versions`.
6. Commit your changes, if any, to main.

> [!NOTE]
> Every time you commit to main, a new build of your pack will be made, overwriting the previous build at [latest-dev](/../../releases/tag/latest-dev).
