- [ ] Windows, macOS, `manylinux`
    - [ ] Send a pull request to `pyca/infra` updating the [version and hash](https://github.com/pyca/infra/blob/main/cryptography-linux/openssl-version.sh)
    - [ ] Wait for it to be merged
    - [ ] Wait for the Github Actions job to complete
- [ ] Changelog entry
- [ ] Release
- [ ] File Github Security Advisory indicating which releases are impacted (if OpenSSL release is fixing a vulnerability)
- [ ] Send announcement to mailing lists
- [ ] Forward port changelog entry (if releasing from release branch)
