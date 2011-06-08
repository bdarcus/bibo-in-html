# Introduction

This page includes some examples of the BIBO RDF vocabulary embedded in HTML markup.

# Examples

## Scholarly Article

```html
<div class="reference" about="http://dx.doi.org/10.1134/S0003683806040089" typeOf="bibo:AcademicArticle">
  <span property="dc:creator">
    <span property="foaf:name">I.K. Kurdish</span>
  </span> and 
  <span property="dc:creator">
    <span property="foaf:name">Z.T. Bega</span>
  </span>
  <span property="dc:issued">2006</span>
  <span property="dc:title">Effect of argillaceous minerals on the growth of phosphate-mobilizing 
     bacteria Bacillus subtilis</span>
  <span property="bibo:volume">42</span>
  <span property="bibo:issue">4</span>
  <span property="bibo:pageStart">388</span>-<span property="bibo:pageEnd">391</span>
  <span property="bibo:doi">10.1134/S0003683806040089</span>
</div>
```

## Book

```html
<div class="reference" about="http://example.org/2" typeOf="bibo:Book">
  <span property="dc:title"></span>
</div>
```

## Chapter

```html
<div class="reference" about="http://example.org/3" typeOf="bibo:BookSection">
  <span property="dc:title"></span>
</div>
```

## Newspaper Article

```html
<div class="reference" about="http://example.org/4" typeOf="bibo:Article">
  <span property="dc:title"></span>
</div>
```

## Legal Case

```html
<div class="reference" about="http://example.org/5" typeOf="bibo:LegalCaseDocument">
  <span property="dc:title"></span>
</div>
```

