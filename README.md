# Desktop Flutter grpcman

grpc跨平台桌面客户端调试工具

##### 运行项目：
1. 安装flutter项目及配置相关环境变量
2. 切换flutter为master分支并更新 
   ```
   flutter channel master
   flutter upgrade
   ```
3. 切换flutter为桌面环境
   ```
   // Linux
   flutter config --enable-linux-desktop to enable Linux.
   // On macOS
   export ENABLE_FLUTTER_DESKTOP=true
   // On Windows PowerShell
   $env:ENABLE_FLUTTER_DESKTOP="true"
   // On Windows CMD
   set ENABLE_FLUTTER_DESKTOP=true
   ```
4. 克隆flutter桌面项目
   ```
   git clone https://github.com/google/flutter-desktop-embedding.git
   ```
5. 克隆`flutter-grpcman`到`flutter-desktop-embedding`根目录
   ```
   git clone https://github.com/pku-hit/flutter-grpcman.git
   ```
6. 进入`flutter-grpcman`根目录并安装依赖
   ```
   flutter packages get
   ```
7. 运行
   ```
   flutter run
   ```
