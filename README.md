# 🚀 FootNotes.JS v1.0

Lightweight (4kb) script on pure JS, what creates footnotes in your article, and also list with all of this notes.

Very simple to use. Working example here https://serverwind.github.io/FootNotes.JS/dist , click on [1], [2] etc.

<b>DEMO</b>: https://serverwind.github.io/dist

# Install

1. Add https://serverwind.github.io/src/styles/style.css
2. Add https://serverwind.github.io/src/footnotes.js

# Use

In place, where you want to add footnote insert this code:

<pre>
  &lt;span class="tooltip-link"&gt;&lt;sup&gt;&lt;/sup&gt;&lt;/span&gt;
  &lt;span class="tooltip-hide toolTip increment"&gt;&lt;b&gt;&lt;/b&gt; &lt;a href=""&gt; TEXT &lt;/a&gt;
  &lt;span class="closeTooltip"&gt;x&lt;/span&gt;&lt;/span&gt;
</pre>

Replace TEXT with your own text.

If you need a list of all your footnotes in the end of your article - add this:

<pre>
    &lt;div align="right" style="margin-bottom: 25px;"&gt;
      &lt;span class="spoiler-name"&gt;&lt;i style="color: white;font-size: 16px;" id="spoiler-arrow" class='fa fa-chevron-down'&gt;&lt;/i&gt; Сноски&lt;/span&gt;
    &lt;/div&gt;
    &lt;ol id="spoiler" class="spoilerHidden"&gt;
      &lt;li id="note1"&gt;&lt;/li&gt;
      &lt;li id="note2"&gt;&lt;/li&gt;
      &lt;li id="note3"&gt;&lt;/li&gt;
      &lt;li id="note4"&gt;&lt;/li&gt;
      &lt;li id="note5"&gt;&lt;/li&gt;
      &lt;li id="note6"&gt;&lt;/li&gt;
      &lt;li id="note7"&gt;&lt;/li&gt;
      &lt;li id="note8"&gt;&lt;/li&gt;
      &lt;li id="note9"&gt;&lt;/li&gt;
      &lt;li id="note10"&gt;&lt;/li&gt;
    &lt;/ol&gt;
</pre>
