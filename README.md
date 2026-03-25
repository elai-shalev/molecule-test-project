# Molecule Test Project

Minimal Ansible project for validating Molecule testing on AAP/OpenShift.

## Structure

- `roles/molecule_test_role/` — Simple test role that creates a marker file
- `roles/molecule_test_role/molecule/default/` — Molecule scenario (delegated driver, local connection)
- `playbooks/run_molecule_test.yml` — Wrapper playbook to run molecule via AAP Job Template

## Usage

Requires the **Molecule EE** (`quay.io/eshalev/ee-molecule:latest`) execution environment.
