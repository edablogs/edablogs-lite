---
layout: post
title: Easiest way to install Google chrome on ubuntu 14.04,14.10,13
date: '2014-12-23T00:29:00.000+05:30'
author: pawneshwer
categories:
- computer
tags:
- computer
- Linux
- Ubuntu
modified_time: '2016-02-20T06:51:30.471+05:30'
blogger_id: tag:blogger.com,1999:blog-1967791069058877982.post-3173472496162436505
blogger_orig_url: http://www.edablogs.com/2014/12/easiest-way-to-install-google-chrome-on.html
redirect_from:
- /2014/12/easiest-way-to-install-google-chrome-on.html
---

<div dir="ltr" style="text-align: left;"><div style="line-height: 115%; margin-bottom: 0.35cm;"><div style="clear: both; text-align: center;"><a href="http://www.trickspapa.com/wp-content/uploads/2014/12/google_chrome_ubuntu_12_04.jpg" style="margin-left: 1em; margin-right: 1em;"><img alt="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" border="0" src="http://www.trickspapa.com/wp-content/uploads/2014/12/google_chrome_ubuntu_12_04.jpg" height="151" title="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" width="400" /></a></div><br /><div style="text-align: justify;"><span lang="en-US">Hello reader, Ubuntu users a very good evening to all. From past months i moved to <a href="http://www.ubuntu.com/" rel="homepage" target="_blank" title="Ubuntu (operating system)">Linux Ubuntu</a> from <a href="http://www.microsoft.com/WINDOWS" rel="homepage" target="_blank" title="Windows">Windows</a> 8.1. So now i will write about Ubuntu tricks and help. So in this tutorial i will write about&nbsp;how to install chrome on ubuntu,how to install <a href="http://www.google.com/chrome" rel="homepage" target="_blank" title="Google Chrome">google chrome</a> in ubuntu,chrome standalone installer</span></div></div><div lang="en-US" style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><span lang="en-US">To install <a href="http://en.wikipedia.org/wiki/Google_Chrome" rel="wikipedia" target="_blank" title="Google Chrome">Google chrome</a> you need to first download and install <a href="http://en.wikipedia.org/wiki/Software_repository" rel="wikipedia" target="_blank" title="Software repository">Linux Repository</a> form <a href="http://www.google.com/" rel="homepage" target="_blank" title="Google">Google</a> you that you can install Google chrome via <a href="http://en.wikipedia.org/wiki/Personal_Package_Archive" rel="wikipedia" target="_blank" title="Personal Package Archive">PPA</a>. And key. You can install Google chrome PPA by the following command.</span></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><ul><li><span lang="en-US">First of all open terminal by going to menu and search for terminal (<span style="color: red;">for this you need password of your admin account. Means if you are at college and admin account is restricted to you then you can't execute this command.</span>)</span></li></ul></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><ul><li><span lang="en-US">Now you have opened terminal type the following command in terminal and press enter.</span></li></ul><div>wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | <a href="http://www.sudo.ws/" rel="homepage" target="_blank" title="Sudo">sudo</a> apt-key add -</div><br /><div style="clear: both; text-align: center;"><a href="http://www.trickspapa.com/wp-content/uploads/2014/12/Screenshot-2Bfrom-2B2014-12-22-2B17-3A56-3A59.png" style="margin-left: 1em; margin-right: 1em;"><img alt="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" border="0" src="http://www.trickspapa.com/wp-content/uploads/2014/12/Screenshot-2Bfrom-2B2014-12-22-2B17-3A56-3A59.png" height="179" title="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" width="320" /></a></div><br /></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><ul><li><span lang="en-US">Now this command will ask you to enter your password.</span></li></ul></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><ul><li><span lang="en-US">Now message will come "OK" as shown below in <a href="http://en.wikipedia.org/wiki/Screenshot" rel="wikipedia" target="_blank" title="Screenshot">screen-shot</a>. It means that key is installed successfully. (as shown in above screenshot)</span></li></ul></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><ul><li><span lang="en-US">Now proceed to next step by install Google Linux repository, paste below code .</span></li></ul><div>sudo sh -c 'echo "deb http://dl.google.com/linux/chrome/deb/ stable main" &gt;&gt; /etc/apt/sources.list.d/google-chrome.list'</div></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><ul><li><span lang="en-US">Now message will come as shown in screen-shot means Google repository is also now installed in your system.</span></li></ul><span lang="en-US"><span></span><span></span></span></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><ul><li><span lang="en-US">Now to can continue to installation steps. So update repository by below command.&nbsp;</span></li></ul><div>sudo <a href="http://wiki.debian.org/Apt" rel="homepage" target="_blank" title="Advanced Packaging Tool">apt-get</a> update</div></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><ul><li><span lang="en-US">This command will take 4-5 minutes depending upon your INTERNET speed. As shown below.</span></li></ul><table cellpadding="0" cellspacing="0" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody><tr><td style="text-align: center;"><a href="http://www.trickspapa.com/wp-content/uploads/2014/12/Screenshot-2Bfrom-2B2014-12-22-2B17-3A58-3A31.png" style="margin-left: auto; margin-right: auto;"><img alt="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" border="0" src="http://www.trickspapa.com/wp-content/uploads/2014/12/Screenshot-2Bfrom-2B2014-12-22-2B17-3A58-3A31.png" height="179" title="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" width="320" /></a></td></tr><tr><td style="text-align: center;">Repository update successfully</td></tr></tbody></table></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><ul><li><span lang="en-US">After that paste the following command to install Google chrome's stable version.</span></li></ul><div>sudo apt-get install google-chrome-stable</div><br /><table cellpadding="0" cellspacing="0" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody><tr><td style="text-align: center;"><a href="http://www.trickspapa.com/wp-content/uploads/2014/12/Screenshot-2Bfrom-2B2014-12-22-2B17-3A59-3A21.png" style="margin-left: auto; margin-right: auto;"><img alt="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" border="0" src="http://www.trickspapa.com/wp-content/uploads/2014/12/Screenshot-2Bfrom-2B2014-12-22-2B17-3A59-3A21.png" height="179" title="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" width="320" /></a></td></tr><tr><td style="text-align: center;"><a href="http://en.wikipedia.org/wiki/Installation_%28computer_programs%29" rel="wikipedia" target="_blank" title="Installation (computer programs)">Installation</a> started</td></tr></tbody></table><br /></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><ul><li><span lang="en-US">Congratulations you have installed Google chrome stable version on your Ubuntu PC.</span></li></ul><span lang="en-US"><span></span><span></span></span></div><table cellpadding="0" cellspacing="0" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody><tr><td style="text-align: center;"><a href="http://www.trickspapa.com/wp-content/uploads/2014/12/Screenshot-2Bfrom-2B2014-12-22-2B18-3A16-3A50.png" style="margin-left: auto; margin-right: auto;"><img alt="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" border="0" src="http://www.trickspapa.com/wp-content/uploads/2014/12/Screenshot-2Bfrom-2B2014-12-22-2B18-3A16-3A50.png" height="179" title="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" width="320" /></a></td></tr><tr><td style="text-align: center;">Installation successfull</td></tr></tbody></table><div style="text-align: justify;"><br /></div><table cellpadding="0" cellspacing="0" style="margin-left: auto; margin-right: auto; text-align: center;"><tbody><tr><td style="text-align: center;"><a href="http://www.trickspapa.com/wp-content/uploads/2014/12/Screenshot-2Bfrom-2B2014-12-22-2B18-3A18-3A47.png" style="margin-left: auto; margin-right: auto;"><img alt="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" border="0" src="http://www.trickspapa.com/wp-content/uploads/2014/12/Screenshot-2Bfrom-2B2014-12-22-2B18-3A18-3A47.png" height="179" title="Easiest way to install Google chrome on ubuntu 14.04,14.10,13" width="320" /></a></td></tr><tr><td style="text-align: center;">welcome screen of google chrome</td></tr></tbody></table><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"></div><div style="text-align: justify;"><blockquote><div style="line-height: 115%; margin-bottom: 0.35cm;"><span lang="en-US">If you want to experiment new features of Google chrome then you can install Google chrome's unstable version means beta version. Beta version have more features but bugs also.</span></div></blockquote></div><div style="text-align: justify;"><br /></div><div style="line-height: 115%; margin-bottom: 0.35cm; text-align: justify;"><ul><li><span lang="en-US">To install beta version of Google chrome paste the following command in terminal.</span></li></ul><div>sudo apt-get install google-chrome-beta</div><br />Incase if you are not happy with chrome then you can remove chrome using following command. Open terminal and paste the following command.<br /><br /><div>sudo apt-get remove google-chrome-stable</div><br /><h4>So installation of chrome succeed, now you can start using chrome.</h4></div></div>