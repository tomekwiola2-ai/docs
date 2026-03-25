"C:\Program Files\Git\usr\bin\tar.exe" -xf D:/a/_temp/2feee887-c5ce-499b-8bd8-449cf42159e1/cache.tzst -P -C D:/a/Magisk/Magisk --force-local --use-compress-program "zstd -d"
Cache restored successfully
Cache restored from key: sccache-Windows-9035a9480440e48b146d29693a6196c54d8f3b9c
Run bash $GITHUB_ACTION_PATH/sccache.sh
  % Total    % Received % Xferd  Average Speed  Time    Time    Time   Current
                                 Dload  Upload  Total   Spent   Left   Speed

  0      0   0      0   0      0      0      0                              0
  0      0   0      0   0      0      0      0                              0
  0      0   0      0   0      0      0      0                              0

  0      0   0      0   0      0      0      0                              0
100  7.45M 100  7.45M   0      0  9.49M      0                              0
100  7.45M 100  7.45M   0      0  9.49M      0                              0
100  7.45M 100  7.45M   0      0  9.49M      0                              0
sccache: Starting the server...
sccache: Listening on address 127.0.0.1:4226
Statistics zeroed.
Run gacts/run-and-post-run@v1
$ sccache -s
Unexpected error attempting to determine if executable file exists 'C:\Users\runneradmin\AppData\Local\Microsoft\WindowsApps\bash.EXE': Error: EACCES: permission denied, stat 'C:\Users\runneradmin\AppData\Local\Microsoft\WindowsApps\bash.EXE'
Run echo "GRADLE_USER_HOME=$GITHUB_WORKSPACE/.gradle" >> "$GITHUB_ENV"
Run actions/cache/restore@v5
Cache hit for restore-key: gradle-cache-8b0936250b740486ac4faed7e7af2651d56a6b9f79f304435f8438caead45165
Received 29360128 of 1924822197 (1.5%), 27.9 MBs/sec
Received 134217728 of 1924822197 (7.0%), 63.2 MBs/sec
Received 268435456 of 1924822197 (13.9%), 81.7 MBs/sec
Received 402653184 of 1924822197 (20.9%), 92.6 MBs/sec
Received 536870912 of 1924822197 (27.9%), 98.4 MBs/sec
Received 662700032 of 1924822197 (34.4%), 101.9 MBs/sec
Received 792723456 of 1924822197 (41.2%), 104.9 MBs/sec
Received 931135488 of 1924822197 (48.4%), 108.0 MBs/sec
Received 1065353216 of 1924822197 (55.3%), 110.1 MBs/sec
Received 1186988032 of 1924822197 (61.7%), 110.6 MBs/sec
Received 1287651328 of 1924822197 (66.9%), 109.2 MBs/sec
Received 1421869056 of 1924822197 (73.9%), 110.7 MBs/sec
Received 1522532352 of 1924822197 (79.1%), 109.6 MBs/sec
Received 1614807040 of 1924822197 (83.9%), 107.9 MBs/sec
Received 1744830464 of 1924822197 (90.6%), 108.2 MBs/sec
Received 1879048192 of 1924822197 (97.6%), 108.7 MBs/sec
Received 1924822197 of 1924822197 (100.0%), 108.1 MBs/sec
Cache Size: ~1836 MB (1924822197 B)
"C:\Program Files\Git\usr\bin\tar.exe" -xf D:/a/_temp/840e9223-c1dc-4a06-a29c-83d8fd0de2f7/cache.tzst -P -C D:/a/Magisk/Magisk --force-local --use-compress-program "zstd -d"
Cache restored successfully
Cache restored from key: gradle-cache-8b0936250b740486ac4faed7e7af2651d56a6b9f79f304435f8438caead45165
Run actions/cache/restore@v5
Cache hit for restore-key: gradle-build-cache-9035a9480440e48b146d29693a6196c54d8f3b9c
Received 25165824 of 674164667 (3.7%), 23.9 MBs/sec
Received 146800640 of 674164667 (21.8%), 69.5 MBs/sec
Received 310378496 of 674164667 (46.0%), 98.1 MBs/sec
Received 448790528 of 674164667 (66.6%), 106.0 MBs/sec
Received 608174080 of 674164667 (90.2%), 114.9 MBs/sec
Received 674164667 of 674164667 (100.0%), 114.8 MBs/sec
Cache Size: ~643 MB (674164667 B)
"C:\Program Files\Git\usr\bin\tar.exe" -xf D:/a/_temp/99d28265-4f8a-4521-877b-08ebb3645c1d/cache.tzst -P -C D:/a/Magisk/Magisk --force-local --use-compress-program "zstd -d"
Cache restored successfully
Cache restored from key: gradle-build-cache-9035a9480440e48b146d29693a6196c54d8f3b9c
Run python build.py -v ndk

* Downloading and extracting ondk-r29.5-windows.tar.xz

rm -rf C:\Android\android-sdk\ndk\ondk-r29.5
rm -rf C:\Android\android-sdk\ndk\magisk
mv C:\Android\android-sdk\ndk\ondk-r29.5 -> C:\Android\android-sdk\ndk\magisk# GitHub Docs <!-- omit in toc -->

Welcome to GitHub Docs! GitHub’s documentation is open source, meaning anyone from inside or outside the company can contribute. For full contributing guidelines, visit our [contributing guide](https://docs.github.com/en/contributing).


## Quick links by contributor type

* **Hubbers (GitHub employees):** See [CONTRIBUTING.md](https://github.com/github/docs-content/blob/main/CONTRIBUTING.md) in the `docs-content` repository for GitHub-specific processes.

* **Open source contributors:** See [CONTRIBUTING.md](https://github.com/github/docs/blob/main/.github/CONTRIBUTING.md) in the `docs` repository for a quick-start summary.

## How we sync changes across Docs repositories

There are two GitHub Docs repositories: 

- **`github/docs`** (public): Open to external contributions

- **`github/docs-internal`** (private): For GitHub employee contributions. 

The two repositories sync frequently. Content changes in one are reflected in the other.  Hubbers might prefer to post in `docs` when working with a customer, but `docs` has limitations on the types of contributions it accepts to safeguard the site and our workflows. Internal contributions should usually go to `docs-internal`.

**Important:** The `docs` repository accepts contributions to content files (`.md` files in `/content` and select `/data` sections like reusables only). Infrastructure files, workflows, and site-building code are not open for external modification.

## New to contributing

Here are some resources to help you get started with open source contributions:

* [Finding ways to contribute to open source on GitHub](https://docs.github.com/en/get-started/exploring-projects-on-github/finding-ways-to-contribute-to-open-source-on-github)
* [Set up Git](https://docs.github.com/en/get-started/git-basics/set-up-git)
* [GitHub flow](https://docs.github.com/en/get-started/using-github/github-flow)
* [Collaborating with pull requests](https://docs.github.com/en/github/collaborating-with-pull-requests)

## License

This project is dual-licensed under:

* **Creative Commons Attribution 4.0** - for documentation and content in the assets, content, and data folders (see [LICENSE](LICENSE))
* **MIT License** - for code (see [LICENSE-CODE](LICENSE-CODE))
