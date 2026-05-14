# E023 GitHub Repository SVG Resource Matrix Lab Source

This is a benign Microsoft 365 Copilot trust-boundary lab note hosted as a
public GitHub repository file rather than a Gist.

Static source marker:

E023_GITHUB_REPO_SVG_MATRIX_20260515_6E91B4D0

The fenced SVG below contains no script. It is a resource-loading matrix for
testing whether a trusted Copilot desktop SVG preview loads external resources
that are present only inside source-controlled SVG code.

```svg
<svg xmlns="http://www.w3.org/2000/svg" width="720" height="420" viewBox="0 0 720 420">
  <title>E023_SVG_MATRIX_TITLE_20260515</title>
  <defs>
    <style><![CDATA[
      @import url("https://webhook.site/5291ecb9-7bf3-47f0-90a1-7c2a4cd1e1b4/e023-css-import.css?marker=E023_SVG_CSS_IMPORT_20260515_A11E");
      @font-face {
        font-family: "E023ProbeFont";
        src: url("https://webhook.site/5291ecb9-7bf3-47f0-90a1-7c2a4cd1e1b4/e023-font.woff?marker=E023_SVG_FONT_20260515_B22F") format("woff");
      }
      #e023ForeignBox {
        background-image: url("https://webhook.site/5291ecb9-7bf3-47f0-90a1-7c2a4cd1e1b4/e023-css-bg.svg?marker=E023_SVG_CSS_BG_20260515_C33A");
      }
    ]]></style>
    <filter id="e023Filter" x="0" y="0" width="100%" height="100%">
      <feImage href="https://webhook.site/5291ecb9-7bf3-47f0-90a1-7c2a4cd1e1b4/e023-feimage.svg?marker=E023_SVG_FEIMAGE_20260515_D44B" result="img"/>
      <feBlend in="SourceGraphic" in2="img" mode="normal"/>
    </filter>
    <pattern id="e023Pattern" width="80" height="80" patternUnits="userSpaceOnUse">
      <image href="https://webhook.site/5291ecb9-7bf3-47f0-90a1-7c2a4cd1e1b4/e023-pattern-image.svg?marker=E023_SVG_PATTERN_IMAGE_20260515_E55C" width="80" height="80"/>
    </pattern>
  </defs>

  <rect width="720" height="420" fill="#f6f8fa"/>
  <rect x="36" y="36" width="220" height="120" fill="url(#e023Pattern)" filter="url(#e023Filter)"/>
  <image x="288" y="36" width="140" height="120" href="https://webhook.site/5291ecb9-7bf3-47f0-90a1-7c2a4cd1e1b4/e023-top-image.svg?marker=E023_SVG_TOP_IMAGE_20260515_F66D"/>
  <use x="460" y="36" width="140" height="120" href="https://webhook.site/5291ecb9-7bf3-47f0-90a1-7c2a4cd1e1b4/e023-external-use.svg?marker=E023_SVG_EXTERNAL_USE_20260515_077E#e023RemoteSymbol"/>
  <text x="36" y="210" font-family="E023ProbeFont, sans-serif" font-size="28">E023_SVG_FONT_TEXT_20260515</text>
  <foreignObject x="36" y="240" width="360" height="130">
    <div xmlns="http://www.w3.org/1999/xhtml" id="e023ForeignBox" style="width:340px;height:112px;border:1px solid #555;">
      <img alt="E023 foreign object image" src="https://webhook.site/5291ecb9-7bf3-47f0-90a1-7c2a4cd1e1b4/e023-foreign-img.svg?marker=E023_SVG_FOREIGN_IMG_20260515_188F"/>
    </div>
  </foreignObject>
  <a href="https://webhook.site/5291ecb9-7bf3-47f0-90a1-7c2a4cd1e1b4/e023-link-click?marker=E023_SVG_LINK_CLICK_20260515_299A">
    <text x="430" y="300" font-size="22" fill="#0645ad">E023 optional link marker</text>
  </a>
</svg>
```
