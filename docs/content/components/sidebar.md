+++
title = "Sidebar"
weight = 120
description = "Fixed sidebar layout with collapsible sections using details/summary semantic tags."
+++

Use `.sidebar` on an `<aside>` and `<main>` for the main content area.

<div class="sidebar-example">
{% demo() %}
```html
<aside class="sidebar">
  <h4>Dashboard</h4>
  <nav>
    <a href="#" aria-current="page">Home</a>
    <a href="#">Users</a>
    <details open>
      <summary>Settings</summary>
      <div>
        <a href="#">General</a>
        <a href="#">Security</a>
        <a href="#">Billing</a>
      </div>
    </details>
  </nav>
</aside>
<main>
  <h3>Main Content</h3>
  <p>This area shifts to make room for the sidebar.</p>
</main>
```
</div>

{% end %}
