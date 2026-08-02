# privacyassay.github.io

The second origin Privacyassay measures against.

Some of what the tool checks cannot be answered from a single site. Whether storage is partitioned,
whether a value is reshuffled per site, and whether an identifier survives a hop all need two
registrable domains. `github.io` is on the Public Suffix List, so this host is a separate site from
privacyassay.com by the same rule a browser uses.

`index.html` here is byte-identical to the one on privacyassay.com. It is a copy, not a fork: a
direct visit redirects to the main site, and only the machine-readable entry points the audit loads
in a frame are served from here.

Source, issues and method: [seyedehsanhadi/privacyassay](https://github.com/seyedehsanhadi/privacyassay).
