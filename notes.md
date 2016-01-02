## List projects

- Reference: https://cloud.google.com/bigquery/docs/reference/v2/projects/list
- HTTP request: `GET https://www.googleapis.com/bigquery/v2/projects`
- Scope: `https://www.googleapis.com/auth/cloud-platform.read-only`

- Reference: https://cloud.google.com/resource-manager/reference/rest/v1beta1/projects/list
- HTTP request: `GET https://cloudresourcemanager.googleapis.com/v1beta1/projects`
- Scope: `https://www.googleapis.com/auth/cloud-platform.read-only`

## List disks

- Reference: https://cloud.google.com/compute/docs/reference/latest/disks/list
- HTTP request: `GET https://www.googleapis.com/compute/v1/projects/<project>/zones/<zone>/disks`

## Create snapshot

- Reference: https://cloud.google.com/compute/docs/reference/latest/disks/createSnapshot
- HTTP request: `POST https://www.googleapis.com/compute/v1/projects/project/zones/<zone>/disks/<disk>/createSnapshot`

## List zones

- Refrence: https://cloud.google.com/compute/docs/reference/latest/zones/list
- HTTP request: `GET https://www.googleapis.com/compute/v1/projects/<project>/zones`
