# Game Development in Javascript

Things I used when developing WebGL games.

**NOTE:** This is **NOT** another `awesome-*` repo which contains a huge list of what ever they can. The list below are things I really used and evaluated during my development of WebGL games and libraries. It will not growing too fast and I'm trying to remove seldom used, out-of-date stuffs when there is a better alternative.

## Quick Reference

  - Math
    - [Handness in Math](./docs/handness-in-math.md)
    - [Composing Transformations](./docs/composing_transformations.pdf)
  - Graphics
    - [blending](https://threejs.org/examples/#webgl_materials_blending)
    - [blending-custom](https://threejs.org/examples/#webgl_materials_blending_custom)
  - Misc
    - [Input Lag](./docs/input-lag.md)

## Graphics Development (mainly for WebGL)

  - API Wrapper
    - [regl](https://github.com/regl-project/regl)
    - [twgl.js](https://github.com/greggman/twgl.js)
  - Math
    - [vmath](https://github.com/gamedev-js/vmath)
    - [gl-matrix](https://github.com/toji/gl-matrix)
    - Performance Discussion
      - Hidden Classes + Inline Caching is faster than Typed Array
      - [vecmath#performance](https://github.com/mattdesl/vecmath#performance)
  - Loader
    - [resl](https://github.com/regl-project/resl)
    - [opentype.js](https://github.com/nodebox/opentype.js)
  - Geometry
    - [earcut](https://github.com/mapbox/earcut)
    - [lineclip](https://github.com/mapbox/lineclip)
  - Platform Support
    - [WebGL Report](http://webglreport.com/)
    - [WebGL Texture Tester](http://toji.github.io/texture-tester/)
    - [WebGL Stats](http://webglstats.com/)

## Engine Development

  - Event
    - [EventEmitter2](https://github.com/asyncly/EventEmitter2)
    - [EventEmitter3](https://github.com/primus/eventemitter3)
  - Input
    - [input.js](http://github.com/gamedev-js/input.js)
    - [hammer.js](https://github.com/hammerjs/hammer.js)
  - Animation
    - [fullik](https://github.com/lo-th/fullik)
  - Particle
    - [particulate-js](https://github.com/jpweeks/particulate-js)
  - Physics
    - [verlet-js](https://github.com/subprotocol/verlet-js)
    - [cannon.js](https://github.com/schteppe/cannon.js)
    - [p2.js](https://github.com/schteppe/p2.js)
    - [Oimo.js](https://github.com/lo-th/Oimo.js)
    - [ammo.js](https://github.com/kripken/ammo.js/)

## Authoring Tools Development

  - [electron-utils](https://github.com/electron-utils)
  - [SonyWWS/ATF](https://github.com/SonyWWS/ATF)
  - [litegraph.js](https://github.com/jagenjo/litegraph.js)

## Build Tools

  - [bash-concurrent](https://github.com/themattrix/bash-concurrent)
  - [rollup](https://github.com/rollup/rollup/)

## Authoring Tools

  - Scene Design
    - [webglstudio.js](https://github.com/jagenjo/webglstudio.js)
    - [three.js editor](https://threejs.org/editor/)
  - Shading
    - [shadergraph](https://github.com/unconed/shadergraph)
    - [kodelife](https://hexler.net/software/kodelife)
      - [ShaderSketches](https://github.com/keijiro/ShaderSketches)
  - Procedural Texture
    - [texgen.js](https://github.com/mrdoob/texgen.js/)
    - [simplex-noise.js](https://github.com/jwagner/simplex-noise.js)
    - [webgl-noise](https://github.com/ashima/webgl-noise)
  - Timeline
    - [neo](https://github.com/lo-th/neo)
    - [timeline.js](https://github.com/vorg/timeline.js)
    - [mojs](https://github.com/legomushroom/mojs)
  - Misc
    - [rot.js](https://github.com/ondras/rot.js)

## Data Pipeline Tools

  - Geometry
    - [glTF](https://github.com/KhronosGroup/glTF)
    - [meshoptimizer](https://github.com/zeux/meshoptimizer)
  - Font
    - [msdfgen](https://github.com/Chlumsky/msdfgen)
  - Lighting
    - [cmft](https://github.com/dariomanesku/cmft)
    - [IBLBaker](https://github.com/derkreature/IBLBaker)
    - [aobaker](https://github.com/prideout/aobaker)
    - [LuminanceHDR](https://github.com/LuminanceHDR/LuminanceHDR)
    - [envtools](https://github.com/cedricpinson/envtools)

## Performance Monitor

 - [lstats.js](https://github.com/gamedev-js/lstats.js)
 - [pstats.js](https://github.com/gamedev-js/pstats.js)

## Test Utils

  - [preview-server](https://github.com/gamedev-js/preview-server)
  - [faker.js](https://github.com/Marak/faker.js)
  - [headless-gl](https://github.com/stackgl/headless-gl)
  - [gl-shader-output](https://github.com/Jam3/gl-shader-output)
  - UI
    - [uil](https://github.com/lo-th/uil)
    - [xgui.js](https://github.com/oosmoxiecode/xgui.js)
    - [control-panel](https://github.com/freeman-lab/control-panel)
    - [oui](https://github.com/wearekuva/oui)
    - [dis-gui](https://github.com/wwwtyro/dis-gui)

## Debug

  - [WebGL-Inspector](http://benvanik.github.io/WebGL-Inspector/)
  - [glsl-numerify](https://github.com/realazthat/glsl-numerify)
  - Devtools
    - [insight](https://github.com/3Dparallax/insight)
    - [vector-devtools](https://github.com/disjukr/vector-devtools)
    - [devtools-frontend](https://github.com/ChromeDevTools/devtools-frontend)
      - [devtools source in chromium](https://chromium.googlesource.com/chromium/src.git/+/master/third_party/WebKit/Source/devtools)
  - Mobile
    - [eruda](https://github.com/liriliri/eruda)
    - [vConsole](https://github.com/WechatFE/vConsole)
    - [jsconsole](https://github.com/remy/jsconsole)
    - [各种真机远程调试方法汇总](https://github.com/jieyou/remote_inspect_web_on_real_device)

## Optimization

  - [benchmark.js](https://github.com/bestiejs/benchmark.js)
  - [optimize-js](https://github.com/nolanlawson/optimize-js)
  - [disc](https://github.com/hughsk/disc)
  - [jsperf.com](https://jsperf.com/)

## Demo Tools

  - [ccapture.js](https://github.com/spite/ccapture.js)
  - [gifgen](https://github.com/lukechilds/gifgen)

## Guideline

  - [Airbnb: JavaScript Style Guide](https://github.com/airbnb/javascript)
  - [JavaScript SDK Design Guide](http://sdk-design.js.org/)
  - [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines)