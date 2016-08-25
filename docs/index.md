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
      <h3>A Simple Component</h3>
      <p>
        React components implement a `render()` method that takes input data and
        returns what to display. This example uses an XML-like syntax called
        JSX. Input data that is passed into the component can be accessed by
        `render()` via `this.props`.
      </p>
      <p>
        <strong>JSX is optional and not required to use React.</strong> Try
        clicking on "Compiled JS" to see the raw JavaScript code produced by
        the JSX compiler.
      </p>
      <div id="helloExample"></div>
    </div>
    <div class="example">
      <h3>A Stateful Component</h3>
      <p>
        In addition to taking input data (accessed via `this.props`), a
        component can maintain internal state data (accessed via `this.state`).
        When a component's state data changes, the rendered markup will be
        updated by re-invoking `render()`.
      </p>
      <div id="timerExample"></div>
    </div>
    <div class="example">
      <h3>An Application</h3>
      <p>
        Using `props` and `state`, we can put together a small Todo application.
        This example uses `state` to track the current list of items as well as
        the text that the user has entered. Although event handlers appear to be
        rendered inline, they will be collected and implemented using event
        delegation.
      </p>
      <div id="todoExample"></div>
    </div>
    <div class="example">
      <h3>A Component Using External Plugins</h3>
      <p>
        React is flexible and provides hooks that allow you to interface with
        other libraries and frameworks. This example uses **remarkable**, an
        external Markdown library, to convert the textarea's value in real time.
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
    <a href="docs/getting-started.html" class="button">Get Started</a>
    <a href="downloads.html" class="button">Download React v{{site.react_version}}</a>
  </div>
</section>
