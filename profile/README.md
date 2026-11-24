# SVT — Scalable Vector Templates

A small specification for replaceable text, colors, and images in ordinary SVG.

SVT adds named inputs to SVG artwork. Applications discover those inputs and supply replacement
values; SVG retains responsibility for layout, fonts, styling, and rendering.

The [specification, .NET library, and CLI](https://github.com/svt-project/svt-dotnet) provide a shared
template contract and tools for inspecting inputs and binding replacement values. Conformance
fixtures and authoring examples help developers implement the contract and create reusable artwork.

Bathos is the founding maintainer. Contributions and implementation experience are welcome.
