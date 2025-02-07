---
title: Max Width
skellyCSS: true
---

{{% anchor name="Max Container" level="2" %}}

The `max-container` adds a max-width to your content. The size is set to `1440px` and is added to the `:root` with the `--max-container` custom property.
You can change this size in your project by setting `--max-container` to a different value.

<section class="my-4">
  <h5 class="text--light text--size-md mb-3">Grid demo</h5>
  <div class="max-container">
    <div class="block-container pos-rel blocks p-2">
      <div class="block-container border border--color-lighter pos-abs pin-top pin-right pin-bottom pin-left" style="z-index: -1">
      <div class="block block-1 sg-column"></div>
      <div class="block block-1 sg-column"></div>
      <div class="block block-1 sg-column"></div>
      <div class="block block-1 sg-column"></div>
      <div class="block block-1 sg-column"></div>
      <div class="block block-1 sg-column"></div>
      <div class="block block-1 sg-column"></div>
      <div class="block block-1 sg-column"></div>
      <div class="block block-1 sg-column"></div>
      <div class="block block-1 sg-column"></div>
      <div class="block block-1 sg-column"></div>
      <div class="block block-1 sg-column"></div>
      </div>
      <div class="block tablet-up-6 laptop-up-4">
        <div class="card">
          <code>tablet-up-6</code>
          <code>laptop-up-4</code>
        </div>
      </div>
      <div class="block tablet-up-6 laptop-up-4">
        <div class="card">
          <code>tablet-up-6</code>
          <code>laptop-up-4</code>
        </div>
      </div>
      <div class="block tablet-up-6 laptop-up-4">
        <div class="card">
          <code>tablet-up-6</code>
          <code>laptop-up-4</code>
        </div>
      </div>
      <div class="block tablet-up-6 laptop-up-4">
        <div class="card">
          <code>tablet-up-6</code>
          <code>laptop-up-4</code>
        </div>
      </div>
    </div>
  </div>
</section>

{{< code-markup >}}
{{< highlight html >}}
<div class="max-container">
  <div class="block-container">
    <div class="block tablet-up-6 laptop-up-4"></div>
    <div class="block tablet-up-6 laptop-up-4"></div>
    <div class="block tablet-up-6 laptop-up-4"></div>
    <div class="block tablet-up-6 laptop-up-4"></div>
  </div>
</div>
{{< /highlight >}}
{{< /code-markup >}}