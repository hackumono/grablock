# GrabLock v7.0

Grablock it's the first tool (02/03/2020) for phishing attacks on the lock screen, designed to grab Windows credentials, Android PIN and iPhone Passcode using a https link.


<p align="center">
<a href="https://github.com/evildevill"><img title="Author" src="https://img.shields.io/badge/Author-Evil Devil-red.svg?style=for-the-badge&logo=github"></a>
<a href="#"><img title="Open Source" src="https://img.shields.io/badge/Open%20Source-%E2%9D%A4-green?style=for-the-badge"></a>
</p>
<p align="center">
<a href="#"><img title="Version" src="https://img.shields.io/badge/Version-1.0-green.svg?style=flat-square"></a>
<a href="https://github.com/evildevill/followers"><img title="Followers" src="https://img.shields.io/github/followers/evildevill?color=blue&style=flat-square"></a>
<a href="https://github.com/evildevill/grablock/stargazers/"><img title="Stars" src="https://img.shields.io/github/stars/evildevill/grablock?color=red&style=flat-square"></a>
<a href="https://github.com/evildevill/grablock/network/members"><img title="Forks" src="https://img.shields.io/github/forks/evildevill/grablock?color=red&style=flat-square"></a>
<a href="https://github.com/evildevill/grablock/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/evildevill/grablock?label=Watchers&color=blue&style=flat-square"></a>
<a href="http://hits.dwyl.com/evildevill/grablock"><img src="http://hits.dwyl.com/evildevill/grablock.svg" alt="HitCount"></a>
</p>
<p align="center"><a href="https://www.gnu.org/software/bash/"><img src="https://img.shields.io/badge/-Made%20with%20Bash-1f425f.svg?style=plastic&amp;logo=image%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABgAAAAYCAYAAADgdz34AAAAGXRFWHRTb2Z0d2FyZQBBZG9iZSBJbWFnZVJlYWR5ccllPAAAAyZpVFh0WE1MOmNvbS5hZG9iZS54bXAAAAAAADw%2FeHBhY2tldCBiZWdpbj0i77u%2FIiBpZD0iVzVNME1wQ2VoaUh6cmVTek5UY3prYzlkIj8%2BIDx4OnhtcG1ldGEgeG1sbnM6eD0iYWRvYmU6bnM6bWV0YS8iIHg6eG1wdGs9IkFkb2JlIFhNUCBDb3JlIDUuNi1jMTExIDc5LjE1ODMyNSwgMjAxNS8wOS8xMC0wMToxMDoyMCAgICAgICAgIj4gPHJkZjpSREYgeG1sbnM6cmRmPSJodHRwOi8vd3d3LnczLm9yZy8xOTk5LzAyLzIyLXJkZi1zeW50YXgtbnMjIj4gPHJkZjpEZXNjcmlwdGlvbiByZGY6YWJvdXQ9IiIgeG1sbnM6eG1wPSJodHRwOi8vbnMuYWRvYmUuY29tL3hhcC8xLjAvIiB4bWxuczp4bXBNTT0iaHR0cDovL25zLmFkb2JlLmNvbS94YXAvMS4wL21tLyIgeG1sbnM6c3RSZWY9Imh0dHA6Ly9ucy5hZG9iZS5jb20veGFwLzEuMC9zVHlwZS9SZXNvdXJjZVJlZiMiIHhtcDpDcmVhdG9yVG9vbD0iQWRvYmUgUGhvdG9zaG9wIENDIDIwMTUgKFdpbmRvd3MpIiB4bXBNTTpJbnN0YW5jZUlEPSJ4bXAuaWlkOkE3MDg2QTAyQUZCMzExRTVBMkQxRDMzMkJDMUQ4RDk3IiB4bXBNTTpEb2N1bWVudElEPSJ4bXAuZGlkOkE3MDg2QTAzQUZCMzExRTVBMkQxRDMzMkJDMUQ4RDk3Ij4gPHhtcE1NOkRlcml2ZWRGcm9tIHN0UmVmOmluc3RhbmNlSUQ9InhtcC5paWQ6QTcwODZBMDBBRkIzMTFFNUEyRDFEMzMyQkMxRDhEOTciIHN0UmVmOmRvY3VtZW50SUQ9InhtcC5kaWQ6QTcwODZBMDFBRkIzMTFFNUEyRDFEMzMyQkMxRDhEOTciLz4gPC9yZGY6RGVzY3JpcHRpb24%2BIDwvcmRmOlJERj4gPC94OnhtcG1ldGE%2BIDw%2FeHBhY2tldCBlbmQ9InIiPz6lm45hAAADkklEQVR42qyVa0yTVxzGn7d9Wy03MS2ii8s%2BeokYNQSVhCzOjXZOFNF4jx%2BMRmPUMEUEqVG36jo2thizLSQSMd4N8ZoQ8RKjJtooaCpK6ZoCtRXKpRempbTv5ey83bhkAUphz8fznvP8znn%2B%2F3NeEEJgNBoRRSmz0ub%2FfuxEacBg%2FDmYtiCjgo5NG2mBXq%2BH5I1ogMRk9Zbd%2BQU2e1ML6VPLOyf5tvBQ8yT1lG10imxsABm7SLs898GTpyYynEzP60hO3trHDKvMigUwdeaceacqzp7nOI4n0SSIIjl36ao4Z356OV07fSQAk6xJ3XGg%2BLCr1d1OYlVHp4eUHPnerU79ZA%2F1kuv1JQMAg%2BE4O2P23EumF3VkvHprsZKMzKwbRUXFEyTvSIEmTVbrysp%2BWr8wfQHGK6WChVa3bKUmdWou%2BjpArdGkzZ41c1zG%2Fu5uGH4swzd561F%2BuhIT4%2BLnSuPsv9%2BJKIpjNr9dXYOyk7%2FBZrcjIT4eCnoKgedJP4BEqhG77E3NKP31FO7cfQA5K0dSYuLgz2TwCWJSOBzG6crzKK%2BohNfni%2Bx6OMUMMNe%2Fgf7ocbw0v0acKg6J8Ql0q%2BT%2FAXR5PNi5dz9c71upuQqCKFAD%2BYhrZLEAmpodaHO3Qy6TI3NhBpbrshGtOWKOSMYwYGQM8nJzoFJNxP2HjyIQho4PewK6hBktoDcUwtIln4PjOWzflQ%2Be5yl0yCCYgYikTclGlxadio%2BBQCSiW1UXoVGrKYwH4RgMrjU1HAB4vR6LzWYfFUCKxfS8Ftk5qxHoCUQAUkRJaSEokkV6Y%2F%2BJUOC4hn6A39NVXVBYeNP8piH6HeA4fPbpdBQV5KOx0QaL1YppX3Jgk0TwH2Vg6S3u%2BdB91%2B%2FpuNYPYFl5uP5V7ZqvsrX7jxqMXR6ff3gCQSTzFI0a1TX3wIs8ul%2Bq4HuWAAiM39vhOuR1O1fQ2gT%2F26Z8Z5vrl2OHi9OXZn995nLV9aFfS6UC9JeJPfuK0NBohWpCHMSAAsFe74WWP%2BvT25wtP9Bpob6uGqqyDnOtaeumjRu%2ByFu36VntK%2FPA5umTJeUtPWZSU9BCgud661odVp3DZtkc7AnYR33RRC708PrVi1larW7XwZIjLnd7R6SgSqWSNjU1B3F72pz5TZbXmX5vV81Yb7Lg7XT%2FUXriu8XLVqw6c6XqWnBKiiYU%2BMt3wWF7u7i91XlSEITwSAZ%2FCzAAHsJVbwXYFFEAAAAASUVORK5CYII%3D" alt="made-with-bash"></a></p>

### Features:

#### Lockscreen phishing page for Windows, Android and iPhone
#### Auto detect device
#### Port Forwarding by Ngrok
#### IP Tracker

## Legal disclaimer:

Usage of grablock for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program. 

### Usage:
```
pkg update 
pkg install php 
pkg install openssh
pkg install wget
pkg install git -y
git clone https://github.com/evildevill/grablock.git
cd grablock
bash grablock.sh
```

<p>
<img src="https://visitor-badge.laobi.icu/badge?page_id=evildevill.evildevill" alt="visitor badge"/>
</p>


<h2>Hi, I'm WaSim AkrAm! <img src="https://media.giphy.com/media/12oufCB0MyZ1Go/giphy.gif" width="50"></h2>
<img align='right' src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="230">
<br/>
<a href="https://twitter.com">
  <img align="left" alt="Hackerwasii| Twitter" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/twitter.svg" />
</a>
<a href="https://www.instagram.com/__empty254__/">
  <img align="left" alt="Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />
</a>
<a href="https://github.com/evildevill">
  <img align="left" alt="GitHub" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@3.5.0/icons/github.svg" />
</a>
<a href="https://wa.me/+923137119351">
  <img align="left" alt="whatsapp" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@3.5.0/icons/whatsapp.svg" />
</a>
<br/>
<br/>

### Hi 🙋‍♂️,
### I'm 18 years old Self-taught developer, technical support engineer , Graphics Designer from Pakistan.

<br/>


**I am Into , 🙏**
<br/>
**Machine Learning, Web Development, Mobile Application Development, Cloud Computing, Linux, System Design & Programming**

<br/>

<a href="https://github.com/evildevill">
  <img src="https://github-readme-stats.vercel.app/api?username=evildevill&show_icons=true" alt="evildevill GitHub Stats" />
</a>

<br />

*************

<br />

### Languages and Tools...

<p align="center">
 <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/languages/html.svg" alt="Twitter" style="vertical-align:top; margin:4px"> <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/languages/csharp.svg"alt="Twitter" style="vertical-align:top; margin:4px"> <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/languages/js.svg" alt="Twitter" style="vertical-align:top; margin:4px"> <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/misc/cloud.svg" alt="Twitter" style="vertical-align:top; margin:4px"> <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/misc/datascience.svg" alt="Twitter" style="vertical-align:top; margin:4px"> <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/services/aws.svg" alt="Twitter" style="vertical-align:top; margin:4px"> <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/services/npm.svg" alt="Twitter" style="vertical-align:top; margin:4px"> <img src="https://raw.githubusercontent.com/8bithemant/8bithemant/master/svg/dev/tools/bash.svg" alt="Twitter" style="vertical-align:top; margin:4px">
 </p>
 <p align="center">
 <code><a href="https://www.python.org/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/python/python-ar21.svg"></a></code>
<code><a href="https://www.linux.org/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/linux/linux-ar21.svg"></a></code>
<code><a href="https://reactjs.org/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/reactjs/reactjs-ar21.svg"></a></code>
<code><a href="https://www.docker.com/" target="_blank"><img height="50" src="https://www.vectorlogo.zone/logos/docker/docker-official.svg"></a></code>
<br/><br/>
</p>

***********************************

#### Thank You-🙏🏼

<p>
<img src="https://visitor-badge.laobi.icu/badge?page_id=HackerWaSi" alt="visitor badge"/>
</p>
