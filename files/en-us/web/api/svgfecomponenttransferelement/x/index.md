---
title: "SVGFEComponentTransferElement: x property"
short-title: x
slug: Web/API/SVGFEComponentTransferElement/x
page-type: web-api-instance-property
browser-compat: api.SVGFEComponentTransferElement.x
---

{{APIRef("SVG")}}

The **`x`** read-only property of the {{domxref("SVGFEComponentTransferElement")}} interface describes the horizontal coordinate of the position of an SVG filter primitive as a {{domxref("SVGAnimatedLength")}}.

It reflects the {{SVGElement("feComponentTransfer")}} element's {{SVGAttr("x")}} filter primitive attribute value. The attribute is a [`<length>`](/en-US/docs/Web/SVG/Guides/Content_type#length) or [`<percentage>`](/en-US/docs/Web/SVG/Guides/Content_type#percentage). The `<coordinate>` is a length in the user coordinate system that is the given distance from the origin of the user coordinate system along the x-axis. If the `x` attribute is a percent value, the property value is relative to the width of the filter region in user coordinate system units. The default value is `0`.

## Value

An {{domxref("SVGAnimatedLength")}}.

## Example

```js
const feComponentTransfer = document.querySelector("feComponentTransfer");
const leftPosition = feComponentTransfer.x;
console.log(leftPosition.baseVal.value); // the `x` value
```

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}

## See also

- {{domxref("SVGFEComponentTransferElement.y")}}
- {{SVGElement("feFuncR")}}, {{SVGElement("feFuncG")}}, {{SVGElement("feFuncB")}}, {{SVGElement("feFuncA")}}
