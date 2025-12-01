# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.2.1](https://github.com/lotusnoir/ansible-system_interfaces/compare/1.2.0...1.2.1) - 2025-11-29

### Commits

- add no changes on run flag to keep idempotence [`953bff4`](https://github.com/lotusnoir/ansible-system_interfaces/commit/953bff4a93173e74adfaadb622ca0b36e95dbea7)

## [1.2.0](https://github.com/lotusnoir/ansible-system_interfaces/compare/1.1.0...1.2.0) - 2025-11-25

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`f707165`](https://github.com/lotusnoir/ansible-system_interfaces/commit/f707165440c8e47cf8818dd73cea22b1aec9553b)

## [1.1.0](https://github.com/lotusnoir/ansible-system_interfaces/compare/1.0.0...1.1.0) - 2025-11-17

### Commits

- update core and molecule [`75041d9`](https://github.com/lotusnoir/ansible-system_interfaces/commit/75041d9484414f1356b345ab039f25cc1211fc11)
- add oraclelinux10 support + lint and core fixes [`15910b2`](https://github.com/lotusnoir/ansible-system_interfaces/commit/15910b26b74625358f4dfd240ab44f918b4f9e3b)

## [1.0.0](https://github.com/lotusnoir/ansible-system_interfaces/compare/0.1.0...1.0.0) - 2025-10-29

### Commits

- add trixie (debian13) support [`3dc724b`](https://github.com/lotusnoir/ansible-system_interfaces/commit/3dc724ba56bc6d5a2e51638e84569b29fbd081f0)
- update core, molecule + gitlab-ci [`a64c140`](https://github.com/lotusnoir/ansible-system_interfaces/commit/a64c140587010382bc0370f822c2f4ba66c957b2)
- replace ipaddr plugin by builtin one [`ccf8424`](https://github.com/lotusnoir/ansible-system_interfaces/commit/ccf84248343259b521c06405542b6561d705ac40)
- fix lint [`c503931`](https://github.com/lotusnoir/ansible-system_interfaces/commit/c503931500399e80301e686007048f3889615ddf)
- fix molecule paralelism and little updates [`0de146d`](https://github.com/lotusnoir/ansible-system_interfaces/commit/0de146d79c2801a1050a1d0e65901a39a16778a9)
- add create of /etc/iproute2/rt_tables if doesnt exist [`2e8e0b7`](https://github.com/lotusnoir/ansible-system_interfaces/commit/2e8e0b7bba2bbc615e549f666b232c99801c761e)
- add support for ubuntu24 [`808ea72`](https://github.com/lotusnoir/ansible-system_interfaces/commit/808ea72930e459d52f95caebeeb4b7fe237b166d)
- add version on molecule play image to maintain support on old release [`d514c3d`](https://github.com/lotusnoir/ansible-system_interfaces/commit/d514c3dba9df4c1cd765c72592f276606bd86f87)
- update molecule [`f8833d1`](https://github.com/lotusnoir/ansible-system_interfaces/commit/f8833d190d89967336c886980648dd73f52b91b4)
- add redhat 9 to default supported distrib [`1117f55`](https://github.com/lotusnoir/ansible-system_interfaces/commit/1117f55e274a9c5d38338da096242fdb9d98fa21)

## 0.1.0 - 2023-09-27

### Commits

- fix variable [`a1f4b27`](https://github.com/lotusnoir/ansible-system_interfaces/commit/a1f4b2796fe3ae4b8d976715a27304b19870d087)
- add condition on template [`14c7fde`](https://github.com/lotusnoir/ansible-system_interfaces/commit/14c7fde4a556322149e769c928030653b07cd04d)
- update vars [`53bac7c`](https://github.com/lotusnoir/ansible-system_interfaces/commit/53bac7c181a5eee2bc6103cad32f02d1b3e15426)
- update vars [`2fc8dd7`](https://github.com/lotusnoir/ansible-system_interfaces/commit/2fc8dd794e4e7d1b76302fd7fd05cd767ca036ce)
- update readme + precommit + include vars [`0421f96`](https://github.com/lotusnoir/ansible-system_interfaces/commit/0421f964bbca99d0029a3d6f028bcb9894f9413e)
- ignore molecule on tests [`611740c`](https://github.com/lotusnoir/ansible-system_interfaces/commit/611740c27ccd3a5770edb68b043b58c996650731)
