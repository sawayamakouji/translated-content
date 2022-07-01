---
title: HTTP/2
slug: Glossary/HTTP_2
tags:
  - HTTP
  - HTTP2
translation_of: Glossary/HTTP_2
---
<p><strong>HTTP/2</strong> 是 <a href="/zh-CN/docs/Web/HTTP/Basics_of_HTTP">HTTP 网络协议</a>的一个重要版本。 HTTP / 2 的主要目标是通过启用完整的请求和响应多路复用来减少 {{glossary("延迟")}}，通过有效压缩 HTTP 标头字段来最小化协议开销，并增加对请求优先级和服务器推送的支持。</p>

<p>HTTP/2 不会修改 HTTP 协议的语义。HTTP 1.1 中的所有核心概念（例如 HTTP 方法，状态码，URI 和 headers）都得以保留。而是修改了 HTTP/2 数据在客户端和服务器之间的格式（帧）和传输方式，这两者都管理整个过程，并在新的框架层内隐藏了应用程序的复杂性。所以，所有现有的应用程序都可以不经修改地交付。</p>

<h2 id="参见">参见</h2>

<ul>
 <li>常识
  <ul>
   <li><a href="/zh-CN/docs/Web/HTTP">HTTP on MDN</a></li>
   <li>{{interwiki("wikipedia", "HTTP/2", "HTTP/2")}} on Wikipedia</li>
  </ul>
 </li>
 <li><a href="/zh-CN/docs/Glossary">词汇表</a>
  <ul>
   <li>{{glossary("HTTP")}}</li>
   <li>{{glossary("Latency")}}</li>
  </ul>
 </li>
</ul>