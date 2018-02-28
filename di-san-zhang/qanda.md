#FAQs

<br />

<a id="installation-failed"></a>

#### I am facing issues while setting up.

<b>Solution:</b>

Please verify the system requirements mentioned in [installation](/docs/GetStarted.md) procedure.

<br />

<hr>

<br />

<a id="watchman-error"></a>

#### I am getting a watchman error when I run npm install.

<b>Solution:</b>

<ul>

<li> Update <code>watchman</code> to the latest version. </li>

<li> Run <code>npm</code> install again. </li>

</ul>

<br />

<hr>

<br />

<a id="unrecognized-font"></a>

#### Unrecognized font family ionicons

<div class="panel-body">

When I run it in Xcode I'm getting a "Build Failed" error, with message:

&lt;ul&gt;

    &lt;li&gt;

        ld: library not found for -lRNVectorIcons

    &lt;/li&gt;

    &lt;li&gt;

        clang: error: linker command failed with exit code 1 \(use -v to see invocation\)

    &lt;/li&gt;

&lt;/ul&gt;
</div>

<div class="panel-footer">

&lt;b&gt;Solution:&lt;/b&gt; &lt;br /&gt;

Linking the Vector Icons repo in Xcode will solve the issue.&lt;br /&gt;

More information about how to link libraries to your app.

&lt;font size="1"&gt;

    &lt;a href="http://facebook.github.io/react-native/docs/linking-libraries-ios.html\#content"&gt;

        Click here

    &lt;/a&gt;

&lt;/font&gt;&lt;br /&gt;

If you still face the same issue, then restart packager and run from xcode.
</div>

<br />

<hr>

<br />



