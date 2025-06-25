### ffmpeg-kit-frameworks
FFmpeg-kit的官方编译版本，目前有audio、https版本

如果需要自己编译，请参考下面脚本
#### 0.0.4
```bash
git clone git@github.com:arthenica/ffmpeg-kit.git
cd ffmpeg-kit
```
Ios 平台构建脚本
```bash
./ios.sh --enable-gpl --enable-openssl --xcframework \
--disable-lib-x264 \
--disable-lib-x265 \
--disable-lib-vpx \
--disable-lib-theora \
--disable-lib-webp \
--disable-lib-jpeg \
--disable-lib-png \
--disable-lib-tiff \
--disable-lib-zimg \
--disable-lib-aom
```
Macos 平台构建脚本
```bash
./macos.sh --enable-gpl --enable-openssl --xcframework \
--disable-lib-x264 \
--disable-lib-x265 \
--disable-lib-vpx \
--disable-lib-theora \
--disable-lib-webp \
--disable-lib-jpeg \
--disable-lib-png \
--disable-lib-tiff \
--disable-lib-zimg \
--disable-lib-aom
```
