Please make sure the Tampermonkey 正式版extension before clicking on [Install Script] above!
Note : When accessing Github on the Safari browser, you cannot run any oil monkey scripts. For details, see: #110202
         
•	CloudflareSpeedTest - Test Cloudflare CDN latency and speed, get the fastest IP (IPv4+IPv6)! 5k+ ⭐

•	Trackerslist.com - updated daily! List of popular BT Trackers in the whole network! Effectively improve BT download speed ! 13k+ ⭐

•	YueDu - Sharing my self-made "reading" APP excellent book source (online novel)! 2k+ ⭐

•	Eye protection mode - simple and effective network-wide eye protection, night, dark mode

•	Zhihu Enhancement - Remove login pop-ups, block homepage videos , quickly retract answers/comments, quickly return to the top, block users/keywords/salt selection , default high-definition original images, default off-site direct links...

•	Lansuo cloud network disk enhancement - refresh does not return to the root directory, back to the previous level, right-click the file to display the menu , click to download the file directly, automatically display more files, customize the share link domain name ...

•	自动无缝翻页- Seamlessly connect the content of the next page to the bottom of the page (waterfall flow), currently supports: all "Discuz!, Flarum, phpBB, NexusPHP..." forums , Baidu, Google, Bing, Sogou, Tieba, Douban, NGA, 3DM, Qiantu.com, Ranger.com, Nomad Star, NexusMods, Steam Workshop, Film and Television, Anime, Comics, BT, etc...

If you think it's not bad, go to Github and click [⭐ Star] to encourage it (or share more)! https://github.com/XIU2/UserScript
________________________________________
What does this script do?
After installation, add high-speed download (accelerated download) for Github's Git Clone/SSH, Release, Raw, Code(ZIP) and other files that need to be downloaded ! And on the project list page, add a single-file quick download (☁) link!
 
________________________________________
How to install/use this script?
To use this script, a Tampermonkey script manager extension ( Chrome / Firefox / Edge ) needs to be installed in the browser.
After installing the browser extension, click [Install Script] at the top of this page and the extension will pop up an installation prompt, click [Install] in the prompt .
Other browsers based on Chromium kernel (such as domestic skin browsers) can use Chrome extensions.
Please make sure to use the Tampermonkey official version extension, other user script managers may cause the script to not work properly .
If you want to reinstall the script, please remember to completely delete the script in the recycle bin of the Tampermonkey extension before reinstalling the script.
Don't install .crx extensions offline? Chrome, Edge re-enable hidden [drag-in-install .crx extension] feature!
________________________________________
How to further speed up?
If you want to speed up further, you can try to turn on the hidden multi-threaded download function of the Chrome browser , which will theoretically double the download speed.
________________________________________
What is the principle?
At present, there are many websites or open source projects that accelerate the download of Github files . The script just adds the accelerated file download address to the webpage, which saves the trouble of manual acquisition, and is convenient to directly click on the high-speed download!
Normally, downloading files from Github may not be so slow, but Github is often disturbed and restricted , resulting in slow or even completely inaccessible speeds. Therefore, as long as the speed of your link acceleration source is faster than that of the native CDN used by Github, it is acceleration . Download it~
________________________________________
Can't access Github?
This script can only improve the download speed of Github files, but you may find that since a certain meeting in early March 2021, many regions have intermittently lost access to Github.
In this case, it is useless whether to change DNS or change Hosts, because Qiang interferes/blocks the Github domain name SNI. When any IP points to Github to access, the 443 port of the IP will time out for 3 minutes!
Because it is random interference, it sometimes encounters "short-lived" available IPs ( simulating packet loss, masquerading as the website's own network problem ).
If you are interested, you can read this article explaining the analysis in detail: https://www.v2ex.com/t/758568
So there are currently only three ways to access Github:
1.	ladder
2.	Mirror site ( https://hub.fastgit.xyz/Visit Github to automatically redirect to a mirror site )
3.	Go abroad in the flesh
4.	Local proxy direct connection acceleration, bypassing SNI interference ( https://github.com/docmirror/dev-sidecar / https://gitee.com/docmirror/dev-sidecar )
________________________________________
Why can't the quick download [ ☁ ] directly click to download?
This is because the browser security policy prohibits cross-domain downloading of files (that is, the domain name of the file download address is inconsistent with the current website domain name), and the browser fundamentally restricts this function for security, so it can only be accessed through [Alt + left button] Or [Right Click - Save As...] to download the file.
________________________________________
Thanks to these charitable acceleration sources:
Release, Code (ZIP) file acceleration:
	
https://gh.gh2233.ml
USA (courtesy of @XIU

https://gh.api.99988866.xyz
USA (provided by hunshcn /gh-proxy

https://gh2.yanqishui.work
United States (courtesy of @HongjieCN

https://ghdl.feizhuqwq.cf
United States (courtesy of feizhuqwq

https://gh.ddlc.top
USA (courtesy of @ mtr -static-official

https://gh-proxy-misakano7545.koyeb.app
U.S.
https://gh.flyinbug.top
United States (courtesy of Minimate

https://github.91chi.fun
U.S.
https://proxy.zyun.vip
United States ( provided by Zhidao Station

https://git.xfj0.cn
U.S.
https://gh.con.sh
U.S.
https://ghps.cc
U.S.
https://cors.isteed.cc
USA (courtesy of Lufs 's

https://cdn.githubjs.cf
U.S.
https://download.fastgit.org
Tokyo , Japan (courtesy of FastGit

https://ghproxy.com
Seoul, South Korea (courtesy of ghproxy
Because there are too many acceleration sources in the United States, and for load balancing, it is specially changed to only randomly select a few of them each time a webpage is opened.
Git Clone acceleration:
		
https://gitclone.com
China domestic (provided by GitClone	
https://hub.fastgit.xyz
Tokyo , Japan (courtesy of FastGit

https://ghproxy.com
Seoul, South Korea (courtesy of ghproxy	
https://gh.gcdn.mirr.one
Russia (provided by G-Core Labs CDN	
Git Clone SSH acceleration:
		
git@ssh.fastgit.org	Hong Kong , China ( provided by FastGit

git@git.zhlh6.cn	U.S.	
Raw file acceleration:
		
https://raw.iqiq.io
Hong Kong , China ( provided by iQDNS

https://fastly.jsdelivr.net
Tokyo , Japan (provided by JSDelivr CDN	
https://cdn.staticaly.com
Tokyo , Japan (provided by Statically CDN	
https://raw.fastgit.org
Tokyo , Japan (courtesy of FastGit

https://ghproxy.net
Osaka, Japan	
https://gcore.jsdelivr.net
Others (provided by JSDelivr CDN, Mobile to Hong Kong, Telecom to Japan	
https://raw.githubusercontents.com
Others (Hong Kong, Singapore, USA, etc., not fixed	
https://raw-gh.gcdn.mirr.one
Russia (provided by G-Core Labs CDN	
Notice! Some of the raw acceleration sources have 缓存files, so the downloaded files may not be the latest . You can point the mouse to the download button to check whether the acceleration source is cached.
