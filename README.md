# footballartifactsdb
Database of football cards

Database Schema <br>
<b>team</b><br>
id<br>
name<br>
create_date<br>
modified_date<br>
PK_team_id<br>

<b>artifact_type</b><br>
id<br>
name<br>
create_date<br>
modified_date<br>
PK_artifact_type_id<br>

<b>artifact</b><br>
id<br>
team_id<br>
artifact_type_id<br>
create_date<br>
modified_date<br>
PK_artifact_id<br>
FK_team_id<br>
FK_artifact_type_id<br>

<b>artifact_feature</b><br>
id<br>
artifact_id<br>
description<br>
image_link<br>
create_date<br>
modified_date<br>
PK_artifact_feature_id<br>
FK_artifact_id<br>
