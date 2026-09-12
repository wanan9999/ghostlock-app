构建：
```
cargo build --release
```

使用
```
.\target\release\ghostlock-extract.exe "boot.img" --format json --out .\offsets.json

.\target\release\ghostlock-extract.exe "OTA.zip" --format json --out .\offsets.json
```

导入项目中内置
```
.\target\release\ghostlock-extract.exe "OTA.zip" --register
```