# key bindings (仿blender)

|撤销|重做|
|---|---|
|\<C-z\>|\<C-Z\>|

|全选|取消全选|反选|
|---|---|---|
|a|\<alt-a\>|\<C-i\>|

|缩小|放大|
|---|---|
|-|=|

|调整为擦除|重置|
|---|---|
|t|\<C-t\>|

|镜像|吸附|
|---|---|
|\<C-m\>|S|

|上一帧|下一帧|播放|
|---|---|---|
|左方向|右方向|space|

|i|k|x|
|---|---|---|
|重复关键帧|空白关键帧|删除关键帧|

||画布操作|
|---|---|
|中键|旋转|
|shift+右键|平移(shift+中键不工作,模仿blender游标的移动)|
|f+左键|笔半径|
|e+左键|吸取前景|
|e+右键|吸取背景|

|选择||
|---|---|
|右键|显示弹出面板|
|g|移动所选|
|r或s|变形工具|
|\<C-,\>|工具选项|

|向下合并图层|合并整个图像|
|---|---|
|\<C-j\>|\<C-J\>|

|手绘笔|框选|圆选|加选|减选|
|---|---|---|---|---|
|d|b|c|shift|alt|


# 蒙版

> 一般图层可在动画曲线中控制透明度
> 变形蒙版可在动画曲线中控制x,y,z,rotate,scale,tan等
> 右键带动画曲线的变形蒙版，选择新建图层-基于可见内容会把动画变到图层


# Comfyui
> Downloading plugin krita-ai-diffusion, import to krita.
> manually run comfyui need to source python venv/bin/activate in server directory, then
> run `python main.py --listen 0.0.0.0`





# overview

```shell
  actions
     ai_diffusion.action
  allium.bundle_modified/workspaces
     allium_workspace.kws
  authorinfo
     condexpr01.authorinfo
  input
     alliumcanvaskeybindings.profile
  predefined_image_sizes
     allium_1920x1080_300ppi.predefinedimage
     allium_1080x2400_300ppi.predefinedimage
  pykrita              # ai_diffusion:GPL, need to download manually and import
    ai_diffusion
     ai_diffusion.desktop
  shortcuts
     allium_keybindings.shortcuts
  windowlayouts
     allium_layout.kwl
   KRITA_RESOURCE_VERSION
   allium.bundle
   kritarc              # not rc, settings backup
   kritashortcutsrc     # not rc, settings backup
  󰂺 readme.md
   resourcecache.sqlite
```



