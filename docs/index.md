---
layout: page
title: 用于构建用户界面的JavaScript库
id: home
---

<section class="light home-section">
  <div class="marketing-row">
    <div class="marketing-col">
      <h3>声明式</h3>
      <p>使用React轻松地创建用户界面。为每个状态设计不同的视图，当数据更新时React将高效地重绘需要更新的组件。</p>
      <p>声明式的视图使代码更加容易预见以及便于调试。</p>
    </div>
    <div class="marketing-col">
      <h3>基于组件</h3>
      <p>使用封装自有状态的组件来构成复杂的用户界面。</p>
      <p>组件不需要模板也不再需要操作DOM,而是直接通过JavaScript来完成数据通信及状态管理。</p>
    </div>
    <div class="marketing-col">
      <h3>一次学习，到处编写</h3>
      <p>React并没有假设过你的其余技术栈, 它可以仅仅作为一个小特征在已有项目中使用。</p>
      <p>React可以由服务端Node.js来渲染，也可以使用<a href="https://facebook.github.io/react-native/">React Native</a>来创建移动应用。</p>
    </div>
  </div>
</section>
<hr class="home-divider" />
<section class="home-section">
  <div id="examples">
    <div class="example">
      <h3>一个简单的组件</h3>
      <p>
      React 组件通过一个render()方法，接受输入的参数并返回展示的对象。以下这个例子使用了 JSX，它类似于XML的语法。输入的参数通过render()传入组件后，将存储在this.props。
      </p>
      <p>
        <strong>JSX 是可选的，并不强制要求使用。</strong>
        点击 "Compiled JS" 可以看到 JSX 编译之后的 JavaScript 代码
      </p>
      <div id="helloExample"></div>
    </div>
    <div class="example">
      <h3>一个有状态的组件</h3>
      <p>
        除了接受输入数据(通过 `this.props`), 组件也可以保持内部状态数据(通过 `this.state`)。
        当一个组件的状态数据的变化，展现的标记将被重新调用 `render()` 更新。
      </p>
      <div id="timerExample"></div>
    </div>
    <div class="example">
      <h3>一个应用程序</h3>
      <p>
        使用 `props` 和 `state`, , 我们可以组合构建一个小型的 Todo 程序。
        下面例子使用 `state` 去监测当前列表的项以及用户已经输入的文本。
        尽管事件绑定似乎是以内联的方式，但他们将被收集起来并以事件代理的方式实现。
      </p>
      <div id="todoExample"></div>
    </div>
    <div class="example">
      <h3>一个使用外部插件的组件</h3>
      <p>
        React 是灵活的，并且提供方法允许你跟其他库和框架对接。
        下面例子展现了一个案例，使用外部库 Markdown 实时转化 textarea 的值。
      </p>
      <div id="markdownExample"></div>
    </div>
  </div>
  <script src="/react/js/remarkable.min.js"></script>
  <script src="/react/js/examples/hello.js"></script>
  <script src="/react/js/examples/timer.js"></script>
  <script src="/react/js/examples/todo.js"></script>
  <script src="/react/js/examples/markdown.js"></script>
</section>
<hr class="home-divider" />
<section class="home-bottom-section">
  <div class="buttons-unit">
    <a href="docs/getting-started.html" class="button">开始教程</a>
    <a href="downloads.html" class="button">下载 React v{{site.react_version}}</a>
  </div>
</section>
