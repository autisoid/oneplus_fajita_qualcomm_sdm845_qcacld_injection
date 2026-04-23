# oneplus_fajita_qualcomm_sdm845_qcacld_injection
(broken) My attempt at making frame injection work on a SDM845-based device, OnePlus 6T (fajita)

Causes a kernel panic whenever anything tries to inject a frame. Giving this on outsource because I'm lacking sufficient skills to debug a kernel panic, :D.

QCACLD 3.0 and qca-wifi-host-cmn were taken from https://github.com/V0lk3n/nethunter_kernel_oneplus_sdm845.

Based on patches from https://github.com/Loukious/android_kernel_xiaomi_sm8150/commit/65c6a05ecd9b25ebf0742d39987c6a8a042227f1, inspired by https://medium.com/h7w/they-said-packet-injection-on-qcacld-3-0-was-impossible-i-proved-them-wrong-588fa55ee702.