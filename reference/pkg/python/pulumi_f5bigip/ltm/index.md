<div class="section" id="module-pulumi_f5bigip.ltm">
<span id="ltm"></span><h1>ltm<a class="headerlink" href="#module-pulumi_f5bigip.ltm" title="Permalink to this headline">¶</a></h1>
<dl class="class">
<dt id="pulumi_f5bigip.ltm.DataGroup">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">DataGroup</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>name=None</em>, <em>records=None</em>, <em>type=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.DataGroup" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_datagroup</cite> Manages internal (in-line) datagroup configuration</p>
<p>Resource should be named with their “full path”. The full path is the combination of the partition + name of the resource, for example /Common/my-datagroup.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – , sets the value of the record’s <cite>name</cite> attribute, must be of type defined in <cite>type</cite> attribute</li>
<li><strong>records</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – a set of <cite>name</cite> and <cite>data</cite> attributes, name must be of type specified by the <cite>type</cite> attributed (<cite>string</cite>, <cite>ip</cite> and <cite>integer</cite>), data is optional and can take any value, multiple <cite>record</cite> sets can be specified as needed.</li>
<li><strong>type</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – datagroup type (applies to the <cite>name</cite> field of the record), supports: <cite>string</cite>, <cite>ip</cite> or <cite>integer</cite></li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.DataGroup.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.DataGroup.name" title="Permalink to this definition">¶</a></dt>
<dd><p>, sets the value of the record’s <cite>name</cite> attribute, must be of type defined in <cite>type</cite> attribute</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.DataGroup.records">
<code class="descname">records</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.DataGroup.records" title="Permalink to this definition">¶</a></dt>
<dd><p>a set of <cite>name</cite> and <cite>data</cite> attributes, name must be of type specified by the <cite>type</cite> attributed (<cite>string</cite>, <cite>ip</cite> and <cite>integer</cite>), data is optional and can take any value, multiple <cite>record</cite> sets can be specified as needed.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.DataGroup.type">
<code class="descname">type</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.DataGroup.type" title="Permalink to this definition">¶</a></dt>
<dd><p>datagroup type (applies to the <cite>name</cite> field of the record), supports: <cite>string</cite>, <cite>ip</cite> or <cite>integer</cite></p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.DataGroup.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.DataGroup.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.DataGroup.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.DataGroup.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.IRule">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">IRule</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>irule=None</em>, <em>name=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.IRule" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_irule</cite> Creates iRule on BIG-IP F5 device</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>irule</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Body of the iRule</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the iRule</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.IRule.irule">
<code class="descname">irule</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.IRule.irule" title="Permalink to this definition">¶</a></dt>
<dd><p>Body of the iRule</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.IRule.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.IRule.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the iRule</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.IRule.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.IRule.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.IRule.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.IRule.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.Monitor">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">Monitor</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>defaults_from=None</em>, <em>destination=None</em>, <em>interval=None</em>, <em>ip_dscp=None</em>, <em>manual_resume=None</em>, <em>name=None</em>, <em>parent=None</em>, <em>receive=None</em>, <em>receive_disable=None</em>, <em>reverse=None</em>, <em>send=None</em>, <em>time_until_up=None</em>, <em>timeout=None</em>, <em>transparent=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Monitor" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_monitor</cite> Configures a custom monitor for use by health checks.</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[str] defaults_from
:param pulumi.Input[str] destination: Specify an alias address for monitoring
:param pulumi.Input[int] interval: Check interval in seconds
:param pulumi.Input[int] ip_dscp
:param pulumi.Input[str] manual_resume
:param pulumi.Input[str] name: Name of the monitor
:param pulumi.Input[str] parent: Existing LTM monitor to inherit from
:param pulumi.Input[str] receive: Expected response string
:param pulumi.Input[str] receive_disable
:param pulumi.Input[str] reverse
:param pulumi.Input[str] send: Request string to send
:param pulumi.Input[int] time_until_up
:param pulumi.Input[int] timeout: Timeout in seconds
:param pulumi.Input[str] transparent</p>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Monitor.destination">
<code class="descname">destination</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Monitor.destination" title="Permalink to this definition">¶</a></dt>
<dd><p>Specify an alias address for monitoring</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Monitor.interval">
<code class="descname">interval</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Monitor.interval" title="Permalink to this definition">¶</a></dt>
<dd><p>Check interval in seconds</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Monitor.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Monitor.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the monitor</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Monitor.parent">
<code class="descname">parent</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Monitor.parent" title="Permalink to this definition">¶</a></dt>
<dd><p>Existing LTM monitor to inherit from</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Monitor.receive">
<code class="descname">receive</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Monitor.receive" title="Permalink to this definition">¶</a></dt>
<dd><p>Expected response string</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Monitor.send">
<code class="descname">send</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Monitor.send" title="Permalink to this definition">¶</a></dt>
<dd><p>Request string to send</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Monitor.timeout">
<code class="descname">timeout</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Monitor.timeout" title="Permalink to this definition">¶</a></dt>
<dd><p>Timeout in seconds</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.Monitor.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Monitor.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.Monitor.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Monitor.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.Node">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">Node</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>address=None</em>, <em>connection_limit=None</em>, <em>dynamic_ratio=None</em>, <em>fqdns=None</em>, <em>monitor=None</em>, <em>name=None</em>, <em>rate_limit=None</em>, <em>state=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Node" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_node</cite> Manages a node configuration</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>address</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – IP or hostname of the node</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[int] connection_limit
:param pulumi.Input[int] dynamic_ratio
:param pulumi.Input[list] fqdns
:param pulumi.Input[str] monitor
:param pulumi.Input[str] name: Name of the node
:param pulumi.Input[str] rate_limit
:param pulumi.Input[str] state: Default is “user-up” you can set to “user-down” if you want to disable</p>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Node.address">
<code class="descname">address</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Node.address" title="Permalink to this definition">¶</a></dt>
<dd><p>IP or hostname of the node</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Node.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Node.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the node</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Node.state">
<code class="descname">state</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Node.state" title="Permalink to this definition">¶</a></dt>
<dd><p>Default is “user-up” you can set to “user-down” if you want to disable</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.Node.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Node.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.Node.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Node.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileCookie">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">PersistenceProfileCookie</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>always_send=None</em>, <em>app_service=None</em>, <em>cookie_encryption=None</em>, <em>cookie_encryption_passphrase=None</em>, <em>cookie_name=None</em>, <em>defaults_from=None</em>, <em>expiration=None</em>, <em>hash_length=None</em>, <em>hash_offset=None</em>, <em>httponly=None</em>, <em>match_across_pools=None</em>, <em>match_across_services=None</em>, <em>match_across_virtuals=None</em>, <em>mirror=None</em>, <em>name=None</em>, <em>override_conn_limit=None</em>, <em>timeout=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileCookie" title="Permalink to this definition">¶</a></dt>
<dd><p>Configures a cookie persistence profile</p>
<p>## Reference</p>
<p><cite>name</cite> - (Required) Name of the virtual address</p>
<p><cite>defaults_from</cite> - (Required) Parent cookie persistence profile</p>
<p><cite>match_across_pools</cite> (Optional) (enabled or disabled) match across pools with given persistence record</p>
<p><cite>match_across_services</cite> (Optional) (enabled or disabled) match across services with given persistence record</p>
<p><cite>match_across_virtuals</cite> (Optional) (enabled or disabled) match across virtual servers with given persistence record</p>
<p><cite>mirror</cite> (Optional) (enabled or disabled) mirror persistence record</p>
<p><cite>timeout</cite> (Optional) (enabled or disabled) Timeout for persistence of the session in seconds</p>
<p><cite>override_conn_limit</cite> (Optional) (enabled or disabled) Enable or dissable pool member connection limits are overridden for persisted clients. Per-virtual connection limits remain hard limits and are not overridden.</p>
<p><cite>always_send</cite> (Optional) (enabled or disabled) always send cookies</p>
<p><cite>cookie_encryption</cite> (Optional) (required, preferred, or disabled) To required, preferred, or disabled policy for cookie encryption</p>
<p><cite>cookie_encryption_passphrase</cite> (Optional) (required, preferred, or disabled) Passphrase for encrypted cookies. The field is encrypted on the server and will always return differently then set.
If this is configured specify <cite>ignore_changes</cite> under the <cite>lifecycle</cite> block to ignore returned encrypted value.</p>
<p><cite>cookie_name</cite> (Optional) Name of the cookie to track persistence</p>
<p><cite>expiration</cite> (Optional) Expiration TTL for cookie specified in DAY:HOUR:MIN:SECONDS (Examples: 1:0:0:0 one day, 1:0:0 one hour, 30:0 thirty minutes)</p>
<p><cite>hash_length</cite> (Optional) (Integer) Length of hash to apply to cookie</p>
<p><cite>hash_offset</cite> (Optional) (Integer) Number of characters to skip in the cookie for the hash</p>
<p><cite>httponly</cite> (Optional) (enabled or disabled) Sending only over http</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[str] always_send
:param pulumi.Input[str] app_service
:param pulumi.Input[str] cookie_encryption
:param pulumi.Input[str] cookie_encryption_passphrase
:param pulumi.Input[str] cookie_name
:param pulumi.Input[str] defaults_from
:param pulumi.Input[str] expiration
:param pulumi.Input[int] hash_length
:param pulumi.Input[int] hash_offset
:param pulumi.Input[str] httponly
:param pulumi.Input[str] match_across_pools
:param pulumi.Input[str] match_across_services
:param pulumi.Input[str] match_across_virtuals
:param pulumi.Input[str] mirror
:param pulumi.Input[str] name
:param pulumi.Input[str] override_conn_limit
:param pulumi.Input[int] timeout</p>
<dl class="method">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileCookie.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileCookie.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileCookie.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileCookie.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileDstAddr">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">PersistenceProfileDstAddr</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>app_service=None</em>, <em>defaults_from=None</em>, <em>hash_algorithm=None</em>, <em>mask=None</em>, <em>match_across_pools=None</em>, <em>match_across_services=None</em>, <em>match_across_virtuals=None</em>, <em>mirror=None</em>, <em>name=None</em>, <em>override_conn_limit=None</em>, <em>timeout=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileDstAddr" title="Permalink to this definition">¶</a></dt>
<dd><p>Configures a cookie persistence profile</p>
<p>## Reference</p>
<p><cite>name</cite> - (Required) Name of the virtual address</p>
<p><cite>defaults_from</cite> - (Optional) Specifies the existing profile from which the system imports settings for the new profile.</p>
<p><cite>match_across_pools</cite> (Optional) (enabled or disabled) match across pools with given persistence record</p>
<p><cite>match_across_services</cite> (Optional) (enabled or disabled) match across services with given persistence record</p>
<p><cite>match_across_virtuals</cite> (Optional) (enabled or disabled) match across virtual servers with given persistence record</p>
<p><cite>mirror</cite> (Optional) (enabled or disabled) mirror persistence record</p>
<p><cite>timeout</cite> (Optional) (enabled or disabled) Timeout for persistence of the session in seconds</p>
<p><cite>override_conn_limit</cite> (Optional) (enabled or disabled) Enable or dissable pool member connection limits are overridden for persisted clients. Per-virtual connection limits remain hard limits and are not overridden.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[str] app_service
:param pulumi.Input[str] defaults_from
:param pulumi.Input[str] hash_algorithm
:param pulumi.Input[str] mask
:param pulumi.Input[str] match_across_pools
:param pulumi.Input[str] match_across_services
:param pulumi.Input[str] match_across_virtuals
:param pulumi.Input[str] mirror
:param pulumi.Input[str] name
:param pulumi.Input[str] override_conn_limit
:param pulumi.Input[int] timeout</p>
<dl class="method">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileDstAddr.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileDstAddr.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileDstAddr.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileDstAddr.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileSrcAddr">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">PersistenceProfileSrcAddr</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>app_service=None</em>, <em>defaults_from=None</em>, <em>hash_algorithm=None</em>, <em>map_proxies=None</em>, <em>mask=None</em>, <em>match_across_pools=None</em>, <em>match_across_services=None</em>, <em>match_across_virtuals=None</em>, <em>mirror=None</em>, <em>name=None</em>, <em>override_conn_limit=None</em>, <em>timeout=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileSrcAddr" title="Permalink to this definition">¶</a></dt>
<dd><p>Configures a source address persistence profile</p>
<p>## Reference</p>
<p><cite>name</cite> - (Required) Name of the virtual address</p>
<p><cite>defaults_from</cite> - (Required) Parent cookie persistence profile</p>
<p><cite>match_across_pools</cite> (Optional) (enabled or disabled) match across pools with given persistence record</p>
<p><cite>match_across_services</cite> (Optional) (enabled or disabled) match across services with given persistence record</p>
<p><cite>match_across_virtuals</cite> (Optional) (enabled or disabled) match across virtual servers with given persistence record</p>
<p><cite>mirror</cite> (Optional) (enabled or disabled) mirror persistence record</p>
<p><cite>timeout</cite> (Optional) (enabled or disabled) Timeout for persistence of the session in seconds</p>
<p><cite>override_conn_limit</cite> (Optional) (enabled or disabled) Enable or dissable pool member connection limits are overridden for persisted clients. Per-virtual connection limits remain hard limits and are not overridden.</p>
<p><cite>hash_algorithm</cite> (Optional) Specify the hash algorithm</p>
<p><cite>mask</cite> (Optional) Identify a range of source IP addresses to manage together as a single source address affinity persistent connection when connecting to the pool. Must be a valid IPv4 or IPv6 mask.</p>
<p><cite>map_proxies</cite> (Optional) (enabled or disabled) Directs all to the same single pool member</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[str] app_service
:param pulumi.Input[str] defaults_from
:param pulumi.Input[str] hash_algorithm
:param pulumi.Input[str] map_proxies
:param pulumi.Input[str] mask
:param pulumi.Input[str] match_across_pools
:param pulumi.Input[str] match_across_services
:param pulumi.Input[str] match_across_virtuals
:param pulumi.Input[str] mirror
:param pulumi.Input[str] name
:param pulumi.Input[str] override_conn_limit
:param pulumi.Input[int] timeout</p>
<dl class="method">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileSrcAddr.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileSrcAddr.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileSrcAddr.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileSrcAddr.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileSsl">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">PersistenceProfileSsl</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>app_service=None</em>, <em>defaults_from=None</em>, <em>match_across_pools=None</em>, <em>match_across_services=None</em>, <em>match_across_virtuals=None</em>, <em>mirror=None</em>, <em>name=None</em>, <em>override_conn_limit=None</em>, <em>timeout=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileSsl" title="Permalink to this definition">¶</a></dt>
<dd><p>Configures an SSL persistence profile</p>
<p>## Reference</p>
<p><cite>name</cite> - (Required) Name of the virtual address</p>
<p><cite>defaults_from</cite> - (Required) Parent cookie persistence profile</p>
<p><cite>match_across_pools</cite> (Optional) (enabled or disabled) match across pools with given persistence record</p>
<p><cite>match_across_services</cite> (Optional) (enabled or disabled) match across services with given persistence record</p>
<p><cite>match_across_virtuals</cite> (Optional) (enabled or disabled) match across virtual servers with given persistence record</p>
<p><cite>mirror</cite> (Optional) (enabled or disabled) mirror persistence record</p>
<p><cite>timeout</cite> (Optional) (enabled or disabled) Timeout for persistence of the session in seconds</p>
<p><cite>override_conn_limit</cite> (Optional) (enabled or disabled) Enable or dissable pool member connection limits are overridden for persisted clients. Per-virtual connection limits remain hard limits and are not overridden.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[str] app_service
:param pulumi.Input[str] defaults_from
:param pulumi.Input[str] match_across_pools
:param pulumi.Input[str] match_across_services
:param pulumi.Input[str] match_across_virtuals
:param pulumi.Input[str] mirror
:param pulumi.Input[str] name
:param pulumi.Input[str] override_conn_limit
:param pulumi.Input[int] timeout</p>
<dl class="method">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileSsl.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileSsl.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.PersistenceProfileSsl.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PersistenceProfileSsl.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.Policy">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">Policy</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>controls=None</em>, <em>name=None</em>, <em>published_copy=None</em>, <em>requires=None</em>, <em>rules=None</em>, <em>strategy=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Policy" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_policy</cite> Configures Virtual Server</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>controls</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Specifies the controls</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[str] name
:param pulumi.Input[str] published_copy: If you want to publish the policy else it will be deployed in Drafts mode.
:param pulumi.Input[list] requires: Specifies the protocol
:param pulumi.Input[list] rules: Rules can be applied using the policy
:param pulumi.Input[str] strategy: Specifies the match strategy</p>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Policy.controls">
<code class="descname">controls</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Policy.controls" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the controls</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Policy.published_copy">
<code class="descname">published_copy</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Policy.published_copy" title="Permalink to this definition">¶</a></dt>
<dd><p>If you want to publish the policy else it will be deployed in Drafts mode.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Policy.requires">
<code class="descname">requires</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Policy.requires" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the protocol</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Policy.rules">
<code class="descname">rules</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Policy.rules" title="Permalink to this definition">¶</a></dt>
<dd><p>Rules can be applied using the policy</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Policy.strategy">
<code class="descname">strategy</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Policy.strategy" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the match strategy</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.Policy.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Policy.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.Policy.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Policy.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.Pool">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">Pool</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>allow_nat=None</em>, <em>allow_snat=None</em>, <em>load_balancing_mode=None</em>, <em>monitors=None</em>, <em>name=None</em>, <em>reselect_tries=None</em>, <em>service_down_action=None</em>, <em>slow_ramp_time=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Pool" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_pool</cite> Manages a pool configuration.</p>
<p>Resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[str] allow_nat
:param pulumi.Input[str] allow_snat
:param pulumi.Input[str] load_balancing_mode
:param pulumi.Input[list] monitors: List of monitor names to associate with the pool
:param pulumi.Input[str] name: Name of the pool
:param pulumi.Input[int] reselect_tries
:param pulumi.Input[str] service_down_action
:param pulumi.Input[int] slow_ramp_time</p>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Pool.monitors">
<code class="descname">monitors</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Pool.monitors" title="Permalink to this definition">¶</a></dt>
<dd><p>List of monitor names to associate with the pool</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Pool.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Pool.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the pool</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.Pool.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Pool.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.Pool.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Pool.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.PoolAttachment">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">PoolAttachment</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>node=None</em>, <em>pool=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PoolAttachment" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_pool_attachment</cite> Manages nodes membership in pools</p>
<p>Resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>node</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Node to add to the pool in /Partition/NodeName:Port format (e.g. /Common/Node01:80)</li>
<li><strong>pool</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the pool in /Partition/Name format</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.PoolAttachment.node">
<code class="descname">node</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.PoolAttachment.node" title="Permalink to this definition">¶</a></dt>
<dd><p>Node to add to the pool in /Partition/NodeName:Port format (e.g. /Common/Node01:80)</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.PoolAttachment.pool">
<code class="descname">pool</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.PoolAttachment.pool" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the pool in /Partition/Name format</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.PoolAttachment.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PoolAttachment.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.PoolAttachment.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.PoolAttachment.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">ProfileFastHttp</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>connpool_maxreuse=None</em>, <em>connpool_maxsize=None</em>, <em>connpool_minsize=None</em>, <em>connpool_replenish=None</em>, <em>connpool_step=None</em>, <em>connpoolidle_timeoutoverride=None</em>, <em>defaults_from=None</em>, <em>forcehttp10response=None</em>, <em>idle_timeout=None</em>, <em>maxheader_size=None</em>, <em>name=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_profile_fasthttp</cite> Configures a custom profile_fasthttp for use by health checks.</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>connpool_maxreuse</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the maximum number of times that the system can re-use a current connection. The default value is 0 (zero).</li>
<li><strong>connpool_maxsize</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the maximum number of connections to a load balancing pool. A setting of 0 specifies that a pool can accept an unlimited number of connections. The default value is 2048.</li>
<li><strong>connpool_minsize</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the minimum number of connections to a load balancing pool. A setting of 0 specifies that there is no minimum. The default value is 10.</li>
<li><strong>connpool_replenish</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – The default value is enabled. When this option is enabled, the system replenishes the number of connections to a load balancing pool to the number of connections that existed when the server closed the connection to the pool. When disabled, the system replenishes the connection that was closed by the server, only when there are fewer connections to the pool than the number of connections set in the connpool-min-size connections option. Also see the connpool-min-size option..</li>
<li><strong>connpool_step</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the increment in which the system makes additional connections available, when all available connections are in use. The default value is 4.</li>
<li><strong>connpoolidle_timeoutoverride</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the number of seconds after which a server-side connection in a OneConnect pool is eligible for deletion, when the connection has no traffic.The value of this option overrides the idle-timeout value that you specify. The default value is 0 (zero) seconds, which disables the override setting.</li>
<li><strong>defaults_from</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</li>
<li><strong>forcehttp10response</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies whether to rewrite the HTTP version in the status line of the server to HTTP 1.0 to discourage the client from pipelining or chunking data. The default value is disabled.</li>
<li><strong>idle_timeout</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies an idle timeout in seconds. This setting specifies the number of seconds that a connection is idle before the connection is eligible for deletion.When you specify an idle timeout for the Fast L4 profile, the value must be greater than the bigdb database variable Pva.Scrub time in msec for it to work properly.The default value is 300 seconds.</li>
<li><strong>maxheader_size</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the maximum amount of HTTP header data that the system buffers before making a load balancing decision. The default setting is 32768.</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the profile_fasthttp</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.connpool_maxreuse">
<code class="descname">connpool_maxreuse</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.connpool_maxreuse" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the maximum number of times that the system can re-use a current connection. The default value is 0 (zero).</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.connpool_maxsize">
<code class="descname">connpool_maxsize</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.connpool_maxsize" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the maximum number of connections to a load balancing pool. A setting of 0 specifies that a pool can accept an unlimited number of connections. The default value is 2048.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.connpool_minsize">
<code class="descname">connpool_minsize</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.connpool_minsize" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the minimum number of connections to a load balancing pool. A setting of 0 specifies that there is no minimum. The default value is 10.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.connpool_replenish">
<code class="descname">connpool_replenish</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.connpool_replenish" title="Permalink to this definition">¶</a></dt>
<dd><p>The default value is enabled. When this option is enabled, the system replenishes the number of connections to a load balancing pool to the number of connections that existed when the server closed the connection to the pool. When disabled, the system replenishes the connection that was closed by the server, only when there are fewer connections to the pool than the number of connections set in the connpool-min-size connections option. Also see the connpool-min-size option..</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.connpool_step">
<code class="descname">connpool_step</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.connpool_step" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the increment in which the system makes additional connections available, when all available connections are in use. The default value is 4.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.connpoolidle_timeoutoverride">
<code class="descname">connpoolidle_timeoutoverride</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.connpoolidle_timeoutoverride" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the number of seconds after which a server-side connection in a OneConnect pool is eligible for deletion, when the connection has no traffic.The value of this option overrides the idle-timeout value that you specify. The default value is 0 (zero) seconds, which disables the override setting.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.defaults_from">
<code class="descname">defaults_from</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.defaults_from" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.forcehttp10response">
<code class="descname">forcehttp10response</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.forcehttp10response" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies whether to rewrite the HTTP version in the status line of the server to HTTP 1.0 to discourage the client from pipelining or chunking data. The default value is disabled.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.idle_timeout">
<code class="descname">idle_timeout</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.idle_timeout" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies an idle timeout in seconds. This setting specifies the number of seconds that a connection is idle before the connection is eligible for deletion.When you specify an idle timeout for the Fast L4 profile, the value must be greater than the bigdb database variable Pva.Scrub time in msec for it to work properly.The default value is 300 seconds.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.maxheader_size">
<code class="descname">maxheader_size</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.maxheader_size" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the maximum amount of HTTP header data that the system buffers before making a load balancing decision. The default setting is 32768.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the profile_fasthttp</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileFastHttp.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastHttp.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">ProfileFastL4</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>client_timeout=None</em>, <em>defaults_from=None</em>, <em>explicitflow_migration=None</em>, <em>hardware_syncookie=None</em>, <em>idle_timeout=None</em>, <em>iptos_toclient=None</em>, <em>iptos_toserver=None</em>, <em>keepalive_interval=None</em>, <em>name=None</em>, <em>partition=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_profile_fastl4</cite> Configures a custom profile_fastl4 for use by health checks.</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>client_timeout</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies late binding client timeout in seconds. This setting specifies the number of seconds allowed for a client to transmit enough data to select a server when late binding is enabled. If it expires timeout-recovery mode will dictate what action to take.</li>
<li><strong>defaults_from</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</li>
<li><strong>explicitflow_migration</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Enables or disables late binding explicit flow migration that allows iRules to control when flows move from software to hardware. Explicit flow migration is disabled by default hence BIG-IP automatically migrates flows from software to hardware.</li>
<li><strong>hardware_syncookie</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Enables or disables hardware SYN cookie support when PVA10 is present on the system. Note that when you set the hardware syncookie option to enabled, you may also want to set the following bigdb database variables using the “/sys modify db” command, based on your requirements: pva.SynCookies.Full.ConnectionThreshold (default: 500000), pva.SynCookies.Assist.ConnectionThreshold (default: 500000) pva.SynCookies.ClientWindow (default: 0). The default value is disabled.</li>
<li><strong>idle_timeout</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies an idle timeout in seconds. This setting specifies the number of seconds that a connection is idle before the connection is eligible for deletion.When you specify an idle timeout for the Fast L4 profile, the value must be greater than the bigdb database variable Pva.Scrub time in msec for it to work properly.The default value is 300 seconds.</li>
<li><strong>iptos_toclient</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies an IP ToS number for the client side. This option specifies the Type of Service level that the traffic management system assigns to IP packets when sending them to clients. The default value is 65535 (pass-through), which indicates, do not modify.</li>
<li><strong>iptos_toserver</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies an IP ToS number for the server side. This setting specifies the Type of Service level that the traffic management system assigns to IP packets when sending them to servers. The default value is 65535 (pass-through), which indicates, do not modify.</li>
<li><strong>keepalive_interval</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the keep alive probe interval, in seconds. The default value is disabled (0 seconds).</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the profile_fastl4</li>
<li><strong>partition</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Displays the administrative partition within which this profile resides</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.client_timeout">
<code class="descname">client_timeout</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.client_timeout" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies late binding client timeout in seconds. This setting specifies the number of seconds allowed for a client to transmit enough data to select a server when late binding is enabled. If it expires timeout-recovery mode will dictate what action to take.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.defaults_from">
<code class="descname">defaults_from</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.defaults_from" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.explicitflow_migration">
<code class="descname">explicitflow_migration</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.explicitflow_migration" title="Permalink to this definition">¶</a></dt>
<dd><p>Enables or disables late binding explicit flow migration that allows iRules to control when flows move from software to hardware. Explicit flow migration is disabled by default hence BIG-IP automatically migrates flows from software to hardware.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.hardware_syncookie">
<code class="descname">hardware_syncookie</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.hardware_syncookie" title="Permalink to this definition">¶</a></dt>
<dd><p>Enables or disables hardware SYN cookie support when PVA10 is present on the system. Note that when you set the hardware syncookie option to enabled, you may also want to set the following bigdb database variables using the “/sys modify db” command, based on your requirements: pva.SynCookies.Full.ConnectionThreshold (default: 500000), pva.SynCookies.Assist.ConnectionThreshold (default: 500000) pva.SynCookies.ClientWindow (default: 0). The default value is disabled.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.idle_timeout">
<code class="descname">idle_timeout</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.idle_timeout" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies an idle timeout in seconds. This setting specifies the number of seconds that a connection is idle before the connection is eligible for deletion.When you specify an idle timeout for the Fast L4 profile, the value must be greater than the bigdb database variable Pva.Scrub time in msec for it to work properly.The default value is 300 seconds.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.iptos_toclient">
<code class="descname">iptos_toclient</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.iptos_toclient" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies an IP ToS number for the client side. This option specifies the Type of Service level that the traffic management system assigns to IP packets when sending them to clients. The default value is 65535 (pass-through), which indicates, do not modify.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.iptos_toserver">
<code class="descname">iptos_toserver</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.iptos_toserver" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies an IP ToS number for the server side. This setting specifies the Type of Service level that the traffic management system assigns to IP packets when sending them to servers. The default value is 65535 (pass-through), which indicates, do not modify.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.keepalive_interval">
<code class="descname">keepalive_interval</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.keepalive_interval" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the keep alive probe interval, in seconds. The default value is disabled (0 seconds).</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the profile_fastl4</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.partition">
<code class="descname">partition</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.partition" title="Permalink to this definition">¶</a></dt>
<dd><p>Displays the administrative partition within which this profile resides</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileFastL4.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileFastL4.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.ProfileHttp2">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">ProfileHttp2</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>activation_modes=None</em>, <em>concurrent_streams_per_connection=None</em>, <em>connection_idle_timeout=None</em>, <em>defaults_from=None</em>, <em>header_table_size=None</em>, <em>name=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttp2" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_profile_http2</cite> Configures a custom profile_http2 for use by health checks.</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>activation_modes</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Specifies what will cause an incoming connection to be handled as a HTTP/2 connection. The default values npn and alpn specify that the TLS next-protocol-negotiation and application-layer-protocol-negotiation extensions will be used.</li>
<li><strong>concurrent_streams_per_connection</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies how many concurrent requests are allowed to be outstanding on a single HTTP/2 connection.</li>
<li><strong>connection_idle_timeout</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the number of seconds that a connection is idle before the connection is eligible for deletion..</li>
<li><strong>defaults_from</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[int] header_table_size
:param pulumi.Input[str] name: Name of the profile_http2</p>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileHttp2.activation_modes">
<code class="descname">activation_modes</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttp2.activation_modes" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies what will cause an incoming connection to be handled as a HTTP/2 connection. The default values npn and alpn specify that the TLS next-protocol-negotiation and application-layer-protocol-negotiation extensions will be used.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileHttp2.concurrent_streams_per_connection">
<code class="descname">concurrent_streams_per_connection</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttp2.concurrent_streams_per_connection" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies how many concurrent requests are allowed to be outstanding on a single HTTP/2 connection.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileHttp2.connection_idle_timeout">
<code class="descname">connection_idle_timeout</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttp2.connection_idle_timeout" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the number of seconds that a connection is idle before the connection is eligible for deletion..</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileHttp2.defaults_from">
<code class="descname">defaults_from</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttp2.defaults_from" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileHttp2.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttp2.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the profile_http2</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileHttp2.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttp2.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileHttp2.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttp2.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.ProfileHttpCompress">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">ProfileHttpCompress</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>defaults_from=None</em>, <em>name=None</em>, <em>uri_excludes=None</em>, <em>uri_includes=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttpCompress" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_profile_httpcompress</cite>  Virtual server HTTP compression profile configuration</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>defaults_from</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the profile_httpcompress</li>
<li><strong>uri_excludes</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Disables compression on a specified list of HTTP Request-URI responses. Use a regular expression to specify a list of URIs you do not want to compress.</li>
<li><strong>uri_includes</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Enables compression on a specified list of HTTP Request-URI responses. Use a regular expression to specify a list of URIs you want to compress.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileHttpCompress.defaults_from">
<code class="descname">defaults_from</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttpCompress.defaults_from" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileHttpCompress.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttpCompress.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the profile_httpcompress</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileHttpCompress.uri_excludes">
<code class="descname">uri_excludes</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttpCompress.uri_excludes" title="Permalink to this definition">¶</a></dt>
<dd><p>Disables compression on a specified list of HTTP Request-URI responses. Use a regular expression to specify a list of URIs you do not want to compress.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileHttpCompress.uri_includes">
<code class="descname">uri_includes</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttpCompress.uri_includes" title="Permalink to this definition">¶</a></dt>
<dd><p>Enables compression on a specified list of HTTP Request-URI responses. Use a regular expression to specify a list of URIs you want to compress.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileHttpCompress.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttpCompress.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileHttpCompress.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileHttpCompress.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">ProfileOneConnect</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>defaults_from=None</em>, <em>idle_timeout_override=None</em>, <em>max_age=None</em>, <em>max_reuse=None</em>, <em>max_size=None</em>, <em>name=None</em>, <em>partition=None</em>, <em>share_pools=None</em>, <em>source_mask=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_profile_oneconnect</cite> Configures a custom profile_oneconnect for use by health checks.</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>defaults_from</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</li>
<li><strong>idle_timeout_override</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the number of seconds that a connection is idle before the connection flow is eligible for deletion. Possible values are disabled, indefinite, or a numeric value that you specify. The default value is disabled.</li>
<li><strong>max_age</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the maximum age in number of seconds allowed for a connection in the connection reuse pool. For any connection with an age higher than this value, the system removes that connection from the reuse pool. The default value is 86400.</li>
<li><strong>max_reuse</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the maximum number of times that a server-side connection can be reused. The default value is 1000.</li>
<li><strong>max_size</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the maximum number of connections that the system holds in the connection reuse pool. If the pool is already full, then the server-side connection closes after the response is completed. The default value is 10000.</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the profile_oneconnect</li>
<li><strong>partition</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Displays the administrative partition within which this profile resides</li>
<li><strong>share_pools</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specify if you want to share the pool, default value is “disabled”</li>
<li><strong>source_mask</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies a source IP mask. The default value is 0.0.0.0. The system applies the value of this option to the source address to determine its eligibility for reuse. A mask of 0.0.0.0 causes the system to share reused connections across all clients. A host mask (all 1’s in binary), causes the system to share only those reused connections originating from the same client IP address.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect.defaults_from">
<code class="descname">defaults_from</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect.defaults_from" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect.idle_timeout_override">
<code class="descname">idle_timeout_override</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect.idle_timeout_override" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the number of seconds that a connection is idle before the connection flow is eligible for deletion. Possible values are disabled, indefinite, or a numeric value that you specify. The default value is disabled.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect.max_age">
<code class="descname">max_age</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect.max_age" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the maximum age in number of seconds allowed for a connection in the connection reuse pool. For any connection with an age higher than this value, the system removes that connection from the reuse pool. The default value is 86400.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect.max_reuse">
<code class="descname">max_reuse</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect.max_reuse" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the maximum number of times that a server-side connection can be reused. The default value is 1000.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect.max_size">
<code class="descname">max_size</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect.max_size" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the maximum number of connections that the system holds in the connection reuse pool. If the pool is already full, then the server-side connection closes after the response is completed. The default value is 10000.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the profile_oneconnect</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect.partition">
<code class="descname">partition</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect.partition" title="Permalink to this definition">¶</a></dt>
<dd><p>Displays the administrative partition within which this profile resides</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect.share_pools">
<code class="descname">share_pools</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect.share_pools" title="Permalink to this definition">¶</a></dt>
<dd><p>Specify if you want to share the pool, default value is “disabled”</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect.source_mask">
<code class="descname">source_mask</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect.source_mask" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies a source IP mask. The default value is 0.0.0.0. The system applies the value of this option to the source address to determine its eligibility for reuse. A mask of 0.0.0.0 causes the system to share reused connections across all clients. A host mask (all 1’s in binary), causes the system to share only those reused connections originating from the same client IP address.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileOneConnect.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileOneConnect.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.ProfileTcp">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">ProfileTcp</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>close_wait_timeout=None</em>, <em>defaults_from=None</em>, <em>deferred_accept=None</em>, <em>fast_open=None</em>, <em>finwait2timeout=None</em>, <em>finwait_timeout=None</em>, <em>idle_timeout=None</em>, <em>keepalive_interval=None</em>, <em>name=None</em>, <em>partition=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_profile_tcp</cite> Configures a custom profile_tcp for use by health checks.</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>close_wait_timeout</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the number of seconds that a connection remains in a LAST-ACK state before quitting. A value of 0 represents a term of forever (or until the maxrtx of the FIN state). The default value is 5 seconds.</li>
<li><strong>defaults_from</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</li>
<li><strong>deferred_accept</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies, when enabled, that the system defers allocation of the connection chain context until the client response is received. This option is useful for dealing with 3-way handshake DOS attacks. The default value is disabled.</li>
<li><strong>fast_open</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – When enabled, permits TCP Fast Open, allowing properly equipped TCP clients to send data with the SYN packet.</li>
<li><strong>finwait2timeout</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the number of seconds that a connection is in the FIN-WAIT-2 state before quitting. The default value is 300 seconds. A value of 0 (zero) represents a term of forever (or until the maxrtx of the FIN state).</li>
<li><strong>finwait_timeout</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the number of seconds that a connection is in the FIN-WAIT-1 or closing state before quitting. The default value is 5 seconds. A value of 0 (zero) represents a term of forever (or until the maxrtx of the FIN state). You can also specify immediate or indefinite.</li>
<li><strong>idle_timeout</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the number of seconds that a connection is idle before the connection is eligible for deletion. The default value is 300 seconds.</li>
<li><strong>keepalive_interval</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Specifies the keep alive probe interval, in seconds. The default value is 1800 seconds.</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the profile_tcp</li>
<li><strong>partition</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Displays the administrative partition within which this profile resides</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.close_wait_timeout">
<code class="descname">close_wait_timeout</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.close_wait_timeout" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the number of seconds that a connection remains in a LAST-ACK state before quitting. A value of 0 represents a term of forever (or until the maxrtx of the FIN state). The default value is 5 seconds.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.defaults_from">
<code class="descname">defaults_from</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.defaults_from" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the profile that you want to use as the parent profile. Your new profile inherits all settings and values from the parent profile specified.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.deferred_accept">
<code class="descname">deferred_accept</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.deferred_accept" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies, when enabled, that the system defers allocation of the connection chain context until the client response is received. This option is useful for dealing with 3-way handshake DOS attacks. The default value is disabled.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.fast_open">
<code class="descname">fast_open</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.fast_open" title="Permalink to this definition">¶</a></dt>
<dd><p>When enabled, permits TCP Fast Open, allowing properly equipped TCP clients to send data with the SYN packet.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.finwait2timeout">
<code class="descname">finwait2timeout</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.finwait2timeout" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the number of seconds that a connection is in the FIN-WAIT-2 state before quitting. The default value is 300 seconds. A value of 0 (zero) represents a term of forever (or until the maxrtx of the FIN state).</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.finwait_timeout">
<code class="descname">finwait_timeout</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.finwait_timeout" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the number of seconds that a connection is in the FIN-WAIT-1 or closing state before quitting. The default value is 5 seconds. A value of 0 (zero) represents a term of forever (or until the maxrtx of the FIN state). You can also specify immediate or indefinite.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.idle_timeout">
<code class="descname">idle_timeout</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.idle_timeout" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the number of seconds that a connection is idle before the connection is eligible for deletion. The default value is 300 seconds.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.keepalive_interval">
<code class="descname">keepalive_interval</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.keepalive_interval" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the keep alive probe interval, in seconds. The default value is 1800 seconds.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the profile_tcp</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.partition">
<code class="descname">partition</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.partition" title="Permalink to this definition">¶</a></dt>
<dd><p>Displays the administrative partition within which this profile resides</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.ProfileTcp.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.ProfileTcp.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.Snat">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">Snat</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>autolasthop=None</em>, <em>full_path=None</em>, <em>mirror=None</em>, <em>name=None</em>, <em>origins=None</em>, <em>partition=None</em>, <em>snatpool=None</em>, <em>sourceport=None</em>, <em>translation=None</em>, <em>vlansdisabled=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Snat" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_snat</cite> Manages a snat configuration</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[str] autolasthop
:param pulumi.Input[str] full_path
:param pulumi.Input[str] mirror: Enables or disables mirroring of SNAT connections.
:param pulumi.Input[str] name: Name of the snat
:param pulumi.Input[list] origins: IP or hostname of the snat
:param pulumi.Input[str] partition: Displays the administrative partition within which this profile resides
:param pulumi.Input[str] snatpool: Specifies the name of a SNAT pool. You can only use this option when automap and translation are not used.
:param pulumi.Input[str] sourceport: Specifies whether the system preserves the source port of the connection. The default is preserve. Use of the preserve-strict setting should be restricted to UDP only under very special circumstances such as nPath or transparent (that is, no translation of any other L3/L4 field), where there is a 1:1 relationship between virtual IP addresses and node addresses, or when clustered multi-processing (CMP) is disabled. The change setting is useful for obfuscating internal network addresses.
:param pulumi.Input[str] translation: Specifies the name of a translated IP address. Note that translated addresses are outside the traffic management system. You can only use this option when automap and snatpool are not used.
:param pulumi.Input[bool] vlansdisabled: Disables the SNAT on all VLANs.</p>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Snat.mirror">
<code class="descname">mirror</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Snat.mirror" title="Permalink to this definition">¶</a></dt>
<dd><p>Enables or disables mirroring of SNAT connections.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Snat.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Snat.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the snat</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Snat.origins">
<code class="descname">origins</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Snat.origins" title="Permalink to this definition">¶</a></dt>
<dd><p>IP or hostname of the snat</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Snat.partition">
<code class="descname">partition</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Snat.partition" title="Permalink to this definition">¶</a></dt>
<dd><p>Displays the administrative partition within which this profile resides</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Snat.snatpool">
<code class="descname">snatpool</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Snat.snatpool" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the name of a SNAT pool. You can only use this option when automap and translation are not used.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Snat.sourceport">
<code class="descname">sourceport</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Snat.sourceport" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies whether the system preserves the source port of the connection. The default is preserve. Use of the preserve-strict setting should be restricted to UDP only under very special circumstances such as nPath or transparent (that is, no translation of any other L3/L4 field), where there is a 1:1 relationship between virtual IP addresses and node addresses, or when clustered multi-processing (CMP) is disabled. The change setting is useful for obfuscating internal network addresses.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Snat.translation">
<code class="descname">translation</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Snat.translation" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the name of a translated IP address. Note that translated addresses are outside the traffic management system. You can only use this option when automap and snatpool are not used.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.Snat.vlansdisabled">
<code class="descname">vlansdisabled</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.Snat.vlansdisabled" title="Permalink to this definition">¶</a></dt>
<dd><p>Disables the SNAT on all VLANs.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.Snat.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Snat.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.Snat.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.Snat.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.SnatPool">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">SnatPool</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>members=None</em>, <em>name=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.SnatPool" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_snatpool</cite> Collections of SNAT translation addresses</p>
<p>Resource should be named with their “full path”. The full path is the combination of the partition + name of the resource, for example /Common/my-snatpool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>members</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – Specifies a translation address to add to or delete from a SNAT pool (at least one address is required)</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the snatpool</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.SnatPool.members">
<code class="descname">members</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.SnatPool.members" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies a translation address to add to or delete from a SNAT pool (at least one address is required)</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.SnatPool.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.SnatPool.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the snatpool</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.SnatPool.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.SnatPool.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.SnatPool.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.SnatPool.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.VirtualAddress">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">VirtualAddress</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>advertize_route=None</em>, <em>arp=None</em>, <em>auto_delete=None</em>, <em>conn_limit=None</em>, <em>enabled=None</em>, <em>icmp_echo=None</em>, <em>name=None</em>, <em>traffic_group=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualAddress" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_virtual_address</cite> Configures Virtual Server</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>advertize_route</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Enabled dynamic routing of the address</li>
<li><strong>arp</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Enable or disable ARP for the virtual address</li>
<li><strong>auto_delete</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Automatically delete the virtual address with the virtual server</li>
<li><strong>conn_limit</strong> (<em>pulumi.Input</em><em>[</em><em>int</em><em>]</em>) – Max number of connections for virtual address</li>
<li><strong>enabled</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Enable or disable the virtual address</li>
<li><strong>icmp_echo</strong> (<em>pulumi.Input</em><em>[</em><em>bool</em><em>]</em>) – Enable/Disable ICMP response to the virtual address</li>
<li><strong>name</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Name of the virtual address</li>
<li><strong>traffic_group</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specify the partition and traffic group</li>
</ul>
</td>
</tr>
</tbody>
</table>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualAddress.advertize_route">
<code class="descname">advertize_route</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualAddress.advertize_route" title="Permalink to this definition">¶</a></dt>
<dd><p>Enabled dynamic routing of the address</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualAddress.arp">
<code class="descname">arp</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualAddress.arp" title="Permalink to this definition">¶</a></dt>
<dd><p>Enable or disable ARP for the virtual address</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualAddress.auto_delete">
<code class="descname">auto_delete</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualAddress.auto_delete" title="Permalink to this definition">¶</a></dt>
<dd><p>Automatically delete the virtual address with the virtual server</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualAddress.conn_limit">
<code class="descname">conn_limit</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualAddress.conn_limit" title="Permalink to this definition">¶</a></dt>
<dd><p>Max number of connections for virtual address</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualAddress.enabled">
<code class="descname">enabled</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualAddress.enabled" title="Permalink to this definition">¶</a></dt>
<dd><p>Enable or disable the virtual address</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualAddress.icmp_echo">
<code class="descname">icmp_echo</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualAddress.icmp_echo" title="Permalink to this definition">¶</a></dt>
<dd><p>Enable/Disable ICMP response to the virtual address</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualAddress.name">
<code class="descname">name</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualAddress.name" title="Permalink to this definition">¶</a></dt>
<dd><p>Name of the virtual address</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualAddress.traffic_group">
<code class="descname">traffic_group</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualAddress.traffic_group" title="Permalink to this definition">¶</a></dt>
<dd><p>Specify the partition and traffic group</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.VirtualAddress.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualAddress.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.VirtualAddress.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualAddress.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

<dl class="class">
<dt id="pulumi_f5bigip.ltm.VirtualServer">
<em class="property">class </em><code class="descclassname">pulumi_f5bigip.ltm.</code><code class="descname">VirtualServer</code><span class="sig-paren">(</span><em>__name__</em>, <em>__opts__=None</em>, <em>client_profiles=None</em>, <em>destination=None</em>, <em>fallback_persistence_profile=None</em>, <em>ip_protocol=None</em>, <em>irules=None</em>, <em>mask=None</em>, <em>name=None</em>, <em>persistence_profiles=None</em>, <em>policies=None</em>, <em>pool=None</em>, <em>port=None</em>, <em>profiles=None</em>, <em>server_profiles=None</em>, <em>snatpool=None</em>, <em>source=None</em>, <em>source_address_translation=None</em>, <em>translate_address=None</em>, <em>translate_port=None</em>, <em>vlans=None</em>, <em>vlans_enabled=None</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer" title="Permalink to this definition">¶</a></dt>
<dd><p><cite>bigip_ltm_virtual_server</cite> Configures Virtual Server</p>
<p>For resources should be named with their “full path”. The full path is the combination of the partition + name of the resource. For example /Common/my-pool.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><ul class="first last simple">
<li><strong>__name__</strong> (<em>str</em>) – The name of the resource.</li>
<li><strong>__opts__</strong> (<a class="reference internal" href="../../pulumi/#pulumi.ResourceOptions" title="pulumi.ResourceOptions"><em>pulumi.ResourceOptions</em></a>) – Options for the resource.</li>
<li><strong>client_profiles</strong> (<em>pulumi.Input</em><em>[</em><em>list</em><em>]</em>) – List of client context profiles associated on the virtual server. Not mutually exclusive with profiles and server_profiles</li>
<li><strong>destination</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Destination IP</li>
<li><strong>fallback_persistence_profile</strong> (<em>pulumi.Input</em><em>[</em><em>str</em><em>]</em>) – Specifies a fallback persistence profile for the Virtual Server to use when the default persistence profile is not available.</li>
</ul>
</td>
</tr>
</tbody>
</table>
<p>:param pulumi.Input[str] ip_protocol
:param pulumi.Input[list] irules
:param pulumi.Input[str] mask: Mask can either be in CIDR notation or decimal, i.e.: 24 or 255.255.255.0. A CIDR mask of 0 is the same as 0.0.0.0
:param pulumi.Input[str] name
:param pulumi.Input[list] persistence_profiles: List of persistence profiles associated with the Virtual Server.
:param pulumi.Input[list] policies
:param pulumi.Input[str] pool: Default pool name
:param pulumi.Input[int] port: Listen port for the virtual server
:param pulumi.Input[list] profiles: List of profiles associated both client and server contexts on the virtual server. This includes protocol, ssl, http, etc.
:param pulumi.Input[list] server_profiles: List of server context profiles associated on the virtual server. Not mutually exclusive with profiles and client_profiles
:param pulumi.Input[str] snatpool: Specifies the name of an existing SNAT pool that you want the virtual server to use to implement selective and intelligent SNATs. DEPRECATED - see Virtual Server Property Groups source-address-translation
:param pulumi.Input[str] source: Specifies an IP address or network from which the virtual server will accept traffic.
:param pulumi.Input[str] source_address_translation: Can be either omitted for none or the values automap or snat
:param pulumi.Input[str] translate_address: Enables or disables address translation for the virtual server. Turn address translation off for a virtual server if you want to use the virtual server to load balance connections to any address. This option is useful when the system is load balancing devices that have the same IP address.
:param pulumi.Input[str] translate_port: Enables or disables port translation. Turn port translation off for a virtual server if you want to use the virtual server to load balance connections to any service
:param pulumi.Input[list] vlans: The virtual server is enabled/disabled on this set of VLANs. See vlans-disabled and vlans-enabled.
:param pulumi.Input[bool] vlans_enabled: Enables the virtual server on the VLANs specified by the VLANs option.</p>
<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.client_profiles">
<code class="descname">client_profiles</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.client_profiles" title="Permalink to this definition">¶</a></dt>
<dd><p>List of client context profiles associated on the virtual server. Not mutually exclusive with profiles and server_profiles</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.destination">
<code class="descname">destination</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.destination" title="Permalink to this definition">¶</a></dt>
<dd><p>Destination IP</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.fallback_persistence_profile">
<code class="descname">fallback_persistence_profile</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.fallback_persistence_profile" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies a fallback persistence profile for the Virtual Server to use when the default persistence profile is not available.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.mask">
<code class="descname">mask</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.mask" title="Permalink to this definition">¶</a></dt>
<dd><p>Mask can either be in CIDR notation or decimal, i.e.: 24 or 255.255.255.0. A CIDR mask of 0 is the same as 0.0.0.0</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.persistence_profiles">
<code class="descname">persistence_profiles</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.persistence_profiles" title="Permalink to this definition">¶</a></dt>
<dd><p>List of persistence profiles associated with the Virtual Server.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.pool">
<code class="descname">pool</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.pool" title="Permalink to this definition">¶</a></dt>
<dd><p>Default pool name</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.port">
<code class="descname">port</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.port" title="Permalink to this definition">¶</a></dt>
<dd><p>Listen port for the virtual server</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.profiles">
<code class="descname">profiles</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.profiles" title="Permalink to this definition">¶</a></dt>
<dd><p>List of profiles associated both client and server contexts on the virtual server. This includes protocol, ssl, http, etc.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.server_profiles">
<code class="descname">server_profiles</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.server_profiles" title="Permalink to this definition">¶</a></dt>
<dd><p>List of server context profiles associated on the virtual server. Not mutually exclusive with profiles and client_profiles</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.snatpool">
<code class="descname">snatpool</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.snatpool" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies the name of an existing SNAT pool that you want the virtual server to use to implement selective and intelligent SNATs. DEPRECATED - see Virtual Server Property Groups source-address-translation</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.source">
<code class="descname">source</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.source" title="Permalink to this definition">¶</a></dt>
<dd><p>Specifies an IP address or network from which the virtual server will accept traffic.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.source_address_translation">
<code class="descname">source_address_translation</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.source_address_translation" title="Permalink to this definition">¶</a></dt>
<dd><p>Can be either omitted for none or the values automap or snat</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.translate_address">
<code class="descname">translate_address</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.translate_address" title="Permalink to this definition">¶</a></dt>
<dd><p>Enables or disables address translation for the virtual server. Turn address translation off for a virtual server if you want to use the virtual server to load balance connections to any address. This option is useful when the system is load balancing devices that have the same IP address.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.translate_port">
<code class="descname">translate_port</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.translate_port" title="Permalink to this definition">¶</a></dt>
<dd><p>Enables or disables port translation. Turn port translation off for a virtual server if you want to use the virtual server to load balance connections to any service</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.vlans">
<code class="descname">vlans</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.vlans" title="Permalink to this definition">¶</a></dt>
<dd><p>The virtual server is enabled/disabled on this set of VLANs. See vlans-disabled and vlans-enabled.</p>
</dd></dl>

<dl class="attribute">
<dt id="pulumi_f5bigip.ltm.VirtualServer.vlans_enabled">
<code class="descname">vlans_enabled</code><em class="property"> = None</em><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.vlans_enabled" title="Permalink to this definition">¶</a></dt>
<dd><p>Enables the virtual server on the VLANs specified by the VLANs option.</p>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.VirtualServer.translate_output_property">
<code class="descname">translate_output_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.translate_output_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of output properties
into a format of their choosing before writing those properties to the resource object.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

<dl class="method">
<dt id="pulumi_f5bigip.ltm.VirtualServer.translate_input_property">
<code class="descname">translate_input_property</code><span class="sig-paren">(</span><em>prop</em><span class="sig-paren">)</span><a class="headerlink" href="#pulumi_f5bigip.ltm.VirtualServer.translate_input_property" title="Permalink to this definition">¶</a></dt>
<dd><p>Provides subclasses of Resource an opportunity to translate names of input properties into
a format of their choosing before sending those properties to the Pulumi engine.</p>
<table class="docutils field-list" frame="void" rules="none">
<col class="field-name" />
<col class="field-body" />
<tbody valign="top">
<tr class="field-odd field"><th class="field-name">Parameters:</th><td class="field-body"><strong>prop</strong> (<em>str</em>) – A property name.</td>
</tr>
<tr class="field-even field"><th class="field-name">Returns:</th><td class="field-body">A potentially transformed property name.</td>
</tr>
<tr class="field-odd field"><th class="field-name">Return type:</th><td class="field-body">str</td>
</tr>
</tbody>
</table>
</dd></dl>

</dd></dl>

</div>
