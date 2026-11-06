> [!IMPORTANT]
> **此 repo 已不再維護。** 這個 image 已移到 [swaglive/docker-images](https://github.com/swaglive/docker-images/tree/master/docker-speedtest)，
> 由 GitHub Actions 推到 `asia-docker.pkg.dev/swag-2c052/swaglive/speedtest`，之後的改動請到 docker-images 開 PR。
> 這裡的 publish workflow 已移除，Docker Hub／ghcr.io 上的 `swaglive/speedtest` 不會再更新。
> 目前 docker-images 是直接沿用這裡最後一版 build 出來的 image。原本的建置方式還留在這個 repo，當作參考。（GENP-6287）

* Build and push Docker
  * Supports
    * Github Registry
    * Docker Hub (TODO)
* Utilizes docker layer caching with Github Container Registry
* Creates Github Release on tag push based on semver

# Getting Started
- [ ] Add `Dockerfile`
- [ ] (Optional) Update Github Actions event conditions
