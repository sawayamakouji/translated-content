---
title: 用户代理
slug: Glossary/User_agent
translation_of: Glossary/User_agent
---
<p>用户代理是代表一个人的计算机程序，例如，一个在 {{Glossary("World Wide Web", "Web")}} 上的 {{Glossary("Browser","浏览器")}}。</p>

<p>除了浏览器之外，用户代理可以是抓取网页的机器人、下载管理器或可以访问 Web 的其他应用程序。随着向服务器发送的每个请求，浏览器包含一个可表明身份的 <code>User-Agent</code>{{Glossary("HTTP")}} 的协议头，叫作用户代理（UA，User Agent）字符串。此字符串通常标识浏览器、及其版本号及其主机操作系统。</p>

<p>垃圾邮件机器人、下载管理器和一些浏览器通常会发送一个假 UA 字符串来宣称自己是不同的客户端。这被称为<em>用户代理欺骗</em>。</p>

<p>用户代理的字符串可以被 {{Glossary("JavaScript")}} 在客户端中使用 <code>navigator.userAgent</code> 获取。</p>

<p>典型的用户代理字符串如下所示： <code>"Mozilla/5.0 (X11; Ubuntu; Linux x86_64; rv:35.0) Gecko/20100101 Firefox/35.0"</code>. </p>

<h2 id="了解更多">了解更多</h2>

<h3 id="基础知识">基础知识</h3>

<ul>
 <li>在维基百科上的 <a href="https://en.wikipedia.org/wiki/User_agent">User agent</a></li>
</ul>

<h3 id="技术参考">技术参考</h3>

<ul>
 <li>在 RFC 2616 的 <a href="https://tools.ietf.org/html/rfc2616#section-14.43">User agent</a> 协议头</li>
</ul>