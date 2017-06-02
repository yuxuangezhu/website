---
layout: default
lead: WebAssembly/<i>wasm</i> WebAssembly 或者 wasm 是一个可移植、体积小、加载快并且兼容 Web 的全新格式
---

<div class="flash flash-warn">
  WebAssembly 是由主流浏览器厂商组成的 <a href="https://www.w3.org/community/webassembly/">W3C 社区团体</a> 制定的一个新的规范。
</div>
<div class="row">
  <div class="bubble col-xs-12 col-md-6">
    <h3>高效</h3>
    <p>WebAssembly 有一套完整的<a href="/docs/semantics/">语义</a>，实际上 wasm 是体积小且加载快的<a href="/docs/binary-encoding/">二进制格式</a>， 其目标就是充分发挥<a href="/docs/portability/#assumptions-for-efficient-execution">硬件</a>能力以达到原生执行效率</p>
  </div>

  <div class="bubble col-xs-12 col-md-6">
    <h3>安全</h3>
    <p>
    WebAssembly 运行在一个沙箱化的<a href="/docs/semantics/#linear-memory">执行环境</a>中，甚至可以在现有的 JavaScript 虚拟机中实现。在<a href="/docs/web/">web环境中</a>，WebAssembly将会严格遵守同源策略以及浏览器安全策略。
    </p>
  </div>

</div>
<div class="row">
  <div class="bubble col-xs-12 col-md-6">
    <h3>开放</h3>
    <p>WebAssembly 设计了一个非常规整的<a href="/docs/text-format/">文本格式</a>用来、调试、测试、实验、优化、学习、教学或者编写程序。可以以这种文本格式在web页面上<a href="/docs/faq/#will-webassembly-support-view-source-on-the-web">查看wasm模块的源码</a>。</p>
  </div>
  <div class="bubble col-xs-12 col-md-6">
    <h3>标准</h3>
    <p>
      WebAssembly 在 <a href="/docs/web/">web</a> 中被设计成无版本、特性可测试、向后兼容的。WebAssembly 可以被 JavaScript 调用，进入 JavaScript 上下文，也可以像 Web API 一样调用浏览器的功能。当然，WebAssembly 不仅可以运行在浏览器上，也可以运行在<a href="/docs/non-web/">非web</a>环境下。
    </p>
  </div>
</div>