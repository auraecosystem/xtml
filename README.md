<br /><br /><br /><br />
<picture>
	<source srcset="https://brand.web4.dev/xtml/header/dark.svg" media="(prefers-color-scheme: dark)">
	<img src="https://brand.web4.dev/sdks/xtml/header/dark.svg">
</picture>
<br /><br /><br /><br />

```html
<!-- MyButton.html -->

<button onclick={e => OnClick(e)}>
  Clicks: {c} <!-- ⬅︎ HTML can "react" natively, no framework! 🚨 -->
</button>

<script lang="C#"> // ⬅︎ script tags in ANY language! 🚨
  void OnClick(Event e)
  {
    c++;
    Console.Log("Hello from C#");
  }
</script>
```
<br />

### Core Benefits

- 🙊 **Language Choice**<br />
  Web4 ends JavaScript’s monopoly on building dynamic user interfaces on the web.
- 👯‍♀️ **Multiplayer Reactivity**<br />
  When application state lives on the server, multiple connected clients can react to the same state change.
- 🙈 **Offline Reactivity**<br />
  Bidirectional protocols enable local-first synchronizations and apps continue to function even without a network connection.
- 🪶 **Zero-Cost Dependencies**<br />
  When applications execute remotely, binaries can grow to gigabytes in size without impacting user experience because they are never transferred to the browser.

> [!NOTE]
> XTML (eXtramural Templating Markup Language) is intended to be a hopeful W3C candidate recommendation for HTML6

## SDKs

> [!IMPORTANT]
> This repository contains no implementation code.  It is used as a common area for cross-language discussions, issues, benchmarks, documentation, and specifications.  For implementation code please visit one of the SDKs below.

<a href="https://github.com/web4foundation/web4-dotnet">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/dotnet/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/dotnet/light/love.svg" style="width: 300px">
    </picture>
</a>
&nbsp;&nbsp;&nbsp;(reference implementation)
<br /><br />
<a href="https://github.com/web4foundation/web4-java">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/java/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/java/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-go">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/go/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/go/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-kotlin">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/kotlin/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/kotlin/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-swift">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/swift/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/swift/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-javascript">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/javascript/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/javascript/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-ruby">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/ruby/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/ruby/light/love.svg" style="width: 300px">
    </picture>
</a>
<br /><br />
<a href="https://github.com/web4foundation/web4-python">
    <picture>
        <source srcset="https://brand.web4.dev/sdks/python/dark/love.svg" media="(prefers-color-scheme: dark)">
        <img src="https://brand.web4.dev/sdks/python/light/love.svg" style="width: 300px">
    </picture>
</a>