# kbengine_ue4_mmo 独立游戏开发记录
记录独立游戏开发中遇到的一些问题

提交和修改记录

* Working tree changes

1 files changed

* pitch yaw 存服务器，初始化的时候不用，第三人称目前只主角只有yaw可以调整


* 自定义滑动屏幕控制视角  滑行


* CatchMeGameViewportClien process input
add push struct macro

* 六边形的能力图 UI 材质


* ResourceLoader 资源同步异步加载工具


* onReqAvatarList_Imp 进来了两次，导致主界面被创建了两次，点击事件失效
删除多余的 PlayCharacter

* tostruct touobject lua调用C++侧强转后判断是否有效再处理
技能动作连入

* redundant  code


* UI调整, 怪物 npc 创建出来了被隐藏不可见Bug


* FindDirect 接口撸界面


* K2_SetActorRotatio 初始化 摄像机对准目标bp_spectator 的旋转角度，摇杆移动修正


* update engine


* WorldLoaderMan for levelLoad and Unload


* UI FrameWook Revised


* add bit lib json lib for lua


* thinker_helper lib


* ULevelStreamingDynamic 子关卡加载和卸载功能测试


* update engine to 4.26


* project file


* luasocket lpeg 集成网络调试器


* Lua_PrintCppStack


* IsValid


* ui->UI


* 选角界面


* kbengine调通  登录选角色流程


* 调通登陆逻辑模块


* 调通登陆逻辑模块


* 升级kbe插件 增加新字体 开始接kbe服务器


* KBEEngine 接入 ImageLoader 函数升级


* DraggableWindow 移出做单独的模块


* __setnewindex


* add RuntimeMeshComponent


* 启用CatchMeGameViewportClient 增加CatchMeLoadingScreen


* CatchMeGameViewportClient


* DraggableWindow


* 移动测试代码位置


* 移动位置


* 改成大写


* Tostring 方便调试 增加wasd移动和摇杆移动


* FProperty 导出到lua 以及gc相关


* EndPlay 之后lua侧gcCpp对象后cpp侧不能再继续调用lua侧对象方法


* 恢复小地图


* Lua VM进入游戏的时候才创建  界面统一放到 UI/UMG 下面


* UProperty的GetOuter 切换到 FProperty的GetOwner


* UProperty的GetOuter 切换到 FProperty的GetOwner


* 生成的lua头文件放项目生成中间文件夹中，Uproperty->FProperty


* Merge branch 'master' of https://github.com/ren19890419/kbengine_ue4_mmo


* LuaSyntaxCheck 新增 5.3.5支持，5.3.5自带跳过Lua文件 BOM头部功能


* upgrade to 4.25

Signed-off-by: thinker <302842818@qq.com>

* 工程配置修改


* LuaSyntaxCheck 支持命令行传如参数 检查的文件或文件夹


* luaL_dofile_checkbom 增加 UTF-8 带BOM头的Lua文件的加载


* print warn error and sublime project

Signed-off-by: thinker <302842818@qq.com>

* upgrade to 4.24 (2019/9/28)

Signed-off-by: thinker <302842818@qq.com>

* update to UE4.24
lua error pause when play in editor not crashed！！！

* VaTexAtlas


* ImageLoader.cpp  Async cannot use  templated fixed


* add SparseDelegate UUInt16Property Export

Signed-off-by: thinker <302842818@qq.com>

* add SparseDelegate


* update engine to 4.23

Signed-off-by: thinker <302842818@qq.com>

* Merge branch 'master' of https://github.com/ren19890419/kbengine_ue4_mmo


* serpent

Signed-off-by: thinker <302842818@qq.com>

* lua-messagepack-0.5.1.tar.gz

Signed-off-by: thinker <302842818@qq.com>

* luauint

Signed-off-by: thinker <302842818@qq.com>

* 4.22 error

Signed-off-by: thinker <302842818@qq.com>

* lua-protobuf

Signed-off-by: thinker <302842818@qq.com>

* toos for lua  stack check -->StackGuard.h

Signed-off-by: thinker <302842818@qq.com>

* Lua test project configure

Signed-off-by: thinker <302842818@qq.com>

* remove sln

Signed-off-by: thinker <302842818@qq.com>

* Merge branch 'master' of https://github.com/ren19890419/kbengine_ue4_mmo

# Conflicts:
#	CatchMe.sln

* refres engines struct

Signed-off-by: thinker <302842818@qq.com>

* lua test project

Signed-off-by: thinker <302842818@qq.com>

* Use EngineSourceDir Relative script.lua.h

Signed-off-by: thinker <302842818@qq.com>

* generated lua.h header use relatived path..

Signed-off-by: thinker <302842818@qq.com>

* undefined __cplusplus

Signed-off-by: thinker <302842818@qq.com>

* kbengine_ue4_plugins

Signed-off-by: thinker <302842818@qq.com>

* kbengine_ue4_plugins

Signed-off-by: thinker <302842818@qq.com>

* Intergrated Bugly

Signed-off-by: thinker <302842818@qq.com>

* changing case for a directory
Signed-off-by: thinker <302842818@qq.com>
git mv “permission denied”
Also, if you’re just changing case for a directory, you will need to change it to an intermediate directory. i.e.
git mv app App-tmp
git mv App-tmp App

* build tools

Signed-off-by: thinker <302842818@qq.com>

* fixed compile errors

Signed-off-by: thinker <302842818@qq.com>

* Added Tools Folder

Signed-off-by: thinker <302842818@qq.com>

* added ImageLoader Utilities

Signed-off-by: thinker <302842818@qq.com>

* change map size


* eliminate some warnings;

Signed-off-by: thinker <302842818@qq.com>

* use common lua lib
update plugins to 4.22
Signed-off-by: thinker <302842818@qq.com>

* lua lib

Signed-off-by: thinker <302842818@qq.com>

* solution

Signed-off-by: thinker <302842818@qq.com>

* master amend

Signed-off-by: thinker <302842818@qq.com>

* LuaGlueGenerator

Signed-off-by: thinker <302842818@qq.com>

* jumction batch file
Signed-off-by: thinker <302842818@qq.com>

* added project

Signed-off-by: thinker <302842818@qq.com>

* Merge branch 'master' of https://github.com/ren19890419/kbengine_ue4_mmo


* Merge branch 'master' of https://github.com/ren19890419/kbengine_ue4_mmo

# Conflicts:
#	README.md

* Merge branch 'master' of https://github.com/ren19890419/kbengine_ue4_mmo

# Conflicts:
#	README.md

* Update README.md


* Update README.md

Signed-off-by: thinkerthen <302842818@qq.com>

* kbe submodule


* remove


* remove


* remove submodule


* Merge branch 'master' of https://github.com/ren19890419/kbengine_ue4_mmo


* Update .gitmodules


* submodule


* project


* initial


* Initial commit


