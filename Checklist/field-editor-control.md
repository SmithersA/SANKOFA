# Dev / Design SharePoint HTML Editor Field Control (ECM)

Custom code cannot violate any of the following control settings
<table>
  <thead>
    <tr>
      <th scope="col">&#10003;</th>
      <th scope="col">Attribute</th>
      <th scope="col">Description</th>
      <th scope="col">XML</th>
     </tr>
  </thead>
  <tr>
    <td>&#9744;</td>
    <td>AllowExternalUrls</td>
    <td>Only URLs internal to the current site collection are allowed to be referenced in a link or an image.</td>
    <td>Example <code>AllowExternalUrls="false"</code></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowFonts</td>
    <td>Content may contain Font tags.</td>
    <td>Example <code>AllowFonts="true"</code></td>
  </tr>
  <tr>
    <!-- not dev-specific -->
    <td>&#9744;</td>
    <td>AllowHtmlSourceEditing</td>
    <td>HTML Editor can be switched into a mode that allows the HTML to be edited directly.</td>
    <td>Example <code>AllowReusableContent="false"</code></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowReusableContent</td>
    <td>Content may contain reusable content fragments stored in a centralized list.</td>
    <td>Example <code>AllowReusableContent="false"</code></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowHeadings</td>
    <td>Content may contain HTML heading tags (H1, H2, and so on).</td>
    <td>Example <code>AllowHeadings="false"</code></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowTextMarkup</td>
    <td>Content may contain bold, italic, and underlined text.</td>
    <td>Example <code>AllowTextMarkup="false"</code></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowImages</td>
    <td>Content may contain images.</td>
    <td>Example <code>AllowImages="false"</code></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowLists</td>
    <td>Content may contain numbered or bulleted lists.</td>
    <td>Example <code>AllowLists="false"</code></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowTables</td>
    <td>Content may contain table-related tags such as <pre><code><table>, <tr>, and <td></code></pre>.</td>
    <td>Example <code>AllowTables="false"</code></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowHyperlinks</td>
    <td>Content may contain links to other URLs.</td>
    <td>Example <code>AllowHyperlinks="false"</code></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowHtmlSourceEditing</td>
    <td>When set to false, the HTML editor is disabled from switching to HTML source editing mode.</td>
    <td>Example <code>AllowHTMLSourceEditing="false"</code></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowHyperlinks</td>
    <td>Gets or sets the constraint that allows hyperlinks to be added to the HTML. If this flag is set to false, <A>, <AREA>, and <MAP> tags are removed from the HTML. Default is true. This property also determines whether the editing user interface (UI) enables these operations.</td>
    <td>Example <code>AllowHyperlinks="false"</code></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowImageFormatting</td>
    <td>Gets or sets image formatting items. This restriction disables only menus and does not force the content to adhere to this restriction.</td>
    <td></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowImagePositioning</td>
    <td>Gets or sets the position of the image. This restriction disables only menus and does not force the content to adhere to this restriction.</td>
    <td></td>
  </tr>
  <tr>
    <td>&#9744;</td>
    <td>AllowImageStyles</td>
    <td>Gets or sets whether the Table Styles menu is enabled. This restriction disables only the menu and does not force the content to adhere to this restriction.</td>
    <td></td>
  </tr>
</table>

#### More information can be found [How to: Customize the SharePoint HTML Editor Field Control (ECM)](https://docs.microsoft.com/en-us/previous-versions/office/developer/sharepoint-2010/ms561507(v%3doffice.14))
