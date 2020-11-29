# LowEnd-AHatInTime

인텥 내장그래픽이 꼴받게 하잖아!


### 적용한것들
- [x] Remove Shadow
- [x] Remove DynamicLights
- [x] Remove PostProcessing

### 적용방법
```cmd
아래 폴더에 파일 덮어씌우기
\steamapps\common\HatinTime\HatinTimeGame\Config
```

### 벤치마크
마파이타운 : 55~60

### 게임설정
- 720P
- 모든옵션 매우낮음(성능)
- 온라인 플레이 X

### 시스템 환경
cpu : i5-10210u  
mem : ddr3l 16G  
gpu : hd620  



SplitscreenMaxDrawDistanceScale=0.6 ;Before : 0.9
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