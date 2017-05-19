# \<s-moment\>

Polymer element wrapper for the moment library.

Contain behavior that validates date and time input using momentjs and optional locale support.

## Usage

```html
<s-moment></s-moment>
<s-moment datetime="1991-12-31" output-format="MMM DD[,] YYYY"></s-moment>
```

```html
<s-moment-validator date-format="DD/MM/YYYY" validator-name="dateValidator"></s-moment-validator>
<paper-input auto-validate label="Enter a valid date string" validator="dateValidator"></paper-input>
```

```html
<s-moment-validator date-format="L" locale="cs" validator-name="dateValidator2"></s-moment-validator>
<paper-input auto-validate label="Enter a valid czech date (DD.MM.YYYY)" validator="dateValidator2">
```

For specific language you need import locale script.

```html
<link rel="import" href="moment-cs-locale-script.html">
```

## Install

```
bower install s-moment --save
```

## Viewing the Element

```
$ polymer serve --open
```
