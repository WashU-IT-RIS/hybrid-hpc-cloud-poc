# hybrid-hpc-cloud-poc

This is a repository for Hybrid HPC Cloud POC project.

## Directory

Shown below are descriptions of each blueprint directory.

all - All workload experiment blueprints
bolton - Dr. Kelly Bolton’s Lab workload experiment blueprints
holehouse - Dr. Alex Holehouse’s Lab workload experiment blueprints
interactive - Interactive workload experiment blueprints
jin - Dr. Peter Jin’s Lab workload experiment blueprints
mix - Mix workload experiment blueprints
swamidass - Dr. Joshua Swamidass’s Lab workload experiment blueprints
wang - Dr. Jian Wang’s Lab workload experiment blueprints

## Deployment

The deployment is using the Google HPC Toolkit.  Shown below are
step-by-step instructions.

1. Change directory to the directory of a blueprint that you would like to
   deploy.  Shown below is an example command.
   ```bash
   cd jin//infrastructure-blueprint
   ```bash
2. Deploy using `ghpc`.  Shown below is an example command.
   ```bash
   ./ghpc deploy hpc-cloud-poc-jin-regular-vendormanaged-8b.yaml
   ```

## Cleanup

Shown below is an example command to cleanup an infrastructure created using
`ghpc`.

```bash
./ghpc destroy jin-r-vm-8b
```
