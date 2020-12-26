# camunda_bpm_postgresql
create camunda bmp tables with postgresql 

schema.sql de camundanin postgresql de yaratmaq ucun scriptleri var.
susmaya gore public shemasinda yaradir eger biz ferqli schemada yaratmaq isteyirikse 

properties fileni 

1. camunda.bpm.database.schema-name=grp_bpm
2. camunda.bpm.database.table-prefix=grp_bpm.

setirlerini artiririq
 

CREATE SCHEMA IF NOT EXISTS grp_bpm;

SET search_path TO   grp_bpm;

1. schema.sql file na yuxaridaki setirleri artiririq
