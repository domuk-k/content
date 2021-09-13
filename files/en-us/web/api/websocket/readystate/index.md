---
title: WebSocket.readyState
slug: Web/API/WebSocket/readyState
tags:
- API
- Property
- Reference
- Web API
- WebSocket
browser-compat: api.WebSocket.readyState
---
<p>{{APIRef("Web Sockets API")}}</p>

<p>The <strong><code>WebSocket.readyState</code></strong> read-only property returns the
  current state of the {{domxref("WebSocket")}} connection.</p>

<h2 id="Value">Value</h2>

<p>One of the following <code>unsigned short</code> values:</p>

<table class="standard-table">
  <thead>
    <tr>
      <th>Value</th>
      <th>State</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>0</code></td>
      <td><code>CONNECTING</code></td>
      <td>Socket has been created. The connection is not yet open.</td>
    </tr>
    <tr>
      <td><code>1</code></td>
      <td><code>OPEN</code></td>
      <td>The connection is open and ready to communicate.</td>
    </tr>
    <tr>
      <td><code>2</code></td>
      <td><code>CLOSING</code></td>
      <td>The connection is in the process of closing.</td>
    </tr>
    <tr>
      <td><code>3</code></td>
      <td><code>CLOSED</code></td>
      <td>The connection is closed or couldn't be opened.</td>
    </tr>
  </tbody>
</table>

<h2 id="Specifications">Specifications</h2>

{{Specifications}}

<h2 id="Browser_compatibility">Browser compatibility</h2>

<p>{{Compat}}</p>