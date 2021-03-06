## Instruments

```@docs
ICDataServer.newinstrument
ICDataServer.updateinstrument
ICDataServer.deleteinstrument
ICDataServer.listinstruments
```

## Constraints on the `instruments` table

To enforce consistent conventions in the `instruments` table, there are some
supporting tables that list the allowed values for an associated column in the
`instruments` table.

### `instrumentkinds` table

This table, consisting of one column `kind`, lists the different kinds of
instruments that may be used in a measurement. More values can be added manually
via a database query or via the `instrumentkinds.json` setup file to accommodate
new instrument types.
