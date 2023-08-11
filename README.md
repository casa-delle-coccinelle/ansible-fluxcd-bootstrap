# ansible-fluxcd-bootstrap

Sample role that does flux bootstrap of a cluster from a Github repo.
As part of the bootstrap role creates a `aws-credentials` ns and deploys `awssm-secret` there to enable ExternalSecretsOperator.
Role is explicitly intended for personal usage (in other words - I don't expect it will work for you).

## Prerequisites
Role expects to be able to run a docker container.

## Parameters
Check [defaults/main.yaml](defaults/main.yaml)

