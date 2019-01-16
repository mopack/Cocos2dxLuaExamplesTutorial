## AudioEngineTest中的功能說明 (Cocos2d-x-3.17.1 LuaTest)

### 環境建立

**1. 建立一個空環境**

* 先找到LuaTest-NewAudioEngineTest的資料夾，例如：

```bash
C:\Program Files (x86)\cocos2d-x-3.17.1\build\Debug.win32\lua-tests\Resources\src\NewAudioEngineTest
```

* 將資料夾中的NewAudioEngineTest.lua備份，然後將NewAudioEngineTest.lua改成如下：

```lua
function AudioEngineTest()
    local scene = cc.Scene:create()    
    scene:addChild(CreateBackMenuItem())
    return scene
end
```

你執行的結果應該如下：

 ![](\Images\t1.png)

 * 
 ‵‵‵
 C:\Program Files (x86)\cocos2d-x-3.17.1\build\Debug.win32\lua-tests\helper.lua