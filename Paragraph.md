In HTML paragraph defines with `<p></P>` tag
```html
<p>This is a paragraph . This is a paragraph . </p>
```

output : 
<p>This is a paragraph . This is a paragraph . </p>

### Line braker

In HTML `<br>` tag use for break the line

```HTML
<p>
This is line one. <br>
This is line two. <br>
This is line three. 
</p>
```

output :

This is line one.
This is line two.
This is line three. 

### Horizontal line

In HTML  `<hr>` tag use for create a horizonal line

```HTML
<P> This is a paragraph . </p>
<hr>
<p> This is another paragraph . <p>
```

output : 

This is a paragraph .

---

This is another paragraph .


### The poem problem and `<pre></pre>` tag

If we write a poem with `<p>` tag , the poem gives output as a normal paragraph

```HTML
<p>
Hold fast to dreams  
For if dreams die  
Life is a broken-winged bird  
That cannot fly.  
Hold fast to dreams  
For when dreams go  
Life is a barren field  
Frozen with snow.
</p>
```

output : 
 
<p>
Hold fast to dreams  
For if dreams die  
Life is a broken-winged bird  
That cannot fly.  
Hold fast to dreams  
For when dreams go  
Life is a barren field  
Frozen with snow.
</p>

Now solving the problem with `<pre>` tag

```HTML
<pre>
Hold fast to dreams  
For if dreams die  
Life is a broken-winged bird  
That cannot fly.  
Hold fast to dreams  
For when dreams go  
Life is a barren field  
Frozen with snow.
</pre>
```

output : 

Hold fast to dreams  
For if dreams die  
Life is a broken-winged bird  
That cannot fly.  
Hold fast to dreams  
For when dreams go  
Life is a barren field  
Frozen with snow.

### HTML `<wbr>` Tag

The `<wbr>` (Word Break Opportunity) tag specifies where in a text it would be ok to add a line-break. When a word is too long, the browser might break it at the wrong place.  use the `<wbr>` element to add word break opportunities.

Example :

```HTML
<p>This is a veryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryvery<wbr>longwordthatwillbreakatspecific<wbr>placeswhenthebrowserwindowisresized.</p>
```

Output :
<p>This is a veryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryveryvery<wbr>longwordthatwillbreakatspecific<wbr>placeswhenthebrowserwindowisresized.</p>


