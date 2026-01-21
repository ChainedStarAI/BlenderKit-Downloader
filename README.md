This Blender add-on is designed for bulk downloading of assets (`Free` and `Full`) from [BlenderKit.com](https://www.blenderkit.com) in ".blend" format. Main reason for its existence is that the [Official add-on](https://www.blenderkit.com/get-blenderkit/) requires you to manually enter the link and save the project file for each asset.

UI is located in Sidebar (toggle by **N** key), in **[BK Downloader]** tab :

**Links file** – text file containing list of links (one per line) to each desired resource

**Output path** – folder where the downloaded ".blend" files will be saved

**API Key** – downloading assets released under Full plan requires a [paid subscription](https://www.blenderkit.com/plans/pricing/).

**Delay** – delay in seconds before starting download of new asset after the previous one has finished downloading (additional random 1–5 seconds will be added to it for each asset).

**Console** – displays a list of assets to download, their order numbers, names, and current downloading status. When finished, you'll see a report on successful/failed downloads.

<details>
<summary><strong>SPOILER: Where can I get API Key?</strong></summary>
After payment go to the <a href="https://www.blenderkit.com/profile/addon/">ADD-ON tab</a> of your profile (Upper right corner of website -> Your round avatar -> ADD-ON) and press <strong>Show API Key</strong>. Paste this into add-on "API Key" field and you will be able to download <code>Full</code> plan assets as well. For security reasons, the add-on does not store the entered value in memory – you need to specify it for each session.
<br><br>
Don't share your API Key with anyone, otherwise you may get banned. If you suspect that your API Key has leaked, click <strong>[Reset]</strong> in the ADD-ON tab on website to create a new version and delete the old one.
</details>

<details>
<summary><strong>SPOILER: Is this legal?</strong></summary>
Assets downloading are performed via their <a href="https://www.blenderkit.com/api/v1/">open API</a>. Links to each asset can only be obtained from their official website. Downloading assets from <code>Full</code> plan without an API key (paid subscription) is not possible with this add-on, nor is downloading <code>Private</code> assets (hidden by the author) possible. So, using this add-on is completely legal and cannot lead to ban, as long as you don't download hundreds of assets with 0.1 second delay in 24/7, of course.
</details>

<details>
<summary><strong>SPOILER: How to install?</strong></summary>
Just like any other add-on for Blender:
<br><br>
1) Upper left corner of Blender<br>
2) Edit<br>
3) Preferences...<br>
4) Upper right corner of the opened window<br>
5) [↓]<br>
6) Install from disk...<br>
7) Select the downloaded .ZIP file.
<br><br>
The add-on is activated automatically.
</details>
<br>

Tested in [Blender 4.2.6 LTS](https://www.blender.org/download/lts/4-2/). If you have any suggestions for improving the add-on or bug reports, please write in this thread.
