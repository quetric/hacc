<div id="readme" class="Box-body readme blob js-code-block-container">
<article class="markdown-body entry-content p-3 p-md-6" itemprop="text">
<p align="right">
<a href="https://github.com/fpgasystems/hacc/blob/main/cli/docs/sgutil-get.md#sgutil-get">Back to sgutil get</a>
</p>

## sgutil get serial

<code>sgutil get serial [flags] [--help]</code>
<p>
  &nbsp; &nbsp; Retreives FPGA serial number from the server/s.
</p>
<!-- The number of parallel client threads to run is four by default. -->

### Flags
<code>-w, --word <string></code>
<p>
  &nbsp; &nbsp; Filters FPGA serial number according to regexp expression.
</p>

<code>-h, --help <string></code>
<p>
  &nbsp; &nbsp; Help to use this command.
</p>

### Examples
```
$ sgutil get serial
$ sgutil get serial -w u55c-06
```