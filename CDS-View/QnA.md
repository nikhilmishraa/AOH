### What is the difference between CDS View and CDS View Entity?

CDS View Entity is a newer version of CDS View. When we activate CDS View, some additional artifacts are generated such as SQL View, DDIC Object.
These artifacts are not generated for CDS View Entity. Therefore, some annotations have been removed from CDS View Entity.

For e.g.
````ABAP
@AbapCatalog.sqlViewName: ‘Z....’
@AbapCatalog.preserveKey: true

" Syntax -
" CDS View: -
define view Z..... as select from … { ... }

" CDS View Entity: -
define view entity Z..... as select from …. { ... }
````


