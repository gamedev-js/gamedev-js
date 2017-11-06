# Game Development in Javascript

Things I used when developing WebGL games.

**NOTE:** This is **NOT** another `awesome-*` repo which contains a huge list of what ever they can. The list below are things I really used and evaluated during my development of WebGL games and libraries. It will not growing too fast and I'm trying to remove seldom used, out-of-date stuffs when there is a better alternative.

## Quick References

  - Math
    - [Basic Math Symbols](http://www.rapidtables.com/math/symbols/Basic_Math_Symbols.htm)
    - [Handness in Math](./docs/handness-in-math.md)
    - [Composing Transformations](./docs/composing_transformations.pdf)
    - [Easings](http://easings.net/)
    - [Tweeny Easing Functions](http://greggman.github.io/doodles/tweeny-graph.html)
    - [Math For Motion](https://soulwire.co.uk/math-for-motion/)
  - Graphics
    - [blending](https://threejs.org/examples/#webgl_materials_blending)
    - [blending-custom](https://threejs.org/examples/#webgl_materials_blending_custom)
    - [PBR Cheat Sheet](https://www.artstation.com/artwork/YeBr3)
  - API References
    - [HTML Canvas Cheatsheet](https://skilled.co/html-canvas/images/HTML_Canvas_Cheatsheet.pdf)
    - [WebGL Quick Reference](https://www.khronos.org/files/webgl/webgl-reference-card-1_0.pdf)
    - [OpenGL ES shading language reference](http://www.shaderific.com/glsl/)
    - [OpenGL 4.3 Quick Reference](https://www.khronos.org/files/opengl43-quick-reference-card.pdf)
    - [docs.GL (OpenGL API Documentation)](http://docs.gl/)
  - Language
    - [The Modern JavaScript Tutorial](https://javascript.info/)
  - Misc
    - [Input Lag](./docs/input-lag.md)
    - [Lighintg Guide](./docs/lighting-guide.md)
    - [awesome-creative-coding](https://github.com/terkelg/awesome-creative-coding)
    - [A Study Path for Game Programmer](https://github.com/miloyip/game-programmer)

## Graphics Development (mainly for WebGL)

  - API Wrapper
    - [regl](https://github.com/regl-project/regl)
    - [twgl.js](https://github.com/greggman/twgl.js)
  - Math
    - [vmath](https://github.com/gamedev-js/vmath)
    - [gl-matrix](https://github.com/toji/gl-matrix)
    - [bit-twiddle](https://github.com/mikolalysenko/bit-twiddle)
    - Performance Discussion
      - **Conclusion:** Hidden Classes + Inline Caching is much faster than Typed Array in both creating and indexing.
      - [vecmath#performance](https://github.com/mattdesl/vecmath#performance)
      - [three.js#1703: Vertex to extend Vector3?](https://github.com/mrdoob/three.js/issues/1703)
      - [cannon.js#8: Float32Array vs Vec3](https://github.com/schteppe/cannon.js/issues/8)
      - [Efficient JavaScript Vector Math](http://media.tojicode.com/sfjs-vectors/)
        - This slides is wrong about Typed Array indexing performance, actually the Vector object wins.
  - Loader
    - [resl](https://github.com/regl-project/resl)
    - [opentype.js](https://github.com/nodebox/opentype.js)
  - Geometry
    - [earcut](https://github.com/mapbox/earcut)
    - [lineclip](https://github.com/mapbox/lineclip)
    - [geometry-processing-js](https://github.com/GeometryCollective/geometry-processing-js)
  - Post Process
    - [StackBlur](https://github.com/flozz/StackBlur)
  - Platform Support
    - [WebGL Report](http://webglreport.com/)
    - [WebGL Texture Tester](http://toji.github.io/texture-tester/)
    - [WebGL Stats](http://webglstats.com/)
  - Shader Transpiling
    - [glslify](https://github.com/stackgl/glslify)
  - Misc
    - [Beware of Transparent Pixels](http://www.adriancourreges.com/blog/2017/05/09/beware-of-transparent-pixels/)

## Audio Development

  - [web-audio-engine](https://github.com/mohayonao/web-audio-engine)
  - [pizzicato](https://github.com/alemangui/pizzicato)

## Engine Development

  - Data Structure
    - [memop](https://github.com/gamedev-js/memop)
    - [BitArray.js](https://github.com/brockwhittaker/BitArray.js)
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
    - 2D
      - [p2.js](https://github.com/schteppe/p2.js)
      - [planck.js](https://github.com/shakiba/planck.js)
    - 3D
      - [cannon.js](https://github.com/schteppe/cannon.js)
      - [Oimo.js](https://github.com/lo-th/Oimo.js)
      - [ammo.js](https://github.com/kripken/ammo.js/)

## Authoring Tools Development

  - [electron-utils](https://github.com/electron-utils)
  - [SonyWWS/ATF](https://github.com/SonyWWS/ATF)
  - [litegraph.js](https://github.com/jagenjo/litegraph.js)
  - [mxgraph](https://github.com/jgraph/mxgraph)
  - [das-ui](https://github.com/szymonkaliski/DAS-UI)

## Multiplayer Development

  - [HappyFunTimes](https://github.com/greggman/HappyFunTimes)
  - [SocketCluster](http://socketcluster.io/)
    - [iogrid](https://github.com/SocketCluster/iogrid)

## Build Tools

  - [bash-concurrent](https://github.com/themattrix/bash-concurrent)
  - [rollup](https://github.com/rollup/rollup/)
  - [buble](https://gitlab.com/Rich-Harris/buble)

## Authoring Tools

  - Scene Design
    - [webglstudio.js](https://github.com/jagenjo/webglstudio.js)
    - [three.js editor](https://threejs.org/editor/)
    - [Structure Synth](http://structuresynth.sourceforge.net/index.php)
  - Modeling
    - [solvespace](https://github.com/solvespace/solvespace)
    - [blender](https://www.blender.org/)
    - [SketchUp](https://www.sketchup.com/)
  - VFX
    - [PopcornFX](https://www.popcornfx.com/)
  - Shading
    - [shadergraph](https://github.com/unconed/shadergraph)
    - [kodelife](https://hexler.net/software/kodelife)
      - [ShaderSketches](https://github.com/keijiro/ShaderSketches)
    - [glslEditor](https://github.com/patriciogonzalezvivo/glslEditor)
    - [Shadertoy](https://www.shadertoy.com/)
    - [GLSLbin](http://glslb.in/)
    - [GLSL Sandbox](http://glslsandbox.com/)
  - Procedural Texture
    - [texgen.js](https://github.com/mrdoob/texgen.js/)
    - [simplex-noise.js](https://github.com/jwagner/simplex-noise.js)
    - [webgl-noise](https://github.com/ashima/webgl-noise)
  - Timeline
    - [neo](https://github.com/lo-th/neo)
    - [timeline.js](https://github.com/vorg/timeline.js)
    - [mojs](https://github.com/legomushroom/mojs)
  - GamePlay
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

  - [Spector.js](https://github.com/BabylonJS/Spector.js)
  - [WebGL-Inspector](http://benvanik.github.io/WebGL-Inspector/)
  - [glsl-numerify](https://github.com/realazthat/glsl-numerify)
  - Devtools
    - [insight](https://github.com/3Dparallax/insight)
    - [audion](https://github.com/google/audion)
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
  - [prepack](https://github.com/facebook/prepack)

## Demo Tools

  - [ccapture.js](https://github.com/spite/ccapture.js)
  - [gifgen](https://github.com/lukechilds/gifgen)

## Documentation Development

  - [mermaid](https://github.com/knsv/mermaid)
  - [documentation.js](https://github.com/documentationjs/documentation)
  - Guideline
    - [Airbnb: JavaScript Style Guide](https://github.com/airbnb/javascript)
    - [JavaScript SDK Design Guide](https://github.com/hueitan/javascript-sdk-design)
    - [中文文案排版指北](https://github.com/sparanoid/chinese-copywriting-guidelines)

## Publish

  - [Front End Checklist](https://github.com/thedaviddias/Front-End-Checklist)