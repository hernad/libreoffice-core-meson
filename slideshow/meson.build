slideshow_lib = shared_library('slideshow',
  'source/engine/activities/activitiesfactory.cxx',
  'source/engine/activities/activitybase.cxx',
  'source/engine/activities/continuousactivitybase.cxx',
  'source/engine/activities/continuouskeytimeactivitybase.cxx',
  'source/engine/activities/discreteactivitybase.cxx',
  'source/engine/activitiesqueue.cxx',
  'source/engine/activities/simplecontinuousactivitybase.cxx',
  'source/engine/animatedsprite.cxx',
  'source/engine/animationfactory.cxx',
  'source/engine/animationnodes/animationaudionode.cxx',
  'source/engine/animationnodes/animationbasenode.cxx',
  'source/engine/animationnodes/animationcolornode.cxx',
  'source/engine/animationnodes/animationcommandnode.cxx',
  'source/engine/animationnodes/animationnodefactory.cxx',
  'source/engine/animationnodes/animationpathmotionnode.cxx',
  'source/engine/animationnodes/animationsetnode.cxx',
  'source/engine/animationnodes/animationtransformnode.cxx',
  'source/engine/animationnodes/animationtransitionfilternode.cxx',
  'source/engine/animationnodes/basecontainernode.cxx',
  'source/engine/animationnodes/basenode.cxx',
  'source/engine/animationnodes/generateevent.cxx',
  'source/engine/animationnodes/nodetools.cxx',
  'source/engine/animationnodes/paralleltimecontainer.cxx',
  'source/engine/animationnodes/propertyanimationnode.cxx',
  'source/engine/animationnodes/sequentialtimecontainer.cxx',
  'source/engine/attributemap.cxx',
  'source/engine/color.cxx',
  'source/engine/delayevent.cxx',
  'source/engine/effectrewinder.cxx',
  'source/engine/eventmultiplexer.cxx',
  'source/engine/eventqueue.cxx',
  'source/engine/expressionnodefactory.cxx',
  'source/engine/rehearsetimingsactivity.cxx',
  'source/engine/screenupdater.cxx',
  'source/engine/shapeattributelayer.cxx',
  'source/engine/shapes/appletshape.cxx',
  'source/engine/shapes/backgroundshape.cxx',
  'source/engine/shapes/drawinglayeranimation.cxx',
  'source/engine/shapes/drawshape.cxx',
  'source/engine/shapes/drawshapesubsetting.cxx',
  'source/engine/shapes/externalshapebase.cxx',
  'source/engine/shapes/gdimtftools.cxx',
  'source/engine/shapes/intrinsicanimationactivity.cxx',
  'source/engine/shapes/mediashape.cxx',
  'source/engine/shapes/shapeimporter.cxx',
  'source/engine/shapesubset.cxx',
  'source/engine/shapes/viewappletshape.cxx',
  'source/engine/shapes/viewbackgroundshape.cxx',
  'source/engine/shapes/viewmediashape.cxx',
  'source/engine/shapes/viewshape.cxx',
  'source/engine/slidebitmap.cxx',
  'source/engine/slide/layer.cxx',
  'source/engine/slide/layermanager.cxx',
  'source/engine/slide/shapemanagerimpl.cxx',
  'source/engine/slideshowcontext.cxx',
  'source/engine/slideshowimpl.cxx',
  'source/engine/slide/slideanimations.cxx',
  'source/engine/slide/slideimpl.cxx',
  'source/engine/slide/targetpropertiescreator.cxx',
  'source/engine/slide/userpaintoverlay.cxx',
  'source/engine/slideview.cxx',
  'source/engine/smilfunctionparser.cxx',
  'source/engine/soundplayer.cxx',
  'source/engine/tools.cxx',
  'source/engine/transitions/barndoorwipe.cxx',
  'source/engine/transitions/barwipepolypolygon.cxx',
  'source/engine/transitions/boxwipe.cxx',
  'source/engine/transitions/checkerboardwipe.cxx',
  'source/engine/transitions/clippingfunctor.cxx',
  'source/engine/transitions/clockwipe.cxx',
  'source/engine/transitions/combtransition.cxx',
  'source/engine/transitions/doublediamondwipe.cxx',
  'source/engine/transitions/ellipsewipe.cxx',
  'source/engine/transitions/fanwipe.cxx',
  'source/engine/transitions/figurewipe.cxx',
  'source/engine/transitions/fourboxwipe.cxx',
  'source/engine/transitions/iriswipe.cxx',
  'source/engine/transitions/parametricpolypolygonfactory.cxx',
  'source/engine/transitions/pinwheelwipe.cxx',
  'source/engine/transitions/randomwipe.cxx',
  'source/engine/transitions/shapetransitionfactory.cxx',
  'source/engine/transitions/slidechangebase.cxx',
  'source/engine/transitions/slidetransitionfactory.cxx',
  'source/engine/transitions/snakewipe.cxx',
  'source/engine/transitions/spiralwipe.cxx',
  'source/engine/transitions/sweepwipe.cxx',
  'source/engine/transitions/transitionfactorytab.cxx',
  'source/engine/transitions/transitiontools.cxx',
  'source/engine/transitions/veewipe.cxx',
  'source/engine/transitions/waterfallwipe.cxx',
  'source/engine/transitions/zigzagwipe.cxx',
  'source/engine/unoviewcontainer.cxx',
  'source/engine/usereventqueue.cxx',
  'source/engine/waitsymbol.cxx',
  'source/engine/pointersymbol.cxx',
  'source/engine/wakeupevent.cxx',

  udk_fake_h, off_fake_h, canvas_hxx,
  cpp_args: ['-DBOOST_SPIRIT_USE_OLD_NAMESPACE',
             '-DLIBO_INTERNAL_ONLY'],
  include_directories: [main_inc, udkh_inc, offapi_inc, 'inc', 'source/inc', setup_inc],
  link_with: [avmedia_lib,
    basegfx_lib,
    canvastools_lib,
    comphelper_lib,
    cppcanvas_lib,
    cppu_lib,
    cppuhelper_lib,
    sal_lib,
    salhelper_lib,
    svl_lib,
    svt_lib,
    svxcore_lib,
    tl_lib,
    utl_lib,
    vcl_lib,
  ],
  dependencies: [],
  install: true,
)

