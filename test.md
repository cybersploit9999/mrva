### apache/tvm

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C55).*

#### Paths

<details>
<summary>Path with 3 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21)
   <pre><code class="python">

   def pack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """Pack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L476C5-L476C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path + "." + style
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

3. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C73)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(<strong>dst</strong>, path)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C51).*

#### Paths

<details>
<summary>Path with 3 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21)
   <pre><code class="python">

   def pack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """Pack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L476C5-L476C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path + "." + style
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

3. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C73)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(<strong>dst</strong>, path)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C55).*

#### Paths

<details>
<summary>Path with 2 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21)
   <pre><code class="python">

   def pack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """Pack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C75-L479C79)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, <strong>path</strong>)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C51).*

#### Paths

<details>
<summary>Path with 2 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21)
   <pre><code class="python">

   def pack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """Pack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C75-L479C79)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, <strong>path</strong>)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C28-L458C31) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C55).*

#### Paths

<details>
<summary>Path with 3 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C28-L458C31)
   <pre><code class="python">

   def pack_folder(path: str, <strong>dst</strong>: str = None, style="tar.gz"):
       """Pack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L476C5-L476C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path + "." + style
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

3. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C73)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(<strong>dst</strong>, path)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C28-L458C31) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C51).*

#### Paths

<details>
<summary>Path with 3 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C28-L458C31)
   <pre><code class="python">

   def pack_folder(path: str, <strong>dst</strong>: str = None, style="tar.gz"):
       """Pack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L476C5-L476C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path + "." + style
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

3. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C73)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(<strong>dst</strong>, path)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C45-L458C50) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C55).*

#### Paths

<details>
<summary>Path with 3 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C45-L458C50)
   <pre><code class="python">

   def pack_folder(path: str, dst: str = None, <strong>style</strong>="tar.gz"):
       """Pack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L476C5-L476C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path + "." + style
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

3. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C73)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(<strong>dst</strong>, path)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C45-L458C50) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C51).*

#### Paths

<details>
<summary>Path with 3 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C45-L458C50)
   <pre><code class="python">

   def pack_folder(path: str, dst: str = None, <strong>style</strong>="tar.gz"):
       """Pack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L476C5-L476C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path + "." + style
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

3. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C73)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(<strong>dst</strong>, path)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C26) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C55).*

#### Paths

<details>
<summary>Path with 6 steps</summary>

1. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C26)
   <pre><code class="python">        return self._report

       def export(self, <strong>path</strong>: str = None, dump: bool = True) -&gt; Union[str, dict]:
           """Export the pipeline

   </code></pre>

2. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L486C9-L486C13)
   <pre><code class="python">        """

           <strong>path</strong> = path or "msc_export"
           if path.endswith(".tar.gz"):
               folder, dump = msc_utils.msc_dir(path.replace(".tar.gz", ""), keep_history=False), True
   </code></pre>

3. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L543C35-L543C62)
   <pre><code class="python">        folder.finalize()
           if path.endswith(".tar.gz"):
               msc_utils.pack_folder(<strong>path.replace(".tar.gz", "")</strong>, "tar.gz")
           return path

   </code></pre>

4. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21)
   <pre><code class="python">

   def pack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """Pack the folder

   </code></pre>

5. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L476C5-L476C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path + "." + style
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

6. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C73)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(<strong>dst</strong>, path)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C26) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C51).*

#### Paths

<details>
<summary>Path with 6 steps</summary>

1. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C26)
   <pre><code class="python">        return self._report

       def export(self, <strong>path</strong>: str = None, dump: bool = True) -&gt; Union[str, dict]:
           """Export the pipeline

   </code></pre>

2. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L486C9-L486C13)
   <pre><code class="python">        """

           <strong>path</strong> = path or "msc_export"
           if path.endswith(".tar.gz"):
               folder, dump = msc_utils.msc_dir(path.replace(".tar.gz", ""), keep_history=False), True
   </code></pre>

3. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L543C35-L543C62)
   <pre><code class="python">        folder.finalize()
           if path.endswith(".tar.gz"):
               msc_utils.pack_folder(<strong>path.replace(".tar.gz", "")</strong>, "tar.gz")
           return path

   </code></pre>

4. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21)
   <pre><code class="python">

   def pack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """Pack the folder

   </code></pre>

5. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L476C5-L476C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path + "." + style
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

6. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C73)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(<strong>dst</strong>, path)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C26) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C55).*

#### Paths

<details>
<summary>Path with 5 steps</summary>

1. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C26)
   <pre><code class="python">        return self._report

       def export(self, <strong>path</strong>: str = None, dump: bool = True) -&gt; Union[str, dict]:
           """Export the pipeline

   </code></pre>

2. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L486C9-L486C13)
   <pre><code class="python">        """

           <strong>path</strong> = path or "msc_export"
           if path.endswith(".tar.gz"):
               folder, dump = msc_utils.msc_dir(path.replace(".tar.gz", ""), keep_history=False), True
   </code></pre>

3. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L543C35-L543C62)
   <pre><code class="python">        folder.finalize()
           if path.endswith(".tar.gz"):
               msc_utils.pack_folder(<strong>path.replace(".tar.gz", "")</strong>, "tar.gz")
           return path

   </code></pre>

4. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21)
   <pre><code class="python">

   def pack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """Pack the folder

   </code></pre>

5. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C75-L479C79)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, <strong>path</strong>)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C80)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, path)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C26) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C51).*

#### Paths

<details>
<summary>Path with 5 steps</summary>

1. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C26)
   <pre><code class="python">        return self._report

       def export(self, <strong>path</strong>: str = None, dump: bool = True) -&gt; Union[str, dict]:
           """Export the pipeline

   </code></pre>

2. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L486C9-L486C13)
   <pre><code class="python">        """

           <strong>path</strong> = path or "msc_export"
           if path.endswith(".tar.gz"):
               folder, dump = msc_utils.msc_dir(path.replace(".tar.gz", ""), keep_history=False), True
   </code></pre>

3. [python/tvm/contrib/msc/pipeline/pipeline.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L543C35-L543C62)
   <pre><code class="python">        folder.finalize()
           if path.endswith(".tar.gz"):
               msc_utils.pack_folder(<strong>path.replace(".tar.gz", "")</strong>, "tar.gz")
           return path

   </code></pre>

4. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C21)
   <pre><code class="python">

   def pack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """Pack the folder

   </code></pre>

5. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C75-L479C79)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar --exculde={0} -zcvf {0} {1} &amp;&amp; rm -rf {1}".format(dst, <strong>path</strong>)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C50)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar -zxvf {} {}".format(path, dst)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C23) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L519C23-L519C55).*

#### Paths

<details>
<summary>Path with 2 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C23)
   <pre><code class="python">

   def unpack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """UnPack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C40-L514C44)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar -zxvf {} {}".format(<strong>path</strong>, dst)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C50)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar -zxvf {} {}".format(path, dst)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C23) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L521C19-L521C51).*

#### Paths

<details>
<summary>Path with 2 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C23)
   <pre><code class="python">

   def unpack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """UnPack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C40-L514C44)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar -zxvf {} {}".format(<strong>path</strong>, dst)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C50)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar -zxvf {} {}".format(path, dst)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C23) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L519C23-L519C55).*

#### Paths

<details>
<summary>Path with 3 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C23)
   <pre><code class="python">

   def unpack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """UnPack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L511C5-L511C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path.split(".")[0]
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

3. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C46-L514C49)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar -zxvf {} {}".format(path, <strong>dst</strong>)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C50)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar -zxvf {} {}".format(path, dst)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C23) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L521C19-L521C51).*

#### Paths

<details>
<summary>Path with 3 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C23)
   <pre><code class="python">

   def unpack_folder(<strong>path</strong>: str, dst: str = None, style="tar.gz"):
       """UnPack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L511C5-L511C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path.split(".")[0]
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

3. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C46-L514C49)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar -zxvf {} {}".format(path, <strong>dst</strong>)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C50)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar -zxvf {} {}".format(path, dst)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C30-L493C33) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L519C23-L519C55).*

#### Paths

<details>
<summary>Path with 3 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C30-L493C33)
   <pre><code class="python">

   def unpack_folder(path: str, <strong>dst</strong>: str = None, style="tar.gz"):
       """UnPack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L511C5-L511C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path.split(".")[0]
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

3. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C46-L514C49)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar -zxvf {} {}".format(path, <strong>dst</strong>)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C50)

<pre><code class="python">    root = os.path.dirname(path)
    if style == "tar.gz":
        cmd = <strong>"tar -zxvf {} {}".format(path, dst)</strong>
    else:
        raise NotImplementedError("Pack style {} is not supported".format(style))
</code></pre>

*This formatted string which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C30-L493C33) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L521C19-L521C51).*

#### Paths

<details>
<summary>Path with 3 steps</summary>

1. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C30-L493C33)
   <pre><code class="python">

   def unpack_folder(path: str, <strong>dst</strong>: str = None, style="tar.gz"):
       """UnPack the folder

   </code></pre>

2. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L511C5-L511C8)
   <pre><code class="python">    """

       <strong>dst</strong> = dst or path.split(".")[0]
       root = os.path.dirname(path)
       if style == "tar.gz":
   </code></pre>

3. [python/tvm/contrib/msc/core/utils/file.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C46-L514C49)
   <pre><code class="python">    root = os.path.dirname(path)
       if style == "tar.gz":
           cmd = "tar -zxvf {} {}".format(path, <strong>dst</strong>)
       else:
           raise NotImplementedError("Pack style {} is not supported".format(style))
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L385C9-L395C21)

<pre><code class="python">    # Invoke Marvell Backend with appropriate options
    compile_cmd = (
        <strong>mrvl_exec</strong>
<strong>        + " -mn "</strong>
<strong>        + symbol_name</strong>
<strong>        + " -f1 "</strong>
<strong>        + nodes_json_file</strong>
<strong>        + " -f2 "</strong>
<strong>        + consts_json_file</strong>
<strong>        + " "</strong>
<strong>        + compiler_opts</strong>
<strong>        + " -b "</strong>
<strong>        + batch_size</strong>
    )

</code></pre>

*This string concatenation which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L356C5-L356C16) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L398C15-L398C37).*

#### Paths

<details>
<summary>Path with 2 steps</summary>

1. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L356C5-L356C16)
   <pre><code class="python">@tvm._ffi.register_func("tvm.mrvl.CompileModel")
   def compile_model(
       <strong>symbol_name</strong>,
       nodes_json_string,
       consts_json_string,
   </code></pre>

2. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L385C9-L394C17)
   <pre><code class="python">    # Invoke Marvell Backend with appropriate options
       compile_cmd = (
           <strong>mrvl_exec</strong>
   <strong>        + " -mn "</strong>
   <strong>        + symbol_name</strong>
   <strong>        + " -f1 "</strong>
   <strong>        + nodes_json_file</strong>
   <strong>        + " -f2 "</strong>
   <strong>        + consts_json_file</strong>
   <strong>        + " "</strong>
   <strong>        + compiler_opts</strong>
   <strong>        + " -b "</strong>
           + batch_size
       )
   </code></pre>

</details>

<details>
<summary>Path with 8 steps</summary>

1. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L356C5-L356C16)
   <pre><code class="python">@tvm._ffi.register_func("tvm.mrvl.CompileModel")
   def compile_model(
       <strong>symbol_name</strong>,
       nodes_json_string,
       consts_json_string,
   </code></pre>

2. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L363C58-L363C85)
   <pre><code class="python">    """Compile the model using Marvell Backend compiler and return the generated binary"""
       # generate pair of json files
       nodes_json_file = write_json_file(nodes_json_string, <strong>f"{symbol_name}-nodes.json"</strong>)
       consts_json_file = write_json_file(consts_json_string, f"{symbol_name}-consts.json")
       mrvl_exec = "mrvl-tmlc"
   </code></pre>

3. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L333C34-L333C47)
   <pre><code class="python">
   @tvm._ffi.register_func("tvm.mrvl.WriteJsonFile")
   def write_json_file(json_string, <strong>json_filename</strong>):
       """Generate json file under working directory"""
       working_dir = get_working_dir()
   </code></pre>

4. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L336C5-L336C14)
   <pre><code class="python">    """Generate json file under working directory"""
       working_dir = get_working_dir()
       <strong>json_file</strong> = os.path.join(working_dir, json_filename)
       with open(json_file, "w") as out_file:
           out_file.write(json_string)
   </code></pre>

5. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L339C12-L339C21)
   <pre><code class="python">    with open(json_file, "w") as out_file:
           out_file.write(json_string)
       return <strong>json_file</strong>


   </code></pre>

6. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L363C23-L363C86)
   <pre><code class="python">    """Compile the model using Marvell Backend compiler and return the generated binary"""
       # generate pair of json files
       nodes_json_file = <strong>write_json_file(nodes_json_string, f"{symbol_name}-nodes.json")</strong>
       consts_json_file = write_json_file(consts_json_string, f"{symbol_name}-consts.json")
       mrvl_exec = "mrvl-tmlc"
   </code></pre>

7. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L363C5-L363C20)
   <pre><code class="python">    """Compile the model using Marvell Backend compiler and return the generated binary"""
       # generate pair of json files
       <strong>nodes_json_file</strong> = write_json_file(nodes_json_string, f"{symbol_name}-nodes.json")
       consts_json_file = write_json_file(consts_json_string, f"{symbol_name}-consts.json")
       mrvl_exec = "mrvl-tmlc"
   </code></pre>

8. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L385C9-L394C17)
   <pre><code class="python">    # Invoke Marvell Backend with appropriate options
       compile_cmd = (
           <strong>mrvl_exec</strong>
   <strong>        + " -mn "</strong>
   <strong>        + symbol_name</strong>
   <strong>        + " -f1 "</strong>
   <strong>        + nodes_json_file</strong>
   <strong>        + " -f2 "</strong>
   <strong>        + consts_json_file</strong>
   <strong>        + " "</strong>
   <strong>        + compiler_opts</strong>
   <strong>        + " -b "</strong>
           + batch_size
       )
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L385C9-L395C21)

<pre><code class="python">    # Invoke Marvell Backend with appropriate options
    compile_cmd = (
        <strong>mrvl_exec</strong>
<strong>        + " -mn "</strong>
<strong>        + symbol_name</strong>
<strong>        + " -f1 "</strong>
<strong>        + nodes_json_file</strong>
<strong>        + " -f2 "</strong>
<strong>        + consts_json_file</strong>
<strong>        + " "</strong>
<strong>        + compiler_opts</strong>
<strong>        + " -b "</strong>
<strong>        + batch_size</strong>
    )

</code></pre>

*This string concatenation which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L357C5-L357C22) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L398C15-L398C37).*

#### Paths

<details>
<summary>Path with 4 steps</summary>

1. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L357C5-L357C22)
   <pre><code class="python">def compile_model(
       symbol_name,
       <strong>nodes_json_string</strong>,
       consts_json_string,
       compiler_opts,
   </code></pre>

2. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L375C5-L375C15)
   <pre><code class="python">
       # Parse the nodes_json string for the batch size
       <strong>dictionary</strong> = json.loads(nodes_json_string)
       batch_size = dictionary["batch_size"]

   </code></pre>

3. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L376C5-L376C15)
   <pre><code class="python">    # Parse the nodes_json string for the batch size
       dictionary = json.loads(nodes_json_string)
       <strong>batch_size</strong> = dictionary["batch_size"]

       # Check for supported batch size
   </code></pre>

4. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L395C11-L395C21)
   <pre><code class="python">        + compiler_opts
           + " -b "
           + <strong>batch_size</strong>
       )

   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L385C9-L395C21)

<pre><code class="python">    # Invoke Marvell Backend with appropriate options
    compile_cmd = (
        <strong>mrvl_exec</strong>
<strong>        + " -mn "</strong>
<strong>        + symbol_name</strong>
<strong>        + " -f1 "</strong>
<strong>        + nodes_json_file</strong>
<strong>        + " -f2 "</strong>
<strong>        + consts_json_file</strong>
<strong>        + " "</strong>
<strong>        + compiler_opts</strong>
<strong>        + " -b "</strong>
<strong>        + batch_size</strong>
    )

</code></pre>

*This string concatenation which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L359C5-L359C18) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L398C15-L398C37).*

#### Paths

<details>
<summary>Path with 2 steps</summary>

1. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L359C5-L359C18)
   <pre><code class="python">    nodes_json_string,
       consts_json_string,
       <strong>compiler_opts</strong>,
   ):
       """Compile the model using Marvell Backend compiler and return the generated binary"""
   </code></pre>

2. [python/tvm/contrib/mrvl.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L385C9-L394C17)
   <pre><code class="python">    # Invoke Marvell Backend with appropriate options
       compile_cmd = (
           <strong>mrvl_exec</strong>
   <strong>        + " -mn "</strong>
   <strong>        + symbol_name</strong>
   <strong>        + " -f1 "</strong>
   <strong>        + nodes_json_file</strong>
   <strong>        + " -f2 "</strong>
   <strong>        + consts_json_file</strong>
   <strong>        + " "</strong>
   <strong>        + compiler_opts</strong>
   <strong>        + " -b "</strong>
           + batch_size
       )
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C46)

<pre><code class="python">    cmd2 += [temp_ir, "-o", file_target]
    proc = subprocess.Popen(
        <strong>" ".join(cmd1) + ";" + " ".join(cmd2)</strong>,
        shell=True,
        stdout=subprocess.PIPE,
</code></pre>

*This string concatenation which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C25-L110C36) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L154C12-L159C6).*

#### Paths

<details>
<summary>Path with 4 steps</summary>

1. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C25-L110C36)
   <pre><code class="python">

   def compile_metal(code, <strong>path_target</strong>=None, sdk="macosx", min_os_version=None):
       """Compile metal with CLI tool from env.

   </code></pre>

2. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L136C5-L136C16)
   <pre><code class="python">    with open(temp_code, "w") as out_file:
           out_file.write(code)
       <strong>file_target</strong> = path_target if path_target else temp_target

       # See:
   </code></pre>

3. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L153C5-L153C9)
   <pre><code class="python">    cmd1 += ["-c", temp_code, "-o", temp_ir]
       cmd2 = ["xcrun", "-sdk", sdk, "metallib"]
       <strong>cmd2</strong> += [temp_ir, "-o", file_target]
       proc = subprocess.Popen(
           " ".join(cmd1) + ";" + " ".join(cmd2),
   </code></pre>

4. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C32-L155C46)
   <pre><code class="python">    cmd2 += [temp_ir, "-o", file_target]
       proc = subprocess.Popen(
           " ".join(cmd1) + ";" + <strong>" ".join(cmd2)</strong>,
           shell=True,
           stdout=subprocess.PIPE,
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C46)

<pre><code class="python">    cmd2 += [temp_ir, "-o", file_target]
    proc = subprocess.Popen(
        <strong>" ".join(cmd1) + ";" + " ".join(cmd2)</strong>,
        shell=True,
        stdout=subprocess.PIPE,
</code></pre>

*This string concatenation which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C43-L110C46) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L154C12-L159C6).*

#### Paths

<details>
<summary>Path with 4 steps</summary>

1. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C43-L110C46)
   <pre><code class="python">

   def compile_metal(code, path_target=None, <strong>sdk</strong>="macosx", min_os_version=None):
       """Compile metal with CLI tool from env.

   </code></pre>

2. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L150C5-L150C9)
   <pre><code class="python">    else:
           raise RuntimeError(f"Unsupported sdk: {sdk}")
       <strong>cmd1</strong> = ["xcrun", "-sdk", sdk, "metal", language_version, min_target, "-O3"]
       cmd1 += ["-c", temp_code, "-o", temp_ir]
       cmd2 = ["xcrun", "-sdk", sdk, "metallib"]
   </code></pre>

3. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L151C5-L151C9)
   <pre><code class="python">        raise RuntimeError(f"Unsupported sdk: {sdk}")
       cmd1 = ["xcrun", "-sdk", sdk, "metal", language_version, min_target, "-O3"]
       <strong>cmd1</strong> += ["-c", temp_code, "-o", temp_ir]
       cmd2 = ["xcrun", "-sdk", sdk, "metallib"]
       cmd2 += [temp_ir, "-o", file_target]
   </code></pre>

4. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C29)
   <pre><code class="python">    cmd2 += [temp_ir, "-o", file_target]
       proc = subprocess.Popen(
           <strong>" ".join(cmd1) + ";"</strong> + " ".join(cmd2),
           shell=True,
           stdout=subprocess.PIPE,
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C46)

<pre><code class="python">    cmd2 += [temp_ir, "-o", file_target]
    proc = subprocess.Popen(
        <strong>" ".join(cmd1) + ";" + " ".join(cmd2)</strong>,
        shell=True,
        stdout=subprocess.PIPE,
</code></pre>

*This string concatenation which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C43-L110C46) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L154C12-L159C6).*

#### Paths

<details>
<summary>Path with 4 steps</summary>

1. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C43-L110C46)
   <pre><code class="python">

   def compile_metal(code, path_target=None, <strong>sdk</strong>="macosx", min_os_version=None):
       """Compile metal with CLI tool from env.

   </code></pre>

2. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L152C5-L152C9)
   <pre><code class="python">    cmd1 = ["xcrun", "-sdk", sdk, "metal", language_version, min_target, "-O3"]
       cmd1 += ["-c", temp_code, "-o", temp_ir]
       <strong>cmd2</strong> = ["xcrun", "-sdk", sdk, "metallib"]
       cmd2 += [temp_ir, "-o", file_target]
       proc = subprocess.Popen(
   </code></pre>

3. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L153C5-L153C9)
   <pre><code class="python">    cmd1 += ["-c", temp_code, "-o", temp_ir]
       cmd2 = ["xcrun", "-sdk", sdk, "metallib"]
       <strong>cmd2</strong> += [temp_ir, "-o", file_target]
       proc = subprocess.Popen(
           " ".join(cmd1) + ";" + " ".join(cmd2),
   </code></pre>

4. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C32-L155C46)
   <pre><code class="python">    cmd2 += [temp_ir, "-o", file_target]
       proc = subprocess.Popen(
           " ".join(cmd1) + ";" + <strong>" ".join(cmd2)</strong>,
           shell=True,
           stdout=subprocess.PIPE,
   </code></pre>

</details>

----------------------------------------

[python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C46)

<pre><code class="python">    cmd2 += [temp_ir, "-o", file_target]
    proc = subprocess.Popen(
        <strong>" ".join(cmd1) + ";" + " ".join(cmd2)</strong>,
        shell=True,
        stdout=subprocess.PIPE,
</code></pre>

*This string concatenation which depends on [library input](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C57-L110C71) is later used in a [shell command](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L154C12-L159C6).*

#### Paths

<details>
<summary>Path with 9 steps</summary>

1. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C57-L110C71)
   <pre><code class="python">

   def compile_metal(code, path_target=None, sdk="macosx", <strong>min_os_version</strong>=None):
       """Compile metal with CLI tool from env.

   </code></pre>

2. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L143C48-L143C62)
   <pre><code class="python">    #   xcrun -sdk macosx metal -c MyLibrary.metal -o MyLibrary.air
       #   xcrun -sdk macosx metallib MyLibrary.air -o MyLibrary.metallib
       min_target = __get_min_os_version_cmd(sdk, <strong>min_os_version</strong>)
       if sdk == "macosx":
           language_version = "-std=macos-metal2.3"
   </code></pre>

3. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L56C35-L56C49)
   <pre><code class="python">

   def __get_min_os_version_cmd(sdk, <strong>min_os_version</strong>):
       if min_os_version is None:
           min_os_version = __get_min_os_version(sdk)
   </code></pre>

4. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L60C16-L60C53)
   <pre><code class="python">        min_os_version = __get_min_os_version(sdk)
       if min_os_version is not None:
           return <strong>"-mios-version-min=" + min_os_version</strong>
       return ""

   </code></pre>

5. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L143C18-L143C63)
   <pre><code class="python">    #   xcrun -sdk macosx metal -c MyLibrary.metal -o MyLibrary.air
       #   xcrun -sdk macosx metallib MyLibrary.air -o MyLibrary.metallib
       min_target = <strong>__get_min_os_version_cmd(sdk, min_os_version)</strong>
       if sdk == "macosx":
           language_version = "-std=macos-metal2.3"
   </code></pre>

6. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L143C5-L143C15)
   <pre><code class="python">    #   xcrun -sdk macosx metal -c MyLibrary.metal -o MyLibrary.air
       #   xcrun -sdk macosx metallib MyLibrary.air -o MyLibrary.metallib
       <strong>min_target</strong> = __get_min_os_version_cmd(sdk, min_os_version)
       if sdk == "macosx":
           language_version = "-std=macos-metal2.3"
   </code></pre>

7. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L150C5-L150C9)
   <pre><code class="python">    else:
           raise RuntimeError(f"Unsupported sdk: {sdk}")
       <strong>cmd1</strong> = ["xcrun", "-sdk", sdk, "metal", language_version, min_target, "-O3"]
       cmd1 += ["-c", temp_code, "-o", temp_ir]
       cmd2 = ["xcrun", "-sdk", sdk, "metallib"]
   </code></pre>

8. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L151C5-L151C9)
   <pre><code class="python">        raise RuntimeError(f"Unsupported sdk: {sdk}")
       cmd1 = ["xcrun", "-sdk", sdk, "metal", language_version, min_target, "-O3"]
       <strong>cmd1</strong> += ["-c", temp_code, "-o", temp_ir]
       cmd2 = ["xcrun", "-sdk", sdk, "metallib"]
       cmd2 += [temp_ir, "-o", file_target]
   </code></pre>

9. [python/tvm/contrib/xcode.py](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C29)
   <pre><code class="python">    cmd2 += [temp_ir, "-o", file_target]
       proc = subprocess.Popen(
           <strong>" ".join(cmd1) + ";"</strong> + " ".join(cmd2),
           shell=True,
           stdout=subprocess.PIPE,
   </code></pre>

</details>

----------------------------------------

|  | source | sink |  |  |  |  |  |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C20) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C72) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C20) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C54) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C20) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C72) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C20) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C50) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C20) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C75-L479C78) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C20) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C54) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C20) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C75-L479C78) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C17-L458C20) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C50) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C28-L458C30) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C72) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C28-L458C30) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C54) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C28-L458C30) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C72) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C28-L458C30) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C50) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for style`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C45-L458C49) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C72) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for style`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C45-L458C49) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C54) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for style`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C45-L458C49) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C72) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for style`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L458C45-L458C49) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C50) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C25) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C72) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C25) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C54) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C25) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C70-L479C72) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C25) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C50) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C25) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C75-L479C78) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C25) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L484C23-L484C54) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C15-L479C79) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C25) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L479C75-L479C78) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/pipeline/pipeline.py#L470C22-L470C25) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L486C19-L486C50) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C49) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C22) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C40-L514C43) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C22) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L519C23-L519C54) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C49) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C22) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C40-L514C43) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C22) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L521C19-L521C50) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C49) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C22) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C46-L514C48) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C22) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L519C23-L519C54) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C49) | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C22) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C46-L514C48) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for path`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C19-L493C22) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L521C19-L521C50) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C49) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C30-L493C32) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C46-L514C48) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C30-L493C32) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L519C23-L519C54) | `shell command` |
| [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C15-L514C49) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C30-L493C32) | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L514C46-L514C48) | `This formatted string which depends on $@ is later used in a $@.` | [`ControlFlowNode for dst`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L493C30-L493C32) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/msc/core/utils/file.py#L521C19-L521C50) | `shell command` |
| [`ControlFlowNode for BinaryExpr`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L385C9-L395C20) | [`ControlFlowNode for symbol_name`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L356C5-L356C15) | [`ControlFlowNode for BinaryExpr`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L385C9-L394C16) | `This string concatenation which depends on $@ is later used in a $@.` | [`ControlFlowNode for symbol_name`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L356C5-L356C15) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L398C15-L398C36) | `shell command` |
| [`ControlFlowNode for BinaryExpr`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L385C9-L395C20) | [`ControlFlowNode for nodes_json_string`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L357C5-L357C21) | [`ControlFlowNode for batch_size`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L395C11-L395C20) | `This string concatenation which depends on $@ is later used in a $@.` | [`ControlFlowNode for nodes_json_string`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L357C5-L357C21) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L398C15-L398C36) | `shell command` |
| [`ControlFlowNode for BinaryExpr`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L385C9-L395C20) | [`ControlFlowNode for compiler_opts`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L359C5-L359C17) | [`ControlFlowNode for BinaryExpr`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L385C9-L394C16) | `This string concatenation which depends on $@ is later used in a $@.` | [`ControlFlowNode for compiler_opts`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L359C5-L359C17) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/mrvl.py#L398C15-L398C36) | `shell command` |
| [`ControlFlowNode for BinaryExpr`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C45) | [`ControlFlowNode for path_target`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C25-L110C35) | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C32-L155C45) | `This string concatenation which depends on $@ is later used in a $@.` | [`ControlFlowNode for path_target`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C25-L110C35) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L154C12-L159C5) | `shell command` |
| [`ControlFlowNode for BinaryExpr`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C45) | [`ControlFlowNode for sdk`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C43-L110C45) | [`ControlFlowNode for BinaryExpr`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C28) | `This string concatenation which depends on $@ is later used in a $@.` | [`ControlFlowNode for sdk`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C43-L110C45) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L154C12-L159C5) | `shell command` |
| [`ControlFlowNode for BinaryExpr`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C45) | [`ControlFlowNode for sdk`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C43-L110C45) | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C32-L155C45) | `This string concatenation which depends on $@ is later used in a $@.` | [`ControlFlowNode for sdk`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C43-L110C45) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L154C12-L159C5) | `shell command` |
| [`ControlFlowNode for BinaryExpr`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C45) | [`ControlFlowNode for min_os_version`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C57-L110C70) | [`ControlFlowNode for BinaryExpr`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L155C9-L155C28) | `This string concatenation which depends on $@ is later used in a $@.` | [`ControlFlowNode for min_os_version`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L110C57-L110C70) | `library input` | [`ControlFlowNode for Attribute()`](https://github.com/apache/tvm/blob/567eeed38bdbcefb68e36328af6ab1501a81d51e/python/tvm/contrib/xcode.py#L154C12-L159C5) | `shell command` |
