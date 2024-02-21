<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-janus-webrtc-server" class="anchor" aria-hidden="true" tabindex="-1" href="#janus-webrtc-server"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Janus WebRTC 服务器</font></font></h1>
<p dir="auto"><a href="/meetecho/janus-gateway/blob/master/COPYING"><img src="https://camo.githubusercontent.com/3a7dab0df64e2758b8984024a5a118e0220141563c595e9c3b5cd849f9d6160d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d47504c76332d627269676874677265656e2e737667" alt="许可证：GPL v3" data-canonical-src="https://img.shields.io/badge/License-GPLv3-brightgreen.svg" style="max-width: 100%;"></a>
<a target="_blank" rel="noopener noreferrer" href="https://github.com/meetecho/janus-gateway/workflows/janus-ci/badge.svg"><img src="https://github.com/meetecho/janus-gateway/workflows/janus-ci/badge.svg" alt="雅努斯-ci" style="max-width: 100%;"></a>
<a href="https://scan.coverity.com/projects/meetecho-janus-gateway" rel="nofollow"><img src="https://camo.githubusercontent.com/62a4b8031c4672241ff4a1d5ff9575af388644fc1d3dc7910e4ba728573ed43d/68747470733a2f2f7363616e2e636f7665726974792e636f6d2f70726f6a656374732f31333236352f62616467652e737667" alt="Coverity 扫描构建状态" data-canonical-src="https://scan.coverity.com/projects/13265/badge.svg" style="max-width: 100%;"></a>
<a href="https://bugs.chromium.org/p/oss-fuzz/issues/list?sort=-opened&amp;can=1&amp;q=proj:janus-gateway" rel="nofollow"><img src="https://camo.githubusercontent.com/b41d4f7413147a8a753cea089b44c362b784b3f983bd5779e928082076969a23/68747470733a2f2f6f73732d66757a7a2d6275696c642d6c6f67732e73746f726167652e676f6f676c65617069732e636f6d2f6261646765732f6a616e75732d676174657761792e737667" alt="模糊测试状态" data-canonical-src="https://oss-fuzz-build-logs.storage.googleapis.com/badges/janus-gateway.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://www.meetecho.com" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Janus 是由Meetecho</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设计和开发的开源通用 WebRTC 服务器</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">该版本的服务器是为 Linux 系统量身定制的，尽管它也可以针对 MacOS 计算机进行编译和安装。</font><font style="vertical-align: inherit;">不支持 Windows，但如果这是一个要求，Janus 可以在 Windows 10 上的“Windows Subsystem for Linux”中工作：不要信任</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">提供</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Janus .exe 版本的存储库，它们不是官方的，不会受到支持。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于一些在线演示和文档，请务必访问</font></font><a href="https://janus.conf.meetecho.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目网站</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！</font></font></p>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意：</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这是 Janus 版本的主要分支</font></font><code>multistream</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，这是新版本。</font><font style="vertical-align: inherit;">如果您想查看 Janus 的旧版（即，</font></font><code>0.x</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">又名“旧版”），请单击</font></font><a href="https://github.com/meetecho/janus-gateway/tree/0.x"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此处</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
</blockquote>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您对 Janus 有疑问，或者希望与我们和其他用户讨论 Janus，请加入我们的</font></font><a href="https://janus.discourse.group/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">如果您遇到错误，请在</font></font><a href="https://github.com/meetecho/janus-gateway/issues"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">GitHub</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上提交问题：不过，请确保</font><font style="vertical-align: inherit;">在打开问题或拉取请求之前阅读</font></font><a href="/meetecho/janus-gateway/blob/master/.github/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">指南。</font></font></a><font style="vertical-align: inherit;"></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-dependencies" class="anchor" aria-hidden="true" tabindex="-1" href="#dependencies"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">依赖关系</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要安装它，您需要满足以下依赖项：</font></font></p>
<ul dir="auto">
<li><a href="https://github.com/akheron/jansson"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扬松</font></font></a></li>
<li><a href="https://hyperrealm.github.io/libconfig/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">库配置</font></font></a></li>
<li><a href="https://libnice.freedesktop.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">libnice</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（建议至少 v0.1.16，推荐 v0.1.18）</font></font></li>
<li><a href="https://www.openssl.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenSSL</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（至少 v1.0.1e）</font></font></li>
<li><a href="https://github.com/cisco/libsrtp"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">libsrtp</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（建议至少 v2.x）</font></font></li>
<li><a href="https://github.com/sctplab/usrsctp"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">usrsctp</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅当您对数据通道感兴趣时才需要）</font></font></li>
<li><a href="https://www.gnu.org/software/libmicrohttpd/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">libmicrohttpd</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（至少 v0.9.59；仅当您对 Janus API 的 REST 支持感兴趣时才需要）</font></font></li>
<li><a href="https://libwebsockets.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">libwebsockets</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（建议至少为 v4.x；仅当您对 Janus API 的 WebSocket 支持感兴趣时才需要）</font></font></li>
<li><a href="https://www.cmake.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">cmake</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅当您对 WebSockets 和/或 BoringSSL 支持感兴趣时才需要，因为它们使用它）</font></font></li>
<li><a href="https://github.com/alanxz/rabbitmq-c"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">rabbitmq-c</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅当您对 Janus API 或事件的 RabbitMQ 支持感兴趣时才需要）</font></font></li>
<li><a href="https://eclipse.org/paho/clients/c" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">paho.mqtt.c</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅当您对 Janus API 或事件的 MQTT 支持感兴趣时才需要）</font></font></li>
<li><a href="https://nanomsg.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">nanomsg</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅当您对 Janus API 的 Nanomsg 支持感兴趣时才需要）</font></font></li>
<li><a href="https://curl.haxx.se/libcurl/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">libcurl</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅当您对 TURN REST API 支持感兴趣时才需要）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">几个插件依赖于更多的库：</font></font></p>
<ul dir="auto">
<li><a href="https://github.com/freeswitch/sofia-sip"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Sofia-SIP</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅 SIP 插件需要）</font></font></li>
<li><a href="https://opus-codec.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">libopus</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅 AudioBridge 插件需要）</font></font></li>
<li><a href="https://www.speex.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">speexdsp</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅 AudioBridge 插件需要）</font></font></li>
<li><a href="https://xiph.org/ogg/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">libogg</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（语音邮件插件和/或后处理器以及可选的 AudioBridge 和流媒体插件所需）</font></font></li>
<li><a href="https://curl.haxx.se/libcurl/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">libcurl</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅当您对流媒体插件或示例事件处理程序插件中的 RTSP 支持感兴趣时才需要）</font></font></li>
<li><a href="https://www.lua.org/download.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Lua</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅 Lua 插件需要）</font></font></li>
<li><a href="https://duktape.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Duktape</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">（仅 Duktape 插件需要）</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">此外，您还需要以下库和工具：</font></font></p>
<ul dir="auto">
<li><a href="https://docs.gtk.org/glib/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通用库</font></font></a></li>
<li><a href="https://zlib.net/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">兹库</font></font></a></li>
<li><a href="https://www.freedesktop.org/wiki/Software/pkg-config/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">pkg 配置</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">所有这些库通常在大多数最常见的发行版上都可用。</font><font style="vertical-align: inherit;">例如，在最新的 Fedora 上安装这些库非常简单：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>yum install libmicrohttpd-devel jansson-devel \
   openssl-devel libsrtp-devel sofia-sip-devel glib2-devel \
   opus-devel libogg-devel libcurl-devel pkgconfig \
   speexdsp-devel libconfig-devel libtool autoconf automake
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="yum install libmicrohttpd-devel jansson-devel \
   openssl-devel libsrtp-devel sofia-sip-devel glib2-devel \
   opus-devel libogg-devel libcurl-devel pkgconfig \
   speexdsp-devel libconfig-devel libtool autoconf automake" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"></font><code>yum install epel-release</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，如果您尝试在 CentOS 计算机上进行安装，您可能也必须这样</font><font style="vertical-align: inherit;">做。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Ubuntu 或 Debian 上，它需要这样的东西：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>apt install libmicrohttpd-dev libjansson-dev \
	libssl-dev libsofia-sip-ua-dev libglib2.0-dev \
	libopus-dev libogg-dev libcurl4-openssl-dev liblua5.3-dev \
	libspeexdsp-dev libconfig-dev pkg-config libtool automake
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="apt install libmicrohttpd-dev libjansson-dev \
	libssl-dev libsofia-sip-ua-dev libglib2.0-dev \
	libopus-dev libogg-dev libcurl4-openssl-dev liblua5.3-dev \
	libspeexdsp-dev libconfig-dev pkg-config libtool automake" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，libopus 可能无法在您的发行版上开箱即用。</font><font style="vertical-align: inherit;">在这种情况下，您必须</font></font><a href="https://www.opus-codec.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手动安装它</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然</font></font><code>libnice</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">大多数发行版通常都以软件包的形式提供，但 Ubuntu 中开箱即用的版本已知会导致问题。</font><font style="vertical-align: inherit;">因此，我们始终建议手动编译和安装 libnice 的主版本。</font><font style="vertical-align: inherit;">要构建 libnice，您需要 Python 3、Meson 和 Ninja：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone https://gitlab.freedesktop.org/libnice/libnice
cd libnice
meson --prefix=/usr build &amp;&amp; ninja -C build &amp;&amp; sudo ninja -C build install
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://gitlab.freedesktop.org/libnice/libnice
cd libnice
meson --prefix=/usr build &amp;&amp; ninja -C build &amp;&amp; sudo ninja -C build install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请确保先删除发行版，否则会导致安装之间发生冲突。</font><font style="vertical-align: inherit;">如果您出于某种原因想要保留两者，对于 libnice 的自定义安装，您还可以运行</font></font><code>pkg-config --cflags --libs nice</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">以确保 Janus 可以找到正确的安装。</font><font style="vertical-align: inherit;">如果失败，您可能需要</font></font><code>PKG_CONFIG_PATH</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在编译 Janus 之前设置环境变量，例如，</font></font><code>export PKG_CONFIG_PATH=/path/to/libnice/lib/pkgconfig</code></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您有兴趣编译示例事件处理程序插件，您还需要安装 libcurl 的开发版本（通常</font></font><code>libcurl-devel</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Fedora/CentOS 上，</font></font><code>libcurl4-openssl-dev</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Ubuntu/Debian 上）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您的发行版附带了 1.5 版之前的 libsrtp，您必须卸载该版本并</font></font><a href="https://github.com/cisco/libsrtp/releases"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手动安装 1.5.x、1.6.x 或</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2.x。</font><font style="vertical-align: inherit;">事实上，已知 1.4.x 会导致 WebRTC 出现多个问题。</font><font style="vertical-align: inherit;">虽然支持 1.5.x，但我们建议安装 2.x。</font><font style="vertical-align: inherit;">请注意，以下步骤适用于版本 2.2.0，但可能有更新的版本可用：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>wget https://github.com/cisco/libsrtp/archive/v2.2.0.tar.gz
tar xfv v2.2.0.tar.gz
cd libsrtp-2.2.0
./configure --prefix=/usr --enable-openssl
make shared_library &amp;&amp; sudo make install
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="wget https://github.com/cisco/libsrtp/archive/v2.2.0.tar.gz
tar xfv v2.2.0.tar.gz
cd libsrtp-2.2.0
./configure --prefix=/usr --enable-openssl
make shared_library &amp;&amp; sudo make install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，该</font></font><code>--enable-openssl</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">部分很</font></font><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重要</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，因为 AES-GCM 支持需要它。</font><font style="vertical-align: inherit;">作为替代方案，您还可以</font></font><code>--enable-nss</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">让 libsrtp 使用 NSS 而不是 OpenSSL。</font><font style="vertical-align: inherit;">未能配置 libsrtp 可能会在启动 Janus 时导致未定义的引用，因为我们会尝试使用不存在的方法。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Janus 配置脚本会自动检测您安装了哪一个并自动链接到正确的库，如果两者都安装了，则选择 2.x。</font><font style="vertical-align: inherit;">如果您希望选择 1.5 或 1.6（不推荐），请</font></font><code>--disable-libsrtp2</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在配置 Janus 时传递以强制其使用旧版本。</font></font></p>
<ul dir="auto">
<li><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装 libsrtp 时，无论是哪个版本，</font></font><code>--libdir=/usr/lib64</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您安装在 x86_64 发行版上，都可能需要传递到配置脚本。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您想使用 BoringSSL 而不是 OpenSSL（例如，因为您想利用</font></font><code>--enable-dtls-settimeout</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">），则必须手动将其安装到特定位置。</font><font style="vertical-align: inherit;">使用以下步骤：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone https://boringssl.googlesource.com/boringssl
cd boringssl
# Don't barf on errors
sed -i s/" -Werror"//g CMakeLists.txt
# Build
mkdir -p build
cd build
cmake -DCMAKE_CXX_FLAGS="-lrt" ..
make
cd ..
# Install
sudo mkdir -p /opt/boringssl
sudo cp -R include /opt/boringssl/
sudo mkdir -p /opt/boringssl/lib
sudo cp build/ssl/libssl.a /opt/boringssl/lib/
sudo cp build/crypto/libcrypto.a /opt/boringssl/lib/
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://boringssl.googlesource.com/boringssl
cd boringssl
# Don't barf on errors
sed -i s/&quot; -Werror&quot;//g CMakeLists.txt
# Build
mkdir -p build
cd build
cmake -DCMAKE_CXX_FLAGS=&quot;-lrt&quot; ..
make
cd ..
# Install
sudo mkdir -p /opt/boringssl
sudo cp -R include /opt/boringssl/
sudo mkdir -p /opt/boringssl/lib
sudo cp build/ssl/libssl.a /opt/boringssl/lib/
sudo cp build/crypto/libcrypto.a /opt/boringssl/lib/" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装库后，您必须</font></font><code>--enable-boringssl</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">向配置脚本传递一个附加标志，因为默认情况下，假设使用 OpenSSL，将构建 Janus。</font><font style="vertical-align: inherit;">默认情况下，Janus 期望 BoringSSL 安装在</font></font><code>/opt/boringssl</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">-- 如果安装在其他位置，请将路径传递给配置脚本，如下所示：</font></font><code>--enable-boringssl=/path/to/boringssl</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用 OpenSSL 并且想要切换到 BoringSSL，请确保您还在</font></font><code>make clean</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Janus 中执行</font><font style="vertical-align: inherit;">文件夹，然后使用新的 BoringSSL 支持进行编译。</font><font style="vertical-align: inherit;">如果您启用了 BoringSSL 支持，并且还希望 Janus 能够检测 DTLS 超时并以更快的重传速度做出反应，那么</font></font><code>--enable-dtls-settimeout</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">也可以传递给配置脚本。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于数据通道支持所需的 usrsctp，它通常在存储库中不可用，因此如果您对它们感兴趣（支持是可选的），您必须手动安装它。</font><font style="vertical-align: inherit;">这是一个非常简单且标准的过程：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone https://github.com/sctplab/usrsctp
cd usrsctp
./bootstrap
./configure --prefix=/usr --disable-programs --disable-inet --disable-inet6
make &amp;&amp; sudo make install
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/sctplab/usrsctp
cd usrsctp
./bootstrap
./configure --prefix=/usr --disable-programs --disable-inet --disable-inet6
make &amp;&amp; sudo make install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您在 x86_64 发行版上进行安装，则可能需要传递</font></font><code>--libdir=/usr/lib64</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到配置脚本。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这同样适用于 libwebsockets，它是可选 WebSockets 支持所必需的。</font><font style="vertical-align: inherit;">如果您有兴趣支持 WebSockets 来控制 Janus，作为默认纯 HTTP REST API 的替代（或替代），您必须手动安装它：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone https://libwebsockets.org/repo/libwebsockets
cd libwebsockets
# If you want the stable version of libwebsockets, uncomment the next line
# git checkout v4.3-stable
mkdir build
cd build
# See https://github.com/meetecho/janus-gateway/issues/732 re: LWS_MAX_SMP
# See https://github.com/meetecho/janus-gateway/issues/2476 re: LWS_WITHOUT_EXTENSIONS
cmake -DLWS_MAX_SMP=1 -DLWS_WITHOUT_EXTENSIONS=0 -DCMAKE_INSTALL_PREFIX:PATH=/usr -DCMAKE_C_FLAGS="-fpic" ..
make &amp;&amp; sudo make install
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://libwebsockets.org/repo/libwebsockets
cd libwebsockets
# If you want the stable version of libwebsockets, uncomment the next line
# git checkout v4.3-stable
mkdir build
cd build
# See https://github.com/meetecho/janus-gateway/issues/732 re: LWS_MAX_SMP
# See https://github.com/meetecho/janus-gateway/issues/2476 re: LWS_WITHOUT_EXTENSIONS
cmake -DLWS_MAX_SMP=1 -DLWS_WITHOUT_EXTENSIONS=0 -DCMAKE_INSTALL_PREFIX:PATH=/usr -DCMAKE_C_FLAGS=&quot;-fpic&quot; ..
make &amp;&amp; sudo make install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li>
<p dir="auto"><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果 libwebsockets.org 由于任何原因无法访问，请将第一行替换为：</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">git 克隆</font></font><a href="https://github.com/warmcat/libwebsockets.git"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://github.com/warmcat/libwebsockets.git</font></font></a></p>
</li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这同样适用于 Eclipse Paho MQTT C 客户端库，这是可选 MQTT 支持所必需的。</font><font style="vertical-align: inherit;">如果您有兴趣集成 MQTT 通道作为 HTTP 和/或 WebSockets 的替代（或替代）来控制 Janus，或作为 Janus Events 的载体，您可以通过以下步骤安装最新版本：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone https://github.com/eclipse/paho.mqtt.c.git
cd paho.mqtt.c
make &amp;&amp; sudo make install
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/eclipse/paho.mqtt.c.git
cd paho.mqtt.c
make &amp;&amp; sudo make install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可能想为库设置不同的安装路径，为此，请将最后一个命令替换为“sudo prefix=/usr make install”。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您对 Nanomsg 支持感兴趣，则需要安装相关的 C 库。</font><font style="vertical-align: inherit;">它通常在几乎所有存储库中作为易于安装的包提供。</font><font style="vertical-align: inherit;">以下是如何在 Ubuntu 上安装它的示例：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>aptitude install libnanomsg-dev
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="aptitude install libnanomsg-dev" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">最后，rabbitmq-c 也是如此，这是可选的 RabbitMQ 支持所必需的。</font><font style="vertical-align: inherit;">事实上，可以找到该库的多个不同版本，并且大多数分发存储库中通常提供的版本相对于当前的开发状态来说并不是最新的。</font><font style="vertical-align: inherit;">因此，如果您有兴趣集成 RabbitMQ 队列作为 HTTP 和/或 WebSockets 的替代（或替代）来控制 Janus，您可以通过以下步骤安装最新版本：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone https://github.com/alanxz/rabbitmq-c
cd rabbitmq-c
git submodule init
git submodule update
mkdir build &amp;&amp; cd build
cmake -DCMAKE_INSTALL_PREFIX=/usr ..
make &amp;&amp; sudo make install
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/alanxz/rabbitmq-c
cd rabbitmq-c
git submodule init
git submodule update
mkdir build &amp;&amp; cd build
cmake -DCMAKE_INSTALL_PREFIX=/usr ..
make &amp;&amp; sudo make install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ul dir="auto">
<li><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意：</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您在 x86_64 发行版上进行安装，则可能需要传递</font></font><code>--libdir=/usr/lib64</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">到配置脚本。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">总而言之，如果您也有兴趣构建 Janus 文档，那么您还需要一些额外的工具：</font></font></p>
<ul dir="auto">
<li><a href="https://www.doxygen.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">多氧</font></font></a></li>
<li><a href="https://www.graphviz.org/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">图形可视化</font></font></a></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在费多拉上：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>yum install doxygen graphviz
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="yum install doxygen graphviz" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 Ubuntu/Debian 上：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>aptitude install doxygen graphviz
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="aptitude install doxygen graphviz" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-compile" class="anchor" aria-hidden="true" tabindex="-1" href="#compile"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编译</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装完所有依赖项后，获取代码：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>git clone https://github.com/meetecho/janus-gateway.git
cd janus-gateway
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/meetecho/janus-gateway.git
cd janus-gateway" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后只需使用：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>sh autogen.sh
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="sh autogen.sh" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">生成配置文件。</font><font style="vertical-align: inherit;">之后，像往常一样进行配置和编译，开始整个编译过程：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>./configure --prefix=/opt/janus
make
make install
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./configure --prefix=/opt/janus
make
make install" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">由于 Janus 需要核心及其模块的配置文件才能工作，因此您可能还需要安装要使用的默认配置文件，可以这样做：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>make configs
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="make configs" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请记住只执行一次，否则后续操作</font></font><code>make configs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">将覆盖您同时修改的任何配置文件。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您已经安装了上述库，但对数据通道、WebSockets、MQTT 和/或 RabbitMQ 等不感兴趣，您可以在配置时禁用它们：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>./configure --disable-websockets --disable-data-channels --disable-rabbitmq --disable-mqtt
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./configure --disable-websockets --disable-data-channels --disable-rabbitmq --disable-mqtt" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">几乎所有外部模块和许多功能都有配置标志，因此您可能需要发出 a</font></font><code>./configure --help</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">来挖掘可用选项。</font><font style="vertical-align: inherit;">在进行配置后，将始终显示将要构建的内容的摘要，使您可以仔细检查是否存在需要和不需要的内容。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果 Doxygen 和 graphviz 可用，该过程还可以为您构建文档。</font><font style="vertical-align: inherit;">默认情况下，编译过程不会尝试构建文档，因此如果您更喜欢构建它，请使用</font></font><code>--enable-docs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置选项：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>./configure --enable-docs
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./configure --enable-docs" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您还可以有选择地启用/禁用其他功能（例如，您不关心的特定插件，或者您是否想要构建录音后处理器）。</font><font style="vertical-align: inherit;">配置时使用 --help 选项以获取更多信息。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-building-on-freebsd" class="anchor" aria-hidden="true" tabindex="-1" href="#building-on-freebsd"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">基于 FreeBSD 构建</font></font></h3>
<ul dir="auto">
<li><em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></em><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：由于 #2051，流的 rtp_forward 只能流式传输到 IPv6，因此目前 FreeBSD 不支持该功能。</font></font></li>
</ul>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 FreeBSD 上构建时，您可以从 ports 或 package 安装依赖项，这里仅使用 pkg 方法。</font><font style="vertical-align: inherit;">您还需要使用</font></font><code>gmake</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代替</font></font><code>make</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，因为它是一个 GNU makefile。</font></font><code>./configure</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以在没有参数的情况下运行，因为默认前缀是</font></font><code>/usr/local</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您的默认前缀</font></font><code>LOCALBASE</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">请注意，已</font></font><code>configure.ac</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">编码为在 base 中使用 openssl。</font><font style="vertical-align: inherit;">如果您希望从 ports 或任何其他 ssl 使用 openssl，则必须进行</font></font><code>configure.ac</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">相应更改。</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>pkg install libsrtp2 libusrsctp jansson libnice libmicrohttpd libwebsockets curl opus sofia-sip libogg jansson libnice libconfig \
    speexdsp libtool gmake autoconf autoconf-wrapper glib
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pkg install libsrtp2 libusrsctp jansson libnice libmicrohttpd libwebsockets curl opus sofia-sip libogg jansson libnice libconfig \
    speexdsp libtool gmake autoconf autoconf-wrapper glib" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h3 tabindex="-1" dir="auto"><a id="user-content-building-on-macos" class="anchor" aria-hidden="true" tabindex="-1" href="#building-on-macos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在 MacOS 上构建</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">虽然上述大多数说明在 MacOS 上编译 Janus 时也适用，但在执行此操作时有几个方面需要强调。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">首先，您可以使用</font></font><code>brew</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装大部分依赖项：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>brew install jansson libnice openssl srtp libusrsctp libmicrohttpd \
	libwebsockets cmake rabbitmq-c sofia-sip opus libogg curl glib \
	speexdsp libconfig pkg-config autoconf automake libtool
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="brew install jansson libnice openssl srtp libusrsctp libmicrohttpd \
	libwebsockets cmake rabbitmq-c sofia-sip opus libogg curl glib \
	speexdsp libconfig pkg-config autoconf automake libtool" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">不过，对于 libwebsockets 而言，请确保安装的版本高于，否则您可能会遇到</font><a href="https://groups.google.com/forum/#!topic/meetecho-janus/HsFaEXBz4Cg" rel="nofollow"><font style="vertical-align: inherit;">本文</font></a></font><code>2.4.1</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中描述的问题</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">如果</font><font style="vertical-align: inherit;">没有提供更新版本，您必须手动安装该库。</font></font><a href="https://groups.google.com/forum/#!topic/meetecho-janus/HsFaEXBz4Cg" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><code>brew</code><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，在配置 Janus 时，您可能还需要提供自定义</font></font><code>prefix</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>PKG_CONFIG_PATH</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，例如：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>./configure --prefix=/usr/local/janus PKG_CONFIG_PATH=/usr/local/opt/openssl/lib/pkgconfig
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="./configure --prefix=/usr/local/janus PKG_CONFIG_PATH=/usr/local/opt/openssl/lib/pkgconfig" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其他一切的工作方式与 Linux 上完全相同。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-configure-and-start" class="anchor" aria-hidden="true" tabindex="-1" href="#configure-and-start"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置并启动</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要启动服务器，您可以使用</font></font><code>janus</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可执行文件。</font><font style="vertical-align: inherit;">您可以在配置文件中配置多项内容：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>&lt;installdir&gt;/etc/janus/janus.jcfg
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="<installdir>/etc/janus/janus.jcfg" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或在命令行上：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>&lt;installdir&gt;/bin/janus --help

Usage: janus [OPTIONS]...

-h, --help                    Print help and exit
-V, --version                 Print version and exit
-b, --daemon                  Launch Janus in background as a daemon
                              (default=off)
-p, --pid-file=path           Open the specified PID file when starting Janus
                              (default=none)
-N, --disable-stdout          Disable stdout based logging  (default=off)
-L, --log-file=path           Log to the specified file (default=stdout only)
-H  --cwd-path                Working directory for Janus daemon process
                              (default=/)
-i, --interface=ipaddress     Interface to use (will be the public IP)
-P, --plugins-folder=path     Plugins folder (default=./plugins)
-C, --config=filename         Configuration file to use
-F, --configs-folder=path     Configuration files folder (default=./conf)
-c, --cert-pem=filename       DTLS certificate
-k, --cert-key=filename       DTLS certificate key
-K, --cert-pwd=text           DTLS certificate key passphrase (if needed)
-S, --stun-server=address:port
                              STUN server(:port) to use, if needed (e.g.,
                              Janus behind NAT, default=none)
-1, --nat-1-1=ip              Public IP to put in all host candidates,
                              assuming a 1:1 NAT is in place (e.g., Amazon
                              EC2 instances, default=none)
-2, --keep-private-host       When nat-1-1 is used (e.g., Amazon EC2
                              instances), don't remove the private host,
                              but keep both to simulate STUN  (default=off)
-E, --ice-enforce-list=list   Comma-separated list of the only interfaces to
                              use for ICE gathering; partial strings are
                              supported (e.g., eth0 or eno1,wlan0,
                              default=none)
-X, --ice-ignore-list=list    Comma-separated list of interfaces or IP
                              addresses to ignore for ICE gathering;
                              partial strings are supported (e.g.,
                              vmnet8,192.168.0.1,10.0.0.1 or
                              vmnet,192.168., default=vmnet)
-6, --ipv6-candidates         Whether to enable IPv6 candidates or not
                              (experimental)  (default=off)
-O, --ipv6-link-local         Whether IPv6 link-local candidates should be
                              gathered as well  (default=off)
-l, --libnice-debug           Whether to enable libnice debugging or not
                              (default=off)
-f, --full-trickle            Do full-trickle instead of half-trickle
                              (default=off)
-I, --ice-lite                Whether to enable the ICE Lite mode or not
                              (default=off)
-T, --ice-tcp                 Whether to enable ICE-TCP or not (warning: only
                              works with ICE Lite)
                              (default=off)
-Q, --min-nack-queue=number   Minimum size of the NACK queue (in ms) per user
                              for retransmissions, no matter the RTT
-t, --no-media-timer=number   Time (in s) that should pass with no media
                              (audio or video) being received before Janus
                              notifies you about this
-W, --slowlink-threshold=number
                              Number of lost packets (per s) that should
                              trigger a 'slowlink' Janus API event to users
                              (default=0, feature disabled)
-r, --rtp-port-range=min-max  Port range to use for RTP/RTCP (only available
							  if the installed libnice supports it)
-B, --twcc-period=number      How often (in ms) to send TWCC feedback back to
                              senders, if negotiated (default=200ms)
-n, --server-name=name        Public name of this Janus instance
                              (default=MyJanusInstance)
-s, --session-timeout=number  Session timeout value, in seconds (default=60)
-m, --reclaim-session-timeout=number
                              Reclaim session timeout value, in seconds
                              (default=0)
-d, --debug-level=1-7         Debug/logging level (0=disable debugging,
                              7=maximum debug level; default=4)
-D, --debug-timestamps        Enable debug/logging timestamps  (default=off)
-o, --disable-colors          Disable color in the logging  (default=off)
-M, --debug-locks             Enable debugging of locks/mutexes (very
                              verbose!)  (default=off)
-a, --apisecret=randomstring  API secret all requests need to pass in order
                              to be accepted by Janus (useful when wrapping
                              Janus API requests in a server, none by
                              default)
-A, --token-auth              Enable token-based authentication for all
                              requests  (default=off)
-e, --event-handlers          Enable event handlers  (default=off)
-w, --no-webrtc-encryption    Disable WebRTC encryption, so no DTLS or SRTP
                              (only for debugging!)  (default=off)
</code></pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通过命令行传递的选项优先于配置文件中指定的选项。</font><font style="vertical-align: inherit;">要启动服务器，只需运行：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>&lt;installdir&gt;/bin/janus
</code></pre><div class="zeroclipboard-container">
   
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">这将启动服务器，并让它查看配置文件。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保您查看了所有配置文件，以便根据您的特定需求定制 Janus：每个配置文件都有记录，因此根据您的要求进行更改应该不难。</font><font style="vertical-align: inherit;">该存储库附带了一些默认值（假设您</font></font><code>make configs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在安装服务器后出现问题），这些默认值往往对通用部署有意义，并且还包括所有插件的一些示例配置（例如，要监听的 Web 服务器、要创建的会议室、流式安装点）在启动时可用等）。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要测试它是否正常工作，您可以使用文件夹中此包提供的演示：这些演示与</font><a href="https://janus.conf.meetecho.com/" rel="nofollow"><font style="vertical-align: inherit;">项目网站</font></a></font><code>html</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上在线提供的演示完全相同</font><font style="vertical-align: inherit;">。</font><font style="vertical-align: inherit;">只需将其包含的文件复制到网络服务器中，或使用用户空间网络服务器来提供文件夹中的文件</font><font style="vertical-align: inherit;">（例如，使用 php 或 python），然后</font><font style="vertical-align: inherit;">在 Chrome 或 Firefox 中打开页面。</font><font style="vertical-align: inherit;">将提供利用不同插件的演示页面列表。</font><font style="vertical-align: inherit;">如果您更改了任何与传输相关的默认配置，请记住在演示 JavaScript 文件中编辑传输/端口详细信息。</font><font style="vertical-align: inherit;">此外，演示引用了预先配置的插件资源，因此如果您添加一些新资源（例如，新的视频会议），您可能需要调整演示页面才能实际使用它们。</font></font><a href="https://janus.conf.meetecho.com/" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font><code>html</code><font style="vertical-align: inherit;"></font><code>index.html</code><font style="vertical-align: inherit;"></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-documentation" class="anchor" aria-hidden="true" tabindex="-1" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Janus 有完整的记录。</font></font><a href="https://janus.conf.meetecho.com/docs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在项目网站</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">上找到使用 Doxygen 自动生成的当前文档</font><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-help-us" class="anchor" aria-hidden="true" tabindex="-1" href="#help-us"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">帮助我们！</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">欢迎任何想法、反馈或（希望不是！）侮辱！</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><a href="https://github.com/meetecho"><font style="vertical-align: inherit;">由@meetecho</font></a><font style="vertical-align: inherit;">开发</font></font><a href="https://github.com/meetecho"><font style="vertical-align: inherit;"></font></a></p>
</article></div>
