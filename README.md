# gcp_oci_vm_start
## Video
Loom/Zoom:

## Prereqs
- Cloud access to GCP and OCI
- No PHI/PII; smallest/free-tier shapes

## Google Cloud (GCP)
 Create
1. Console → Compute Engine → Create instance
2. Region/zone:
3. Machine type: <smallest available/free-eligible>
4. Image: Ubuntu LTS
5. Boot disk: default minimal
6. Network: default VPC; ephemeral public IP

GCP create

## Start/Stop
Start:
Stop: <state shows TERMINATED/STOPPED>
GCP running

Delete
Delete instance and verify no disks/IPs remain
GCP cleaned

## Oracle Cloud (OCI)
Create

1. Compartment:
2. Networking: VCN with Internet Connectivity (defaults)
3. Shape: <smallest/free-eligible>
4. Image: Ubuntu (or Oracle Linux)
5. Public IP: ephemeral
6. Boot volume: default minimal

OCI create

Start/Stop
Start:
Stop:
OCI running

Terminate
Terminate and delete boot volume; verify cleanup
OCI cleaned

## Reflections

# Similarities
- 

# Differences
- 

# Preference (OCI vs GCP) and Why
- 
