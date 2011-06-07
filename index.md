# Introduction

This page includes some examples of the BIBO RDF vocabulary embedded in HTML markup.

# Examples

## Scholarly Article

```html
<div class="reference" about="http://example.org/1" typeOf="bibo:AcademicArticle">
  <span property="dc:issued"></span>
  <span property="dc:title"></span>
  <span property="bibo:volume"></span>
  <span property="bibo:issue"></span>
  <span property="bibo:pages"></span>
  <span property="bibo:doi"></span>
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

