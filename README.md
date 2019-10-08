## THIS REPO CONTAINS WIP CONVERTS!

## CONVERTS ARE NOT CONSIDERED COMPLETE UNTIL THEY ARE PUT IN A RELEASE!

The purpose of this repo is to manage the making of .ksh converts and open contributions publiclly. Complete charts will be released via the releases page simultaniously with the main folder on a per update basis, and then archived from the repo after some time to keep size limits down. Despite the warning above, there is nothing stopping you from pulling the WIP converts in this repo on your local machine for you to play them, but do be noted again that charts are not considered complete until they are part of a release. Dedicated reviewers are assigned to each chart to scan mistakes, so while reporting mistakes on a pending convert is not necessary, they are still appreciated. I would prefer if you only submitted  issues for charts that are already demmed complete or in the main folder

# How to Submit

There's different ways to submit your contributions. Since I'm not expecting everyone to know Git I've provided some steps to help you with the process

**Fork, Clone and Push changes** This way requires [Git](https://git-scm.com/). This is the prefered method
1. Fork the repo
2. Clone your repo onto your PC
3. Open repo in your choice of interface: any Git GUI, cmd, powershell...etc
4. Pull any updates `git pull origin master`
5. Make the necessary changes to the convert
6. Stage any files you added or changed `git add .` or `git add file.ksh`
7. Commit changes with a status message `git commit -m "Ready for review"`
8. Merge your changes `git push origin master`
9. Submit a pull request on this page
10. repeat from step 3 for any new converts

**Fork and Upload**
This method doesn't require Git, but you may run into problems later down the line if wanting to contribute more in the future without having an updated the repo. I would suggest using the method above if you want to contribute more than once.
1. Fork the repo
2. Go to your forked repo
3. Make the necessary changes to the convert
4. Upload any changed files to the correct folder
5. Submit a pull request on this page

**Submit an issue with the zip file of your convert** Not prefered but better than nothing
1. Clone the repo or download the templates release for your convert on the releases tab
2. Make the necessary changes to the convert
3. Submit an issue with the topic "Song Name <difficulty> ready for review" and attach your .ksh file or zip of the folder if you added any extra files
  
**DM me on discord** Last resort, if for any reason you don't want to make a GitHub account or Git is just too scary for you, just DM me on discord.
1. Clone the repo or download the templates release for your convert on the releases tab
2. Make the necessary changes to the convert
3. DM me at Ted_the_red#7065 with your .ksh file or zip of the folder if you added any extra files

# Guidelines

Updates will have a lot of this setup for you already but in the event that you need to add something or something is missing from the templates here's what you need to do.

**Metadata**
1. **only use `.ogg` or `.wav` audio formats.** `.mp3` has issues when exporting by adding extra samples of silence to the begining of an audio file and is not accurate when working in DAWs. For this reason, it cannot be timmed reliably via a DAW and should not be used for .ksh.
2. Make sure song files and .ksh files are named by their respective difficulty `mxm, exh, adv, nov, vvd`
3. For jacket file names, name them `jak.png` for static images or `mxm.png, exh.png...etc.` if the jacket is different per difficulty. If it is static, only one image needs to be provided

Dynamic

![Dynamic](https://tedtr.s-ul.eu/UORNnge2)

Static

![Static](https://tedtr.s-ul.eu/jRtFRRlW)

4. Fill out as much relevant descriptive info as possible. In order of importance these are: `Song Title, Artist, Effected by, Illustrated by`
5. Do not change the default backgrounds and forgrounds. Due to complaints with skin incompatibility we will leave these as is.
6. Sample start is not required, but you can add it if you desire.
7. In the detailed metadata section write `../sdvx05.png` under genre icon filename. 

**Chart setup**
1. Mute ksm laser sounds at the start of the chart as we will be using purely FX tracks for each chart. To change these, hit the `v` key and click the red line to change slam volume to 0. Do this with laser volume as well with the `g` key
2. make sure your audio file has at minimum 3/4 of a blank measure to provide a buffer before the chart starts. If the chart starts in the middle of a measure just move the start to the 2nd measure

Here's some examples of chart starts:

![Normal](https://tedtr.s-ul.eu/KUcgMF48) ![3/4 Start](https://tedtr.s-ul.eu/6oBbmyUH) ![Extended Start](https://tedtr.s-ul.eu/MVYLLMMs)

**Uploading**
1. only upload/push modified files. If there is an older chart you are adding a difficulty too, do not add the difficulties already uploaded. this makes for a cleaner folder and clear what was changed.
2. folders should be named in alphanumeric characters, lowercased and underscores for spaces. This saves headache when running commands on these files and provides consistency.

Examples:

* (Extra Symbols) `PARTY TIME!` to `party_time`
* (Letters and Numbers) `D1g1t1ze b0dy` to `d1g1t1ze_b0dy`
* (Kanji/Hirigana) `ゆりゆららららゆるゆり大事件（yuzen remix）` to `yuri_yurararara_yuru_yuri_daijigen_yuzen_remix`
* (Katakana) `タイムトラベル` to `time_travel`

# TODO
- [x] Write submission instructions
- [x] Write guidelines
- [ ] Write some tutorials for convert making 
- [ ] Privide links to resources
