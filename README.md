# Kuberploy GitOps qualification repository

Public fixture repository for Kuberploy VM qualification.

Reusable installer values and public Helm source fixtures are retained. Each fresh
qualification starts with empty generated desired-state paths. Kuberploy owns those
paths during a run; operators clean them before tagging the next fresh baseline.
