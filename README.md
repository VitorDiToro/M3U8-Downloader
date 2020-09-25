![M3U8-Downloader-Build](https://github.com/HeiSir2014/M3U8-Downloader/workflows/M3U8-Downloader-Build/badge.svg)

Original (Chinese) Version: https://github.com/HeiSir2014/M3U8-Downloader

# M3U8-Downloader [直接下载](#下载可执行包)
M3U8-Downloader is an APP developed based on the Electron framework that can download and play HLS video streams. The features are as follows:

| Features | Supported |
| :-- | --: |
| HLS protocol on-demand source | ✓ |
| Custom HTTP protocol header download | ✓ |
| Custom KEY and IV decryption | ✓ |
| Local M3U8 file download | ✓ |
| HLS protocol live source | ✓ |
| Standard AES-128-CBC encryption| ✓ |
| Standard AES-196-CBC encryption| ✓ |
| Standard AES-256-CBC encryption | ✓ |
| Non-standard AES-*-CBC encryption| ㄨ(Customizable) |


<div align="center">
	<br>
	<img width="739" src="https://github.com/HeiSir2014/M3U8-Downloader/blob/master/resource/HLSDownloadShow-3-1.gif?raw=true" alt="M3U8-Downloader">
	<br>
</div>
<div align="center">
	<br>
	<img width="739" src="https://github.com/HeiSir2014/M3U8-Downloader/blob/master/resource/HLSDownloadShow-3-2.gif?raw=true" alt="M3U8-Downloader">
	<br>
</div>

<div align="center">
	<br>
	<img width="739" src="https://github.com/HeiSir2014/M3U8-Downloader/blob/master/resource/HLSDownloadShow-4.gif?raw=true" alt="M3U8-Downloader">
	<br>
</div>

# 流程原理图

---

<div align="center">
	<br>
	<img width="1024" src="https://github.com/HeiSir2014/M3U8-Downloader/raw/master/resource/flowchart.png" alt="M3U8-Downloader">
	<br>
</div>

---

# Official website
[M3U8-Downloader 官网](https://tools.heisir.cn/HLSDownload)

QQ交流群：341972319

[点我加QQ交流群](https://jq.qq.com/?_wv=1027&k=nhFrZBS0)

# Get the M3U8 video address

Open the video webpage in the chrome browser, press F12, click on the tab to go to the Network page, enter "m3u8" in the Filter box, and then press F5 to refresh the page.
If the video on the webpage uses HLS source, you can capture it here Go to the video stream address, then right click Copy -> Copy Link Address.

Provide m3u8 source address, download and lossless transcode Mp4 file


[自定义头添加-视频教程](https://player.bilibili.com/player.html?aid=498666070&bvid=BV1QK411n7VJ&cid=206827525&page=1)

# Download the executable package

## [Recommended] 蓝奏下载
## [Windows 、Linux、MacOS download](https://tools.heisir.cn/HLSDownload/download.html)

## Github download
## [Releases下载](https://github.com/HeiSir2014/M3U8-Downloader/releases)


# 运行源码
### NodeJS开发环境搭建

安装NodeJs最新版，[NodeJs Download](http://nodejs.cn/download/)

### Clone 代码

在任意文件夹下新建一个文件夹存放代码，并执行以下命令
```
cd newdir

git clone https://github.com/HeiSir2014/M3U8-Downloader.git .
```
### Yarn environmental installation

```
npm install yarn -g
```

### Package dependent installation

```
yarn
```
### Run M3U8-Downloader

```
yarn start
```
### Package release

```
//windows 平台打包
yarn pack-win

//mac 平台打包
yarn pack-mac

```

### Enjoy it

### 赞赏

[Appreciate link](https://tools.heisir.cn/HLSDownload/2019/07/08/02/)
