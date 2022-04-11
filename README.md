# footballartifactsdb
Database of football cards

Database Schema
team
=================
id
name
create_date
modified_date
PK_team_id

artifact_type
=================
id
name
create_date
modified_date
PK_artifact_type_id

artifact
=================
id
team_id
artifact_type_id
create_date
modified_date
PK_artifact_id
FK_team_id
FK_artifact_type_id

artifact_feature
=================
id
artifact_id
description
image_link
create_date
modified_date
PK_artifact_feature_id
FK_artifact_id
