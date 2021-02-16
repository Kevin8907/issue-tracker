---
name: perfomance issue
about: Kite is making my Vim editor typing slow
title: 'Perfomance'
labels: ''
assignees: ''

---

**Required Information**
Applicatuions Logs: https://s3.console.aws.amazon.com/s3/object/kite-client-logs/prod/680966/kite_local/client.log.2021-02-15_06-34-39-PM.bak.gz
Resource Usage Logs: https://s3.console.aws.amazon.com/s3/object/kite-client-capture/prod/680966/kite_local/1613435685522586100/capture.gz

**Describe the bug**
When I write with the Kite autocomplete, i look that typing for example: "#include <iostream>" I'm late more than Kite is disable.
what I normally do is open a .cpp document and then write the libraries but I notice that the letters are frozen for a few milliseconds and then Kite appears with autocompletion

