![Device Changelog](https://i.imgur.com/b3fzqwG.jpg)

### Project Elixir for POCO F2 Pro (lmi) Changelogs

### v3.6 POCO F2 Pro (lmi)

- Revert "Don't force enable ims features"
- revert "rootdir: Set proper cpusets for kona"
- Decrease launch boost to 3sec
- overlay: switch SystemUI to SystemUIGoogle
- input: focaltech_spi: Require low latency
- input: focaltech_spi: Optimize interrupt CPU usage
- clk: qcom: mdss: Fix tons of memory leaks
- binder: Revert some 4.19-stable upstreams that seems increase drains
- qcacld-3.0: Remove pm_qos usage
- qcacld-3.0: Free a bunch of pkts at once
- qcacld-3.0: Do not allow any wakelocks to be held
- Selinux is Enforcing
- Build is decrypted
- CTS passes and banking apps working

### Important Note
- This update maybe needs clean flash
