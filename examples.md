# Introduction

This page includes some examples of the BIBO RDF vocabulary embedded in HTML markup using RDFa 1.1.

# Profile Attribute

These examples use RDFa 1.1 profile prefix mapping. Note that the profile URI will change:

```html
<!DOCTYPE html>
<html version="HTML+RDFa 1.1" lang="en"
xmlns="http://www.w3.org/1999/xhtml">
  <head>
    <title>Example Document</title>
  </head>
  <body profile="http://example.org/profile/bibo/">
```

# Examples

## Scholarly Article

```html
<div class="reference" about="http://dx.doi.org/10.1134/S0003683806040089" typeOf="AcademicArticle">
  <span property="creator">
    <span property="name">I.K. Kurdish</span>
  </span> and 
  <span property="creator">
    <span property="name">Z.T. Bega</span>
  </span>
  <span property="issued">2006</span>
  <span property="title">Effect of argillaceous minerals on the growth of phosphate-mobilizing 
     bacteria Bacillus subtilis</span>
  <span property="volume">42</span>
  <span property="issue">4</span>
  <span property="pageStart">388</span>-<span property="pageEnd">391</span>
  <span property="doi">10.1134/S0003683806040089</span>
</div>
```

## Book

```html
<div class="reference" about="http://example.org/2" typeOf="Book">
  <span property="title"></span>
</div>
```

## Chapter

```html
<div class="reference" about="http://example.org/3" typeOf="BookSection">
  <span property="title"></span>
</div>
```

## Newspaper Article

```html
<div class="reference" about="http://example.org/4" typeOf="Article">
  <span property="title"></span>
</div>
```

## Legal Case

```html
<div class="reference" about="http://example.org/5" typeOf="bibo:LegalCaseDocument">
  <span property="dc:title"></span>
</div>
```

