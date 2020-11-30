# LowEnd-AHatInTime(WIP)

인텔 내장그래픽이 꼴받게 하잖아!

### 적용한것들
- [x] Remove Shadow
- [x] Remove DynamicLights
- [x] Remove PostProcessing
- [x] Screen Resolution 100% -> 75%
- [x] Render Distance .9 -> .75
- [x] Resize Texture  4096 -> 2048
- [x] Remove Decals (마법모자 폭발 흔적 등) 

### 적용방법
```cmd
아래 폴더에 파일 덮어씌우기
\steamapps\common\HatinTime\HatinTimeGame\Config
```

### 벤치마크
* 게임 특유의 프레임드랍은 제외<br/>
마파이타운 : 55 ~ 60  
서브콘숲   : 45 ~ 50  
냐쿠자 메트로 : 40 ~ 50  

### 게임설정
- 720P
- 모든옵션 매우낮음(성능)
- 온라인 플레이 X

### 시스템 환경
cpu : i5-10210u  
mem : ddr3l 16G  
gpu : hd620  


### ?
SplitscreenMaxDrawDistanceScale=0.75 ;Before : 0.9
MaxDrawDistanceScale=0.6  
SHSecondaryLighting=True   ;DO NOT EDIT / But EXTREAM FPS BOOST - low spec gamer  
DirectionalLightmaps=True  ;DO NOT EDIT / But EXTREAM FPS BOOST - low spec gamer  
DynamicLights=False     ;Before : True   
DynamicShadows=False    ;Before : True  
LightEnvironmentShadows=False   ;Before :   True  
AdvancedDepthOfField=False  ;Before : True  
bAllowPostProcessing=False  ;Before : True  
bAllowJigglebones=False     ;Before : True  
AllowImageReflections=False ;Before : True  
AllowImageReflectionShadowing=False;Before : True   
ScreenPercentage=75.000000  ;Before : 100.00000  
MotionBlurPause=False  
bAllowMotionBlurScreen=False  
FilteredDistortion=False  
TEXTUREGROUP_*~  


### 참고
[AHIT_S_C](https://steamcommunity.com/sharedfiles/filedetails/?id=1980693032) 