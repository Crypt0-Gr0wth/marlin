# 01 — SRS universel et indexation

Marlin separe un SRS universel, dimensionne par des bornes, de l indexation propre a un circuit R1CS.
Cette separation permet de reutiliser une ceremonie pour plusieurs circuits compatibles.
La cle d indexation reste liee a la relation, aux tailles et au schema d engagement.
Une application doit versionner SRS, circuit et cle de verification ensemble.
Universel ne signifie ni illimite ni sans hypothese de confiance.
Source : [`README.md`](https://github.com/arkworks-rs/marlin/blob/master/README.md).

[Suite](02-ahp-et-engagements.md)
