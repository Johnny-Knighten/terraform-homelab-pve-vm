## [1.3.4](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/1.3.3...1.3.4) (2024-10-23)


### Bug Fixes

* correct dir ssh keys are mounted to ([b5ed1cc](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/b5ed1cc8f683e2b4d91b6dd331c7daa2f67e479b))
* made devcontainer run as non-root and removed extra mount ([60472a1](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/60472a1df8db9d79a3dcdcb42bc9183b8824d018))

## [1.3.3](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/1.3.2...1.3.3) (2024-10-22)


### Bug Fixes

* changed comparison for dynamic ide0 to compare against empty string ([2f06a8a](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/2f06a8a20c1a98942324f7893dff9f9407e38808))

## [1.3.2](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/1.3.1...1.3.2) (2024-10-22)


### Bug Fixes

* made cloudinit drive creation be based on pve_use_cloud_init var ([b9c4ae7](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/b9c4ae72f12a613f2e9c3692d9ef887026b07177))

## [1.3.1](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/1.3.0...1.3.1) (2024-10-21)


### Bug Fixes

* made boot disk var default to null ([213d7cd](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/213d7cd5bb17577da1a779ad395acd8cba4bac99))

## [1.3.0](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/1.2.5...1.3.0) (2024-10-21)


### Features

* added ip and dns outputs ([02ac0a8](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/02ac0a8d10ab9325ad833c9c7294e12c9e75a3e2))

## [1.2.5](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/1.2.4...1.2.5) (2024-10-21)


### Bug Fixes

* corrected startup option default value ([4873231](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/48732318a2b3a0227dc00190771a8b956e19dc5a))

## [1.2.4](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/1.2.3...1.2.4) (2024-10-20)


### Bug Fixes

* added ci vars to fix issues with cloudinit ([a05144a](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/a05144a5c66ef2db69e328ed1465711fd6925102))

## [1.2.3](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/1.2.2...1.2.3) (2024-10-19)


### Bug Fixes

* added cloudinit storage config ([d2cba69](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/d2cba69d2ce409bdecc1332613cd71e82cf3b504))

## [1.2.2](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/1.2.1...1.2.2) (2024-10-19)


### Bug Fixes

* corrected default pve_template value ([143cd64](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/143cd64cdcd18924bfdfc36d051c842ce9d9778f))

## [1.2.1](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/1.2.0...1.2.1) (2024-10-19)


### Bug Fixes

* made ssh key have a blank default ([285acff](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/285acff40e7b449f172ca1e600442409af675e20))

## [1.2.0](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/1.1.0...1.2.0) (2024-10-18)


### Features

* overhaul on pve vm vars ([#2](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/issues/2)) ([581a4f9](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/581a4f9daadb32b225b8dbaf73a834d882566876))

## [1.1.0](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/compare/v1.0.0...1.1.0) (2024-10-17)


### Features

* overhaul and deps update ([#1](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/issues/1)) ([3a45b93](https://github.com/Johnny-Knighten/terraform-homelab-pve-vm/commit/3a45b93c71767fbad2e3b6d84df312c69c5b0d0f))