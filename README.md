activerecord-odbc-adapter-2.0
=============================

Clone of activerecord-odbc-adapter with some organization specific modifications

```
< # -*- coding: utf-8 -*-
676,677c675
<          # idQuoteChar.chr + name + idQuoteChar.chr
< 	  name
---
>           idQuoteChar.chr + name + idQuoteChar.chr
683,684c681
<          # quote_column_name(name)
< 	  name
---
>           quote_column_name(name)
```
