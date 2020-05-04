# plpgsql-convention

## convention
### Language comes `after create function`, `before $$`

```plpgsql
CREATE OR REPLACE FUNCTION raw___campaign.upsert_from_ld203_xml(_xml_file_path text)
 RETURNS record
 LANGUAGE plpgsql
 PARALLEL SAFE
AS $function$
```
