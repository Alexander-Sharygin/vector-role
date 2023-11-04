# Ansible Role: Vector
## Description

Deploy [Vector](https://vector.dev/docs/about/what-is-vector/) high-performance observability data pipeline.

## Requirements

- Ansible >= 2.7 (It might work on previous versions, but we cannot guarantee it)

## Role Variables

All variables which can be overridden are stored in [defaults/main.yml](defaults/main.yml) file as well as in table below.

| Name                   | Default Value    | Description                                 |
|------------------------|------------------|---------------------------------------------|
| `vector_version:`      | "0.32.1"         | Vector version.                             |
| `vector_conf_dest`     | "/etc/vector/vector.toml" | Path for deploying the vector configuration. |
