<div id="readme" class="Box-body readme blob js-code-block-container">
<article class="markdown-body entry-content p-3 p-md-6" itemprop="text">
<p align="right">
<a href="https://github.com/fpgasystems/hacc/blob/main/cli/docs/sgutil-program.md#sgutil-program">Back to sgutil program</a>
</p>

## sgutil program rescan

<code>sgutil program rescan [flags] [--help]</code>
<p>
  &nbsp; &nbsp; Runs the PCI hot-plug process.
</p>

### Flags
<code>-s, --serial <string></code>
<p>
  &nbsp; &nbsp; FPGA's serial number. See <a href="https://github.com/fpgasystems/hacc/blob/main/cli/docs/sgutil-get-serial.md">sgutil get serial</a>.
</p>

<code>-h, --help <string></code>
<p>
  &nbsp; &nbsp; Help to use this command.
</p>

### Examples
```
$ sgutil program rescan -h
$ sgutil program rescan 
```