

# Module scmi_eval #
* [Description](#description)
* [Function Index](#index)
* [Function Details](#functions)


<p>Scheme interpreter expression evaluator</p>.
__Authors:__ Joseph Wayne Norton ([`norton@alum.mit.edu`](mailto:norton@alum.mit.edu)).
<a name="index"></a>

## Function Index ##


<table width="100%" border="1" cellspacing="0" cellpadding="2" summary="function index"><tr><td valign="top"><a href="#default_ccng-1">default_ccng/1</a></td><td></td></tr><tr><td valign="top"><a href="#default_ccok-2">default_ccok/2</a></td><td></td></tr><tr><td valign="top"><a href="#eval-1">eval/1</a></td><td></td></tr><tr><td valign="top"><a href="#eval-2">eval/2</a></td><td></td></tr><tr><td valign="top"><a href="#eval-3">eval/3</a></td><td></td></tr><tr><td valign="top"><a href="#eval-4">eval/4</a></td><td></td></tr><tr><td valign="top"><a href="#exec-1">exec/1</a></td><td></td></tr><tr><td valign="top"><a href="#exec-2">exec/2</a></td><td></td></tr><tr><td valign="top"><a href="#exec-3">exec/3</a></td><td></td></tr><tr><td valign="top"><a href="#exec-4">exec/4</a></td><td></td></tr></table>


<a name="functions"></a>

## Function Details ##

<a name="default_ccng-1"></a>

### default_ccng/1 ###


<pre><code>
default_ccng(Error::<a href="#type-scm_any">scm_any()</a>) -&gt; <a href="#type-scm_any">scm_any()</a>
</code></pre>

<br></br>



<a name="default_ccok-2"></a>

### default_ccok/2 ###


<pre><code>
default_ccok(Value::<a href="#type-scm_any">scm_any()</a>, Ng::<a href="#type-scmi_ccng">scmi_ccng()</a>) -&gt; <a href="#type-scm_any">scm_any()</a>
</code></pre>

<br></br>



<a name="eval-1"></a>

### eval/1 ###


<pre><code>
eval(Exp::<a href="#type-scm_any">scm_any()</a>) -&gt; <a href="#type-scm_any">scm_any()</a>
</code></pre>

<br></br>



<a name="eval-2"></a>

### eval/2 ###


<pre><code>
eval(Exp::<a href="#type-scm_any">scm_any()</a>, Env::<a href="#type-scmi_env">scmi_env()</a>) -&gt; <a href="#type-scm_any">scm_any()</a>
</code></pre>

<br></br>



<a name="eval-3"></a>

### eval/3 ###


<pre><code>
eval(Exp::<a href="#type-scm_any">scm_any()</a>, Env::<a href="#type-scmi_env">scmi_env()</a>, Ok::<a href="#type-scmi_ccok">scmi_ccok()</a>) -&gt; <a href="#type-scm_any">scm_any()</a>
</code></pre>

<br></br>



<a name="eval-4"></a>

### eval/4 ###


<pre><code>
eval(Exp::<a href="#type-scm_any">scm_any()</a>, Env::<a href="#type-scmi_env">scmi_env()</a>, Ok::<a href="#type-scmi_ccok">scmi_ccok()</a>, Ng::<a href="#type-scmi_ccng">scmi_ccng()</a>) -&gt; <a href="#type-scm_any">scm_any()</a>
</code></pre>

<br></br>



<a name="exec-1"></a>

### exec/1 ###


<pre><code>
exec(Exec::<a href="#type-scmi_exec">scmi_exec()</a>) -&gt; <a href="#type-scm_any">scm_any()</a>
</code></pre>

<br></br>



<a name="exec-2"></a>

### exec/2 ###


<pre><code>
exec(Exec::<a href="#type-scmi_exec">scmi_exec()</a>, Env::<a href="#type-scmi_env">scmi_env()</a>) -&gt; <a href="#type-scm_any">scm_any()</a>
</code></pre>

<br></br>



<a name="exec-3"></a>

### exec/3 ###


<pre><code>
exec(Exec::<a href="#type-scmi_exec">scmi_exec()</a>, Env::<a href="#type-scmi_env">scmi_env()</a>, Ok::<a href="#type-scmi_ccok">scmi_ccok()</a>) -&gt; <a href="#type-scm_any">scm_any()</a>
</code></pre>

<br></br>



<a name="exec-4"></a>

### exec/4 ###


<pre><code>
exec(Exec::<a href="#type-scmi_exec">scmi_exec()</a>, Env::<a href="#type-scmi_env">scmi_env()</a>, Ok::<a href="#type-scmi_ccok">scmi_ccok()</a>, Ng::<a href="#type-scmi_ccng">scmi_ccng()</a>) -&gt; <a href="#type-scm_any">scm_any()</a>
</code></pre>

<br></br>



