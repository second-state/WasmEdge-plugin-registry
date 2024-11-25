# WasmEdge-plugin-registry
A place to store the pre-built WasmEdge plugins

## Changelog

### 0.14.1-plugin-lts (d259eed)

* Date: 2024-11-21

```
a72a22705e3c1f04d610a7e2dd222a5a884c021c1ed1ce9e632681eeba84223d  WasmEdge-plugin-stable_diffusion-0.14.1-darwin_arm64.tar.gz
f74f526af0765d4ac81130dc5192985f6bf2926b51810253384ba6e086dd834e  WasmEdge-plugin-stable_diffusion-0.14.1-darwin_x86_64.tar.gz
520e66d9e9b227f829b729d913b2ac1afcec7f2df0b3e972f537e72111c10146  WasmEdge-plugin-stable_diffusion-0.14.1-manylinux_2_28_aarch64.tar.gz
2f293395a0562365f3bd8a00fc5a710567bb4136a7cbd1c2d308b05cc27c8e17  WasmEdge-plugin-stable_diffusion-0.14.1-manylinux_2_28_x86_64.tar.gz
35b766d79d5feb6c8cbbb45e7f2cd55e500030d484f43b941724dea86c93a267  WasmEdge-plugin-stable_diffusion-0.14.1-ubuntu20.04_aarch64.tar.gz
1cf7ebd6f695821ed20d8011aaafd2171e007bdf7021143427acf284ec186ff8  WasmEdge-plugin-stable_diffusion-0.14.1-ubuntu20.04_x86_64.tar.gz
ec913884f055cb486257fdf03d4094a38a9ce41fcb474ef7a3caabbb773d1cc9  WasmEdge-plugin-stable_diffusion-cuda-11.3-0.14.1-ubuntu20.04_x86_64.tar.gz
59e02476819cf5c356bef2649a6ebc159f2f7d649f76e373140ad367657833dc  WasmEdge-plugin-stable_diffusion-cuda-12.0-0.14.1-ubuntu20.04_x86_64.tar.gz
a2c5a893ba55eba8c3c9dbb9d395c88a824216d23f0cb1aced86c62742443c86  WasmEdge-plugin-wasi_nn-ggml-0.14.1-darwin_arm64.tar.gz
a2110ae3041f2b87d36646063a91d4f0d38af030bfdb027e5802723abfb82cd0  WasmEdge-plugin-wasi_nn-ggml-0.14.1-darwin_x86_64.tar.gz
649bedb5c5e6b2050e1d33154cbb7413882785cee71f26f885290485992ac8f2  WasmEdge-plugin-wasi_nn-ggml-0.14.1-manylinux_2_28_aarch64.tar.gz
e7cc630a33f81e6703334a93a3e13110178801c7fb80b3c3dc93df76bf1b83cc  WasmEdge-plugin-wasi_nn-ggml-0.14.1-manylinux_2_28_x86_64.tar.gz
7fd4c714e9fb8a11401ff6cc788c6cccbc55ebfcbe186cc7c391d8366dfeab79  WasmEdge-plugin-wasi_nn-ggml-0.14.1-ubuntu20.04_aarch64.tar.gz
aa186a666c165dfe7bd9d84dd3622693ab35595c5063c505bd619e01105ba8b0  WasmEdge-plugin-wasi_nn-ggml-0.14.1-ubuntu20.04_x86_64.tar.gz
028e39ef6984067bebd486dc01f33b4c9a382e22b5069f15ef5af5c45f3fd32a  WasmEdge-plugin-wasi_nn-ggml-cuda-11.3-0.14.1-ubuntu20.04_x86_64.tar.gz
21770b22a7f2e4d444530a66ea06c7ff48bb4b16aa450b51be2c92f966ceb0cd  WasmEdge-plugin-wasi_nn-ggml-cuda-12.0-0.14.1-ubuntu20.04_x86_64.tar.gz
3aa63fbd75acaab0b2d711ebd5f2673a7b927cfbd7882cbeff2c4fe63794b27e  WasmEdge-plugin-wasi_nn-ggml-noavx-0.14.1-ubuntu20.04_x86_64.tar.gz
95c7df44f79922b128323100d5c301a858098e0a8a2f2b3fce335635aa2bc572  WasmEdge-plugin-wasi_nn-whisper-0.14.1-darwin_arm64.tar.gz
06cdee08331f67d2b95b8663c23843e441d2dd674d455422cfa909e0663292ca  WasmEdge-plugin-wasi_nn-whisper-0.14.1-darwin_x86_64.tar.gz
b63d3309f0a7ea90a77124eecdaac42932fc2a720678f5c3fd0c4a392da75d2b  WasmEdge-plugin-wasi_nn-whisper-0.14.1-manylinux_2_28_aarch64.tar.gz
c89270fd8af402502fef5bbe23bf10b03b3c7e0b2b2b25ddf02d429d6ad9ee25  WasmEdge-plugin-wasi_nn-whisper-0.14.1-manylinux_2_28_x86_64.tar.gz
dec3ea7e16c15c1c466f9a75a7b9d0289fa260de46ffd95a04be072ec63493a0  WasmEdge-plugin-wasi_nn-whisper-0.14.1-ubuntu20.04_aarch64.tar.gz
91f724aa7bee1600bfc2a6bbc0b6b7a897d16dd03f5b87d4264d0c208fa49b52  WasmEdge-plugin-wasi_nn-whisper-0.14.1-ubuntu20.04_x86_64.tar.gz
61c0d96d3a8b4984d3a93eb23f7b2b18b79c004aca02f01d6f2e0106d4ad3598  WasmEdge-plugin-wasi_nn-whisper-cuda-11.3-0.14.1-ubuntu20.04_x86_64.tar.gz
97cbebbaa49dc8ddca10f8541c3fa8837b10eb32e63c5256f6e0837a55c70791  WasmEdge-plugin-wasi_nn-whisper-cuda-12.0-0.14.1-ubuntu20.04_x86_64.tar.gz
```

### Stable Diffusion

#### 0.14.1-plugin-lts (1709a5c3)

* Bugfix: fix the segfault issue when reusing the same context.

```
ca0f5abc1cfee53a80208cdddf9d3b1d50711f3dfa0c0eeb02f5b958c132bdeb  WasmEdge-plugin-stable_diffusion-0.14.1-darwin_arm64.tar.gz
401d3d1002e688955d157fc8972564c216133438bcf867e30b215c6f9132a8c4  WasmEdge-plugin-stable_diffusion-0.14.1-darwin_x86_64.tar.gz
34272155728a8f06f816b1965af72cb2f4ab9b806e4648646b238efdc57b096a  WasmEdge-plugin-stable_diffusion-0.14.1-manylinux_2_28_aarch64.tar.gz
be4d921669bd2e786ac4ec729e55ab3497ad2794d499fffd690b8ee75d46dcd0  WasmEdge-plugin-stable_diffusion-0.14.1-manylinux_2_28_x86_64.tar.gz
4210641a2e5ced3682ffdfeee72825c11727396666e1cc20b6490c6ea9b21efb  WasmEdge-plugin-stable_diffusion-0.14.1-ubuntu20.04_aarch64.tar.gz
9a273e1a35a37d321d3a6eb292123b4fff0e8b616c7444dffc7b14aefb32460a  WasmEdge-plugin-stable_diffusion-0.14.1-ubuntu20.04_x86_64.tar.gz
712d24b0c91f0f7fbcf17c3cebb5858fb33680bb93bbe02bb53418ed031af5d8  WasmEdge-plugin-stable_diffusion-cuda-11.3-0.14.1-ubuntu20.04_x86_64.tar.gz
baddd11aeb2652855e3457c17f14d67ceae4bef36bf238da026930a1e580ed63  WasmEdge-plugin-stable_diffusion-cuda-12.0-0.14.1-ubuntu20.04_x86_64.tar.gz
```

#### 0.14.1-plugin-lts (8a2d406)

```
1062d5a94de5ad724d3868aac6e95f8489c3d8876a3fbbea05376710bef17a7e  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-darwin_arm64.tar.gz
514fb4a8de9cc5a8d365c0450f8d59c2ed9d449ecb5b73756b096462244b5a6a  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-darwin_x86_64.tar.gz
8eec0311bd8e1a3bcf93f306ffd39222f515655b80631bb6eebea8e5af15f184  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-manylinux_2_28_aarch64.tar.gz
dc9436f3564a01fa73214c00a6a3fd4a05a957c91429820aa66de77020c7c39d  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-manylinux_2_28_x86_64.tar.gz
303d6319f81b88b006326940dee00e0460b579dbffba62c38679db9663363f8b  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-ubuntu20.04_aarch64.tar.gz
0306c6803ef5757385ad5f7b179d36abcb30ca8758f9f32e3296dd728fe182e5  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-ubuntu20.04_x86_64.tar.gz
059d7bd7d913684fa0bdd800ddb22b05af9e57bacb1a65fa036aa84b059b6b71  WasmEdge-plugin-wasmedge_stablediffusion-cuda-11.3-0.14.1-ubuntu20.04_x86_64.tar.gz
b54d8f3812c4d813ed03340b471459fd854bc60857dc04fe8cb364406f2155fc  WasmEdge-plugin-wasmedge_stablediffusion-cuda-12.0-0.14.1-ubuntu20.04_x86_64.tar.gz
```

#### 0.14.1 SHA256 Checksums

```
cc6fe83108cc35d2d097d6716f7f9c830183c7432bc7e6f6dc7b0e1c23ea9a5c  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-darwin_arm64.tar.gz
da06a7a8964825d02102bd58a2aab74e745d6272718e1c0bf8dd79674349267f  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-darwin_x86_64.tar.gz
b177fddc8582f046c49b7754b520813a1f8c731b4798665645ff98600bf2e85e  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-manylinux2014_aarch64.tar.gz
3d9da3b2091b3db0b392d3af0dc7430fa8c81c186d9f405f0de4f8aee5427c73  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-manylinux2014_x86_64.tar.gz
392c1acfa405a8e29f71253de43ddf23ba408d557143b4ae2c58b261adf89117  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-manylinux_2_28_aarch64.tar.gz
919da80fca14b1535fb0fbd3fdabdc9e0baba56e3d67441249943f608ed9fc41  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-manylinux_2_28_x86_64.tar.gz
b2cec98a63a8ad67e1d47b18ed2dcaa8613d24c705cd366b5d851f240b6171e4  WasmEdge-plugin-wasmedge_stablediffusion-0.14.1-ubuntu20.04_x86_64.tar.gz
5fced23b11ff5191bd9bbef04606dd1aa2205df0b98493cee511319c23abae11  WasmEdge-plugin-wasmedge_stablediffusion-cuda-11.3-0.14.1-ubuntu20.04_x86_64.tar.gz
e3ac628165a5d41d1566063fc6ebbef94d6799e308f6922651802a20a0b788b4  WasmEdge-plugin-wasmedge_stablediffusion-cuda-12.0-0.14.1-ubuntu20.04_x86_64.tar.gz
cc6fe83108cc35d2d097d6716f7f9c830183c7432bc7e6f6dc7b0e1c23ea9a5c  WasmEdge-plugin-wasmedge_stablediffusion-metal-0.14.1-darwin_arm64.tar.gz
```

### Whisper

#### 0.14.1-plugin-lts (8a2d406)

```
4631feebd15ada38fbcd274fd5fa840ac6a74dcb04aafeb990d289d778c0274e  WasmEdge-plugin-wasi_nn-whisper-0.14.1-darwin_arm64.tar.gz
4745e43f15f862614ff7057141bee5a281cc3cdb11c576c9e703762b8e2cc838  WasmEdge-plugin-wasi_nn-whisper-0.14.1-darwin_x86_64.tar.gz
3be98f1a1514f1ce2fe5f20218213dd2ba7fed4cbecde780fd802e0fd35c6ced  WasmEdge-plugin-wasi_nn-whisper-0.14.1-manylinux_2_28_aarch64.tar.gz
04c6520f4622bab5db1dfb4a53d08cb63b4534419e0a18d011184fc77e0962b9  WasmEdge-plugin-wasi_nn-whisper-0.14.1-manylinux_2_28_x86_64.tar.gz
c55d778abee52e89f578e96879260e1de252114da947b2ce591090e93f2cdab9  WasmEdge-plugin-wasi_nn-whisper-0.14.1-ubuntu20.04_aarch64.tar.gz
fa9d4acf96a81cc17e0848ce708ac1a5086928c20bdc0e495186b0e6f485883b  WasmEdge-plugin-wasi_nn-whisper-0.14.1-ubuntu20.04_x86_64.tar.gz
8af858c7a2c7af8df09511eb791b11df06f11eb61e88c9736e994460974901b6  WasmEdge-plugin-wasi_nn-whisper-cuda-11.3-0.14.1-ubuntu20.04_x86_64.tar.gz
777374e2482f5a4532ecdbfd91450ff2074969b21e2a9fefed335a12b5765126  WasmEdge-plugin-wasi_nn-whisper-cuda-12.0-0.14.1-ubuntu20.04_x86_64.tar.gz
```

#### 0.14.1 SHA256 Checksums

```
ee2bdfc461d3280c866af299926dd1962ed96f9fe894adc39230cebdfa69e834  WasmEdge-plugin-wasi_nn-whisper-0.14.1-darwin_arm64.tar.gz
6e782c462c7cea575737f76cc9183157ec45bfe9aec18a3155f580df26835f1b  WasmEdge-plugin-wasi_nn-whisper-0.14.1-darwin_x86_64.tar.gz
b9b4e2044fa698ca27b4509a2506ec5bb6ab1c444d11ff30228d260199295bcd  WasmEdge-plugin-wasi_nn-whisper-0.14.1-manylinux2014_aarch64.tar.gz
d84318d757d0dd7673180315cb9a94dfdc233ab6277f5800244e8453efbe9933  WasmEdge-plugin-wasi_nn-whisper-0.14.1-manylinux2014_x86_64.tar.gz
7c666b340e4d5bc4d76b5a7fde89a7d03fc9e0d648437307cd1104f3eec3cfba  WasmEdge-plugin-wasi_nn-whisper-0.14.1-manylinux_2_28_aarch64.tar.gz
dce0e4cf86ec28e0978be0f1590194e5bff8b0364da8737ff45ef7f89add1ac5  WasmEdge-plugin-wasi_nn-whisper-0.14.1-manylinux_2_28_x86_64.tar.gz
6daea243d51a52393a3a7832d50c30c42aa63528b4f46d7886d5ebdc677aae16  WasmEdge-plugin-wasi_nn-whisper-0.14.1-ubuntu20.04_x86_64.tar.gz
```
