xmlscript_lib = shared_library('xmlscriptlo',
  'source/misc/unoservices.cxx',
  'source/xml_helper/xml_byteseq.cxx',
  'source/xml_helper/xml_element.cxx',
  'source/xml_helper/xml_impctx.cxx',
  'source/xmldlg_imexp/xmldlg_addfunc.cxx',
  'source/xmldlg_imexp/xmldlg_expmodels.cxx',
  'source/xmldlg_imexp/xmldlg_export.cxx',
  'source/xmldlg_imexp/xmldlg_impmodels.cxx',
  'source/xmldlg_imexp/xmldlg_import.cxx',
  'source/xmlflat_imexp/xmlbas_export.cxx',
  'source/xmlflat_imexp/xmlbas_import.cxx',
  'source/xmllib_imexp/xmllib_export.cxx',
  'source/xmllib_imexp/xmllib_import.cxx',
  'source/xmlmod_imexp/xmlmod_export.cxx',
  'source/xmlmod_imexp/xmlmod_import.cxx',
  udk_fake_h, off_fake_h,
  cpp_args: ['-DLIBO_INTERNAL_ONLY'],
  include_directories: [main_inc, udkh_inc, offapi_inc, 'source/inc'],
  link_with: [comphelper_lib, cppuhelper_lib, cppu_lib, sal_lib, tl_lib, i18nlangtag_lib],
  install: true,
)
