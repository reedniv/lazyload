# lazyload


## Description

Simple Lazyload to blogger

### How to use

**insert in your own template** and insert script below :
<pre><code>
<script type='text/javascript'>
/*! Lazyload */
var lazyload=!1;window.addEventListener("scroll",function(){(0!=document.documentElement.scrollTop&&!1===lazyload||0!=document.body.scrollTop&&!1===lazyload)&&(!function(){var e=document.createElement("script");e.type="text/javascript",e.async=!0,e.src="https://cdn.statically.io/gh/reedniv/lazyload/jquery/v.1.0/lazyload.js?cache=31556952";var a=document.getElementsByTagName("script")[0];a.parentNode.insertBefore(e,a)}(),lazyload=!0)},!0);
</script>
</code></pre>
or you can make it self by insert : <pre><code>https://cdn.statically.io/gh/reedniv/lazyload/jquery/v.1.0/lazyload.js</code></pre>
and you can make cache javascript by inserted code after *.js like this **?cache=31556952**

**before :
<pre><code>https://cdn.statically.io/gh/reedniv/lazyload/jquery/v.1.0/lazyload.js</code></pre>
**after :
<pre><code>https://cdn.statically.io/gh/reedniv/lazyload/jquery/v.1.0/lazyload.js?cache=31556952</code></pre>
