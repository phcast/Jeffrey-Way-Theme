# Jeffrey Way's Theme
Jeffrey Way's theme on Laracasts. Example [here](https://laracasts.com/series/whats-new-in-laravel-5-1/episodes/2).

If you have SyncedSidebarBg enabled in Package Control, please disable that!

<img src="http://i.imgur.com/oUA3alz.png" />

## Install Material Theme
+ Package Control: Install Package --> Material Theme.
+ Install the Facebook Theme: https://github.com/mbixby/facebook-color-scheme

## Configure

Edit `Preferences --> Settings - User` to the following:

````
{
	"auto_complete": true,
	"auto_indent": true,
	"bold_folder_labels": true,
	"caret_style": "phase",
	"color_scheme": "Packages/facebook-color-scheme-master/Facebook.tmTheme",
	"default_encoding": "UTF-8",
	"detect_indentation": true,
	"draw_indent_guides": true,
	"draw_white_space": "none",
	"enable_tab_scrolling": false,
	"font_face": "Input",
	"font_size": 13,
	"gutter": true,
	"highlight_line": true,
	"ignored_packages":
	[
		"Vintage"
	],
	"indent_subsequent_lines": true,
	"line_numbers": false,
	"line_padding_bottom": 2,
	"line_padding_top": 2,
	"margin": 4,
	"overlay_scroll_bars": "enabled",
	"preview_on_click": false,
	"smart_indent": true,
	"tab_completion": true,
	"tab_size": 4,
	"theme": "Material-Theme-Darker.sublime-theme",
	"trim_automatic_white_space": true,
	"word_wrap": true,
	"wrap_width": 0
}
````

Edit `Material-Theme-Darker.sublime-theme`

````
[
    {
        "class": "tree_row",
        "layer0.texture": "Theme - Default/row_highlight_dark.png",
        "layer0.tint": [
            87,
            93,
            107
        ]
    },
    {
        "class": "sidebar_container",
        "layer0.opacity": 1.0,
        "color": [
            37,
            43,
            57
        ]
    },
    {
        "class": "sidebar_tree",
        "dark_content": true,
        "layer0.opacity": 1,
        "color": [
            37,
            43,
            57
        ]
    },
    {
        "class": "sidebar_label",
        "layer0.tint": [
            87,
            93,
            107
        ]
    },
    {
        "class": "sidebar_heading",
        "shadow_offset": [
            0,
            0
        ]
    },
    {
        "class": "disclosure_button_control",
        "layer0.tint": [
            87,
            93,
            107
        ],
        "layer1.tint": [
            87,
            93,
            107
        ]
    },
    {
        "class": "sidebar_heading",
        "layer0.tint": [
            127,
            133,
            147
        ]
    }
]
````

Edit `Packages --> facebook-color-scheme-master --> Facebook.tmTheme`

````
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
<plist version="1.0">
<dict>
  <key>author</key>
  <string>Michael Obrocnik (mbixby)</string>
  <key>comment</key>
  <string>
    See docs and updates at https://github.com/mbixby/github-color-scheme
  </string>
  <key>name</key>
  <string>Facebook</string>
  <key>settings</key>
  <array>
    <dict>
      <key>comment</key>
      <string>
        252B39 - Fb background
      </string>
      <key>settings</key>
      <dict>
        <key>background</key>
        <string>#263238</string>
        <key>caret</key>
        <string>#979E86</string>
        <key>foreground</key>
        <string>#C3CEE3</string>
        <key>invisibles</key>
        <string>#FF0000</string>
        <key>lineHighlight</key>
        <string>#2F374D</string>
        <key>selection</key>
        <string>#1a1f29</string>
        <key>selectionBorder</key>
        <string>#1a1f29</string>
      </dict>
    </dict>
    <dict>
      <key>comment</key>
      <string>.syntax .c, .syntax .c[ml]</string>
      <key>name</key>
      <string>Comment</string>
      <key>scope</key>
      <string>comment</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#7081BE</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Comment.Preproc</string>
      <key>scope</key>
      <string>comment.block.preprocessor</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.syntax .cp</string>
        <key>fontStyle</key>
        <string>regular</string>
        <key>foreground</key>
        <string>#7081BE</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Comment.Special</string>
      <key>scope</key>
      <string>comment.documentation, comment.block.documentation</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.syntax .cs</string>
        <key>fontStyle</key>
        <string>regular</string>
        <key>foreground</key>
        <string>#7081BE</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Error</string>
      <key>scope</key>
      <string>invalid.illegal</string>
      <key>settings</key>
      <dict>
        <key>background</key>
        <string>#722C40</string>
        <key>comment</key>
        <string>.syntax .err</string>
        <key>foreground</key>
        <string>#E889B5</string>
      </dict>
    </dict>
    <dict>
      <key>comment</key>
      <string>.syntax .k, .syntax .k[dpr]</string>
      <key>name</key>
      <string>Keyword</string>
      <key>scope</key>
      <string>keyword, storage</string>
      <key>settings</key>
      <dict>
        <key>fontStyle</key>
        <string>bold</string>
        <key>foreground</key>
        <string>#FFFFFF</string>
      </dict>
    </dict>
    <dict>
      <key>comment</key>
      <string>.syntax .o, .syntax .ow</string>
      <key>name</key>
      <string>Operator</string>
      <key>scope</key>
      <string>keyword.operator</string>
      <key>settings</key>
      <dict>
        <key>fontStyle</key>
        <string>bold</string>
        <key>foreground</key>
        <string>#E4EAF0</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Keyword.Constant</string>
      <key>scope</key>
      <string>constant.language, support.constant</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .kc</string>
        <key>fontStyle</key>
        <string>bold</string>
        <key>foreground</key>
        <string>#E4EAF0</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Keyword.Type</string>
      <key>scope</key>
      <string>storage.type, support.type</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .kt</string>
        <key>fontStyle</key>
        <string>italic</string>
        <key>foreground</key>
        <string>#d3afc5</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Name.Attribute</string>
      <key>scope</key>
      <string>entity.other.attribute-name</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .na</string>
        <key>foreground</key>
        <string>#90D6CD</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Name.Builtin</string>
      <key>scope</key>
      <string>variable.other</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .nb</string>
        <key>foreground</key>
        <string>#8DC4F0</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Name.Builtin.Pseudo</string>
      <key>scope</key>
      <string>variable.language</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .bp</string>
        <key>foreground</key>
        <string>#B3B2A2</string>
      </dict>
    </dict>
    <dict>
      <key>comment</key>
      <string>TODO: support.class is styled as Name.Constant on GitHub.</string>
      <key>name</key>
      <string>Name.Class</string>
      <key>scope</key>
      <string>entity.name.type, entity.other.inherited-class, support.class</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .nc</string>
        <!-- <key>fontStyle</key> -->
        <!-- <string>bold</string> -->
        <key>foreground</key>
        <string>#E3C78A</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Name.Constant</string>
      <key>scope</key>
      <string>variable.other.constant</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .no</string>
        <key>foreground</key>
        <string>#18C9C9</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Name.Entity</string>
      <key>scope</key>
      <string>constant.character.entity</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .ni</string>
        <key>foreground</key>
        <string>#d67c9b</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Name.Exception</string>
      <key>scope</key>
      <string>entity.name.exception</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .ne</string>
        <key>foreground</key>
        <string>#d67c9b</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Name.Function</string>
      <key>scope</key>
      <string>entity.name.function, support.function, keyword.other.name-of-parameter</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .nf</string>
        <key>foreground</key>
        <string>#8be9ee</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Name.Namespace</string>
      <key>scope</key>
      <string>entity.name.section</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .nn</string>
        <key>foreground</key>
        <string>#dabc83</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Name.Tag</string>
      <key>scope</key>
      <string>entity.name.tag</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .nt</string>
        <key>foreground</key>
        <string>#8db3ff</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Punctuation.Tag</string>
      <key>scope</key>
      <string>punctuation.definition.tag</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .nt</string>
        <key>foreground</key>
        <string>#5768b0</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Name.Variable</string>
      <key>scope</key>
      <string>variable.parameter, support.variable</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .nv, .style .v[cgi]</string>
        <key>fontStyle</key>
        <string>italic</string>
        <key>foreground</key>
        <string>#18C9C9</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Literal.Number</string>
      <key>scope</key>
      <string>constant.numeric, constant.other</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .m, .style .m[fhio], .style .il</string>
        <key>foreground</key>
        <string>#18C9C9</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Literal.String</string>
      <key>scope</key>
      <string>string - string source, constant.character</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .s[bcd2ehixl]</string>
        <key>foreground</key>
        <string>#D5D5CA</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Literal.String.Regex</string>
      <key>scope</key>
      <string>string.regexp</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .sr</string>
        <key>foreground</key>
        <string>#18C9C9</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Literal.String.Symbol</string>
      <key>scope</key>
      <string>constant.other.symbol</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.style .ss</string>
        <key>foreground</key>
        <string>#ABD683</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic.Deleted</string>
      <key>scope</key>
      <string>markup.deleted</string>
      <key>settings</key>
      <dict>
        <key>background</key>
        <string>#3B2A39</string>
        <key>foreground</key>
        <string>#CDBBD6</string>
        <key>comment</key>
        <string>.syntax .gd</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic.Emph</string>
      <key>scope</key>
      <string>markup.italic</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.syntax .ge</string>
        <key>fontStyle</key>
        <string>italic</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic.Error</string>
      <key>scope</key>
      <string>markup.error</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.syntax .gr</string>
        <key>foreground</key>
        <string>#DF7788</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic.Heading</string>
      <key>scope</key>
      <string>markup.heading.1</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.syntax .gh</string>
        <key>foreground</key>
        <string>#CC7093</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic.Inserted</string>
      <key>scope</key>
      <string>markup.inserted</string>
      <key>settings</key>
      <dict>
        <key>background</key>
        <string>#2C344D</string>
        <key>comment</key>
        <string>.syntax .gi</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic.Output</string>
      <key>scope</key>
      <string>markup.output, markup.raw</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.syntax .go</string>
        <key>foreground</key>
        <string>#89CEDD</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic.Prompt</string>
      <key>scope</key>
      <string>markup.prompt</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.syntax .gp</string>
        <key>foreground</key>
        <string>#555555</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic.Strong</string>
      <key>scope</key>
      <string>markup.bold</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.syntax .gs</string>
        <key>fontStyle</key>
        <string>bold</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic.Subheading</string>
      <key>scope</key>
      <string>markup.heading</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.syntax .gu</string>
        <key>foreground</key>
        <string>#C97595</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic.Traceback</string>
      <key>scope</key>
      <string>markup.traceback</string>
      <key>settings</key>
      <dict>
        <key>comment</key>
        <string>.syntax .gt</string>
        <key>foreground</key>
        <string>#89CEDD</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic.Underline</string>
      <key>scope</key>
      <string>markup.underline</string>
      <key>settings</key>
      <dict>
        <key>fontStyle</key>
        <string>underline</string>
      </dict>
    </dict>



    <!-- Diffs -->

    <dict>
      <key>name</key>
      <string>Extra: Diff Range</string>
      <key>scope</key>
      <string>meta.diff.range, meta.diff.index, meta.separator</string>
      <key>settings</key>
      <dict>
        <!-- <key>background</key> -->
        <!-- <string>#EAF2F5</string> -->
        <key>comment</key>
        <string>.syntax .gc</string>
        <key>foreground</key>
        <string>#8DA6EA</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Extra: Diff From</string>
      <key>scope</key>
      <string>meta.diff.header.from-file</string>
      <key>settings</key>
      <dict>
        <key>background</key>
        <string>#722C40</string>
        <key>foreground</key>
        <string>#E889B5</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Extra: Diff To</string>
      <key>scope</key>
      <string>meta.diff.header.to-file</string>
      <key>settings</key>
      <dict>
        <key>background</key>
        <string>#628F50</string>
        <key>foreground</key>
        <string>#B0F7C3</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Extra: Link</string>
      <key>scope</key>
      <string>meta.link</string>
      <key>settings</key>
      <dict>
        <key>fontStyle</key>
        <string></string>
        <key>foreground</key>
        <string>#92A3E0</string>
      </dict>
    </dict>


    
    <!-- CSS and SASS -->

    <dict>
      <key>name</key>
      <string>Property names</string>
      <key>scope</key>
      <string>support.type.property-name</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#C3CEE3</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Property values</string>
      <key>scope</key>
      <string>support.constant.property-value, support.constant.font-name</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#C3CEE3</string>
        <key>fontStyle</key>
        <string></string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Units</string>
      <key>scope</key>
      <string>constant.other.unit, keyword.other.unit</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#18C9C9</string>
        <key>fontStyle</key>
        <string></string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Selectors</string>
      <!-- entity.other.attribute-name.class, entity.other.attribute-name.id -->
      <key>scope</key>
      <string>keyword.control.untitled, entity.other.attribute-name</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#96fbff</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Mixin definitions, imports etc.</string>
      <key>scope</key>
      <string>keyword.control.at-rule</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#E3C78A</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Mixins as properties</string>
      <key>scope</key>
      <string>keyword.control.mixin-shorthand</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#dde9ff</string>
        <key>fontStyle</key>
        <string></string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Url</string>
      <key>scope</key>
      <string>variable.parameter.url.sass</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#C3CEE3</string>
        <key>fontStyle</key>
        <string>normal</string>
      </dict>
    </dict>

  

  
    <!-- Miscellaneous -->

    <dict>
      <key>name</key>
      <string>Parentheses (tone them down)</string>
      <key>scope</key>
      <string>meta.brace.round.coffee</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#798194</string>
      </dict>
    </dict>




    <!-- Markdown (or any structured text) -->
  
    <dict>
      <key>name</key>
      <string>Generic: Heading (single line)</string>
      <key>comment</key>
      <string>
        \s*(#*)$\n? defines the following:
        punctuation.definition.heading.markdown
        entity.name.section.markdown
        markup.heading.markdown
      </string>
      <key>scope</key>
      <string>entity.name.section.markdown</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#71baff</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic: Heading punctuation</string>
      <key>scope</key>
      <string>punctuation.definition.heading</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#4a72ae</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic: Heading (multi line)</string>
      <key>scope</key>
      <string>markup.heading.1 punctuation.definition.heading</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#ff0000</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic: List item dot</string>
      <key>scope</key>
      <string>punctuation.definition.list_item</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#646877</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic: Link title</string>
      <key>scope</key>
      <string>string.other.link.title</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#C3CEE3</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic: Inline raw text (e.g. code)</string>
      <key>scope</key>
      <string>string.raw.inline.markdown</string>
      <key>settings</key>
      <dict>
        <key>background</key>
        <string>#1f2431</string>
        <key>foreground</key>
        <string>#cec8d7</string>
      </dict>
    </dict>
    <dict>
      <key>name</key>
      <string>Generic: Inline code backticks</string>
      <key>scope</key>
      <string>punctuation.definition.raw.markdown</string>
      <key>settings</key>
      <dict>
        <key>foreground</key>
        <string>#5d606e</string>
      </dict>
    </dict>


  </array>
  <key>uuid</key>
  <string>FDD6F02A-74F7-4B6C-97F1-857D792EC90E</string>
</dict>
</plist>
````

## Credits
+ [mbixby](https://github.com/mbixby/facebook-color-scheme) - Facebook Theme.
+ [equinosocia](http://equinusocio.github.io/material-theme/) - Material Theme.
+ [Jeffrey Way](https://github.com/JeffreyWay).

### Important
Please contact me if I have forgotten to mention a source.
